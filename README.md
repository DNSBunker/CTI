# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-171%2C096-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-42%2C216-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--11--12_10%3A03_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-11-12 10:03 UTC</sub>

| | |
|---|---:|
| Active domains | **171,096** |
| Added in the last 24 hours | 42,216 |
| Added in the last 7 days | 596,246 |
| Added in the last 30 days | 596,246 |
| Retired in the last 30 days (offline or cleaned up) | 52,327 |
| Top-level domains represented | 358 |
| Internationalized (IDN / punycode) domains | 0.0 % |
| Domains containing digits | 43.7 % |
| Domains containing hyphens | 44.0 % |
| Average domain length | 28.2 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Oct 14 – Nov 12 (UTC)"
    x-axis ["14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28", "29", "30", "31", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12"]
    y-axis "domains" 0 --> 400000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 292213, 87546, 58360, 41156, 47623, 52549, 16799]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Nov 6 – Nov 12 (UTC)"
    x-axis ["6", "7", "8", "9", "10", "11", "12"]
    y-axis "domains"
    line [272088, 346388, 396638, 382009, 418143, 355765, 171096]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-11-12 | 16,799 | 1,611 |
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
| 1 | `.com` | 36,941 | 21.6 % | ████████████████████ |
| 2 | `.io` | 28,776 | 16.8 % | ████████████████ |
| 3 | `.app` | 25,744 | 15.0 % | ██████████████ |
| 4 | `.org` | 19,966 | 11.7 % | ███████████ |
| 5 | `.cc` | 12,830 | 7.5 % | ███████ |
| 6 | `.au` | 4,947 | 2.9 % | ███ |
| 7 | `.net` | 4,646 | 2.7 % | ███ |
| 8 | `.cn` | 3,845 | 2.2 % | ██ |
| 9 | `.link` | 3,767 | 2.2 % | ██ |
| 10 | `.in` | 2,100 | 1.2 % | █ |
| 11 | `.cd` | 1,669 | 1.0 % | █ |
| 12 | `.br` | 1,470 | 0.9 % | █ |
| 13 | `.uk` | 1,360 | 0.8 % | █ |
| 14 | `.page` | 1,307 | 0.8 % | █ |
| 15 | `.site` | 1,235 | 0.7 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 36941
    ".io" : 28776
    ".app" : 25744
    ".org" : 19966
    ".cc" : 12830
    "other" : 46839
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| MetaMask | 3,044 | ████████████████████ |
| Amazon | 3,000 | ████████████████████ |
| Coinbase | 2,997 | ████████████████████ |
| WhatsApp | 2,993 | ████████████████████ |
| Meta / Facebook | 1,397 | █████████ |
| Instagram | 1,008 | ███████ |
| Netflix | 959 | ██████ |
| OpenSea | 604 | ████ |
| Microsoft / Office 365 | 552 | ████ |
| Google | 488 | ███ |
| Ledger | 383 | ███ |
| PayPal | 373 | ██ |
| Apple / iCloud | 339 | ██ |
| Airbnb | 134 | █ |
| Trust Wallet | 124 | █ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 5,163 | ████████████████████ |
| `wallet` | 3,039 | ████████████ |
| `auth` | 2,416 | █████████ |
| `help` | 2,184 | ████████ |
| `secure` | 1,330 | █████ |
| `support` | 1,232 | █████ |
| `service` | 1,223 | █████ |
| `account` | 1,105 | ████ |
| `claim` | 976 | ████ |
| `update` | 735 | ███ |
| `connect` | 666 | ███ |
| `verify` | 487 | ██ |

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
