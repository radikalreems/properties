# Parcels: Lots 137 & 138 Tree Ln

County offices, parcel search, and the zoning code are in [../county.md](../county.md). This file is only these two lots. Pulled from the county’s public GIS on September 24, 2026. The parcel layer has no owner names. Assessed value, deed, and tax bill still have to come from the offices in the county file.

The Zillow pin (41.953156, −122.52417) is about 6 miles west of the parcels. Use the centroids below.

## The two parcels

The listing names one number, `102340090`. In county format that is **102-340-090**. The assessor acreage on that parcel is **2.5**. The parcel that shares its boundary and is **2.7** acres is **102-340-100**. Together they are 5.2 assessor acres, which matches the listing’s “2.7 and 2.5.” The MLS did not print the second APN, so treat 102-340-100 as the matching neighbor until the deed or the listing broker says otherwise.

A zero-acre parcel, **102-310-170** (land-use code `000`), also touches 102-340-090. That is not one of the two lots. Check it on the assessor map in case it is the road strip.

| | Lot A | Lot B |
| --- | --- | --- |
| APN | 102-340-090 | 102-340-100 |
| Fee / assessment number | 102340090000 | 102340100000 |
| Assessor acres | 2.5 | 2.7 |
| Land-use code | 190 | 190 |
| Zoning | R-R-B-2.5 | R-R-B-2.5 |
| Tax rate area | 081-000 | 081-000 |
| PLSS | Sec. 3, T47N, R5W | Sec. 3, T47N, R5W |
| Map book | 102, Iron Gate Lake Estates | same |
| Timber preserve / ag preserve | No / No | No / No |
| Fire | State Responsibility Area, Very High | same |
| Centroid | 41.953873, −122.416284 | 41.953898, −122.417269 |

Map book 102 is the county’s book for the Iron Gate Lake Estates subdivision. Neighborhood code on both parcels is `102`.

GIS polygons are not a survey. The county digitized parcels at 1:24,000, and the drawn shape can disagree with the assessor acreage. Use 2.5 and 2.7 from the `Acres` field, and get a survey before relying on a fence line or a building site.

- Both lots on a map: https://www.google.com/maps?q=41.95387,-122.41628
- County map viewer (parcels, zoning, roads, flood, fire): https://experience.arcgis.com/experience/c9a297953b9745198a47ac596aacece6
- Public parcel layer: https://services3.arcgis.com/JmPiYilyU1x5zuxM/arcgis/rest/services/Siskiyou_Parcels_Public/FeatureServer

Search the map viewer as `102-340-090` or `102-340-100`. Some county search boxes want the fee number with the trailing `000` (`102340090000`).

## What R-R-B-2.5 means

County GIS zoning on both polygons is **R-R-B-2.5**. A stale third-party listing shortened that to “RRB.”

The county code treats this as Rural Residential Agricultural (R-R) plus a B combining district. The B-2.5 piece sets the **minimum parcel size on a future division at 2½ acres**. These lots are already 2.5 and 2.7 acres, so the zoning does not leave room to split either one. The R-R rules still apply on top of that minimum.

R-R is written for a house mixed with small-scale farming. The use list includes one single-family dwelling, or one mobile home instead of that house, a guesthouse, one second dwelling if the general rules allow it, and crop or tree farming. It excludes commercial dairies, kennels, and commercial rabbit, fox, goat, horse, hog, and poultry operations. Read the current section before relying on that list. The ordinance has been amended.

- Zoning ordinance, Title 10, Chapter 6, from Article 37: https://library.municode.com/ca/siskiyou_county/codes/code_of_ordinances
- R-R district: Article 48
- B combining districts and the 2½-acre minimum: Article 53, sections 10-6.5301 and 10-6.5302
- Lot width, height, coverage, and yard sizes: Article 55, Table 10-6.5501. The R-R row shows a 20-foot front yard, 5-foot side yard, and 20-foot rear yard, with footnotes.
- Road setbacks can be stricter than the zoning yard. Title 10, Chapter 3 uses the greater of 50 feet from the road centerline or 20 feet from the property line along the road, unless a variance applies.

Planning will confirm the zone in writing. Use the Property Information Inquiry form on the zoning page, or email planning@co.siskiyou.ca.us. They say inquiry replies take about ten days.

https://www.siskiyoucounty.gov/planning/page/zoning

Zoning is not the general plan designation. Ask planning for the general plan map on these two APNs. Overlays such as septic limitation or erosion hazard, if any, live there and will not show up in the zoning field.

## Fire

