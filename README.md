# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-751%2C645-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-99%2C148-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--10--24_21%3A40_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-10-24 21:40 UTC</sub>

| | |
|---|---:|
| Active domains | **751,645** |
| Added in the last 24 hours | 99,148 |
| Added in the last 7 days | 126,089 |
| Added in the last 30 days | 126,089 |
| Retired in the last 30 days (offline or cleaned up) | 23,014 |
| Top-level domains represented | 599 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 20.3 % |
| Domains containing hyphens | 15.8 % |
| Average domain length | 18.5 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Sep 25 – Oct 24 (UTC)"
    x-axis ["25", "26", "27", "28", "29", "30", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24"]
    y-axis "domains" 0 --> 100000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1227, 14240, 21381, 89241]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Oct 21 – Oct 24 (UTC)"
    x-axis ["21", "22", "23", "24"]
    y-axis "domains"
    line [472713, 588659, 629951, 751645]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-10-24 | 89,241 | 10,581 |
| 2026-10-23 | 21,381 | 4,228 |
| 2026-10-22 | 14,240 | 7,320 |
| 2026-10-21 | 1,227 | 885 |
| 2026-10-20 | 0 | 0 |
| 2026-10-19 | 0 | 0 |
| 2026-10-18 | 0 | 0 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.xyz` | 325,068 | 43.2 % | ████████████████████ |
| 2 | `.com` | 144,938 | 19.3 % | █████████ |
| 3 | `.dev` | 41,513 | 5.5 % | ███ |
| 4 | `.click` | 26,469 | 3.5 % | ██ |
| 5 | `.shop` | 21,727 | 2.9 % | █ |
| 6 | `.sbs` | 17,102 | 2.3 % | █ |
| 7 | `.top` | 14,145 | 1.9 % | █ |
| 8 | `.org` | 12,575 | 1.7 % | █ |
| 9 | `.net` | 10,079 | 1.3 % | █ |
| 10 | `.io` | 8,895 | 1.2 % | █ |
| 11 | `.app` | 7,650 | 1.0 % | █ |
| 12 | `.cc` | 6,913 | 0.9 % | █ |
| 13 | `.info` | 6,166 | 0.8 % | █ |
| 14 | `.baby` | 5,455 | 0.7 % | █ |
| 15 | `.live` | 5,406 | 0.7 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".xyz" : 325068
    ".com" : 144938
    ".dev" : 41513
    ".click" : 26469
    ".shop" : 21727
    "other" : 191930
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| WhatsApp | 3,932 | ████████████████████ |
| Coinbase | 3,003 | ███████████████ |
| Meta / Facebook | 2,965 | ███████████████ |
| Google | 1,660 | ████████ |
| PayPal | 1,589 | ████████ |
| MetaMask | 1,433 | ███████ |
| Netflix | 1,232 | ██████ |
| Apple / iCloud | 1,202 | ██████ |
| Ledger | 1,151 | ██████ |
| Amazon | 1,046 | █████ |
| Instagram | 879 | ████ |
| Microsoft / Office 365 | 786 | ████ |
| Binance | 680 | ███ |
| Telegram | 430 | ██ |
| American Express | 420 | ██ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 3,990 | ████████████████████ |
| `invest` | 3,855 | ███████████████████ |
| `trade` | 3,131 | ████████████████ |
| `service` | 3,043 | ███████████████ |
| `casino` | 2,668 | █████████████ |
| `wallet` | 2,660 | █████████████ |
| `support` | 2,176 | ███████████ |
| `connect` | 2,112 | ███████████ |
| `secure` | 1,700 | █████████ |
| `auth` | 1,599 | ████████ |
| `security` | 1,562 | ████████ |
| `bet` | 1,509 | ████████ |

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
