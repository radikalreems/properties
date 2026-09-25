# Properties

Notes on vacant lots. Right now that is Hornbrook, in Siskiyou County.

## Where things are

Lots are grouped by county:

```
lots/<county>/county.md
lots/<county>/<folder>/summary.md
lots/<county>/<folder>/listing.md
lots/<county>/<folder>/photos/
```

`county.md` is how to look up parcels, zoning, taxes, and the other county offices. It is not about one lot.

`summary.md` is the short notes for a lot. `listing.md` is the raw dump from the listing page, when one has been saved. Pictures are in `photos`.

## Folder names

A folder is named `price-per-acre / acres / list-price`.

The price per acre is rounded to the nearest dollar, then divided by 1000. Drop a trailing `.0`. A $5,000 one-acre lot is `5-1-5000`. If that name is already taken, the next one is `5-1-5000-2`.

Lower numbers at the start are cheaper per acre.

## A summary

`summary.md` follows `summary.template.md`:

1. Address
2. Where the listing came from
3. Last checked
4. Links to the listing and the parcel map
5. Details (price, acres, and so on)
6. Parcel (one row per APN)
7. Extra, when there is something else to say

Blank fields mean the source did not say. Assessed value and tax bill are only filled in when a source is named in the file.
