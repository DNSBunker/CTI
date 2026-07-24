# xRuffKez CTI (Cyber Threat Intelligence)

A continuously updated, fully independent threat intelligence feed of malicious,
phishing, and dangerous domains — verified through automated multi-source corroboration.

---

## What This Is

Every listed domain has been independently flagged by 4 security intelligence
APIs and confirmed resolvable at time of evaluation. No domain is listed based on a
single signal.

---

## Domain Lifecycle

**Added:** flagged by multiple independent security APIs and confirmed live.

**Removed:** no longer flagged by the required number of APIs,
or no longer resolvable. Removed domains are recorded in `unflagged.txt`.

---

## Privacy

All evaluation queries are ephemeral. No user data, query content, or network
metadata is retained or published.

>[!NOTE]
>DNSBunker.org Resolvers User Data and Queries are NOT used by this CTI project by any means!

---

## File Reference

| File | Description |
|------|-------------|
| `domains.txt` | Active threat domains, alpha num sorted |
| `rpz.txt` | DNS Response Policy Zone for e.g. BIND / Knot / Unbound |
| `adblock.txt` | Adblock Plus / uBlock Origin filter list – auto-refreshes every hour |
| `unflagged.txt` | Last 500 Domains removed from the feed |
| `STATS.md` | Live statistics, updated on every push |

---

## Statistics

See [STATS.md](STATS.md) for per-push, per-hour, per-day, per-week, per-month, and
all-time breakdowns, the Hall of Shame, and detection distribution across
4 independent security intelligence APIs.

---

## License

[GNU General Public License v2.0](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html)  
Copyright (C) DNSBunker.org / xRuffKez  
SPDX-License-Identifier: GPL-2.0-only

---

Project: [dnsbunker.org](https://dnsbunker.org) · Repo: [github.com/DNSBunker/CTI](https://github.com/DNSBunker/CTI)
