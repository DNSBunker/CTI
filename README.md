# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-474%2C682-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-1%2C134%2C747-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--11--24_09%3A45_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-CC0--1.0-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-11-24 09:45 UTC</sub>

| | |
|---|---:|
| Active domains | **474,682** |
| Added in the last 24 hours | 1,134,747 |
| Added in the last 7 days | 2,371,064 |
| Added in the last 30 days | 3,095,938 |
| Retired in the last 30 days (offline or cleaned up) | 140,969 |
| Top-level domains represented | 660 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 27.4 % |
| Domains containing hyphens | 23.6 % |
| Average domain length | 19.2 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Oct 26 – Nov 24 (UTC)"
    x-axis ["26", "27", "28", "29", "30", "31", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24"]
    y-axis "domains" 0 --> 1200000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 292213, 87546, 58360, 41156, 47623, 52549, 48149, 19581, 19803, 20986, 19995, 16913, 418, 20356, 721638, 302590, 102224, 1065553, 158285]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Nov 6 – Nov 24 (UTC)"
    x-axis ["6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24"]
    y-axis "domains"
    line [272088, 346388, 396638, 382009, 418143, 355765, 344361, 334208, 339933, 354999, 368552, 379552, 379894, 376537, 1059296, 1334519, 1422467, 1477941, 474682]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-11-24 | 158,285 | 809 |
| 2026-11-23 | 1,065,553 | 10,618 |
| 2026-11-22 | 102,224 | 6,653 |
| 2026-11-21 | 302,590 | 8,524 |
| 2026-11-20 | 721,638 | 13,854 |
| 2026-11-19 | 20,356 | 6,618 |
| 2026-11-18 | 418 | 48 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.com` | 135,914 | 28.6 % | ████████████████████ |
| 2 | `.cc` | 41,118 | 8.7 % | ██████ |
| 3 | `.org` | 26,304 | 5.5 % | ████ |
| 4 | `.app` | 25,650 | 5.4 % | ████ |
| 5 | `.cd` | 24,656 | 5.2 % | ████ |
| 6 | `.click` | 23,416 | 4.9 % | ███ |
| 7 | `.digital` | 20,451 | 4.3 % | ███ |
| 8 | `.shop` | 14,777 | 3.1 % | ██ |
| 9 | `.xyz` | 12,130 | 2.6 % | ██ |
| 10 | `.net` | 11,233 | 2.4 % | ██ |
| 11 | `.sbs` | 10,952 | 2.3 % | ██ |
| 12 | `.info` | 8,951 | 1.9 % | █ |
| 13 | `.top` | 8,816 | 1.9 % | █ |
| 14 | `.io` | 7,916 | 1.7 % | █ |
| 15 | `.live` | 6,256 | 1.3 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 135914
    ".cc" : 41118
    ".org" : 26304
    ".app" : 25650
    ".cd" : 24656
    "other" : 221040
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| WhatsApp | 3,274 | ████████████████████ |
| Google | 2,872 | ██████████████████ |
| Coinbase | 2,130 | █████████████ |
| MetaMask | 1,702 | ██████████ |
| Meta / Facebook | 1,618 | ██████████ |
| Apple / iCloud | 1,330 | ████████ |
| Microsoft / Office 365 | 1,281 | ████████ |
| Netflix | 1,187 | ███████ |
| PayPal | 1,165 | ███████ |
| Amazon | 1,129 | ███████ |
| Instagram | 903 | ██████ |
| OpenSea | 653 | ████ |
| Ledger | 441 | ███ |
| Trust Wallet | 417 | ███ |
| Spotify | 324 | ██ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 3,675 | ████████████████████ |
| `service` | 2,724 | ███████████████ |
| `invest` | 1,968 | ███████████ |
| `wallet` | 1,937 | ███████████ |
| `casino` | 1,902 | ██████████ |
| `support` | 1,573 | █████████ |
| `secure` | 1,529 | ████████ |
| `account` | 1,460 | ████████ |
| `trade` | 1,425 | ████████ |
| `update` | 1,295 | ███████ |
| `claim` | 1,208 | ███████ |
| `connect` | 1,041 | ██████ |

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
