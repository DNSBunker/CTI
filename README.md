# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-298%2C243-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-26%2C653-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--11--01_14%3A49_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-11-01 14:49 UTC</sub>

| | |
|---|---:|
| Active domains | **298,243** |
| Added in the last 24 hours | 26,653 |
| Added in the last 7 days | 190,930 |
| Added in the last 30 days | 227,778 |
| Retired in the last 30 days (offline or cleaned up) | 586,792 |
| Top-level domains represented | 566 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 34.5 % |
| Domains containing hyphens | 29.7 % |
| Average domain length | 21.1 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Oct 3 – Nov 1 (UTC)"
    x-axis ["3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28", "29", "30", "31", "1"]
    y-axis "domains" 0 --> 100000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1227, 14240, 21381, 90492, 13281, 13149, 36078, 15350, 11978, 0, 0, 10602]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Oct 21 – Nov 1 (UTC)"
    x-axis ["21", "22", "23", "24", "25", "26", "27", "28", "29", "30", "31", "1"]
    y-axis "domains"
    line [472713, 588659, 629951, 748222, 574614, 473331, 457795, 371010, 376945, 376945, 376945, 298243]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-11-01 | 10,602 | 95,637 |
| 2026-10-31 | 0 | 0 |
| 2026-10-30 | 0 | 0 |
| 2026-10-29 | 11,978 | 5,456 |
| 2026-10-28 | 15,350 | 99,912 |
| 2026-10-27 | 36,078 | 54,651 |
| 2026-10-26 | 13,149 | 115,925 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.com` | 99,197 | 33.3 % | ████████████████████ |
| 2 | `.dev` | 31,560 | 10.6 % | ██████ |
| 3 | `.shop` | 11,018 | 3.7 % | ██ |
| 4 | `.click` | 9,778 | 3.3 % | ██ |
| 5 | `.org` | 9,106 | 3.1 % | ██ |
| 6 | `.top` | 8,986 | 3.0 % | ██ |
| 7 | `.sbs` | 8,756 | 2.9 % | ██ |
| 8 | `.net` | 8,597 | 2.9 % | ██ |
| 9 | `.xyz` | 8,081 | 2.7 % | ██ |
| 10 | `.io` | 6,560 | 2.2 % | █ |
| 11 | `.cc` | 6,217 | 2.1 % | █ |
| 12 | `.app` | 6,194 | 2.1 % | █ |
| 13 | `.info` | 6,071 | 2.0 % | █ |
| 14 | `.digital` | 4,825 | 1.6 % | █ |
| 15 | `.br` | 4,814 | 1.6 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 99197
    ".dev" : 31560
    ".shop" : 11018
    ".click" : 9778
    ".org" : 9106
    "other" : 137584
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| WhatsApp | 4,427 | ████████████████████ |
| Coinbase | 2,067 | █████████ |
| Meta / Facebook | 1,162 | █████ |
| Google | 914 | ████ |
| MetaMask | 896 | ████ |
| Apple / iCloud | 853 | ████ |
| Netflix | 739 | ███ |
| Ledger | 611 | ███ |
| PayPal | 588 | ███ |
| Instagram | 565 | ███ |
| Amazon | 543 | ██ |
| Telegram | 540 | ██ |
| Microsoft / Office 365 | 482 | ██ |
| Binance | 340 | ██ |
| TikTok | 320 | █ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `trade` | 2,414 | ████████████████████ |
| `login` | 2,284 | ███████████████████ |
| `casino` | 1,761 | ███████████████ |
| `service` | 1,496 | ████████████ |
| `wallet` | 1,489 | ████████████ |
| `support` | 1,340 | ███████████ |
| `bet` | 1,245 | ██████████ |
| `secure` | 1,028 | █████████ |
| `auth` | 1,022 | ████████ |
| `invest` | 959 | ████████ |
| `update` | 793 | ███████ |
| `account` | 763 | ██████ |

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
