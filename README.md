# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-47%2C125-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-8%2C878-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--10--31_01%3A50_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-10-31 01:50 UTC</sub>

| | |
|---|---:|
| Active domains | **47,125** |
| Added in the last 24 hours | 8,878 |
| Added in the last 7 days | 51,349 |
| Added in the last 30 days | 51,349 |
| Retired in the last 30 days (offline or cleaned up) | 2,347 |
| Top-level domains represented | 251 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 50.6 % |
| Domains containing hyphens | 59.5 % |
| Average domain length | 29.7 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Oct 2 – Oct 31 (UTC)"
    x-axis ["2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28", "29", "30", "31"]
    y-axis "domains" 0 --> 50000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 41794, 9463, 92]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Oct 29 – Oct 31 (UTC)"
    x-axis ["29", "30", "31"]
    y-axis "domains"
    line [40447, 47381, 47125]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-10-31 | 92 | 318 |
| 2026-10-30 | 9,463 | 2,029 |
| 2026-10-29 | 41,794 | 0 |
| 2026-10-28 | 0 | 0 |
| 2026-10-27 | 0 | 0 |
| 2026-10-26 | 0 | 0 |
| 2026-10-25 | 0 | 0 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.com` | 11,599 | 24.6 % | ████████████████████ |
| 2 | `.dev` | 9,927 | 21.1 % | █████████████████ |
| 3 | `.app` | 8,325 | 17.7 % | ██████████████ |
| 4 | `.org` | 3,265 | 6.9 % | ██████ |
| 5 | `.io` | 1,545 | 3.3 % | ███ |
| 6 | `.cn` | 1,295 | 2.7 % | ██ |
| 7 | `.club` | 1,057 | 2.2 % | ██ |
| 8 | `.pro` | 826 | 1.8 % | █ |
| 9 | `.shop` | 697 | 1.5 % | █ |
| 10 | `.ph` | 679 | 1.4 % | █ |
| 11 | `.host` | 660 | 1.4 % | █ |
| 12 | `.net` | 642 | 1.4 % | █ |
| 13 | `.top` | 598 | 1.3 % | █ |
| 14 | `.link` | 570 | 1.2 % | █ |
| 15 | `.xyz` | 449 | 1.0 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 11599
    ".dev" : 9927
    ".app" : 8325
    ".org" : 3265
    ".io" : 1545
    "other" : 12464
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| WhatsApp | 2,309 | ████████████████████ |
| Meta / Facebook | 945 | ████████ |
| Coinbase | 923 | ████████ |
| Apple / iCloud | 885 | ████████ |
| PayPal | 834 | ███████ |
| Netflix | 576 | █████ |
| Instagram | 557 | █████ |
| Telegram | 519 | ████ |
| TikTok | 394 | ███ |
| OpenSea | 317 | ███ |
| Ledger | 308 | ███ |
| MetaMask | 278 | ██ |
| Google | 218 | ██ |
| LinkedIn | 208 | ██ |
| Microsoft / Office 365 | 181 | ██ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 868 | ████████████████████ |
| `support` | 555 | █████████████ |
| `account` | 453 | ██████████ |
| `secure` | 421 | ██████████ |
| `wallet` | 346 | ████████ |
| `service` | 332 | ████████ |
| `update` | 284 | ███████ |
| `casino` | 265 | ██████ |
| `auth` | 258 | ██████ |
| `help` | 218 | █████ |
| `verify` | 216 | █████ |
| `connect` | 198 | █████ |

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
