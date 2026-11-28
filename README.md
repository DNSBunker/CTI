# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-734%2C035-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-98%2C421-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--11--28_14%3A32_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-CC0--1.0-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-11-28 14:32 UTC</sub>

| | |
|---|---:|
| Active domains | **734,035** |
| Added in the last 24 hours | 98,421 |
| Added in the last 7 days | 1,666,798 |
| Added in the last 30 days | 3,436,674 |
| Retired in the last 30 days (offline or cleaned up) | 201,086 |
| Top-level domains represented | 685 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 28.5 % |
| Domains containing hyphens | 33.3 % |
| Average domain length | 21.5 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Oct 30 – Nov 28 (UTC)"
    x-axis ["30", "31", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28"]
    y-axis "domains" 0 --> 1200000
    bar [0, 0, 0, 0, 0, 0, 0, 292213, 87546, 58360, 41156, 47623, 52549, 48149, 19581, 19803, 20986, 19995, 16913, 418, 20356, 721638, 302590, 102224, 1065553, 232121, 90433, 33730, 114377, 28360]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Nov 6 – Nov 28 (UTC)"
    x-axis ["6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28"]
    y-axis "domains"
    line [272088, 346388, 396638, 382009, 418143, 355765, 344361, 334208, 339933, 354999, 368552, 379552, 379894, 376537, 1059296, 1334519, 1422467, 1477941, 537165, 617721, 638075, 733171, 734035]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-11-28 | 28,360 | 25,546 |
| 2026-11-27 | 114,377 | 11,884 |
| 2026-11-26 | 33,730 | 10,026 |
| 2026-11-25 | 90,433 | 5,506 |
| 2026-11-24 | 232,121 | 7,964 |
| 2026-11-23 | 1,065,553 | 10,618 |
| 2026-11-22 | 102,224 | 6,653 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.com` | 195,862 | 26.7 % | ████████████████████ |
| 2 | `.dev` | 65,862 | 9.0 % | ███████ |
| 3 | `.cc` | 51,166 | 7.0 % | █████ |
| 4 | `.io` | 50,943 | 6.9 % | █████ |
| 5 | `.app` | 47,995 | 6.5 % | █████ |
| 6 | `.org` | 29,104 | 4.0 % | ███ |
| 7 | `.click` | 25,520 | 3.5 % | ███ |
| 8 | `.digital` | 20,902 | 2.8 % | ██ |
| 9 | `.shop` | 20,351 | 2.8 % | ██ |
| 10 | `.net` | 17,281 | 2.4 % | ██ |
| 11 | `.xyz` | 15,321 | 2.1 % | ██ |
| 12 | `.top` | 12,472 | 1.7 % | █ |
| 13 | `.sbs` | 10,601 | 1.4 % | █ |
| 14 | `.info` | 10,397 | 1.4 % | █ |
| 15 | `.cn` | 8,425 | 1.1 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 195862
    ".dev" : 65862
    ".cc" : 51166
    ".io" : 50943
    ".app" : 47995
    "other" : 322207
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| Coinbase | 12,952 | ████████████████████ |
| MetaMask | 10,416 | ████████████████ |
| WhatsApp | 5,616 | █████████ |
| Google | 3,293 | █████ |
| Meta / Facebook | 2,512 | ████ |
| Microsoft / Office 365 | 2,030 | ███ |
| Apple / iCloud | 1,997 | ███ |
| OpenSea | 1,856 | ███ |
| Netflix | 1,663 | ███ |
| PayPal | 1,533 | ██ |
| Ledger | 1,512 | ██ |
| Instagram | 1,462 | ██ |
| Amazon | 1,415 | ██ |
| Trust Wallet | 824 | █ |
| Telegram | 583 | █ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 13,347 | ████████████████████ |
| `wallet` | 10,816 | ████████████████ |
| `help` | 6,743 | ██████████ |
| `auth` | 5,110 | ████████ |
| `support` | 4,921 | ███████ |
| `service` | 4,099 | ██████ |
| `casino` | 4,072 | ██████ |
| `secure` | 3,862 | ██████ |
| `trade` | 3,197 | █████ |
| `account` | 3,095 | █████ |
| `connect` | 2,723 | ████ |
| `claim` | 2,488 | ████ |

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

[CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/): to the extent possible under law, DNSBunker.org / xRuffKez has waived all copyright and related rights to these lists. Use, copy, modify and redistribute them freely, also commercially, without asking.  
SPDX-License-Identifier: CC0-1.0

---

Project: [dnsbunker.org](https://dnsbunker.org) · Repository: [github.com/DNSBunker/CTI](https://github.com/DNSBunker/CTI)
