# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-386%2C944-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-19%2C604-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--10--28_12%3A43_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-10-28 12:43 UTC</sub>

| | |
|---|---:|
| Active domains | **386,944** |
| Added in the last 24 hours | 19,604 |
| Added in the last 7 days | 197,420 |
| Added in the last 30 days | 198,647 |
| Retired in the last 30 days (offline or cleaned up) | 464,554 |
| Top-level domains represented | 601 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 31.3 % |
| Domains containing hyphens | 25.9 % |
| Average domain length | 20.6 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Sep 29 – Oct 28 (UTC)"
    x-axis ["29", "30", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28"]
    y-axis "domains" 0 --> 100000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1227, 14240, 21381, 90492, 13281, 13149, 36078, 8799]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Oct 21 – Oct 28 (UTC)"
    x-axis ["21", "22", "23", "24", "25", "26", "27", "28"]
    y-axis "domains"
    line [472713, 588659, 629951, 748222, 574614, 473331, 457795, 386944]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-10-28 | 8,799 | 78,767 |
| 2026-10-27 | 36,078 | 54,651 |
| 2026-10-26 | 13,149 | 115,925 |
| 2026-10-25 | 13,281 | 186,380 |
| 2026-10-24 | 90,492 | 16,398 |
| 2026-10-23 | 21,381 | 4,228 |
| 2026-10-22 | 14,240 | 7,320 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.com` | 114,422 | 29.6 % | ████████████████████ |
| 2 | `.xyz` | 42,996 | 11.1 % | ████████ |
| 3 | `.dev` | 37,645 | 9.7 % | ███████ |
| 4 | `.shop` | 14,109 | 3.6 % | ██ |
| 5 | `.org` | 11,191 | 2.9 % | ██ |
| 6 | `.click` | 11,002 | 2.8 % | ██ |
| 7 | `.net` | 10,000 | 2.6 % | ██ |
| 8 | `.sbs` | 9,529 | 2.5 % | ██ |
| 9 | `.top` | 9,467 | 2.4 % | ██ |
| 10 | `.io` | 8,391 | 2.2 % | █ |
| 11 | `.cc` | 7,365 | 1.9 % | █ |
| 12 | `.info` | 7,107 | 1.8 % | █ |
| 13 | `.app` | 6,997 | 1.8 % | █ |
| 14 | `.digital` | 5,751 | 1.5 % | █ |
| 15 | `.pro` | 5,066 | 1.3 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 114422
    ".xyz" : 42996
    ".dev" : 37645
    ".shop" : 14109
    ".org" : 11191
    "other" : 166581
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| WhatsApp | 4,175 | ████████████████████ |
| Coinbase | 2,831 | ██████████████ |
| Meta / Facebook | 1,637 | ████████ |
| MetaMask | 1,315 | ██████ |
| Google | 1,192 | ██████ |
| Netflix | 1,045 | █████ |
| Apple / iCloud | 1,026 | █████ |
| PayPal | 971 | █████ |
| Instagram | 894 | ████ |
| Ledger | 776 | ████ |
| Amazon | 761 | ████ |
| Telegram | 723 | ███ |
| Microsoft / Office 365 | 603 | ███ |
| TikTok | 505 | ██ |
| Binance | 403 | ██ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 3,116 | ████████████████████ |
| `trade` | 2,522 | ████████████████ |
| `service` | 1,963 | █████████████ |
| `wallet` | 1,952 | █████████████ |
| `support` | 1,669 | ███████████ |
| `casino` | 1,610 | ██████████ |
| `auth` | 1,519 | ██████████ |
| `invest` | 1,443 | █████████ |
| `secure` | 1,342 | █████████ |
| `bet` | 1,115 | ███████ |
| `connect` | 1,070 | ███████ |
| `account` | 1,039 | ███████ |

## Files

| File | Format | Use it with |
|---|---|---|
| [`domains.txt`](https://raw.githubusercontent.com/DNSBunker/CTI/main/domains.txt) | one domain per line | Technitium, Blocky, dnsmasq/Unbound scripts, firewalls, SIEM enrichment |
| [`adblock.txt`](https://raw.githubusercontent.com/DNSBunker/CTI/main/adblock.txt) | `\|\|domain^` | AdGuard Home, Pi-hole v6, uBlock Origin, AdGuard, NextDNS-style filters |
| [`rpz.txt`](https://raw.githubusercontent.com/DNSBunker/CTI/main/rpz.txt) | DNS Response Policy Zone | BIND, Unbound, Knot Resolver, PowerDNS Recursor |

Each entry covers the domain **and all of its subdomains**. On shared hosting and cloud platforms only the individual malicious hostname is listed, never the platform itself.

<details><summary><b>AdGuard Home / Pi-hole</b></summary>

AdGuard Home: *Filters → DNS blocklists → Add blocklist → Add a custom list* and enter

```
https://raw.githubusercontent.com/DNSBunker/CTI/main/adblock.txt
```

Pi-hole v6: *Lists → Add a new subscribed list* with the same URL (the adblock format also blocks subdomains).

</details>

<details><summary><b>uBlock Origin / AdGuard browser extension</b></summary>

[Subscribe with one click](https://subscribe.adblockplus.org/?location=https%3A%2F%2Fraw.githubusercontent.com%2FDNSBunker%2FCTI%2Fmain%2Fadblock.txt&title=xRuffKez%20CTI%20%28Cyber%20Threat%20Intelligence%29), or add the URL under *Filter lists → Import*:

```
https://raw.githubusercontent.com/DNSBunker/CTI/main/adblock.txt
```

</details>

<details><summary><b>Unbound (RPZ)</b></summary>

```yaml
rpz:
    name: cti.rpz
    url: https://raw.githubusercontent.com/DNSBunker/CTI/main/rpz.txt
    rpz-action-override: nxdomain
    rpz-log: yes
    rpz-log-name: cti
