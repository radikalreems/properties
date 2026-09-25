# Parcel: Shasta Ln Lot 164

County offices, parcel search, and the zoning code are in [../county.md](../county.md). This file is only this lot. The county GIS pull is September 25, 2026. The public parcel layer has no owner names. Assessed value, the deed, and the tax bill still have to come from the offices in the county file.

Realtor.com does not print an APN or a pin. The parcel below is the one in Iron Gate Lake Estates whose assessor acres are 2.5 and whose outline matches the dimensions on the listing.

## Which parcel

The listing sides are 212, 75, 50, 354, 260, and 561. Added together those are 1,512 feet.

County parcel **102-120-250** is 2.5 assessor acres, in map book 102, and its GIS perimeter is **1,512.5 feet**. Measured in State Plane feet, the six drawn sides are 50, 75, 204, 258, 380, and 546. Four of those sit within about 16 feet of a published side. The 354-foot side is the weak one: the closest drawn side is 380. That is the closest match among the parcels in this part of the subdivision. No other 2.5-acre parcel there had a perimeter of 1,512 feet.

The listing did not name this APN. A deed or the assessor map is what confirms the lot number.

| | |
| --- | --- |
| APN | 102-120-250 |
| Fee / assessment number | 102120250000 |
| Assessor acres | 2.5 |
| Land-use code | 190 |
| Zoning | R-R-B-2.5 |
| Tax rate area | 052-000 |
| PLSS | Sec. 11, T47N, R5W |
| Map book | 102, Iron Gate Lake Estates |
| Timber preserve / ag preserve | No / No |
| Centroid | 41.943800, −122.383517 |

The parcel layer's zoning field is blank. R-R-B-2.5 is from the county zoning layer at that centroid. Neighborhood code is `102`. The tax-rate-area field is stored as `052000`.

GIS polygons are not a survey. The county digitized parcels at 1:24,000. The drawn shape is about 120,400 square feet, while 2.5 assessor acres is 108,900 square feet. Use the `Acres` field, and get a survey before relying on a fence line or a building site.

- Centroid: https://www.google.com/maps?q=41.943800,-122.383517
- County map viewer: https://experience.arcgis.com/experience/c9a297953b9745198a47ac596aacece6
- Public parcel layer: https://services3.arcgis.com/JmPiYilyU1x5zuxM/arcgis/rest/services/Siskiyou_Parcels_Public/FeatureServer

Search the map viewer as `102-120-250`. Some county search boxes want the fee number `102120250000`.

## What is next to it

These two parcels share a boundary with 102-120-250:

| APN | Assessor acres | Land-use code |
| --- | --- | --- |
| 102-120-240 | 2.6 | 190 |
| 102-120-270 | 0 | 000 |

102-120-270 is a zero-acre parcel, the same pattern as the road strip next to Tree Lane. The county road layer has no named road within 30 meters of this lot. Shasta Lane is not in that layer. The listing calls the road gravel. Check 102-120-270 on the assessor map before treating it as the road.

Shasta Lane lot 175 is APN 102-140-130. That parcel is within about 8 meters of 102-120-250, so the two listings are on the same stretch of the subdivision. The county address point for 14929 Shasta Lane sits on 102-120-150, also within that 8 meters. 15455 Shasta Lane is farther up the street, on 102-270-190. Those addresses are houses, not this vacant lot.

A 617.3-acre parcel, 041-050-050, comes within that same 8 meters. It does not share a boundary on the strict intersect. It is not part of this sale.

## Zoning

County zoning at the centroid is **R-R-B-2.5**, Rural Residential Agricultural with a B combining district. B-2.5 sets the minimum parcel size on a future division at 2½ acres. This lot is already 2.5 assessor acres, so the zoning does not leave room to split it.

R-R is written for a house mixed with small-scale farming. The use list includes one single-family dwelling, or one mobile home instead of that house, a guesthouse, one second dwelling if the general rules allow it, and crop or tree farming. It excludes commercial dairies, kennels, and commercial rabbit, fox, goat, horse, hog, and poultry operations. Read the current section before relying on that list.

- Zoning ordinance: https://library.municode.com/ca/siskiyou_county/codes/code_of_ordinances
- R-R district: Title 10, Chapter 6, Article 48
- B combining district: Article 53, sections 10-6.5301 and 10-6.5302
- Lot width, height, coverage, and yards: Article 55, Table 10-6.5501. The R-R row shows a 20-foot front yard, 5-foot side yard, and 20-foot rear yard, with footnotes.
- Road setback, Title 10, Chapter 3: the greater of 50 feet from the road centerline or 20 feet from the property line along the road, unless a variance applies.

Zoning is not the general plan designation. Ask planning for the general plan and for overlays such as septic limits or erosion hazard. Those do not show in the zoning field.

https://www.siskiyoucounty.gov/planning/page/zoning

## Fire and flood

The state's State Fire Hazard Severity Zones layer, at the centroid, is **State Responsibility Area, Very High** (FHSZ 3). The county layer named FireHazardSeverity labels the same point **State Responsibility Area, High** (hazard code 2). The 2025 local-responsibility layer has no polygon here. The two maps disagree, so confirm the current zone before a building plan.

FEMA's National Flood Hazard Layer, queried at the centroid on September 25, 2026, returns **Zone X**, described as an area of minimal flood hazard. The special-flood-hazard flag is false. No base flood elevation is published. That is the centroid, not a survey of the whole lot.

https://msc.fema.gov/portal/search

## What the listing says about the land

These are Realtor.com fields from the September 25, 2026 capture, not county records.

- Road surface: gravel. Remarks say electricity is at the road, and the utilities list says electricity is available.
- Sewer: perc test required.
- Water: well needed.
- Utilities also list cellular phone reception.
- Subdivision on the page: Iron Gate Lake Estates. Lot number 164. Area: Iron Gate.
- Dimensions on the page: 212 by 75 by 50 (front), then 354 by 260 by 561. Topography: varied. View: hills, valley, trees and woods.
- Remarks say it is about a 15 minute drive from town or to I-5.

## Still not in a public layer

- Owner, assessed value, and the tax bill for TRA 052-000.
- A recorded lot number tying lot 164 to 102-120-250. The match above is the outline and the acreage, not the deed.
- CC&Rs, any road maintenance dues, and the road easement. RecorderWorks, searched by APN: https://recorder.co.siskiyou.ca.us/RecorderWorksInternet/default.aspx
- What land-use code 190 means. The same code is on the other vacant Iron Gate lots in this folder. The layer has no legend.
- General plan designation and any septic or erosion overlay.
- A perc result. The listing only says a perc test is required.
- Whether the power line is on this parcel or only at the road, as the remarks say.
