# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-425%2C671-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-726%2C295-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--10--21_14%3A53_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-10-21 14:53 UTC</sub>

| | |
|---|---:|
| Active domains | **425,671** |
| Added in the last 24 hours | 726,295 |
| Added in the last 7 days | 2,055,037 |
| Added in the last 30 days | 2,160,977 |
| Retired in the last 30 days (offline or cleaned up) | 200,441 |
| Top-level domains represented | 480 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 16.3 % |
| Domains containing hyphens | 13.1 % |
| Average domain length | 17.4 characters |

## Activity, last 30 days

```mermaid
xychart-beta
    title "New domains per day (UTC)"
    x-axis ["09-22", "09-23", "09-24", "09-25", "09-26", "09-27", "09-28", "09-29", "09-30", "10-01", "10-02", "10-03", "10-04", "10-05", "10-06", "10-07", "10-08", "10-09", "10-10", "10-11", "10-12", "10-13", "10-14", "10-15", "10-16", "10-17", "10-18", "10-19", "10-20", "10-21"]
    y-axis "domains"
    bar [39726, 1734, 1225, 1043, 972, 1473, 1069, 439, 380, 250, 198, 214, 476, 378, 5, 0, 0, 0, 0, 0, 0, 541, 0, 57882, 0, 164033, 401329, 503696, 394145, 533411]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 10-21 | 533,411 | 111,841 |
| 10-20 | 394,145 | 6 |
| 10-19 | 503,696 | 12 |
| 10-18 | 401,329 | 28,527 |
| 10-17 | 164,033 | 656 |
| 10-16 | 0 | 0 |
| 10-15 | 57,882 | 937 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.xyz` | 208,014 | 48.9 % | ████████████████████ |
| 2 | `.com` | 90,325 | 21.2 % | █████████ |
| 3 | `.click` | 18,658 | 4.4 % | ██ |
| 4 | `.sbs` | 12,967 | 3.0 % | █ |
| 5 | `.shop` | 8,727 | 2.1 % | █ |
| 6 | `.net` | 7,125 | 1.7 % | █ |
| 7 | `.top` | 6,955 | 1.6 % | █ |
| 8 | `.org` | 5,950 | 1.4 % | █ |
| 9 | `.dev` | 5,505 | 1.3 % | █ |
| 10 | `.app` | 4,965 | 1.2 % | █ |
| 11 | `.live` | 4,431 | 1.0 % | █ |
| 12 | `.io` | 2,943 | 0.7 % | █ |
| 13 | `.baby` | 2,876 | 0.7 % | █ |
| 14 | `.info` | 2,853 | 0.7 % | █ |
| 15 | `.vip` | 2,630 | 0.6 % | █ |

```mermaid
pie showData title Share of the 8 most common TLDs
    ".xyz" : 208014
    ".com" : 90325
    ".click" : 18658
    ".sbs" : 12967
    ".shop" : 8727
    ".net" : 7125
    ".top" : 6955
    ".org" : 5950
    "other" : 66950
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| WhatsApp | 2,089 | ████████████████████ |
| Meta / Facebook | 1,318 | █████████████ |
| Coinbase | 1,224 | ████████████ |
| PayPal | 1,087 | ██████████ |
| Netflix | 737 | ███████ |
| Binance | 606 | ██████ |
| Google | 584 | ██████ |
| Apple / iCloud | 536 | █████ |
| Amazon | 447 | ████ |
| Microsoft / Office 365 | 438 | ████ |
| MetaMask | 381 | ████ |
| Ledger | 331 | ███ |
| Instagram | 281 | ███ |
| Booking.com | 237 | ██ |
| American Express | 235 | ██ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `invest` | 2,963 | ████████████████████ |
| `trade` | 2,555 | █████████████████ |
| `service` | 1,946 | █████████████ |
| `casino` | 1,738 | ████████████ |
| `login` | 1,319 | █████████ |
| `connect` | 1,097 | ███████ |
| `bet` | 1,061 | ███████ |
| `wallet` | 853 | ██████ |
| `update` | 794 | █████ |
| `support` | 793 | █████ |
| `secure` | 763 | █████ |
| `account` | 741 | █████ |

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
