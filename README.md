# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-248%2C904-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-263%2C735-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--11--06_19%3A47_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-11-06 19:47 UTC</sub>

| | |
|---|---:|
| Active domains | **248,904** |
| Added in the last 24 hours | 263,735 |
| Added in the last 7 days | 263,735 |
| Added in the last 30 days | 263,735 |
| Retired in the last 30 days (offline or cleaned up) | 5,354 |
| Top-level domains represented | 476 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 46.4 % |
| Domains containing hyphens | 48.5 % |
| Average domain length | 26.9 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Oct 8 – Nov 6 (UTC)"
    x-axis ["8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28", "29", "30", "31", "1", "2", "3", "4", "5", "6"]
    y-axis "domains" 0 --> 300000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 263735]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-11-06 | 263,735 | 5,354 |
| 2026-11-05 | 0 | 0 |
| 2026-11-04 | 0 | 0 |
| 2026-11-03 | 0 | 0 |
| 2026-11-02 | 0 | 0 |
| 2026-11-01 | 0 | 0 |
| 2026-10-31 | 0 | 0 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.com` | 57,320 | 23.0 % | ████████████████████ |
| 2 | `.dev` | 41,554 | 16.7 % | ██████████████ |
| 3 | `.app` | 31,429 | 12.6 % | ███████████ |
| 4 | `.io` | 18,178 | 7.3 % | ██████ |
| 5 | `.org` | 13,577 | 5.5 % | █████ |
| 6 | `.click` | 11,478 | 4.6 % | ████ |
| 7 | `.digital` | 9,382 | 3.8 % | ███ |
| 8 | `.top` | 4,454 | 1.8 % | ██ |
| 9 | `.sbs` | 4,238 | 1.7 % | █ |
| 10 | `.xyz` | 4,065 | 1.6 % | █ |
| 11 | `.cc` | 4,041 | 1.6 % | █ |
| 12 | `.net` | 3,694 | 1.5 % | █ |
| 13 | `.info` | 3,481 | 1.4 % | █ |
| 14 | `.me` | 3,095 | 1.2 % | █ |
| 15 | `.link` | 2,293 | 0.9 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 57320
    ".dev" : 41554
    ".app" : 31429
    ".io" : 18178
    ".org" : 13577
    "other" : 86846
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| Coinbase | 3,604 | ████████████████████ |
| MetaMask | 3,294 | ██████████████████ |
| Meta / Facebook | 1,841 | ██████████ |
| Amazon | 1,678 | █████████ |
| WhatsApp | 1,600 | █████████ |
| Microsoft / Office 365 | 1,387 | ████████ |
| Google | 1,343 | ███████ |
| Instagram | 1,258 | ███████ |
| Netflix | 1,199 | ███████ |
| PayPal | 1,107 | ██████ |
| Apple / iCloud | 1,096 | ██████ |
| Ledger | 1,032 | ██████ |
| OpenSea | 798 | ████ |
| Trust Wallet | 246 | █ |
| TikTok | 208 | █ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 5,402 | ████████████████████ |
| `wallet` | 3,055 | ███████████ |
| `auth` | 2,380 | █████████ |
| `support` | 2,277 | ████████ |
| `help` | 2,225 | ████████ |
| `account` | 2,030 | ████████ |
| `service` | 1,944 | ███████ |
| `secure` | 1,690 | ██████ |
| `update` | 1,290 | █████ |
| `claim` | 1,227 | █████ |
| `connect` | 903 | ███ |
| `verify` | 687 | ███ |

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
