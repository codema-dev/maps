These maps area based on SEAI's Monitoring & Reporting (M&R) dataset which was requested by Codema - Dublin's Energy Agency under Freedom of Information (FOI) on 21/01/2020. The M&R data includes offices, schools, universities, banks, hospitals, gardai stations, post offices, theatres, courts, local authority & government buildings, libraries.

---

**Locations geocoded by Google Maps**

> **Caveats:**

> - 807/1156 buildings (i.e. unique building name and postcode) were successfully located in the correct postcode.  

> - These Locations were geocoded using the `Google Maps Geocoding API` and verified to be in the correct Postcode, however, there may still be incorrect locations.  Please contact us at `codema-dev@codema.ie` if you spot any!

<iframe src="https://www.google.com/maps/d/embed?mid=1invy4mzMToGKjc0a0_0ZkzRy_6bEbJnh" width="1000" height="600"></iframe>

---

**Locations geocoded by Openstreetmaps Nomantim**

To find specific buildings in `Dun Laoghaire` (for example):

- Click on  `- column -` and select `nominatim_address` `contains` `Dun Laoghaire`

> **Caveats:**

> - 279/1156 buildings (i.e. unique building name and postcode) were successfully located in the correct postcode.  

> - These Locations were geocoded using the `Openstreetmaps Nominatim` geocoder and verified to be in the correct Postcode, however, there may still be incorrect locations.  Please contact us at `codema-dev@codema.ie` if you spot any!

<iframe src="https://dublin-monitoring-and-reporting-osm.glitch.me/data/demands" width="1000" height="1500"></iframe>


---

**Entire dataset (including unsuccessfully geocoded buildings)**

The entire public sector dataset can be queried using the [datasette](https://github.com/simonw/datasette) application below.  **If you know the location of any of these missing buildings please go to [Openstreetmap.org](https://www.openstreetmap.org/) and enter the missing location!**

To find the buildings that were not successfully geocoded by Google Maps:

-  Click on `- column -` and select `google_maps_geocoding_was_successful` `=` `False`
- Or click `google_maps_geocoding_was_successful` under `suggested facets`.

<iframe src="https://dublin-public-building-demands.glitch.me/data/demands" width="1000" height="1000"></iframe>