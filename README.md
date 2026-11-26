# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-629%2C636-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-65%2C745-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--11--26_10%3A32_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-CC0--1.0-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-11-26 10:32 UTC</sub>

| | |
|---|---:|
| Active domains | **629,636** |
| Added in the last 24 hours | 65,745 |
| Added in the last 7 days | 2,530,594 |
| Added in the last 30 days | 3,276,242 |
| Retired in the last 30 days (offline or cleaned up) | 156,131 |
| Top-level domains represented | 679 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 25.6 % |
| Domains containing hyphens | 29.1 % |
| Average domain length | 20.0 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Oct 28 – Nov 26 (UTC)"
    x-axis ["28", "29", "30", "31", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26"]
    y-axis "domains" 0 --> 1200000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 292213, 87546, 58360, 41156, 47623, 52549, 48149, 19581, 19803, 20986, 19995, 16913, 418, 20356, 721638, 302590, 102224, 1065553, 232121, 90433, 16035]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Nov 6 – Nov 26 (UTC)"
    x-axis ["6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26"]
    y-axis "domains"
    line [272088, 346388, 396638, 382009, 418143, 355765, 344361, 334208, 339933, 354999, 368552, 379552, 379894, 376537, 1059296, 1334519, 1422467, 1477941, 537165, 617721, 629636]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-11-26 | 16,035 | 2,501 |
| 2026-11-25 | 90,433 | 5,506 |
| 2026-11-24 | 232,121 | 7,964 |
| 2026-11-23 | 1,065,553 | 10,618 |
| 2026-11-22 | 102,224 | 6,653 |
| 2026-11-21 | 302,590 | 8,524 |
| 2026-11-20 | 721,638 | 13,854 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.com` | 169,184 | 26.9 % | ████████████████████ |
| 2 | `.cc` | 47,002 | 7.5 % | ██████ |
| 3 | `.app` | 36,703 | 5.8 % | ████ |
| 4 | `.io` | 36,148 | 5.7 % | ████ |
| 5 | `.cd` | 28,781 | 4.6 % | ███ |
| 6 | `.org` | 28,145 | 4.5 % | ███ |
| 7 | `.click` | 25,628 | 4.1 % | ███ |
| 8 | `.dev` | 25,075 | 4.0 % | ███ |
| 9 | `.digital` | 21,122 | 3.4 % | ██ |
| 10 | `.shop` | 18,405 | 2.9 % | ██ |
| 11 | `.xyz` | 14,967 | 2.4 % | ██ |
| 12 | `.net` | 14,414 | 2.3 % | ██ |
| 13 | `.top` | 11,477 | 1.8 % | █ |
| 14 | `.sbs` | 11,243 | 1.8 % | █ |
| 15 | `.info` | 10,330 | 1.6 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 169184
    ".cc" : 47002
    ".app" : 36703
    ".io" : 36148
    ".cd" : 28781
    "other" : 311818
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| Coinbase | 10,495 | ████████████████████ |
| MetaMask | 8,738 | █████████████████ |
| WhatsApp | 5,161 | ██████████ |
| Google | 3,136 | ██████ |
| Meta / Facebook | 1,767 | ███ |
| Apple / iCloud | 1,747 | ███ |
| OpenSea | 1,618 | ███ |
| Microsoft / Office 365 | 1,440 | ███ |
| Netflix | 1,335 | ███ |
| Amazon | 1,275 | ██ |
| PayPal | 1,260 | ██ |
| Instagram | 947 | ██ |
| Ledger | 751 | █ |
| Trust Wallet | 720 | █ |
| Telegram | 498 | █ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 9,342 | ████████████████████ |
| `wallet` | 9,114 | ████████████████████ |
| `help` | 5,386 | ████████████ |
| `casino` | 3,590 | ████████ |
| `support` | 3,530 | ████████ |
| `service` | 3,271 | ███████ |
| `auth` | 3,191 | ███████ |
| `secure` | 2,991 | ██████ |
| `connect` | 2,348 | █████ |
| `trade` | 2,346 | █████ |
| `invest` | 2,202 | █████ |
| `claim` | 2,131 | █████ |

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
