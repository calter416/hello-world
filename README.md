# hello-world
idea repository

## Data files

| File | ZIP code | Coverage |
| --- | --- | --- |
| `zip1.csv` | 60657 | Monthly, Jan 1996 – Mar 2020 (291 rows) |
| `zip2.csv` | 77494 | Monthly, Jan 1996 – Mar 2020 (291 rows) |

Both files share the same columns:

- *(unnamed first column)*: row index, starting at 0
- `ds`: month-end date (`YYYY-MM-DD`)
- `<zip>zip`: the monthly value for that ZIP code (`60657zip` or `77494zip`)
- `Recession`: `True` for months during a U.S. recession (Mar–Nov 2001, Dec 2007 – Jun 2009, and from Jan 2020 onward), otherwise `False`
- `Month`: month number (1–12)
- `Year`: four-digit year
