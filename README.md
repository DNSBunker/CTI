# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-374%2C527-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-14%2C977-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--10--29_07%3A08_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-10-29 07:08 UTC</sub>

| | |
|---|---:|
| Active domains | **374,527** |
| Added in the last 24 hours | 14,977 |
| Added in the last 7 days | 195,232 |
| Added in the last 30 days | 210,699 |
| Retired in the last 30 days (offline or cleaned up) | 487,224 |
| Top-level domains represented | 600 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 32.7 % |
| Domains containing hyphens | 27.3 % |
| Average domain length | 21.0 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Sep 30 – Oct 29 (UTC)"
    x-axis ["30", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28", "29"]
    y-axis "domains" 0 --> 100000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1227, 14240, 21381, 90492, 13281, 13149, 36078, 15350, 5501]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Oct 21 – Oct 29 (UTC)"
    x-axis ["21", "22", "23", "24", "25", "26", "27", "28", "29"]
    y-axis "domains"
    line [472713, 588659, 629951, 748222, 574614, 473331, 457795, 371010, 374527]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-10-29 | 5,501 | 1,525 |
| 2026-10-28 | 15,350 | 99,912 |
| 2026-10-27 | 36,078 | 54,651 |
| 2026-10-26 | 13,149 | 115,925 |
| 2026-10-25 | 13,281 | 186,380 |
| 2026-10-24 | 90,492 | 16,398 |
| 2026-10-23 | 21,381 | 4,228 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.com` | 113,275 | 30.2 % | ████████████████████ |
| 2 | `.dev` | 39,438 | 10.5 % | ███████ |
| 3 | `.xyz` | 31,048 | 8.3 % | █████ |
| 4 | `.shop` | 13,738 | 3.7 % | ██ |
| 5 | `.org` | 11,554 | 3.1 % | ██ |
| 6 | `.click` | 10,285 | 2.7 % | ██ |
| 7 | `.net` | 9,979 | 2.7 % | ██ |
| 8 | `.top` | 9,393 | 2.5 % | ██ |
| 9 | `.sbs` | 9,327 | 2.5 % | ██ |
| 10 | `.io` | 8,437 | 2.3 % | █ |
| 11 | `.cc` | 7,385 | 2.0 % | █ |
| 12 | `.info` | 7,090 | 1.9 % | █ |
| 13 | `.app` | 6,918 | 1.8 % | █ |
| 14 | `.br` | 5,760 | 1.5 % | █ |
| 15 | `.digital` | 5,724 | 1.5 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 113275
    ".dev" : 39438
    ".xyz" : 31048
    ".shop" : 13738
    ".org" : 11554
    "other" : 165474
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| WhatsApp | 4,326 | ████████████████████ |
| Coinbase | 2,856 | █████████████ |
| Meta / Facebook | 1,636 | ████████ |
| MetaMask | 1,326 | ██████ |
| Google | 1,189 | █████ |
| Apple / iCloud | 1,032 | █████ |
| Netflix | 1,031 | █████ |
| PayPal | 928 | ████ |
| Instagram | 899 | ████ |
| Ledger | 770 | ████ |
| Telegram | 744 | ███ |
| Amazon | 740 | ███ |
| Microsoft / Office 365 | 592 | ███ |
| TikTok | 507 | ██ |
| Binance | 408 | ██ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 3,127 | ████████████████████ |
| `trade` | 2,490 | ████████████████ |
| `wallet` | 1,956 | █████████████ |
| `service` | 1,915 | ████████████ |
| `support` | 1,670 | ███████████ |
| `auth` | 1,525 | ██████████ |
| `invest` | 1,378 | █████████ |
| `secure` | 1,353 | █████████ |
| `casino` | 1,343 | █████████ |
| `bet` | 1,129 | ███████ |
| `connect` | 1,046 | ███████ |
| `account` | 1,034 | ███████ |

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
