# Summary files

When adding or editing a `summary.md`, follow `summary.template.md`.

Put the file at `lots/<county>/<ratio>-<acres>-<price>/summary.md`.

The folder name is the list price per acre, rounded to the nearest dollar, divided by 1000, then the listing acres, then the list price with no commas or dollar sign. A $5,000 one-acre lot is `5-1-5000`. Drop a trailing `.0`. If that folder already exists, append `-2`, then `-3`, and so on.

Keep this order:

1. Address as the title.
2. **Where it came from** — say the site if it was found on Zillow or Realtor.com. If it came directly from a real estate agent, say that. If it was found on a site and then verified with an agent, say both and the date of that check.
3. **Last checked** — the date this file was compared to the live listing, as YYYY-MM-DD.
4. **Links** — each site where the listing was found, then this lot’s parcel link (assessor or county map).
5. **Details** — price, acres, time on the market, address, coordinates, road access, septic, water, electricity, HOA / association fees, assessed value, and tax bill. Name the source for time on the market. Leave a field blank if the page does not say.
6. **Parcel** — one row per APN in the sale, with that parcel’s zoning and assessor acres, then **Notes** for other parcel facts that do not fit the table. Use the county record. Leave a cell blank, and omit Notes, when there is nothing to add.
7. **Extra** — anything that does not fit above. Include the subdivision when the lot is in one. Omit the section when it would be empty.

HOA / association fees are `unknown`, `0`, or the amount. When the amount is known, add a note naming the fee (road dues, HOA, and so on).

Do not invent a price, a time on market, a check date, an assessed value, or a tax bill. Those last two need a county record, a tax bill, or another source named in the file. How to use the county offices stays in that county’s `county.md`.
