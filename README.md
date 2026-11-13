# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-326%2C715-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-22%2C480-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--11--13_12%3A09_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-11-13 12:09 UTC</sub>

| | |
|---|---:|
| Active domains | **326,715** |
| Added in the last 24 hours | 22,480 |
| Added in the last 7 days | 345,158 |
| Added in the last 30 days | 637,371 |
| Retired in the last 30 days (offline or cleaned up) | 68,556 |
| Top-level domains represented | 605 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 31.6 % |
| Domains containing hyphens | 28.3 % |
| Average domain length | 21.7 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Oct 15 – Nov 13 (UTC)"
    x-axis ["15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28", "29", "30", "31", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13"]
    y-axis "domains" 0 --> 400000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 292213, 87546, 58360, 41156, 47623, 52549, 48149, 9775]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Nov 6 – Nov 13 (UTC)"
    x-axis ["6", "7", "8", "9", "10", "11", "12", "13"]
    y-axis "domains"
    line [272088, 346388, 396638, 382009, 418143, 355765, 344361, 326715]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-11-13 | 9,775 | 3,168 |
| 2026-11-12 | 48,149 | 14,672 |
| 2026-11-11 | 52,549 | 6,737 |
| 2026-11-10 | 47,623 | 11,709 |
| 2026-11-09 | 41,156 | 10,905 |
| 2026-11-08 | 58,360 | 4,794 |
| 2026-11-07 | 87,546 | 6,920 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.com` | 95,705 | 29.3 % | ████████████████████ |
| 2 | `.app` | 24,449 | 7.5 % | █████ |
| 3 | `.org` | 24,143 | 7.4 % | █████ |
| 4 | `.click` | 20,811 | 6.4 % | ████ |
| 5 | `.cc` | 17,875 | 5.5 % | ████ |
| 6 | `.digital` | 16,574 | 5.1 % | ███ |
| 7 | `.sbs` | 10,833 | 3.3 % | ██ |
| 8 | `.io` | 8,100 | 2.5 % | ██ |
| 9 | `.shop` | 8,063 | 2.5 % | ██ |
| 10 | `.net` | 7,971 | 2.4 % | ██ |
| 11 | `.xyz` | 7,868 | 2.4 % | ██ |
| 12 | `.info` | 6,393 | 2.0 % | █ |
| 13 | `.top` | 6,289 | 1.9 % | █ |
| 14 | `.cn` | 5,486 | 1.7 % | █ |
| 15 | `.cd` | 4,148 | 1.3 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 95705
    ".app" : 24449
    ".org" : 24143
    ".click" : 20811
    ".cc" : 17875
    "other" : 143732
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| WhatsApp | 3,693 | ████████████████████ |
| Amazon | 3,382 | ██████████████████ |
| Google | 1,913 | ██████████ |
| MetaMask | 1,497 | ████████ |
| Coinbase | 1,479 | ████████ |
| Meta / Facebook | 1,429 | ████████ |
| Netflix | 1,128 | ██████ |
| Apple / iCloud | 1,127 | ██████ |
| Microsoft / Office 365 | 1,011 | █████ |
| PayPal | 973 | █████ |
| Instagram | 819 | ████ |
| OpenSea | 615 | ███ |
| Ledger | 338 | ██ |
| Telegram | 259 | █ |
| Spotify | 240 | █ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 3,312 | ████████████████████ |
| `service` | 2,401 | ██████████████ |
| `invest` | 1,510 | █████████ |
| `wallet` | 1,462 | █████████ |
| `support` | 1,265 | ████████ |
| `secure` | 1,226 | ███████ |
| `account` | 1,208 | ███████ |
| `claim` | 1,094 | ███████ |
| `casino` | 1,085 | ███████ |
| `update` | 1,059 | ██████ |
| `help` | 917 | ██████ |
| `connect` | 865 | █████ |

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
