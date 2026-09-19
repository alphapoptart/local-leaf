# Local leaf, in one place

A Florida cannabis deal browser: every dispensary in range, every product with a
real price, the discounts it is actually advertised at, and one deduplicated
ledger of what is new since the last visit.

**This repository is the published copy of the site** - the built app plus one
pre-built data file per area. It is what GitHub Pages serves. It has no backend
and no source for the data pipeline in it; the application that gathers and
prices the listings runs privately.

## What you are looking at

A **fixed snapshot**, dated **2026-09-19T01:08:12+00:00**. One data file holds the whole state, so
precise location works exactly as it does in the live app: allow the location
prompt, type any Florida city, or take a quick pick, and the page lists every
dispensary within the radius of that point - all of them, with their real menus
and the prices they advertise.

What is frozen is the price data itself. It was read on the date above, and
stock and prices move hourly, so read every figure as "as of then".

| | |
|--|--|
| Dispensaries | 664 |
| Priced items | 36,597 |
| On sale | 22,942 |

## Running it yourself

Open the URL and allow location, or choose an area. Then browse, filter, sort.

## Notes on the data

Prices and offers come from publicly listed dispensary menus. "New" means *first
seen by this project's importer*, not a published listing date - the provider
does not publish one, so nothing here claims otherwise. Stock and prices change
constantly; treat this copy as a snapshot with a timestamp, which is what it
says it is.

Not affiliated with, endorsed by, or operated by any dispensary or listing
service. For informational use.