Both parcels fall in the **State Responsibility Area** and the county’s state fire-hazard layer labels them **Very High** (FHSZ 3). They are not in the local-responsibility (LRA) layer. That classification is what drives wildfire building standards and defensible-space rules if someone builds. Confirm the current map on the county viewer or Cal Fire’s severity-zone maps before a building plan.

## Where the rest of the lot file is

### Owner, assessed value, legal description

Assessor parcel search. Vacant lots often have no street address, so search the APN, not “Tree Ln.”

https://www.siskiyoucounty.gov/assessor-recorder/page/assessors-office-parcel-values-and-maps-online

That page sends you to two outside systems after a disclaimer:

- **Megabyte** for the parcel lookup.
- **ParcelQuest Lite** for the annual assessment value notice. The button is on the parcel’s Assessment section.

The public GIS land-use code is `190` on both parcels. That layer has no legend. The assessor’s office is who can say what 190 means and what the assessed land value is. Characteristic sheets sold online are for single-family houses, not vacant land.

Assessor maps show the lot lines inside book 102. Copies are at the office or through the link on the parcel-search page.

- Map book locations (book 102 = Iron Gate Lake Estates): https://www.siskiyoucounty.gov/sites/default/files/fileattachments/assessor/recorder/page/4021/asr-20180829-mapbooklocations.pdf
- Parcel maps page: https://www.siskiyoucounty.gov/assessor-recorder/page/parcel-maps

Assessor-Recorder, 311 Fourth Street, Room 108, Yreka. Monday–Friday, 8:00–noon and 1:00–5:00. Assessor 530-842-8036. Recorder 530-842-8065. assessor@co.siskiyou.ca.us.

### Deed, CC&Rs, subdivision map, road easement

RecorderWorks, searched by APN. Records run from 1928. This is where the deed, any CC&Rs for Iron Gate Lake Estates, the subdivision map, and road or utility easements should be.

https://recorder.co.siskiyou.ca.us/RecorderWorksInternet/default.aspx

The county’s index page is https://www.siskiyoucounty.gov/assessor-recorder/page/online-services. Online copies ordered there are picked up at the office.

The listing says a private HOA maintains the road. The recorder’s easement and CC&Rs, not the MLS remarks, are what show whether that is true and what it costs. The map viewer’s county-road layer shows whether Tree Lane is a county road at all.

### Tax bill

Tax rate area on both parcels is **081-000**. The bill amount is not in the public parcel layer. Zillow’s 1.05% rate and its $170-a-month tax line are not a county bill. Get the value notice from ParcelQuest, then the bill from the Treasurer-Tax Collector (the county site lists “Pay Taxes” under services).

### Septic and well

Environmental Health reviews sewage and wells, in this order: floodplain check, on-site sewage review, well permit, well install, water quantity and quality if required, then the sewage permit.

https://www.siskiyoucounty.gov/environmentalhealth/page/land-use

Forms, including the perc-test form and the individual sewage review application:

https://www.siskiyoucounty.gov/environmentalhealth/page/applications-and-permits

Nearby well logs, if any, are in the state well-completion reports: https://data.cnra.ca.gov/dataset/well-completion-reports

### Building and planning permits

Building, Planning, and Environmental Health applications go through Community Development’s online portal. The county has said the first response can take about five business days.

https://www.siskiyoucounty.gov/community-development/page/online-permitting-portal

Community Development is at 806 South Main Street, Yreka, 530-841-2100. Hours posted on the zoning page are Monday–Thursday, 8:00–5:00, closed noon–1:00, Friday by appointment.

### Flood

Zillow called the listing pin FEMA Zone X (unshaded). That pin is in the wrong place, so the flood label needs to be checked on the parcels themselves. The county map viewer includes flood hazard areas. FEMA’s official map is https://msc.fema.gov/portal/search. Search the centroids above, not the Zillow coordinate.

### Jurisdiction check

https://siskiyou.maps.arcgis.com/apps/webappviewer/index.html?id=a5bd2968680f40d28e20c8ebb5ab089a

## Still not in a public layer

- Owner and assessed value (Assessor / ParcelQuest).
- Whether the deed actually conveys both 102-340-090 and 102-340-100.
- CC&Rs, HOA dues, and the road easement (RecorderWorks).
- What land-use code 190 means.
- General plan designation and any septic or erosion overlay.
- Perc result, well feasibility, and power at the road.
- The tax bill for TRA 081-000.
- Flood zone on the real parcels, as opposed to Zillow’s misplaced pin.
