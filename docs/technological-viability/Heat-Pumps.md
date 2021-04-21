This map shows the percentage of heat pump ready homes[<sup>1</sup>](#1) in each Dublin Small Area[<sup>2</sup>](#2).

> The map is based on a closed-access version of the Building Energy Rating (BER) database provided to `Codema - Dublin's Energy Agency` by `SEAI` on 07/2020.  

> **Caveat:** where it was not possible to calculate heat pump readiness using building fabric information it an estimate was used based on the building's age[<sup>3</sup>](#3)

<object type="text/html" data="../../html/heat_pump_ready_hhs.html" width="1000" height="1000" frameborder="0"></object>

Methodology explained in bullet-point format and implemented in `Python` using open-access versions of the data on `Google Colaboratory`[<sup>4</sup>](#4):

<script src="https://gist.github.com/rdmolony/859455279c2c7141f1a8a76e67aa3290.js"></script>

---

<a id="1"><sup>1</sup></a> [SEAI advise](https://www.seai.ie/publications/Technical_Advisor_Role.pdf) that a building with a Heat Loss Parameter (HLP) of less than 2.3 is heat pump ready.

<a id="2"><sup>2</sup></a> Small Areas are areas of population generally comprising between 80 and 120 dwellings created by The National Institute of Regional and Spatial Analysis (NIRSA) on behalf of the Ordnance Survey Ireland (OSi) in consultation with CSO. Small Areas were designed as the lowest level of geography for the compilation of statistics in line with data protection and generally comprise either complete or part of townlands or neighbourhoods.

<a id="3"><sup>3</sup></a> Heat pump readiness for unknown buildings is estimated based on building age (see `heat_pump_ready` vs `period_built` distribution in the methodology above):

- not heat pump ready: ["not stated", "before 1919", "1919 - 1945", "1946 - 1960", "1961 - 1970", "1971 - 1980", "1981 - 1990"]
- heat pump ready: ["1991 - 2000", "2001 - 2005", "2006 - 2010", "2011 or later"]

<a id="4"><sup>4</sup></a> Click `Open in Colab` to run the code yourself in `Google Colaboratory`