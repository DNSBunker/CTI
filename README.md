# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-678%2C919-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-58%2C069-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--11--27_18%3A05_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-CC0--1.0-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-11-27 18:05 UTC</sub>

| | |
|---|---:|
| Active domains | **678,919** |
| Added in the last 24 hours | 58,069 |
| Added in the last 7 days | 1,879,085 |
| Added in the last 30 days | 3,346,371 |
| Retired in the last 30 days (offline or cleaned up) | 168,404 |
| Top-level domains represented | 682 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 26.7 % |
| Domains containing hyphens | 30.5 % |
| Average domain length | 20.5 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Oct 29 – Nov 27 (UTC)"
    x-axis ["29", "30", "31", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27"]
    y-axis "domains" 0 --> 1200000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 292213, 87546, 58360, 41156, 47623, 52549, 48149, 19581, 19803, 20986, 19995, 16913, 418, 20356, 721638, 302590, 102224, 1065553, 232121, 90433, 33730, 52434]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Nov 6 – Nov 27 (UTC)"
    x-axis ["6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27"]
    y-axis "domains"
    line [272088, 346388, 396638, 382009, 418143, 355765, 344361, 334208, 339933, 354999, 368552, 379552, 379894, 376537, 1059296, 1334519, 1422467, 1477941, 537165, 617721, 638075, 678919]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-11-27 | 52,434 | 4,748 |
| 2026-11-26 | 33,730 | 10,026 |
| 2026-11-25 | 90,433 | 5,506 |
| 2026-11-24 | 232,121 | 7,964 |
| 2026-11-23 | 1,065,553 | 10,618 |
| 2026-11-22 | 102,224 | 6,653 |
| 2026-11-21 | 302,590 | 8,524 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.com` | 176,979 | 26.1 % | ████████████████████ |
| 2 | `.cc` | 49,987 | 7.4 % | ██████ |
| 3 | `.io` | 41,240 | 6.1 % | █████ |
| 4 | `.dev` | 40,230 | 5.9 % | █████ |
| 5 | `.app` | 40,159 | 5.9 % | █████ |
| 6 | `.cd` | 31,656 | 4.7 % | ████ |
| 7 | `.org` | 28,609 | 4.2 % | ███ |
| 8 | `.click` | 25,610 | 3.8 % | ███ |
| 9 | `.digital` | 21,006 | 3.1 % | ██ |
| 10 | `.shop` | 20,875 | 3.1 % | ██ |
| 11 | `.xyz` | 15,187 | 2.2 % | ██ |
| 12 | `.net` | 15,176 | 2.2 % | ██ |
| 13 | `.top` | 11,905 | 1.8 % | █ |
| 14 | `.sbs` | 11,060 | 1.6 % | █ |
| 15 | `.info` | 10,423 | 1.5 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 176979
    ".cc" : 49987
    ".io" : 41240
    ".dev" : 40230
    ".app" : 40159
    "other" : 330324
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| Coinbase | 12,396 | ████████████████████ |
| MetaMask | 9,595 | ███████████████ |
| WhatsApp | 5,404 | █████████ |
| Google | 3,252 | █████ |
| Meta / Facebook | 2,094 | ███ |
| Apple / iCloud | 1,907 | ███ |
| Microsoft / Office 365 | 1,799 | ███ |
| OpenSea | 1,753 | ███ |
| Netflix | 1,595 | ███ |
| PayPal | 1,441 | ██ |
| Amazon | 1,376 | ██ |
| Ledger | 1,277 | ██ |
| Instagram | 1,222 | ██ |
| Trust Wallet | 813 | █ |
| Telegram | 544 | █ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 12,213 | ████████████████████ |
| `wallet` | 10,349 | █████████████████ |
| `help` | 5,796 | █████████ |
| `auth` | 4,709 | ████████ |
| `casino` | 4,035 | ███████ |
| `support` | 3,960 | ██████ |
| `secure` | 3,552 | ██████ |
| `service` | 3,478 | ██████ |
| `connect` | 2,512 | ████ |
| `trade` | 2,384 | ████ |
| `claim` | 2,264 | ████ |
| `invest` | 2,221 | ████ |

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
