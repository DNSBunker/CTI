# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-385%2C113-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-43%2C447-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--11--10_00%3A52_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-11-10 00:52 UTC</sub>

| | |
|---|---:|
| Active domains | **385,113** |
| Added in the last 24 hours | 43,447 |
| Added in the last 7 days | 482,844 |
| Added in the last 30 days | 482,844 |
| Retired in the last 30 days (offline or cleaned up) | 32,641 |
| Top-level domains represented | 615 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 39.1 % |
| Domains containing hyphens | 30.4 % |
| Average domain length | 22.5 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Oct 12 – Nov 10 (UTC)"
    x-axis ["12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28", "29", "30", "31", "1", "2", "3", "4", "5", "6", "7", "8", "9", "10"]
    y-axis "domains" 0 --> 400000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 292213, 87546, 58360, 41156, 3569]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Nov 6 – Nov 10 (UTC)"
    x-axis ["6", "7", "8", "9", "10"]
    y-axis "domains"
    line [272088, 346388, 396638, 382009, 385113]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-11-10 | 3,569 | 371 |
| 2026-11-09 | 41,156 | 10,905 |
| 2026-11-08 | 58,360 | 4,794 |
| 2026-11-07 | 87,546 | 6,920 |
| 2026-11-06 | 292,213 | 9,651 |
| 2026-11-05 | 0 | 0 |
| 2026-11-04 | 0 | 0 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.com` | 108,144 | 28.1 % | ████████████████████ |
| 2 | `.io` | 26,855 | 7.0 % | █████ |
| 3 | `.app` | 26,758 | 6.9 % | █████ |
| 4 | `.org` | 21,299 | 5.5 % | ████ |
| 5 | `.click` | 19,617 | 5.1 % | ████ |
| 6 | `.cc` | 16,139 | 4.2 % | ███ |
| 7 | `.digital` | 15,715 | 4.1 % | ███ |
| 8 | `.top` | 11,110 | 2.9 % | ██ |
| 9 | `.sbs` | 9,796 | 2.5 % | ██ |
| 10 | `.xyz` | 8,920 | 2.3 % | ██ |
| 11 | `.net` | 8,156 | 2.1 % | ██ |
| 12 | `.shop` | 7,431 | 1.9 % | █ |
| 13 | `.info` | 5,645 | 1.5 % | █ |
| 14 | `.cn` | 4,472 | 1.2 % | █ |
| 15 | `.au` | 4,415 | 1.1 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 108144
    ".io" : 26855
    ".app" : 26758
    ".org" : 21299
    ".click" : 19617
    "other" : 182440
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| Amazon | 4,240 | ████████████████████ |
| Coinbase | 4,000 | ███████████████████ |
| WhatsApp | 3,796 | ██████████████████ |
| MetaMask | 3,369 | ████████████████ |
| Meta / Facebook | 2,925 | ██████████████ |
| Google | 2,168 | ██████████ |
| Apple / iCloud | 1,835 | █████████ |
| Instagram | 1,586 | ███████ |
| Netflix | 1,497 | ███████ |
| PayPal | 1,489 | ███████ |
| Microsoft / Office 365 | 1,260 | ██████ |
| Telegram | 827 | ████ |
| TikTok | 736 | ███ |
| OpenSea | 659 | ███ |
| Ledger | 571 | ███ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 5,982 | ████████████████████ |
| `wallet` | 2,883 | ██████████ |
| `service` | 2,733 | █████████ |
| `auth` | 2,466 | ████████ |
| `help` | 2,179 | ███████ |
| `casino` | 2,071 | ███████ |
| `secure` | 1,933 | ██████ |
| `support` | 1,764 | ██████ |
| `account` | 1,749 | ██████ |
| `invest` | 1,370 | █████ |
| `update` | 1,299 | ████ |
| `claim` | 1,157 | ████ |

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
