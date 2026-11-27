# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-648%2C052-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-36%2C138-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--11--27_06%3A49_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-CC0--1.0-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-11-27 06:49 UTC</sub>

| | |
|---|---:|
| Active domains | **648,052** |
| Added in the last 24 hours | 36,138 |
| Added in the last 7 days | 1,839,328 |
| Added in the last 30 days | 3,306,614 |
| Retired in the last 30 days (offline or cleaned up) | 165,688 |
| Top-level domains represented | 680 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 26.3 % |
| Domains containing hyphens | 29.7 % |
| Average domain length | 20.3 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Oct 29 – Nov 27 (UTC)"
    x-axis ["29", "30", "31", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27"]
    y-axis "domains" 0 --> 1200000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 292213, 87546, 58360, 41156, 47623, 52549, 48149, 19581, 19803, 20986, 19995, 16913, 418, 20356, 721638, 302590, 102224, 1065553, 232121, 90433, 33730, 12677]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Nov 6 – Nov 27 (UTC)"
    x-axis ["6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27"]
    y-axis "domains"
    line [272088, 346388, 396638, 382009, 418143, 355765, 344361, 334208, 339933, 354999, 368552, 379552, 379894, 376537, 1059296, 1334519, 1422467, 1477941, 537165, 617721, 638075, 648052]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-11-27 | 12,677 | 2,032 |
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
| 1 | `.com` | 170,131 | 26.3 % | ████████████████████ |
| 2 | `.cc` | 48,972 | 7.6 % | ██████ |
| 3 | `.app` | 39,343 | 6.1 % | █████ |
| 4 | `.io` | 36,847 | 5.7 % | ████ |
| 5 | `.cd` | 30,458 | 4.7 % | ████ |
| 6 | `.dev` | 29,039 | 4.5 % | ███ |
| 7 | `.org` | 28,211 | 4.4 % | ███ |
| 8 | `.click` | 25,523 | 3.9 % | ███ |
| 9 | `.digital` | 20,989 | 3.2 % | ██ |
| 10 | `.shop` | 20,889 | 3.2 % | ██ |
| 11 | `.xyz` | 15,088 | 2.3 % | ██ |
| 12 | `.net` | 14,787 | 2.3 % | ██ |
| 13 | `.top` | 11,769 | 1.8 % | █ |
| 14 | `.sbs` | 10,950 | 1.7 % | █ |
| 15 | `.info` | 10,352 | 1.6 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 170131
    ".cc" : 48972
    ".app" : 39343
    ".io" : 36847
    ".cd" : 30458
    "other" : 322301
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| Coinbase | 10,836 | ████████████████████ |
| MetaMask | 9,013 | █████████████████ |
| WhatsApp | 5,303 | ██████████ |
| Google | 3,181 | ██████ |
| Meta / Facebook | 1,889 | ███ |
| Apple / iCloud | 1,799 | ███ |
| OpenSea | 1,687 | ███ |
| Netflix | 1,633 | ███ |
| Microsoft / Office 365 | 1,548 | ███ |
| Amazon | 1,524 | ███ |
| PayPal | 1,324 | ██ |
| Instagram | 1,147 | ██ |
| Ledger | 1,126 | ██ |
| Trust Wallet | 796 | █ |
| Telegram | 513 | █ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 10,942 | ████████████████████ |
| `wallet` | 9,428 | █████████████████ |
| `help` | 5,465 | ██████████ |
| `casino` | 3,913 | ███████ |
| `support` | 3,692 | ███████ |
| `auth` | 3,486 | ██████ |
| `service` | 3,350 | ██████ |
| `secure` | 3,231 | ██████ |
| `connect` | 2,375 | ████ |
| `trade` | 2,357 | ████ |
| `invest` | 2,178 | ████ |
| `claim` | 2,162 | ████ |

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
