# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-397%2C386-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-58%2C401-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--11--09_00%3A46_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-11-09 00:46 UTC</sub>

| | |
|---|---:|
| Active domains | **397,386** |
| Added in the last 24 hours | 58,401 |
| Added in the last 7 days | 439,073 |
| Added in the last 30 days | 439,073 |
| Retired in the last 30 days (offline or cleaned up) | 21,526 |
| Top-level domains represented | 595 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 42.4 % |
| Domains containing hyphens | 37.7 % |
| Average domain length | 24.3 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Oct 11 – Nov 9 (UTC)"
    x-axis ["11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28", "29", "30", "31", "1", "2", "3", "4", "5", "6", "7", "8", "9"]
    y-axis "domains" 0 --> 400000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 292213, 87546, 58360, 954]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Nov 6 – Nov 9 (UTC)"
    x-axis ["6", "7", "8", "9"]
    y-axis "domains"
    line [272088, 346388, 396638, 397386]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-11-09 | 954 | 161 |
| 2026-11-08 | 58,360 | 4,794 |
| 2026-11-07 | 87,546 | 6,920 |
| 2026-11-06 | 292,213 | 9,651 |
| 2026-11-05 | 0 | 0 |
| 2026-11-04 | 0 | 0 |
| 2026-11-03 | 0 | 0 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.com` | 102,216 | 25.7 % | ████████████████████ |
| 2 | `.dev` | 49,442 | 12.4 % | ██████████ |
| 3 | `.app` | 27,123 | 6.8 % | █████ |
| 4 | `.io` | 25,333 | 6.4 % | █████ |
| 5 | `.org` | 20,780 | 5.2 % | ████ |
| 6 | `.click` | 17,681 | 4.4 % | ███ |
| 7 | `.digital` | 14,613 | 3.7 % | ███ |
| 8 | `.cc` | 12,895 | 3.2 % | ███ |
| 9 | `.top` | 9,296 | 2.3 % | ██ |
| 10 | `.sbs` | 8,310 | 2.1 % | ██ |
| 11 | `.xyz` | 7,956 | 2.0 % | ██ |
| 12 | `.net` | 7,471 | 1.9 % | █ |
| 13 | `.shop` | 5,456 | 1.4 % | █ |
| 14 | `.info` | 4,920 | 1.2 % | █ |
| 15 | `.au` | 3,873 | 1.0 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 102216
    ".dev" : 49442
    ".app" : 27123
    ".io" : 25333
    ".org" : 20780
    "other" : 172492
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| Coinbase | 4,096 | ████████████████████ |
| Amazon | 3,958 | ███████████████████ |
| WhatsApp | 3,801 | ███████████████████ |
| MetaMask | 3,321 | ████████████████ |
| Meta / Facebook | 2,392 | ████████████ |
| Google | 2,094 | ██████████ |
| Apple / iCloud | 1,948 | ██████████ |
| PayPal | 1,531 | ███████ |
| Instagram | 1,508 | ███████ |
| Netflix | 1,491 | ███████ |
| Microsoft / Office 365 | 1,452 | ███████ |
| Ledger | 1,138 | ██████ |
| Telegram | 858 | ████ |
| TikTok | 736 | ████ |
| OpenSea | 690 | ███ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 6,172 | ████████████████████ |
| `wallet` | 3,491 | ███████████ |
| `service` | 2,691 | █████████ |
| `auth` | 2,612 | ████████ |
| `support` | 2,534 | ████████ |
| `help` | 2,290 | ███████ |
| `secure` | 2,052 | ███████ |
| `casino` | 1,940 | ██████ |
| `account` | 1,939 | ██████ |
| `claim` | 1,382 | ████ |
| `update` | 1,307 | ████ |
| `connect` | 1,276 | ████ |

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
