# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-331%2C876-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-18%2C822-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--11--13_19%3A36_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-11-13 19:36 UTC</sub>

| | |
|---|---:|
| Active domains | **331,876** |
| Added in the last 24 hours | 18,822 |
| Added in the last 7 days | 351,777 |
| Added in the last 30 days | 643,990 |
| Retired in the last 30 days (offline or cleaned up) | 69,425 |
| Top-level domains represented | 610 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 31.6 % |
| Domains containing hyphens | 28.2 % |
| Average domain length | 21.6 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Oct 15 – Nov 13 (UTC)"
    x-axis ["15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28", "29", "30", "31", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13"]
    y-axis "domains" 0 --> 400000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 292213, 87546, 58360, 41156, 47623, 52549, 48149, 16394]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Nov 6 – Nov 13 (UTC)"
    x-axis ["6", "7", "8", "9", "10", "11", "12", "13"]
    y-axis "domains"
    line [272088, 346388, 396638, 382009, 418143, 355765, 344361, 331876]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-11-13 | 16,394 | 4,037 |
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
| 1 | `.com` | 96,883 | 29.2 % | ████████████████████ |
| 2 | `.app` | 24,480 | 7.4 % | █████ |
| 3 | `.org` | 24,251 | 7.3 % | █████ |
| 4 | `.click` | 20,828 | 6.3 % | ████ |
| 5 | `.cc` | 18,988 | 5.7 % | ████ |
| 6 | `.digital` | 16,628 | 5.0 % | ███ |
| 7 | `.sbs` | 10,905 | 3.3 % | ██ |
| 8 | `.shop` | 8,360 | 2.5 % | ██ |
| 9 | `.io` | 8,123 | 2.4 % | ██ |
| 10 | `.net` | 8,077 | 2.4 % | ██ |
| 11 | `.xyz` | 7,961 | 2.4 % | ██ |
| 12 | `.info` | 6,425 | 1.9 % | █ |
| 13 | `.top` | 6,361 | 1.9 % | █ |
| 14 | `.cn` | 5,762 | 1.7 % | █ |
| 15 | `.cd` | 5,279 | 1.6 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 96883
    ".app" : 24480
    ".org" : 24251
    ".click" : 20828
    ".cc" : 18988
    "other" : 146446
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| WhatsApp | 3,729 | ████████████████████ |
| Amazon | 3,674 | ████████████████████ |
| Google | 1,941 | ██████████ |
| MetaMask | 1,499 | ████████ |
| Coinbase | 1,480 | ████████ |
| Meta / Facebook | 1,431 | ████████ |
| Netflix | 1,134 | ██████ |
| Apple / iCloud | 1,098 | ██████ |
| Microsoft / Office 365 | 1,017 | █████ |
| PayPal | 977 | █████ |
| Instagram | 821 | ████ |
| OpenSea | 616 | ███ |
| Ledger | 341 | ██ |
| Telegram | 259 | █ |
| Spotify | 241 | █ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 3,330 | ████████████████████ |
| `service` | 2,419 | ███████████████ |
| `invest` | 1,521 | █████████ |
| `wallet` | 1,468 | █████████ |
| `support` | 1,270 | ████████ |
| `secure` | 1,234 | ███████ |
| `account` | 1,214 | ███████ |
| `claim` | 1,125 | ███████ |
| `casino` | 1,111 | ███████ |
| `update` | 1,077 | ██████ |
| `help` | 920 | ██████ |
| `connect` | 876 | █████ |

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
