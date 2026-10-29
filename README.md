# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-32%2C368-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-33%2C513-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--10--29_19%3A15_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-10-29 19:15 UTC</sub>

| | |
|---|---:|
| Active domains | **32,368** |
| Added in the last 24 hours | 33,513 |
| Added in the last 7 days | 33,513 |
| Added in the last 30 days | 33,513 |
| Retired in the last 30 days (offline or cleaned up) | 0 |
| Top-level domains represented | 185 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 55.3 % |
| Domains containing hyphens | 61.0 % |
| Average domain length | 32.2 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Sep 30 – Oct 29 (UTC)"
    x-axis ["30", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28", "29"]
    y-axis "domains" 0 --> 40000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 33513]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-10-29 | 33,513 | 0 |
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
| 1 | `.com` | 8,555 | 26.4 % | ████████████████████ |
| 2 | `.app` | 8,320 | 25.7 % | ███████████████████ |
| 3 | `.dev` | 6,944 | 21.5 % | ████████████████ |
| 4 | `.org` | 1,345 | 4.2 % | ███ |
| 5 | `.io` | 912 | 2.8 % | ██ |
| 6 | `.host` | 625 | 1.9 % | █ |
| 7 | `.club` | 592 | 1.8 % | █ |
| 8 | `.link` | 552 | 1.7 % | █ |
| 9 | `.pro` | 385 | 1.2 % | █ |
| 10 | `.net` | 338 | 1.0 % | █ |
| 11 | `.shop` | 321 | 1.0 % | █ |
| 12 | `.site` | 319 | 1.0 % | █ |
| 13 | `.xyz` | 236 | 0.7 % | █ |
| 14 | `.page` | 232 | 0.7 % | █ |
| 15 | `.top` | 227 | 0.7 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 8555
    ".app" : 8320
    ".dev" : 6944
    ".org" : 1345
    ".io" : 912
    "other" : 6292
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| Meta / Facebook | 677 | ████████████████████ |
| Apple / iCloud | 578 | █████████████████ |
| WhatsApp | 538 | ████████████████ |
| Instagram | 450 | █████████████ |
| Coinbase | 390 | ████████████ |
| OpenSea | 360 | ███████████ |
| PayPal | 348 | ██████████ |
| Netflix | 342 | ██████████ |
| Ledger | 273 | ████████ |
| MetaMask | 230 | ███████ |
| TikTok | 173 | █████ |
| Microsoft / Office 365 | 166 | █████ |
| Telegram | 154 | █████ |
| Amazon | 137 | ████ |
| Google | 132 | ████ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 687 | ████████████████████ |
| `support` | 365 | ███████████ |
| `account` | 359 | ██████████ |
| `secure` | 343 | ██████████ |
| `service` | 261 | ████████ |
| `update` | 257 | ███████ |
| `wallet` | 244 | ███████ |
| `auth` | 231 | ███████ |
| `security` | 169 | █████ |
| `verify` | 161 | █████ |
| `help` | 151 | ████ |
| `connect` | 143 | ████ |

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
