# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-335%2C299-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-19%2C167-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--11--14_01%3A25_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-11-14 01:25 UTC</sub>

| | |
|---|---:|
| Active domains | **335,299** |
| Added in the last 24 hours | 19,167 |
| Added in the last 7 days | 268,597 |
| Added in the last 30 days | 648,356 |
| Retired in the last 30 days (offline or cleaned up) | 69,997 |
| Top-level domains represented | 612 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 31.6 % |
| Domains containing hyphens | 28.1 % |
| Average domain length | 21.6 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Oct 16 – Nov 14 (UTC)"
    x-axis ["16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28", "29", "30", "31", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14"]
    y-axis "domains" 0 --> 400000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 292213, 87546, 58360, 41156, 47623, 52549, 48149, 19581, 1179]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Nov 6 – Nov 14 (UTC)"
    x-axis ["6", "7", "8", "9", "10", "11", "12", "13", "14"]
    y-axis "domains"
    line [272088, 346388, 396638, 382009, 418143, 355765, 344361, 334208, 335299]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-11-14 | 1,179 | 119 |
| 2026-11-13 | 19,581 | 4,490 |
| 2026-11-12 | 48,149 | 14,672 |
| 2026-11-11 | 52,549 | 6,737 |
| 2026-11-10 | 47,623 | 11,709 |
| 2026-11-09 | 41,156 | 10,905 |
| 2026-11-08 | 58,360 | 4,794 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.com` | 97,900 | 29.2 % | ████████████████████ |
| 2 | `.app` | 24,489 | 7.3 % | █████ |
| 3 | `.org` | 24,350 | 7.3 % | █████ |
| 4 | `.click` | 20,862 | 6.2 % | ████ |
| 5 | `.cc` | 19,448 | 5.8 % | ████ |
| 6 | `.digital` | 16,660 | 5.0 % | ███ |
| 7 | `.sbs` | 10,903 | 3.3 % | ██ |
| 8 | `.shop` | 8,528 | 2.5 % | ██ |
| 9 | `.net` | 8,163 | 2.4 % | ██ |
| 10 | `.io` | 8,134 | 2.4 % | ██ |
| 11 | `.xyz` | 8,004 | 2.4 % | ██ |
| 12 | `.info` | 6,520 | 1.9 % | █ |
| 13 | `.top` | 6,410 | 1.9 % | █ |
| 14 | `.cn` | 5,873 | 1.8 % | █ |
| 15 | `.cd` | 5,804 | 1.7 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 97900
    ".app" : 24489
    ".org" : 24350
    ".click" : 20862
    ".cc" : 19448
    "other" : 148250
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| Amazon | 3,948 | ████████████████████ |
| WhatsApp | 3,738 | ███████████████████ |
| Google | 1,959 | ██████████ |
| MetaMask | 1,500 | ████████ |
| Coinbase | 1,481 | ████████ |
| Meta / Facebook | 1,433 | ███████ |
| Netflix | 1,134 | ██████ |
| Apple / iCloud | 1,094 | ██████ |
| Microsoft / Office 365 | 1,020 | █████ |
| PayPal | 979 | █████ |
| Instagram | 823 | ████ |
| OpenSea | 617 | ███ |
| Ledger | 339 | ██ |
| Telegram | 260 | █ |
| Spotify | 243 | █ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 3,332 | ████████████████████ |
| `service` | 2,428 | ███████████████ |
| `invest` | 1,524 | █████████ |
| `wallet` | 1,467 | █████████ |
| `support` | 1,275 | ████████ |
| `secure` | 1,235 | ███████ |
| `account` | 1,215 | ███████ |
| `casino` | 1,131 | ███████ |
| `claim` | 1,115 | ███████ |
| `update` | 1,092 | ███████ |
| `help` | 921 | ██████ |
| `connect` | 879 | █████ |

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
