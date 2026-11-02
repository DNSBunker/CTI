# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-209%2C665-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-4%2C903-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--11--02_21%3A25_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-11-02 21:25 UTC</sub>

| | |
|---|---:|
| Active domains | **209,665** |
| Added in the last 24 hours | 4,903 |
| Added in the last 7 days | 107,872 |
| Added in the last 30 days | 235,212 |
| Retired in the last 30 days (offline or cleaned up) | 683,288 |
| Top-level domains represented | 503 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 31.9 % |
| Domains containing hyphens | 29.2 % |
| Average domain length | 20.1 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Oct 4 – Nov 2 (UTC)"
    x-axis ["4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28", "29", "30", "31", "1", "2"]
    y-axis "domains" 0 --> 100000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1227, 14240, 21381, 90492, 13281, 13149, 36078, 15350, 11978, 0, 0, 13504, 4532]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Oct 21 – Nov 2 (UTC)"
    x-axis ["21", "22", "23", "24", "25", "26", "27", "28", "29", "30", "31", "1", "2"]
    y-axis "domains"
    line [472713, 588659, 629951, 748222, 574614, 473331, 457795, 371010, 376945, 376945, 376945, 224607, 209665]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-11-02 | 4,532 | 18,801 |
| 2026-11-01 | 13,504 | 173,332 |
| 2026-10-31 | 0 | 0 |
| 2026-10-30 | 0 | 0 |
| 2026-10-29 | 11,978 | 5,456 |
| 2026-10-28 | 15,350 | 99,912 |
| 2026-10-27 | 36,078 | 54,651 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.com` | 73,394 | 35.0 % | ████████████████████ |
| 2 | `.dev` | 18,553 | 8.8 % | █████ |
| 3 | `.shop` | 9,823 | 4.7 % | ███ |
| 4 | `.click` | 7,529 | 3.6 % | ██ |
| 5 | `.net` | 6,946 | 3.3 % | ██ |
| 6 | `.top` | 6,945 | 3.3 % | ██ |
| 7 | `.sbs` | 6,905 | 3.3 % | ██ |
| 8 | `.xyz` | 5,934 | 2.8 % | ██ |
| 9 | `.org` | 5,382 | 2.6 % | █ |
| 10 | `.live` | 4,355 | 2.1 % | █ |
| 11 | `.info` | 4,280 | 2.0 % | █ |
| 12 | `.cn` | 4,214 | 2.0 % | █ |
| 13 | `.cc` | 4,113 | 2.0 % | █ |
| 14 | `.app` | 4,060 | 1.9 % | █ |
| 15 | `.pro` | 3,870 | 1.8 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 73394
    ".dev" : 18553
    ".shop" : 9823
    ".click" : 7529
    ".net" : 6946
    "other" : 93420
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| WhatsApp | 4,164 | ████████████████████ |
| Coinbase | 907 | ████ |
| Meta / Facebook | 782 | ████ |
| Apple / iCloud | 689 | ███ |
| Netflix | 533 | ███ |
| Google | 505 | ██ |
| Telegram | 498 | ██ |
| Ledger | 462 | ██ |
| PayPal | 327 | ██ |
| Amazon | 316 | ██ |
| Instagram | 311 | █ |
| Microsoft / Office 365 | 292 | █ |
| TikTok | 283 | █ |
| MetaMask | 256 | █ |
| American Express | 243 | █ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `trade` | 2,308 | ████████████████████ |
| `casino` | 1,757 | ███████████████ |
| `service` | 1,081 | █████████ |
| `login` | 1,039 | █████████ |
| `support` | 908 | ████████ |
| `invest` | 837 | ███████ |
| `bet` | 719 | ██████ |
| `secure` | 614 | █████ |
| `wallet` | 488 | ████ |
| `token` | 476 | ████ |
| `account` | 471 | ████ |
| `update` | 468 | ████ |

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
