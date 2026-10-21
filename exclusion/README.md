# exclusion/ (private)

Owner-managed lists for the tif engine, polled every 60 s and applied without a restart.

| File | Effect | Entries |
|---|---|---:|
| `whitelist.txt` | never listed (domain + all subdomains) | 160 |
| `hosting-apexes.txt` | platform never listed, tenants judged one by one | 3603 |
| `regex.txt` | `/regex/` prefilter on registrable domains | 36 |

Format: one entry per line, `#` (regex: `!`) starts a comment. A file that does not
parse (e.g. an HTML error page) is ignored and the last good copy stays active.
Keep this repository private: these lists describe how candidates are pre-selected.
