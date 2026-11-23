# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-915%2C462-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-529%2C396-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--11--23_16%3A32_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-CC0--1.0-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-11-23 16:32 UTC</sub>

| | |
|---|---:|
| Active domains | **915,462** |
| Added in the last 24 hours | 529,396 |
| Added in the last 7 days | 1,658,736 |
| Added in the last 30 days | 2,366,697 |
| Retired in the last 30 days (offline or cleaned up) | 139,326 |
| Top-level domains represented | 713 |
| Internationalized (IDN / punycode) domains | 0.5 % |
| Domains containing digits | 37.9 % |
| Domains containing hyphens | 25.9 % |
| Average domain length | 19.0 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Oct 25 – Nov 23 (UTC)"
    x-axis ["25", "26", "27", "28", "29", "30", "31", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23"]
    y-axis "domains" 0 --> 800000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 292213, 87546, 58360, 41156, 47623, 52549, 48149, 19581, 19803, 20986, 19995, 16913, 418, 20356, 721638, 302590, 102224, 494597]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Nov 6 – Nov 23 (UTC)"
    x-axis ["6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23"]
    y-axis "domains"
    line [272088, 346388, 396638, 382009, 418143, 355765, 344361, 334208, 339933, 354999, 368552, 379552, 379894, 376537, 1059296, 1334519, 1422467, 915462]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-11-23 | 494,597 | 9,784 |
| 2026-11-22 | 102,224 | 6,653 |
| 2026-11-21 | 302,590 | 8,524 |
| 2026-11-20 | 721,638 | 13,854 |
| 2026-11-19 | 20,356 | 6,618 |
| 2026-11-18 | 418 | 48 |
| 2026-11-17 | 16,913 | 4,450 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.com` | 198,914 | 21.7 % | ████████████████████ |
| 2 | `.xyz` | 89,369 | 9.8 % | █████████ |
| 3 | `.top` | 62,420 | 6.8 % | ██████ |
| 4 | `.cc` | 50,016 | 5.5 % | █████ |
| 5 | `.click` | 48,860 | 5.3 % | █████ |
| 6 | `.shop` | 41,124 | 4.5 % | ████ |
| 7 | `.org` | 31,841 | 3.5 % | ███ |
| 8 | `.app` | 29,878 | 3.3 % | ███ |
| 9 | `.cd` | 23,856 | 2.6 % | ██ |
| 10 | `.sbs` | 21,591 | 2.4 % | ██ |
| 11 | `.digital` | 18,103 | 2.0 % | ██ |
| 12 | `.info` | 16,615 | 1.8 % | ██ |
| 13 | `.site` | 16,055 | 1.8 % | ██ |
| 14 | `.net` | 15,291 | 1.7 % | ██ |
| 15 | `.cfd` | 14,888 | 1.6 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 198914
    ".xyz" : 89369
    ".top" : 62420
    ".cc" : 50016
    ".click" : 48860
    "other" : 465883
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| WhatsApp | 5,620 | ████████████████████ |
| Google | 5,006 | ██████████████████ |
| Apple / iCloud | 4,532 | ████████████████ |
| ChatGPT / OpenAI | 4,524 | ████████████████ |
| Amazon | 2,763 | ██████████ |
| Coinbase | 2,629 | █████████ |
| Microsoft / Office 365 | 2,500 | █████████ |
| Meta / Facebook | 2,362 | ████████ |
| Ledger | 1,947 | ███████ |
| MetaMask | 1,802 | ██████ |
| PayPal | 1,631 | ██████ |
| Netflix | 1,631 | ██████ |
| Instagram | 1,299 | █████ |
| Telegram | 1,078 | ████ |
| Binance | 1,072 | ████ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `casino` | 48,205 | ████████████████████ |
| `service` | 10,649 | ████ |
| `login` | 7,259 | ███ |
| `crypto` | 5,651 | ██ |
| `support` | 4,743 | ██ |
| `secure` | 4,558 | ██ |
| `wallet` | 4,350 | ██ |
| `account` | 4,075 | ██ |
| `bet` | 3,398 | █ |
| `update` | 3,008 | █ |
| `invest` | 2,301 | █ |
| `verify` | 1,761 | █ |

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
