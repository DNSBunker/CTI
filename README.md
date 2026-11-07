# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-291%2C862-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-279%2C602-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--11--07_04%3A36_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-11-07 04:36 UTC</sub>

| | |
|---|---:|
| Active domains | **291,862** |
| Added in the last 24 hours | 279,602 |
| Added in the last 7 days | 317,554 |
| Added in the last 30 days | 317,554 |
| Retired in the last 30 days (offline or cleaned up) | 14,104 |
| Top-level domains represented | 512 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 44.3 % |
| Domains containing hyphens | 43.7 % |
| Average domain length | 25.7 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Oct 9 – Nov 7 (UTC)"
    x-axis ["9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28", "29", "30", "31", "1", "2", "3", "4", "5", "6", "7"]
    y-axis "domains" 0 --> 400000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 292213, 25341]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Nov 6 – Nov 7 (UTC)"
    x-axis ["6", "7"]
    y-axis "domains"
    line [272088, 291862]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-11-07 | 25,341 | 4,453 |
| 2026-11-06 | 292,213 | 9,651 |
| 2026-11-05 | 0 | 0 |
| 2026-11-04 | 0 | 0 |
| 2026-11-03 | 0 | 0 |
| 2026-11-02 | 0 | 0 |
| 2026-11-01 | 0 | 0 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.com` | 74,211 | 25.4 % | ████████████████████ |
| 2 | `.dev` | 44,708 | 15.3 % | ████████████ |
| 3 | `.app` | 27,739 | 9.5 % | ███████ |
| 4 | `.io` | 21,898 | 7.5 % | ██████ |
| 5 | `.org` | 16,146 | 5.5 % | ████ |
| 6 | `.click` | 12,241 | 4.2 % | ███ |
| 7 | `.digital` | 9,836 | 3.4 % | ███ |
| 8 | `.top` | 6,182 | 2.1 % | ██ |
| 9 | `.cc` | 5,845 | 2.0 % | ██ |
| 10 | `.xyz` | 5,058 | 1.7 % | █ |
| 11 | `.net` | 5,016 | 1.7 % | █ |
| 12 | `.sbs` | 4,954 | 1.7 % | █ |
| 13 | `.info` | 3,849 | 1.3 % | █ |
| 14 | `.shop` | 2,534 | 0.9 % | █ |
| 15 | `.cn` | 2,505 | 0.9 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 74211
    ".dev" : 44708
    ".app" : 27739
    ".io" : 21898
    ".org" : 16146
    "other" : 107160
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| Coinbase | 3,973 | ████████████████████ |
| MetaMask | 3,286 | █████████████████ |
| WhatsApp | 3,116 | ████████████████ |
| Amazon | 2,111 | ███████████ |
| Meta / Facebook | 2,092 | ███████████ |
| Google | 1,747 | █████████ |
| Apple / iCloud | 1,540 | ████████ |
| Microsoft / Office 365 | 1,465 | ███████ |
| Netflix | 1,356 | ███████ |
| PayPal | 1,326 | ███████ |
| Instagram | 1,325 | ███████ |
| Ledger | 1,124 | ██████ |
| OpenSea | 697 | ████ |
| Telegram | 510 | ███ |
| TikTok | 498 | ███ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 5,497 | ████████████████████ |
| `wallet` | 3,086 | ███████████ |
| `auth` | 2,379 | █████████ |
| `support` | 2,315 | ████████ |
| `service` | 2,213 | ████████ |
| `help` | 2,173 | ████████ |
| `account` | 1,842 | ███████ |
| `secure` | 1,801 | ███████ |
| `update` | 1,287 | █████ |
| `claim` | 1,264 | █████ |
| `casino` | 1,112 | ████ |
| `connect` | 1,054 | ████ |

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
