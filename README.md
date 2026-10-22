# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-565%2C424-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-12%2C786-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--10--22_19%3A11_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-10-22 19:11 UTC</sub>

| | |
|---|---:|
| Active domains | **565,424** |
| Added in the last 24 hours | 12,786 |
| Added in the last 7 days | 12,786 |
| Added in the last 30 days | 12,786 |
| Retired in the last 30 days (offline or cleaned up) | 2,410 |
| Top-level domains represented | 496 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 18.0 % |
| Domains containing hyphens | 16.0 % |
| Average domain length | 18.5 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Sep 23 – Oct 22 (UTC)"
    x-axis ["23", "24", "25", "26", "27", "28", "29", "30", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22"]
    y-axis "domains" 0 --> 15000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1227, 11559]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Oct 21 – Oct 22 (UTC)"
    x-axis ["21", "22"]
    y-axis "domains"
    line [472713, 565424]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-10-22 | 11,559 | 1,525 |
| 2026-10-21 | 1,227 | 885 |
| 2026-10-20 | 0 | 0 |
| 2026-10-19 | 0 | 0 |
| 2026-10-18 | 0 | 0 |
| 2026-10-17 | 0 | 0 |
| 2026-10-16 | 0 | 0 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.xyz` | 277,106 | 49.0 % | ████████████████████ |
| 2 | `.com` | 104,122 | 18.4 % | ████████ |
| 3 | `.dev` | 30,870 | 5.5 % | ██ |
| 4 | `.click` | 18,739 | 3.3 % | █ |
| 5 | `.sbs` | 13,519 | 2.4 % | █ |
| 6 | `.shop` | 11,104 | 2.0 % | █ |
| 7 | `.org` | 8,847 | 1.6 % | █ |
| 8 | `.net` | 8,341 | 1.5 % | █ |
| 9 | `.top` | 7,925 | 1.4 % | █ |
| 10 | `.app` | 5,560 | 1.0 % | █ |
| 11 | `.live` | 4,524 | 0.8 % | █ |
| 12 | `.io` | 4,187 | 0.7 % | █ |
| 13 | `.me` | 3,516 | 0.6 % | █ |
| 14 | `.cc` | 3,274 | 0.6 % | █ |
| 15 | `.info` | 3,126 | 0.6 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".xyz" : 277106
    ".com" : 104122
    ".dev" : 30870
    ".click" : 18739
    ".sbs" : 13519
    "other" : 121068
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| WhatsApp | 2,704 | ████████████████████ |
| Meta / Facebook | 2,612 | ███████████████████ |
| Coinbase | 1,416 | ██████████ |
| PayPal | 1,380 | ██████████ |
| Ledger | 977 | ███████ |
| Netflix | 849 | ██████ |
| Instagram | 757 | ██████ |
| Apple / iCloud | 713 | █████ |
| Google | 677 | █████ |
| MetaMask | 616 | █████ |
| Binance | 615 | █████ |
| Microsoft / Office 365 | 584 | ████ |
| Amazon | 551 | ████ |
| American Express | 253 | ██ |
| Booking.com | 244 | ██ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `invest` | 3,391 | ████████████████████ |
| `trade` | 2,816 | █████████████████ |
| `login` | 2,624 | ███████████████ |
| `service` | 2,417 | ██████████████ |
| `casino` | 2,003 | ████████████ |
| `support` | 1,810 | ███████████ |
| `connect` | 1,596 | █████████ |
| `wallet` | 1,486 | █████████ |
| `security` | 1,369 | ████████ |
| `secure` | 1,261 | ███████ |
| `bet` | 1,196 | ███████ |
| `account` | 1,129 | ███████ |

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
