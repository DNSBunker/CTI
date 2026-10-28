# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-458%2C762-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-36%2C659-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--10--28_04%3A57_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-10-28 04:57 UTC</sub>

| | |
|---|---:|
| Active domains | **458,762** |
| Added in the last 24 hours | 36,659 |
| Added in the last 7 days | 192,504 |
| Added in the last 30 days | 193,731 |
| Retired in the last 30 days (offline or cleaned up) | 388,250 |
| Top-level domains represented | 604 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 31.4 % |
| Domains containing hyphens | 23.5 % |
| Average domain length | 20.2 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Sep 29 – Oct 28 (UTC)"
    x-axis ["29", "30", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28"]
    y-axis "domains" 0 --> 100000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1227, 14240, 21381, 90492, 13281, 13149, 36078, 3883]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Oct 21 – Oct 28 (UTC)"
    x-axis ["21", "22", "23", "24", "25", "26", "27", "28"]
    y-axis "domains"
    line [472713, 588659, 629951, 748222, 574614, 473331, 457795, 458762]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-10-28 | 3,883 | 2,463 |
| 2026-10-27 | 36,078 | 54,651 |
| 2026-10-26 | 13,149 | 115,925 |
| 2026-10-25 | 13,281 | 186,380 |
| 2026-10-24 | 90,492 | 16,398 |
| 2026-10-23 | 21,381 | 4,228 |
| 2026-10-22 | 14,240 | 7,320 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.com` | 131,068 | 28.6 % | ████████████████████ |
| 2 | `.xyz` | 65,117 | 14.2 % | ██████████ |
| 3 | `.dev` | 36,838 | 8.0 % | ██████ |
| 4 | `.shop` | 21,674 | 4.7 % | ███ |
| 5 | `.click` | 21,416 | 4.7 % | ███ |
| 6 | `.sbs` | 14,606 | 3.2 % | ██ |
| 7 | `.top` | 12,427 | 2.7 % | ██ |
| 8 | `.org` | 11,347 | 2.5 % | ██ |
| 9 | `.net` | 10,279 | 2.2 % | ██ |
| 10 | `.io` | 8,430 | 1.8 % | █ |
| 11 | `.info` | 7,444 | 1.6 % | █ |
| 12 | `.cc` | 7,390 | 1.6 % | █ |
| 13 | `.app` | 7,186 | 1.6 % | █ |
| 14 | `.digital` | 5,769 | 1.3 % | █ |
| 15 | `.live` | 5,173 | 1.1 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 131068
    ".xyz" : 65117
    ".dev" : 36838
    ".shop" : 21674
    ".click" : 21416
    "other" : 182649
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| WhatsApp | 4,071 | ████████████████████ |
| Coinbase | 2,830 | ██████████████ |
| Meta / Facebook | 1,646 | ████████ |
| MetaMask | 1,319 | ██████ |
| Google | 1,249 | ██████ |
| Apple / iCloud | 1,076 | █████ |
| Netflix | 1,074 | █████ |
| PayPal | 980 | █████ |
| Instagram | 906 | ████ |
| Ledger | 791 | ████ |
| Amazon | 775 | ████ |
| Telegram | 718 | ████ |
| Microsoft / Office 365 | 642 | ███ |
| TikTok | 498 | ██ |
| Binance | 406 | ██ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 3,204 | ████████████████████ |
| `trade` | 2,615 | ████████████████ |
| `service` | 2,350 | ███████████████ |
| `casino` | 2,064 | █████████████ |
| `wallet` | 1,990 | ████████████ |
| `invest` | 1,871 | ████████████ |
| `support` | 1,748 | ███████████ |
| `auth` | 1,538 | ██████████ |
| `secure` | 1,427 | █████████ |
| `bet` | 1,253 | ████████ |
| `connect` | 1,157 | ███████ |
| `account` | 1,127 | ███████ |

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
