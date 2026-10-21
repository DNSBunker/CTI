# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-471%2C660-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-647%2C597-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--10--21_17%3A51_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-10-21 17:51 UTC</sub>

| | |
|---|---:|
| Active domains | **471,660** |
| Added in the last 24 hours | 647,597 |
| Added in the last 7 days | 2,056,638 |
| Added in the last 30 days | 2,162,578 |
| Retired in the last 30 days (offline or cleaned up) | 200,441 |
| Top-level domains represented | 487 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 18.5 % |
| Domains containing hyphens | 17.4 % |
| Average domain length | 18.5 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Sep 22 – Oct 21 (UTC)"
    x-axis ["22", "23", "24", "25", "26", "27", "28", "29", "30", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21"]
    y-axis "domains" 0 --> 600000
    bar [39726, 1734, 1225, 1043, 972, 1473, 1069, 439, 380, 250, 198, 214, 476, 378, 5, 0, 0, 0, 0, 0, 0, 541, 0, 57882, 0, 164033, 401329, 503696, 394145, 535012]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-10-21 | 535,012 | 111,841 |
| 2026-10-20 | 394,145 | 6 |
| 2026-10-19 | 503,696 | 12 |
| 2026-10-18 | 401,329 | 28,527 |
| 2026-10-17 | 164,033 | 656 |
| 2026-10-16 | 0 | 0 |
| 2026-10-15 | 57,882 | 937 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.xyz` | 208,152 | 44.1 % | ████████████████████ |
| 2 | `.com` | 97,343 | 20.6 % | █████████ |
| 3 | `.dev` | 28,161 | 6.0 % | ███ |
| 4 | `.click` | 18,666 | 4.0 % | ██ |
| 5 | `.sbs` | 12,992 | 2.8 % | █ |
| 6 | `.shop` | 8,844 | 1.9 % | █ |
| 7 | `.net` | 7,714 | 1.6 % | █ |
| 8 | `.top` | 7,067 | 1.5 % | █ |
| 9 | `.org` | 6,041 | 1.3 % | █ |
| 10 | `.app` | 5,479 | 1.2 % | █ |
| 11 | `.live` | 4,448 | 0.9 % | █ |
| 12 | `.io` | 4,048 | 0.9 % | █ |
| 13 | `.me` | 3,935 | 0.8 % | █ |
| 14 | `.info` | 2,965 | 0.6 % | █ |
| 15 | `.baby` | 2,876 | 0.6 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".xyz" : 208152
    ".com" : 97343
    ".dev" : 28161
    ".click" : 18666
    ".sbs" : 12992
    "other" : 106346
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| Meta / Facebook | 2,372 | ████████████████████ |
| WhatsApp | 2,265 | ███████████████████ |
| Coinbase | 1,340 | ███████████ |
| PayPal | 1,235 | ██████████ |
| Ledger | 951 | ████████ |
| Netflix | 877 | ███████ |
| Instagram | 760 | ██████ |
| Apple / iCloud | 678 | ██████ |
| Binance | 622 | █████ |
| Google | 620 | █████ |
| MetaMask | 562 | █████ |
| Microsoft / Office 365 | 544 | █████ |
| Amazon | 500 | ████ |
| American Express | 241 | ██ |
| Booking.com | 240 | ██ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `invest` | 2,982 | ████████████████████ |
| `trade` | 2,639 | ██████████████████ |
| `login` | 2,316 | ████████████████ |
| `service` | 2,238 | ███████████████ |
| `casino` | 1,751 | ████████████ |
| `support` | 1,645 | ███████████ |
| `connect` | 1,341 | █████████ |
| `wallet` | 1,290 | █████████ |
| `bet` | 1,083 | ███████ |
| `secure` | 1,052 | ███████ |
| `account` | 1,032 | ███████ |
| `update` | 923 | ██████ |

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
