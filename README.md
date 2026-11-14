# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-333%2C407-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-19%2C625-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--11--14_11%3A45_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-11-14 11:45 UTC</sub>

| | |
|---|---:|
| Active domains | **333,407** |
| Added in the last 24 hours | 19,625 |
| Added in the last 7 days | 277,080 |
| Added in the last 30 days | 656,839 |
| Retired in the last 30 days (offline or cleaned up) | 77,832 |
| Top-level domains represented | 611 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 30.7 % |
| Domains containing hyphens | 27.0 % |
| Average domain length | 20.9 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Oct 16 – Nov 14 (UTC)"
    x-axis ["16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28", "29", "30", "31", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14"]
    y-axis "domains" 0 --> 400000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 292213, 87546, 58360, 41156, 47623, 52549, 48149, 19581, 9662]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Nov 6 – Nov 14 (UTC)"
    x-axis ["6", "7", "8", "9", "10", "11", "12", "13", "14"]
    y-axis "domains"
    line [272088, 346388, 396638, 382009, 418143, 355765, 344361, 334208, 333407]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-11-14 | 9,662 | 7,954 |
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
| 1 | `.com` | 94,768 | 28.4 % | ████████████████████ |
| 2 | `.app` | 24,578 | 7.4 % | █████ |
| 3 | `.org` | 24,357 | 7.3 % | █████ |
| 4 | `.cc` | 20,800 | 6.2 % | ████ |
| 5 | `.click` | 20,653 | 6.2 % | ████ |
| 6 | `.digital` | 16,593 | 5.0 % | ████ |
| 7 | `.sbs` | 10,620 | 3.2 % | ██ |
| 8 | `.shop` | 8,400 | 2.5 % | ██ |
| 9 | `.io` | 8,059 | 2.4 % | ██ |
| 10 | `.xyz` | 7,979 | 2.4 % | ██ |
| 11 | `.net` | 7,890 | 2.4 % | ██ |
| 12 | `.cd` | 7,350 | 2.2 % | ██ |
| 13 | `.top` | 6,472 | 1.9 % | █ |
| 14 | `.info` | 6,344 | 1.9 % | █ |
| 15 | `.cn` | 6,107 | 1.8 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 94768
    ".app" : 24578
    ".org" : 24357
    ".cc" : 20800
    ".click" : 20653
    "other" : 148251
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| WhatsApp | 3,831 | ████████████████████ |
| Google | 1,977 | ██████████ |
| MetaMask | 1,500 | ████████ |
| Coinbase | 1,484 | ████████ |
| Meta / Facebook | 1,437 | ████████ |
| Netflix | 1,148 | ██████ |
| Apple / iCloud | 1,036 | █████ |
| Microsoft / Office 365 | 1,026 | █████ |
| PayPal | 983 | █████ |
| Amazon | 947 | █████ |
| Instagram | 828 | ████ |
| OpenSea | 613 | ███ |
| Ledger | 342 | ██ |
| Telegram | 263 | █ |
| Spotify | 246 | █ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 3,335 | ████████████████████ |
| `service` | 2,276 | ██████████████ |
| `invest` | 1,525 | █████████ |
| `wallet` | 1,471 | █████████ |
| `support` | 1,293 | ████████ |
| `secure` | 1,250 | ███████ |
| `account` | 1,223 | ███████ |
| `casino` | 1,148 | ███████ |
| `update` | 1,116 | ███████ |
| `claim` | 1,113 | ███████ |
| `help` | 927 | ██████ |
| `connect` | 860 | █████ |

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
