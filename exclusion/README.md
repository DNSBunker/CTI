# exclusion/ (private)

Owner-managed lists for the tif engine, polled every 30 s and applied without a restart.

| File | Effect | Entries |
|---|---|---:|
| `whitelist.txt` | never listed (domain + all subdomains) | 470 |
| `hosting-apexes.txt` | platform never listed, tenants judged one by one | 3470 |
| `ip-whitelist.txt` | a domain whose addresses all lie in these networks is never listed | 82 |
| `auto_excluded.txt` | written by the engine: released listings, not taken in again | - |

Format: one entry per line, `#` starts a comment. A file that does not
parse (e.g. an HTML error page) is ignored and the last good copy stays active.
Keep this repository private: these lists describe how candidates are pre-selected.
