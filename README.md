# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-272%2C050-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-292%2C612-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--11--07_00%3A21_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-11-07 00:21 UTC</sub>

| | |
|---|---:|
| Active domains | **272,050** |
| Added in the last 24 hours | 292,612 |
| Added in the last 7 days | 292,612 |
| Added in the last 30 days | 292,612 |
| Retired in the last 30 days (offline or cleaned up) | 10,040 |
| Top-level domains represented | 499 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 43.9 % |
| Domains containing hyphens | 45.0 % |
| Average domain length | 26.3 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Oct 9 – Nov 7 (UTC)"
    x-axis ["9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28", "29", "30", "31", "1", "2", "3", "4", "5", "6", "7"]
    y-axis "domains" 0 --> 400000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 292213, 399]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Nov 6 – Nov 7 (UTC)"
    x-axis ["6", "7"]
    y-axis "domains"
    line [272088, 272050]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-11-07 | 399 | 389 |
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
| 1 | `.com` | 67,131 | 24.7 % | ████████████████████ |
| 2 | `.dev` | 44,171 | 16.2 % | █████████████ |
| 3 | `.app` | 29,577 | 10.9 % | █████████ |
| 4 | `.io` | 21,442 | 7.9 % | ██████ |
| 5 | `.org` | 15,566 | 5.7 % | █████ |
| 6 | `.click` | 11,630 | 4.3 % | ███ |
| 7 | `.digital` | 9,560 | 3.5 % | ███ |
| 8 | `.top` | 4,839 | 1.8 % | █ |
| 9 | `.net` | 4,537 | 1.7 % | █ |
| 10 | `.cc` | 4,459 | 1.6 % | █ |
| 11 | `.sbs` | 4,361 | 1.6 % | █ |
| 12 | `.xyz` | 4,206 | 1.5 % | █ |
| 13 | `.info` | 3,605 | 1.3 % | █ |
| 14 | `.link` | 2,333 | 0.9 % | █ |
| 15 | `.site` | 2,109 | 0.8 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 67131
    ".dev" : 44171
    ".app" : 29577
    ".io" : 21442
    ".org" : 15566
    "other" : 94163
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| Coinbase | 3,592 | ████████████████████ |
| MetaMask | 3,273 | ██████████████████ |
| Meta / Facebook | 1,806 | ██████████ |
| Amazon | 1,783 | ██████████ |
| WhatsApp | 1,659 | █████████ |
| Google | 1,360 | ████████ |
| Microsoft / Office 365 | 1,330 | ███████ |
| Instagram | 1,236 | ███████ |
| Netflix | 1,164 | ██████ |
| PayPal | 1,112 | ██████ |
| Apple / iCloud | 1,097 | ██████ |
| Ledger | 1,031 | ██████ |
| OpenSea | 747 | ████ |
| Trust Wallet | 244 | █ |
| TikTok | 212 | █ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 5,363 | ████████████████████ |
| `wallet` | 3,051 | ███████████ |
| `auth` | 2,368 | █████████ |
| `support` | 2,239 | ████████ |
| `help` | 2,201 | ████████ |
| `service` | 2,116 | ████████ |
| `account` | 1,869 | ███████ |
| `secure` | 1,691 | ██████ |
| `claim` | 1,272 | █████ |
| `update` | 1,251 | █████ |
| `connect` | 1,017 | ████ |
| `invest` | 710 | ███ |

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
