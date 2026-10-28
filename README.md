# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-370%2C889-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-14%2C997-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--10--28_21%3A54_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-10-28 21:54 UTC</sub>

| | |
|---|---:|
| Active domains | **370,889** |
| Added in the last 24 hours | 14,997 |
| Added in the last 7 days | 202,851 |
| Added in the last 30 days | 204,078 |
| Retired in the last 30 days (offline or cleaned up) | 485,027 |
| Top-level domains represented | 600 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 32.3 % |
| Domains containing hyphens | 26.9 % |
| Average domain length | 20.9 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Sep 29 – Oct 28 (UTC)"
    x-axis ["29", "30", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28"]
    y-axis "domains" 0 --> 100000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1227, 14240, 21381, 90492, 13281, 13149, 36078, 14230]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Oct 21 – Oct 28 (UTC)"
    x-axis ["21", "22", "23", "24", "25", "26", "27", "28"]
    y-axis "domains"
    line [472713, 588659, 629951, 748222, 574614, 473331, 457795, 370889]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-10-28 | 14,230 | 99,240 |
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
| 1 | `.com` | 112,783 | 30.4 % | ████████████████████ |
| 2 | `.dev` | 37,843 | 10.2 % | ███████ |
| 3 | `.xyz` | 31,193 | 8.4 % | ██████ |
| 4 | `.shop` | 13,676 | 3.7 % | ██ |
| 5 | `.org` | 11,370 | 3.1 % | ██ |
| 6 | `.click` | 10,007 | 2.7 % | ██ |
| 7 | `.net` | 9,933 | 2.7 % | ██ |
| 8 | `.top` | 9,226 | 2.5 % | ██ |
| 9 | `.sbs` | 9,077 | 2.4 % | ██ |
| 10 | `.io` | 8,423 | 2.3 % | █ |
| 11 | `.cc` | 7,466 | 2.0 % | █ |
| 12 | `.info` | 7,091 | 1.9 % | █ |
| 13 | `.app` | 6,887 | 1.9 % | █ |
| 14 | `.digital` | 5,731 | 1.5 % | █ |
| 15 | `.br` | 5,441 | 1.5 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 112783
    ".dev" : 37843
    ".xyz" : 31193
    ".shop" : 13676
    ".org" : 11370
    "other" : 164024
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| WhatsApp | 4,277 | ████████████████████ |
| Coinbase | 2,843 | █████████████ |
| Meta / Facebook | 1,621 | ████████ |
| MetaMask | 1,324 | ██████ |
| Google | 1,180 | ██████ |
| Apple / iCloud | 1,024 | █████ |
| Netflix | 1,022 | █████ |
| PayPal | 943 | ████ |
| Instagram | 894 | ████ |
| Ledger | 770 | ████ |
| Amazon | 747 | ███ |
| Telegram | 734 | ███ |
| Microsoft / Office 365 | 590 | ███ |
| TikTok | 505 | ██ |
| Binance | 406 | ██ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 3,107 | ████████████████████ |
| `trade` | 2,488 | ████████████████ |
| `wallet` | 1,950 | █████████████ |
| `service` | 1,887 | ████████████ |
| `support` | 1,662 | ███████████ |
| `auth` | 1,519 | ██████████ |
| `invest` | 1,380 | █████████ |
| `secure` | 1,341 | █████████ |
| `casino` | 1,252 | ████████ |
| `bet` | 1,089 | ███████ |
| `connect` | 1,043 | ███████ |
| `account` | 1,031 | ███████ |

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
