# Properties

Notes on vacant lots. Right now that is Hornbrook, in Siskiyou County.

## Where things are

Lots are grouped by county:

```
lots/<county>/county.md
lots/<county>/<folder>/listing.md
lots/<county>/<folder>/photos/
```

`county.md` is how to look up parcels, zoning, taxes, and the other county offices. It is not about one lot.

Each lot folder has a `listing.md` and, when pictures were saved, a `photos` folder.

## Folder names

A folder is named `price-per-acre / acres / list-price`.

The price per acre is rounded to the nearest dollar, then divided by 1000. Drop a trailing `.0`. A $5,000 one-acre lot is `5-1-5000`. If that name is already taken, the next one is `5-1-5000-2`.

Lower numbers at the start are cheaper per acre.

## A listing

`listing.md` follows `listing.template.md`:

1. Address
2. Last checked
3. Links to the listing and the parcel map
4. Details (price, acres, and so on)
5. Parcel (one row per APN)
6. Extra, when there is something else to say

Blank fields mean the source did not say. Assessed value and tax bill are only filled in when a source is named in the file.
