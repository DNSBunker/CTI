# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-40%2C308-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-41%2C634-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--10--29_22%3A16_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-10-29 22:16 UTC</sub>

| | |
|---|---:|
| Active domains | **40,308** |
| Added in the last 24 hours | 41,634 |
| Added in the last 7 days | 41,634 |
| Added in the last 30 days | 41,634 |
| Retired in the last 30 days (offline or cleaned up) | 0 |
| Top-level domains represented | 215 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 54.6 % |
| Domains containing hyphens | 59.9 % |
| Average domain length | 31.6 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Sep 30 – Oct 29 (UTC)"
    x-axis ["30", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28", "29"]
    y-axis "domains" 0 --> 50000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 41634]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-10-29 | 41,634 | 0 |
| 2026-10-28 | 0 | 0 |
| 2026-10-27 | 0 | 0 |
| 2026-10-26 | 0 | 0 |
| 2026-10-25 | 0 | 0 |
| 2026-10-24 | 0 | 0 |
| 2026-10-23 | 0 | 0 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.com` | 9,732 | 24.1 % | ████████████████████ |
| 2 | `.app` | 9,315 | 23.1 % | ███████████████████ |
| 3 | `.dev` | 9,217 | 22.9 % | ███████████████████ |
| 4 | `.org` | 3,007 | 7.5 % | ██████ |
| 5 | `.io` | 1,502 | 3.7 % | ███ |
| 6 | `.club` | 1,039 | 2.6 % | ██ |
| 7 | `.host` | 645 | 1.6 % | █ |
| 8 | `.link` | 560 | 1.4 % | █ |
| 9 | `.net` | 471 | 1.2 % | █ |
| 10 | `.pro` | 458 | 1.1 % | █ |
| 11 | `.shop` | 341 | 0.8 % | █ |
| 12 | `.site` | 324 | 0.8 % | █ |
| 13 | `.ph` | 251 | 0.6 % | █ |
| 14 | `.xyz` | 249 | 0.6 % | █ |
| 15 | `.top` | 243 | 0.6 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 9732
    ".app" : 9315
    ".dev" : 9217
    ".org" : 3007
    ".io" : 1502
    "other" : 7535
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| Meta / Facebook | 686 | ████████████████████ |
| Apple / iCloud | 602 | ██████████████████ |
| WhatsApp | 570 | █████████████████ |
| Instagram | 463 | █████████████ |
| Coinbase | 391 | ███████████ |
| PayPal | 370 | ███████████ |
| OpenSea | 360 | ██████████ |
| Netflix | 345 | ██████████ |
| Ledger | 275 | ████████ |
| MetaMask | 233 | ███████ |
| TikTok | 193 | ██████ |
| Telegram | 184 | █████ |
| Microsoft / Office 365 | 166 | █████ |
| Amazon | 137 | ████ |
| Google | 133 | ████ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 843 | ████████████████████ |
| `support` | 493 | ████████████ |
| `account` | 409 | ██████████ |
| `secure` | 385 | █████████ |
| `wallet` | 321 | ████████ |
| `service` | 303 | ███████ |
| `update` | 296 | ███████ |
| `auth` | 252 | ██████ |
| `help` | 207 | █████ |
| `security` | 196 | █████ |
| `claim` | 188 | ████ |
| `verify` | 181 | ████ |

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
