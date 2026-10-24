# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-697%2C733-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-84%2C210-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--10--24_07%3A56_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-10-24 07:56 UTC</sub>

| | |
|---|---:|
| Active domains | **697,733** |
| Added in the last 24 hours | 84,210 |
| Added in the last 7 days | 103,883 |
| Added in the last 30 days | 103,883 |
| Retired in the last 30 days (offline or cleaned up) | 13,768 |
| Top-level domains represented | 587 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 18.9 % |
| Domains containing hyphens | 16.1 % |
| Average domain length | 18.5 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Sep 25 – Oct 24 (UTC)"
    x-axis ["25", "26", "27", "28", "29", "30", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24"]
    y-axis "domains" 0 --> 80000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1227, 14240, 21381, 67035]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Oct 21 – Oct 24 (UTC)"
    x-axis ["21", "22", "23", "24"]
    y-axis "domains"
    line [472713, 588659, 629951, 697733]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-10-24 | 67,035 | 1,335 |
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
| 1 | `.xyz` | 307,353 | 44.1 % | ████████████████████ |
| 2 | `.com` | 135,004 | 19.3 % | █████████ |
| 3 | `.dev` | 40,986 | 5.9 % | ███ |
| 4 | `.click` | 26,255 | 3.8 % | ██ |
| 5 | `.sbs` | 17,429 | 2.5 % | █ |
| 6 | `.shop` | 13,863 | 2.0 % | █ |
| 7 | `.org` | 11,854 | 1.7 % | █ |
| 8 | `.top` | 11,757 | 1.7 % | █ |
| 9 | `.net` | 9,954 | 1.4 % | █ |
| 10 | `.io` | 8,182 | 1.2 % | █ |
| 11 | `.app` | 6,723 | 1.0 % | █ |
| 12 | `.cc` | 6,379 | 0.9 % | █ |
| 13 | `.info` | 5,495 | 0.8 % | █ |
| 14 | `.live` | 5,270 | 0.8 % | █ |
| 15 | `.digital` | 4,146 | 0.6 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".xyz" : 307353
    ".com" : 135004
    ".dev" : 40986
    ".click" : 26255
    ".sbs" : 17429
    "other" : 170706
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| WhatsApp | 3,484 | ████████████████████ |
| Meta / Facebook | 2,845 | ████████████████ |
| Coinbase | 2,451 | ██████████████ |
| Google | 1,659 | ██████████ |
| PayPal | 1,497 | █████████ |
| MetaMask | 1,231 | ███████ |
| Ledger | 1,126 | ██████ |
| Apple / iCloud | 987 | ██████ |
| Netflix | 939 | █████ |
| Instagram | 805 | █████ |
| Microsoft / Office 365 | 690 | ████ |
| Amazon | 654 | ████ |
| Binance | 623 | ████ |
| Telegram | 397 | ██ |
| American Express | 362 | ██ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `invest` | 3,799 | ████████████████████ |
| `login` | 3,704 | ███████████████████ |
| `trade` | 3,048 | ████████████████ |
| `service` | 2,826 | ███████████████ |
| `casino` | 2,625 | ██████████████ |
| `wallet` | 2,583 | ██████████████ |
| `support` | 2,119 | ███████████ |
| `connect` | 2,049 | ███████████ |
| `secure` | 1,517 | ████████ |
| `security` | 1,506 | ████████ |
| `bet` | 1,461 | ████████ |
| `account` | 1,414 | ███████ |

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