```

</details>

<details><summary><b>BIND 9 (RPZ)</b></summary>

Fetch the zone periodically, e.g. hourly from cron:

```sh
curl -fsS -o /var/named/cti.rpz.tmp https://raw.githubusercontent.com/DNSBunker/CTI/main/rpz.txt && mv /var/named/cti.rpz.tmp /var/named/cti.rpz && rndc reload cti.rpz
```

```
zone "cti.rpz" { type primary; file "/var/named/cti.rpz"; };
options { response-policy { zone "cti.rpz"; }; };
```

</details>

<details><summary><b>Knot Resolver / PowerDNS Recursor</b></summary>

Knot Resolver 5:

```lua
policy.add(policy.rpz(policy.DENY, '/etc/knot-resolver/cti.rpz', true))
```

PowerDNS Recursor (Lua config):

```lua
rpzFile("/etc/powerdns/cti.rpz", {defpol=Policy.NXDOMAIN})
```

Download the zone file as shown for BIND.

</details>

## Listing policy

- **Verified before listing.** A domain is published only after it has been confirmed as active and malicious; suspicious-looking names alone are not enough.
- **Continuously re-verified.** Entries that go offline or are no longer malicious are removed automatically. The list reflects current threats, not history.
- **Precise.** Shared platforms (hosting, cloud, CDN, dynamic DNS) are never listed as a whole; only the individual hostname is.
- **Protected services.** Well-known legitimate services are on an allowlist and are never listed.

## False positives

Found a legitimate domain on the list? Please [open an issue](https://github.com/DNSBunker/CTI/issues/new?title=False%20positive%3A%20) with the domain and a short note why it is legitimate. Reports are reviewed with priority, and a confirmed false positive is removed from every file with the next update.

## Privacy

This project does not collect, store or publish any user data, queries or network metadata.

>[!NOTE]
>DNSBunker.org Resolvers User Data and Queries are NOT used by this CTI project by any means!

## License

[GNU General Public License v2.0](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html)  
Copyright (C) DNSBunker.org / xRuffKez  
SPDX-License-Identifier: GPL-2.0-only

---

Project: [dnsbunker.org](https://dnsbunker.org) · Repository: [github.com/DNSBunker/CTI](https://github.com/DNSBunker/CTI)
