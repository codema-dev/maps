**Potential**

This District Heating Viability map was created by the `codema` team [on 23/04/2021] using:

- [SEAI's BER Public database](https://ndber.seai.ie/BERResearchTool/Register/Register.aspx) at Small Area level[<sup>1</sup>](#1) `07/2020` `closed-access`
- Valuation Office floor areas[<sup>2</sup>](#2) `2015` `closed-access`
- SEAI's Monitoring & Reporting annual gas demands[<sup>3</sup>](#3) `2018` `closed-access`

> Please read through the attached methodology below prior to using any results as the mapped outputs are very sensitive to the assumptions made.

> If you have any feedback on the process please either raise an issue [on the Github](https://github.com/codema-dev/dublin-energy-webmaps/) or email us at `codema-dev@codema.ie`

<object type="text/html" data="../../html/dublin_tj_per_km2_year.html" width="1000" height="1000" frameborder="0"></object>

Methodology explained in bullet-point format and implemented in `Python` using open-access versions of the data on `Google Colaboratory`[<sup>4</sup>](#4):

<script src="https://gist.github.com/rdmolony/23224c5defdcd63d2c020e779d913fcf.js"></script>

**Waste Heat Sources**

<object type="text/html" data="../../html/waste_heat_sources.html" width="1000" height="1000" frameborder="0"></object>

---

<a id="1"><sup>1</sup></a> The publicly available BER database is at postcode level
<a id="2"><sup>2</sup></a> The publicly available valuation office doesn't include commercially sensitive floor areas.  This data was obtained through the `codema` partnership the 4 Dublin Local Authorities.
<a id="3"><sup>3</sup></a> Obtained via a Freedom-of-Information request
<a id="4"><sup>4</sup></a> Click `Open in Colab` to run the code yourself in `Google Colaboratory`