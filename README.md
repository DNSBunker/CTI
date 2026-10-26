# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-534%2C730-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-12%2C386-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--10--26_17%3A50_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-10-26 17:50 UTC</sub>

| | |
|---|---:|
| Active domains | **534,730** |
| Added in the last 24 hours | 12,386 |
| Added in the last 7 days | 150,709 |
| Added in the last 30 days | 150,709 |
| Retired in the last 30 days (offline or cleaned up) | 264,472 |
| Top-level domains represented | 604 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 26.9 % |
| Domains containing hyphens | 20.6 % |
| Average domain length | 19.6 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Sep 27 – Oct 26 (UTC)"
    x-axis ["27", "28", "29", "30", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26"]
    y-axis "domains" 0 --> 100000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1227, 14240, 21381, 90492, 13281, 10088]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Oct 21 – Oct 26 (UTC)"
    x-axis ["21", "22", "23", "24", "25", "26"]
    y-axis "domains"
    line [472713, 588659, 629951, 748222, 574614, 534730]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-10-26 | 10,088 | 49,261 |
| 2026-10-25 | 13,281 | 186,380 |
| 2026-10-24 | 90,492 | 16,398 |
| 2026-10-23 | 21,381 | 4,228 |
| 2026-10-22 | 14,240 | 7,320 |
| 2026-10-21 | 1,227 | 885 |
| 2026-10-20 | 0 | 0 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.com` | 140,358 | 26.2 % | ████████████████████ |
| 2 | `.xyz` | 130,671 | 24.4 % | ███████████████████ |
| 3 | `.dev` | 37,098 | 6.9 % | █████ |
| 4 | `.click` | 25,619 | 4.8 % | ████ |
| 5 | `.shop` | 21,779 | 4.1 % | ███ |
| 6 | `.sbs` | 16,213 | 3.0 % | ██ |
| 7 | `.top` | 13,091 | 2.4 % | ██ |
| 8 | `.org` | 11,407 | 2.1 % | ██ |
| 9 | `.net` | 9,687 | 1.8 % | █ |
| 10 | `.io` | 9,035 | 1.7 % | █ |
| 11 | `.app` | 7,120 | 1.3 % | █ |
| 12 | `.cc` | 7,110 | 1.3 % | █ |
| 13 | `.info` | 6,212 | 1.2 % | █ |
| 14 | `.live` | 5,298 | 1.0 % | █ |
| 15 | `.vip` | 4,437 | 0.8 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 140358
    ".xyz" : 130671
    ".dev" : 37098
    ".click" : 25619
    ".shop" : 21779
    "other" : 179205
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| WhatsApp | 3,961 | ████████████████████ |
| Coinbase | 3,121 | ████████████████ |
| Meta / Facebook | 2,572 | █████████████ |
| Google | 1,587 | ████████ |
| PayPal | 1,391 | ███████ |
| MetaMask | 1,390 | ███████ |
| Netflix | 1,128 | ██████ |
| Apple / iCloud | 1,083 | █████ |
| Ledger | 921 | █████ |
| Instagram | 910 | █████ |
| Amazon | 807 | ████ |
| Microsoft / Office 365 | 702 | ████ |
| Binance | 641 | ███ |
| Telegram | 491 | ██ |
| American Express | 379 | ██ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 3,566 | ████████████████████ |
| `trade` | 2,847 | ████████████████ |
| `service` | 2,408 | ██████████████ |
| `wallet` | 2,377 | █████████████ |
| `invest` | 2,338 | █████████████ |
| `casino` | 2,328 | █████████████ |
| `support` | 1,861 | ██████████ |
| `auth` | 1,610 | █████████ |
| `connect` | 1,581 | █████████ |
| `secure` | 1,535 | █████████ |
| `bet` | 1,326 | ███████ |
| `account` | 1,246 | ███████ |

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
