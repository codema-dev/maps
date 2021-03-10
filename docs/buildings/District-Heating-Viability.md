```
Map currently in development
```

This Heat Demand Density (HDD) estimate is a sum of estimated Residential, Industrial & Non-Industrial building heat demands.  A HDD of greater than 150 TJ/km² indicates that the region may be suitable for District Heating. 

Residential estimate
= Number of dwellings (from 2016 Census) 
* Average Residential heat demand average
* Average Boiler efficiency

Non-Residential estimate
= Total building floor area (from 08/03/2021 Valuation Office Data)
* Building floor area benchmark (fossil fuel demand per unit floor area) corresponding to the building in question
* Average Boiler efficiency

Average Residential Heat Demand
= roughly 10,000 kWh/year (from 2019 Gas Networks Ireland Annual Gas Consumption)
* 85% efficiency (from BER Public search)

Non-Residential Heat Demand Calculations: https://github.com/codema-dev/dublin-building-stock
Non-Residential building floor areas: https://www.valoff.ie/en/open-data/api/
Residential dwellings count: https://www.cso.ie/en/census/census2016reports/census2016smallareapopulationstatistics/
Annual gas consumption: https://www.cso.ie/en/statistics/climateandenergy/networkedgasconsumption/
BER Public search: https://ndber.seai.ie/BERResearchTool/Register/Register.aspx