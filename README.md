# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-1%2C161%2C342-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-830%2C936-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--11--21_07%3A18_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-CC0--1.0-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-11-21 07:18 UTC</sub>

| | |
|---|---:|
| Active domains | **1,161,342** |
| Added in the last 24 hours | 830,936 |
| Added in the last 7 days | 912,039 |
| Added in the last 30 days | 1,579,019 |
| Retired in the last 30 days (offline or cleaned up) | 116,110 |
| Top-level domains represented | 734 |
| Internationalized (IDN / punycode) domains | 0.4 % |
| Domains containing digits | 34.0 % |
| Domains containing hyphens | 24.2 % |
| Average domain length | 18.5 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Oct 23 – Nov 21 (UTC)"
    x-axis ["23", "24", "25", "26", "27", "28", "29", "30", "31", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21"]
    y-axis "domains" 0 --> 800000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 292213, 87546, 58360, 41156, 47623, 52549, 48149, 19581, 19803, 20986, 19995, 16913, 418, 20356, 721638, 111733]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Nov 6 – Nov 21 (UTC)"
    x-axis ["6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21"]
    y-axis "domains"
    line [272088, 346388, 396638, 382009, 418143, 355765, 344361, 334208, 339933, 354999, 368552, 379552, 379894, 376537, 1059296, 1161342]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-11-21 | 111,733 | 1,745 |
| 2026-11-20 | 721,638 | 13,854 |
| 2026-11-19 | 20,356 | 6,618 |
| 2026-11-18 | 418 | 48 |
| 2026-11-17 | 16,913 | 4,450 |
| 2026-11-16 | 19,995 | 4,784 |
| 2026-11-15 | 20,986 | 4,264 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.com` | 309,559 | 26.7 % | ████████████████████ |
| 2 | `.xyz` | 104,394 | 9.0 % | ███████ |
| 3 | `.top` | 67,419 | 5.8 % | ████ |
| 4 | `.cc` | 51,656 | 4.4 % | ███ |
| 5 | `.shop` | 50,883 | 4.4 % | ███ |
| 6 | `.click` | 49,066 | 4.2 % | ███ |
| 7 | `.org` | 39,512 | 3.4 % | ███ |
| 8 | `.app` | 33,950 | 2.9 % | ██ |
| 9 | `.digital` | 27,727 | 2.4 % | ██ |
| 10 | `.info` | 23,991 | 2.1 % | ██ |
| 11 | `.sbs` | 22,805 | 2.0 % | █ |
| 12 | `.net` | 21,157 | 1.8 % | █ |
| 13 | `.cd` | 17,962 | 1.5 % | █ |
| 14 | `.site` | 17,027 | 1.5 % | █ |
| 15 | `.online` | 16,574 | 1.4 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 309559
    ".xyz" : 104394
    ".top" : 67419
    ".cc" : 51656
    ".shop" : 50883
    "other" : 577431
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| WhatsApp | 5,408 | ████████████████████ |
| ChatGPT / OpenAI | 4,565 | █████████████████ |
| Google | 4,413 | ████████████████ |
| Apple / iCloud | 4,258 | ████████████████ |
| Coinbase | 2,667 | ██████████ |
| Amazon | 2,651 | ██████████ |
| Microsoft / Office 365 | 2,591 | ██████████ |
| Meta / Facebook | 2,584 | ██████████ |
| Ledger | 1,964 | ███████ |
| MetaMask | 1,871 | ███████ |
| PayPal | 1,717 | ██████ |
| Netflix | 1,708 | ██████ |
| Instagram | 1,471 | █████ |
| Binance | 1,004 | ████ |
| Telegram | 933 | ███ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `casino` | 47,730 | ████████████████████ |
| `login` | 9,332 | ████ |
| `service` | 8,755 | ████ |
| `crypto` | 6,746 | ███ |
| `bet` | 6,102 | ███ |
| `secure` | 5,947 | ██ |
| `support` | 5,855 | ██ |
| `wallet` | 5,403 | ██ |
| `account` | 4,834 | ██ |
| `update` | 3,825 | ██ |
| `trade` | 2,655 | █ |
| `invest` | 2,619 | █ |

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
