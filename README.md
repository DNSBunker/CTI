# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-336%2C602-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-20%2C032-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--11--14_16%3A59_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-11-14 16:59 UTC</sub>

| | |
|---|---:|
| Active domains | **336,602** |
| Added in the last 24 hours | 20,032 |
| Added in the last 7 days | 281,922 |
| Added in the last 30 days | 661,681 |
| Retired in the last 30 days (offline or cleaned up) | 79,062 |
| Top-level domains represented | 610 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 30.6 % |
| Domains containing hyphens | 26.8 % |
| Average domain length | 20.8 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Oct 16 – Nov 14 (UTC)"
    x-axis ["16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28", "29", "30", "31", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14"]
    y-axis "domains" 0 --> 400000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 292213, 87546, 58360, 41156, 47623, 52549, 48149, 19581, 14504]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Nov 6 – Nov 14 (UTC)"
    x-axis ["6", "7", "8", "9", "10", "11", "12", "13", "14"]
    y-axis "domains"
    line [272088, 346388, 396638, 382009, 418143, 355765, 344361, 334208, 336602]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-11-14 | 14,504 | 9,184 |
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
| 1 | `.com` | 95,195 | 28.3 % | ████████████████████ |
| 2 | `.app` | 24,600 | 7.3 % | █████ |
| 3 | `.org` | 24,402 | 7.2 % | █████ |
| 4 | `.cc` | 21,563 | 6.4 % | █████ |
| 5 | `.click` | 20,628 | 6.1 % | ████ |
| 6 | `.digital` | 16,589 | 4.9 % | ███ |
| 7 | `.sbs` | 10,541 | 3.1 % | ██ |
| 8 | `.shop` | 8,518 | 2.5 % | ██ |
| 9 | `.cd` | 8,443 | 2.5 % | ██ |
| 10 | `.io` | 8,073 | 2.4 % | ██ |
| 11 | `.xyz` | 7,991 | 2.4 % | ██ |
| 12 | `.net` | 7,898 | 2.3 % | ██ |
| 13 | `.top` | 6,504 | 1.9 % | █ |
| 14 | `.info` | 6,333 | 1.9 % | █ |
| 15 | `.cn` | 6,285 | 1.9 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 95195
    ".app" : 24600
    ".org" : 24402
    ".cc" : 21563
    ".click" : 20628
    "other" : 150214
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| WhatsApp | 3,863 | ████████████████████ |
| Google | 1,993 | ██████████ |
| MetaMask | 1,501 | ████████ |
| Coinbase | 1,488 | ████████ |
| Meta / Facebook | 1,437 | ███████ |
| Netflix | 1,149 | ██████ |
| Microsoft / Office 365 | 1,029 | █████ |
| Apple / iCloud | 1,006 | █████ |
| PayPal | 985 | █████ |
| Amazon | 954 | █████ |
| Instagram | 829 | ████ |
| OpenSea | 612 | ███ |
| Ledger | 346 | ██ |
| Telegram | 262 | █ |
| Spotify | 246 | █ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 3,342 | ████████████████████ |
| `service` | 2,282 | ██████████████ |
| `invest` | 1,526 | █████████ |
| `wallet` | 1,474 | █████████ |
| `support` | 1,293 | ████████ |
| `secure` | 1,252 | ███████ |
| `account` | 1,220 | ███████ |
| `casino` | 1,174 | ███████ |
| `update` | 1,124 | ███████ |
| `claim` | 1,109 | ███████ |
| `help` | 928 | ██████ |
| `connect` | 854 | █████ |

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
