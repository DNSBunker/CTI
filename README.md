# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-454%2C503-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-31%2C499-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--10--27_11%3A43_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-10-27 11:43 UTC</sub>

| | |
|---|---:|
| Active domains | **454,503** |
| Added in the last 24 hours | 31,499 |
| Added in the last 7 days | 178,506 |
| Added in the last 30 days | 178,506 |
| Retired in the last 30 days (offline or cleaned up) | 378,060 |
| Top-level domains represented | 605 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 30.8 % |
| Domains containing hyphens | 23.3 % |
| Average domain length | 20.0 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Sep 28 – Oct 27 (UTC)"
    x-axis ["28", "29", "30", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27"]
    y-axis "domains" 0 --> 100000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1227, 14240, 21381, 90492, 13281, 13149, 24736]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Oct 21 – Oct 27 (UTC)"
    x-axis ["21", "22", "23", "24", "25", "26", "27"]
    y-axis "domains"
    line [472713, 588659, 629951, 748222, 574614, 473331, 454503]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-10-27 | 24,736 | 46,924 |
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
| 1 | `.com` | 128,853 | 28.4 % | ████████████████████ |
| 2 | `.xyz` | 66,093 | 14.5 % | ██████████ |
| 3 | `.dev` | 35,289 | 7.8 % | █████ |
| 4 | `.shop` | 21,624 | 4.8 % | ███ |
| 5 | `.click` | 21,396 | 4.7 % | ███ |
| 6 | `.sbs` | 14,580 | 3.2 % | ██ |
| 7 | `.top` | 12,464 | 2.7 % | ██ |
| 8 | `.org` | 10,168 | 2.2 % | ██ |
| 9 | `.net` | 9,932 | 2.2 % | ██ |
| 10 | `.io` | 8,547 | 1.9 % | █ |
| 11 | `.info` | 7,398 | 1.6 % | █ |
| 12 | `.app` | 7,023 | 1.5 % | █ |
| 13 | `.cc` | 6,953 | 1.5 % | █ |
| 14 | `.digital` | 5,806 | 1.3 % | █ |
| 15 | `.live` | 5,160 | 1.1 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 128853
    ".xyz" : 66093
    ".dev" : 35289
    ".shop" : 21624
    ".click" : 21396
    "other" : 181248
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| WhatsApp | 3,831 | ████████████████████ |
| Coinbase | 2,798 | ███████████████ |
| Meta / Facebook | 1,619 | ████████ |
| MetaMask | 1,299 | ███████ |
| Google | 1,262 | ███████ |
| Apple / iCloud | 1,089 | ██████ |
| Netflix | 1,014 | █████ |
| PayPal | 1,006 | █████ |
| Instagram | 884 | █████ |
| Amazon | 784 | ████ |
| Ledger | 784 | ████ |
| Telegram | 676 | ████ |
| Microsoft / Office 365 | 640 | ███ |
| TikTok | 482 | ███ |
| Binance | 404 | ██ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 3,177 | ████████████████████ |
| `trade` | 2,634 | █████████████████ |
| `service` | 2,365 | ███████████████ |
| `casino` | 2,035 | █████████████ |
| `wallet` | 1,987 | █████████████ |
| `invest` | 1,895 | ████████████ |
| `support` | 1,720 | ███████████ |
| `auth` | 1,550 | ██████████ |
| `secure` | 1,413 | █████████ |
| `bet` | 1,266 | ████████ |
| `connect` | 1,165 | ███████ |
| `account` | 1,121 | ███████ |

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
