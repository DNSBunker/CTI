# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-235%2C118-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-26%2C314-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--11--01_17%3A05_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-11-01 17:05 UTC</sub>

| | |
|---|---:|
| Active domains | **235,118** |
| Added in the last 24 hours | 26,314 |
| Added in the last 7 days | 192,684 |
| Added in the last 30 days | 229,532 |
| Retired in the last 30 days (offline or cleaned up) | 653,189 |
| Top-level domains represented | 526 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 33.8 % |
| Domains containing hyphens | 29.3 % |
| Average domain length | 20.2 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Oct 3 – Nov 1 (UTC)"
    x-axis ["3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28", "29", "30", "31", "1"]
    y-axis "domains" 0 --> 100000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1227, 14240, 21381, 90492, 13281, 13149, 36078, 15350, 11978, 0, 0, 12356]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Oct 21 – Nov 1 (UTC)"
    x-axis ["21", "22", "23", "24", "25", "26", "27", "28", "29", "30", "31", "1"]
    y-axis "domains"
    line [472713, 588659, 629951, 748222, 574614, 473331, 457795, 371010, 376945, 376945, 376945, 235118]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-11-01 | 12,356 | 162,034 |
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
| 1 | `.com` | 82,010 | 34.9 % | ████████████████████ |
| 2 | `.dev` | 20,993 | 8.9 % | █████ |
| 3 | `.shop` | 10,124 | 4.3 % | ██ |
| 4 | `.click` | 8,133 | 3.5 % | ██ |
| 5 | `.top` | 7,684 | 3.3 % | ██ |
| 6 | `.sbs` | 7,607 | 3.2 % | ██ |
| 7 | `.net` | 7,231 | 3.1 % | ██ |
| 8 | `.org` | 6,999 | 3.0 % | ██ |
| 9 | `.xyz` | 6,535 | 2.8 % | ██ |
| 10 | `.app` | 5,057 | 2.2 % | █ |
| 11 | `.cc` | 4,759 | 2.0 % | █ |
| 12 | `.info` | 4,562 | 1.9 % | █ |
| 13 | `.live` | 4,562 | 1.9 % | █ |
| 14 | `.cn` | 4,279 | 1.8 % | █ |
| 15 | `.io` | 4,056 | 1.7 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 82010
    ".dev" : 20993
    ".shop" : 10124
    ".click" : 8133
    ".top" : 7684
    "other" : 106174
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| WhatsApp | 4,309 | ████████████████████ |
| Coinbase | 1,343 | ██████ |
| Meta / Facebook | 855 | ████ |
| Google | 723 | ███ |
| Apple / iCloud | 709 | ███ |
| Netflix | 614 | ███ |
| MetaMask | 609 | ███ |
| Telegram | 499 | ██ |
| Ledger | 497 | ██ |
| PayPal | 448 | ██ |
| Amazon | 397 | ██ |
| Microsoft / Office 365 | 371 | ██ |
| Instagram | 356 | ██ |
| TikTok | 283 | █ |
| American Express | 263 | █ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `trade` | 2,322 | ████████████████████ |
| `casino` | 1,769 | ███████████████ |
| `login` | 1,360 | ████████████ |
| `service` | 1,217 | ██████████ |
| `bet` | 1,151 | ██████████ |
| `support` | 1,096 | █████████ |
| `invest` | 865 | ███████ |
| `secure` | 817 | ███████ |
| `wallet` | 777 | ███████ |
| `update` | 621 | █████ |
| `account` | 590 | █████ |
| `verify` | 521 | ████ |

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
