# Parcel: Tableland Road #1400 & 1500

County offices, the tax-lot search, and the zoning code are in [../county.md](../county.md). This file is only this listing. The county tax-lot pull is September 25, 2026. The layer includes an owner name. The land-value fields on these two records are empty, so assessed value and the tax bill still have to come from the assessor.

## Which parcels

Land.com does not print a tax lot. Its pin, 42.501788, −121.419505, falls on a different parcel: map tax lot **3511-00000-05600**, account 276070, 40 assessor acres. That is not this sale.

Movoto, for the same MLS 220218661, prints APN **288003** and additional parcel **288012**. Those are Klamath County account numbers. On the county tax-lot layer they are two adjoining 10-acre lots. Together they are 20 assessor acres, the same as the listing.

| | Tax lot 1400 | Tax lot 1500 |
| --- | --- | --- |
| Account | 288003 | 288012 |
| Map tax lot | 3511-03000-01400 | 3511-03000-01500 |
| OR tax lot | 1835.00S11.00E3000--000001400 | 1835.00S11.00E3000--000001500 |
| Assessor acres | 10 | 10 |
| GIS acres | 9.98 | 9.98 |
| Zoning | FR | FR |
| Property class | 400, rural vacant, tract land only | same |
| Tax code | 229 | 229 |
| Map | 35S 11E 30 | same |
| Fire district | Klamath County Fire District 3 | same |
| City / urban growth boundary | Neither | Neither |
| Inside point | 42.505787, −121.449789 | 42.504883, −121.449782 |
| Assessor page | https://assessor.klamathcounty.org/PSO/detail/288003/R | https://assessor.klamathcounty.org/PSO/detail/288012/R |

The two lots share a boundary. Tax lot 1400 is the north one. The layer’s owner line on both, as of this pull, is Balbin Bruce D and Delena R Balbin et al, mailing address in Vallejo, California. Sale price and sale date on the layer are empty. The layer’s RDATE field is 20260920. Map status on both records is OLD.

GIS acres are the drawn shape. Use the assessor acres, 10 and 10. The county says Land Explorer lines are not a survey.

- Tax map 35S11E30: https://taxmaps.klamathcounty.org/depts/assessor/gis_pdfs/Taxmaps/35S11E30.pdf
- Land Explorer: https://experience.arcgis.com/experience/dfbd28d66a73412ba34c47759c01aa94
- North lot: https://www.google.com/maps?q=42.505787,-121.449789

A different map, 38S 11E 03B, also prints lot numbers 1400 and 1500. That is Klamath Falls Forest Estates, along Highway 66. Those lots are about 2 acres each and are not these accounts.

## Zoning

The tax-lot layer says **FR** on both, not split. In the Klamath County Land Development Code, Article 55.2, FR is Forestry/Range. The purpose section says the zone is for mixed farm and forest land in southern Klamath County, mostly juniper, sagebrush, and bitterbrush, and that it is meant to be more productive than Non-Resource land and less than Exclusive Farm Use or Forestry.

Which rules apply to a house or a land division depends on the tract’s tax status, soil class, and the predominant use as of January 1, 1993. The minimum lot size stated for a new division in that article is 80 acres. These lots are already 10 acres each.

https://www.klamathcounty.org/725/Land-Development-Code

## Fire and flood

The tax-lot layer places both lots in **Klamath County Fire District 3**. Schools on the same layer are Chiloquin Elementary and Chiloquin High.

FEMA’s National Flood Hazard Layer, queried at both inside points on September 25, 2026, returns **Zone X**, an area of minimal flood hazard. The special-flood-hazard flag is false. That is the inside point, not a survey of either lot.

https://msc.fema.gov/portal/search

## What the listing says about the land

Land.com, September 25, 2026: 20 acres, off-grid, camping, and a common-feature tag of campground. The remarks do not name an association.

Movoto, same MLS: dirt road, water source none, fencing none, lot features level and native plants, view territorial, current use recreational, zoning FR, property tax 129.64, HOA $0 a month.

## Still not on the tax-lot record

- Assessed land value and the tax bill for tax code 229. Movoto’s $129.64 is an MLS field.
- The deed, and whether the sale is both accounts.
- Whether the tract is farm-deferred, which changes which zoning article applies.
- Septic, a well, and power. The remarks say off-grid and do not locate a power line.
- What the Land.com campground tag refers to.
