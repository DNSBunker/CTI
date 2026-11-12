# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-346%2C850-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-51%2C695-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--11--12_11%3A19_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-11-12 11:19 UTC</sub>

| | |
|---|---:|
| Active domains | **346,850** |
| Added in the last 24 hours | 51,695 |
| Added in the last 7 days | 608,567 |
| Added in the last 30 days | 608,567 |
| Retired in the last 30 days (offline or cleaned up) | 52,406 |
| Top-level domains represented | 597 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 32.9 % |
| Domains containing hyphens | 30.4 % |
| Average domain length | 22.6 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Oct 14 – Nov 12 (UTC)"
    x-axis ["14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28", "29", "30", "31", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12"]
    y-axis "domains" 0 --> 400000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 292213, 87546, 58360, 41156, 47623, 52549, 29120]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Nov 6 – Nov 12 (UTC)"
    x-axis ["6", "7", "8", "9", "10", "11", "12"]
    y-axis "domains"
    line [272088, 346388, 396638, 382009, 418143, 355765, 346850]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-11-12 | 29,120 | 1,690 |
| 2026-11-11 | 52,549 | 6,737 |
| 2026-11-10 | 47,623 | 11,709 |
| 2026-11-09 | 41,156 | 10,905 |
| 2026-11-08 | 58,360 | 4,794 |
| 2026-11-07 | 87,546 | 6,920 |
| 2026-11-06 | 292,213 | 9,651 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.com` | 94,113 | 27.1 % | ████████████████████ |
| 2 | `.io` | 30,996 | 8.9 % | ███████ |
| 3 | `.app` | 26,237 | 7.6 % | ██████ |
| 4 | `.org` | 23,661 | 6.8 % | █████ |
| 5 | `.click` | 20,110 | 5.8 % | ████ |
| 6 | `.cc` | 17,472 | 5.0 % | ████ |
| 7 | `.digital` | 15,652 | 4.5 % | ███ |
| 8 | `.sbs` | 10,619 | 3.1 % | ██ |
| 9 | `.net` | 7,819 | 2.3 % | ██ |
| 10 | `.shop` | 7,685 | 2.2 % | ██ |
| 11 | `.xyz` | 7,332 | 2.1 % | ██ |
| 12 | `.top` | 6,277 | 1.8 % | █ |
| 13 | `.info` | 5,320 | 1.5 % | █ |
| 14 | `.cn` | 5,231 | 1.5 % | █ |
| 15 | `.link` | 4,043 | 1.2 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 94113
    ".io" : 30996
    ".app" : 26237
    ".org" : 23661
    ".click" : 20110
    "other" : 151733
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| Coinbase | 3,521 | ████████████████████ |
| WhatsApp | 3,370 | ███████████████████ |
| Amazon | 3,093 | ██████████████████ |
| MetaMask | 2,961 | █████████████████ |
| Google | 1,866 | ███████████ |
| Meta / Facebook | 1,479 | ████████ |
| Netflix | 1,136 | ██████ |
| Apple / iCloud | 1,090 | ██████ |
| Microsoft / Office 365 | 1,054 | ██████ |
| PayPal | 969 | ██████ |
| Instagram | 868 | █████ |
| OpenSea | 642 | ████ |
| Ledger | 480 | ███ |
| Telegram | 272 | ██ |
| Spotify | 244 | █ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 5,375 | ████████████████████ |
| `wallet` | 3,217 | ████████████ |
| `auth` | 2,534 | █████████ |
| `service` | 2,500 | █████████ |
| `help` | 1,949 | ███████ |
| `secure` | 1,722 | ██████ |
| `support` | 1,558 | ██████ |
| `invest` | 1,423 | █████ |
| `account` | 1,370 | █████ |
| `casino` | 1,121 | ████ |
| `claim` | 1,120 | ████ |
| `update` | 1,095 | ████ |

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
