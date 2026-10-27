# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-469%2C701-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-12%2C965-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--10--27_00%3A26_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-10-27 00:26 UTC</sub>

| | |
|---|---:|
| Active domains | **469,701** |
| Added in the last 24 hours | 12,965 |
| Added in the last 7 days | 153,967 |
| Added in the last 30 days | 153,967 |
| Retired in the last 30 days (offline or cleaned up) | 335,552 |
| Top-level domains represented | 602 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 30.4 % |
| Domains containing hyphens | 23.1 % |
| Average domain length | 19.9 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Sep 28 – Oct 27 (UTC)"
    x-axis ["28", "29", "30", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27"]
    y-axis "domains" 0 --> 100000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1227, 14240, 21381, 90492, 13281, 13149, 197]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Oct 21 – Oct 27 (UTC)"
    x-axis ["21", "22", "23", "24", "25", "26", "27"]
    y-axis "domains"
    line [472713, 588659, 629951, 748222, 574614, 473331, 469701]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-10-27 | 197 | 4,416 |
| 2026-10-26 | 13,149 | 115,925 |
| 2026-10-25 | 13,281 | 186,380 |
| 2026-10-24 | 90,492 | 16,398 |
| 2026-10-23 | 21,381 | 4,228 |
| 2026-10-22 | 14,240 | 7,320 |
| 2026-10-21 | 1,227 | 885 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.com` | 138,109 | 29.4 % | ████████████████████ |
| 2 | `.xyz` | 72,989 | 15.5 % | ███████████ |
| 3 | `.dev` | 37,162 | 7.9 % | █████ |
| 4 | `.click` | 25,562 | 5.4 % | ████ |
| 5 | `.shop` | 21,843 | 4.7 % | ███ |
| 6 | `.sbs` | 16,195 | 3.4 % | ██ |
| 7 | `.top` | 13,112 | 2.8 % | ██ |
| 8 | `.org` | 9,933 | 2.1 % | █ |
| 9 | `.net` | 9,565 | 2.0 % | █ |
| 10 | `.io` | 8,962 | 1.9 % | █ |
| 11 | `.app` | 7,114 | 1.5 % | █ |
| 12 | `.cc` | 7,029 | 1.5 % | █ |
| 13 | `.info` | 6,225 | 1.3 % | █ |
| 14 | `.live` | 5,301 | 1.1 % | █ |
| 15 | `.vip` | 4,435 | 0.9 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 138109
    ".xyz" : 72989
    ".dev" : 37162
    ".click" : 25562
    ".shop" : 21843
    "other" : 174036
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| WhatsApp | 3,873 | ████████████████████ |
| Coinbase | 3,098 | ████████████████ |
| Meta / Facebook | 2,436 | █████████████ |
| MetaMask | 1,381 | ███████ |
| Google | 1,362 | ███████ |
| PayPal | 1,339 | ███████ |
| Netflix | 1,104 | ██████ |
| Apple / iCloud | 1,040 | █████ |
| Ledger | 912 | █████ |
| Instagram | 906 | █████ |
| Amazon | 788 | ████ |
| Microsoft / Office 365 | 667 | ███ |
| Binance | 619 | ███ |
| Telegram | 597 | ███ |
| TikTok | 415 | ██ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 3,528 | ████████████████████ |
| `trade` | 2,680 | ███████████████ |
| `wallet` | 2,380 | █████████████ |
| `service` | 2,345 | █████████████ |
| `casino` | 2,101 | ████████████ |
| `invest` | 1,950 | ███████████ |
| `support` | 1,847 | ██████████ |
| `auth` | 1,605 | █████████ |
| `secure` | 1,506 | █████████ |
| `bet` | 1,299 | ███████ |
| `connect` | 1,281 | ███████ |
| `account` | 1,235 | ███████ |

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
