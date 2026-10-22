# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-504%2C527-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-9%2C501-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--10--22_13%3A45_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-10-22 13:45 UTC</sub>

| | |
|---|---:|
| Active domains | **504,527** |
| Added in the last 24 hours | 9,501 |
| Added in the last 7 days | 9,501 |
| Added in the last 30 days | 9,501 |
| Retired in the last 30 days (offline or cleaned up) | 1,611 |
| Top-level domains represented | 493 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 19.0 % |
| Domains containing hyphens | 17.1 % |
| Average domain length | 18.5 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Sep 23 – Oct 22 (UTC)"
    x-axis ["23", "24", "25", "26", "27", "28", "29", "30", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22"]
    y-axis "domains" 0 --> 10000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1227, 8274]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Oct 21 – Oct 22 (UTC)"
    x-axis ["21", "22"]
    y-axis "domains"
    line [472713, 504527]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-10-22 | 8,274 | 726 |
| 2026-10-21 | 1,227 | 885 |
| 2026-10-20 | 0 | 0 |
| 2026-10-19 | 0 | 0 |
| 2026-10-18 | 0 | 0 |
| 2026-10-17 | 0 | 0 |
| 2026-10-16 | 0 | 0 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.xyz` | 227,418 | 45.1 % | ████████████████████ |
| 2 | `.com` | 99,957 | 19.8 % | █████████ |
| 3 | `.dev` | 30,564 | 6.1 % | ███ |
| 4 | `.click` | 18,690 | 3.7 % | ██ |
| 5 | `.sbs` | 13,481 | 2.7 % | █ |
| 6 | `.shop` | 10,989 | 2.2 % | █ |
| 7 | `.net` | 8,137 | 1.6 % | █ |
| 8 | `.top` | 7,841 | 1.6 % | █ |
| 9 | `.org` | 6,167 | 1.2 % | █ |
| 10 | `.app` | 5,531 | 1.1 % | █ |
| 11 | `.live` | 4,509 | 0.9 % | █ |
| 12 | `.io` | 4,119 | 0.8 % | █ |
| 13 | `.me` | 3,970 | 0.8 % | █ |
| 14 | `.cc` | 3,129 | 0.6 % | █ |
| 15 | `.info` | 3,065 | 0.6 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".xyz" : 227418
    ".com" : 99957
    ".dev" : 30564
    ".click" : 18690
    ".sbs" : 13481
    "other" : 114417
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| Meta / Facebook | 2,560 | ████████████████████ |
| WhatsApp | 2,356 | ██████████████████ |
| Coinbase | 1,404 | ███████████ |
| PayPal | 1,369 | ███████████ |
| Ledger | 965 | ████████ |
| Netflix | 844 | ███████ |
| Instagram | 759 | ██████ |
| Apple / iCloud | 699 | █████ |
| Google | 662 | █████ |
| Binance | 617 | █████ |
| MetaMask | 616 | █████ |
| Microsoft / Office 365 | 551 | ████ |
| Amazon | 548 | ████ |
| American Express | 252 | ██ |
| Booking.com | 243 | ██ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `invest` | 3,095 | ████████████████████ |
| `trade` | 2,699 | █████████████████ |
| `login` | 2,539 | ████████████████ |
| `service` | 2,367 | ███████████████ |
| `casino` | 1,966 | █████████████ |
| `support` | 1,757 | ███████████ |
| `wallet` | 1,464 | █████████ |
| `connect` | 1,397 | █████████ |
| `bet` | 1,186 | ████████ |
| `secure` | 1,143 | ███████ |
| `account` | 1,117 | ███████ |
| `security` | 982 | ██████ |

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
