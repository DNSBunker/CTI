# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-42%2C283-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-34%2C405-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--10--30_15%3A01_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-10-30 15:01 UTC</sub>

| | |
|---|---:|
| Active domains | **42,283** |
| Added in the last 24 hours | 34,405 |
| Added in the last 7 days | 44,290 |
| Added in the last 30 days | 44,290 |
| Retired in the last 30 days (offline or cleaned up) | 448 |
| Top-level domains represented | 228 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 53.4 % |
| Domains containing hyphens | 59.4 % |
| Average domain length | 31.2 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Oct 1 – Oct 30 (UTC)"
    x-axis ["1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28", "29", "30"]
    y-axis "domains" 0 --> 50000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 41794, 2496]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Oct 29 – Oct 30 (UTC)"
    x-axis ["29", "30"]
    y-axis "domains"
    line [40447, 42283]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-10-30 | 2,496 | 448 |
| 2026-10-29 | 41,794 | 0 |
| 2026-10-28 | 0 | 0 |
| 2026-10-27 | 0 | 0 |
| 2026-10-26 | 0 | 0 |
| 2026-10-25 | 0 | 0 |
| 2026-10-24 | 0 | 0 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.com` | 10,345 | 24.5 % | ████████████████████ |
| 2 | `.dev` | 9,724 | 23.0 % | ███████████████████ |
| 3 | `.app` | 9,191 | 21.7 % | ██████████████████ |
| 4 | `.org` | 3,179 | 7.5 % | ██████ |
| 5 | `.io` | 1,525 | 3.6 % | ███ |
| 6 | `.club` | 1,042 | 2.5 % | ██ |
| 7 | `.host` | 659 | 1.6 % | █ |
| 8 | `.link` | 562 | 1.3 % | █ |
| 9 | `.pro` | 558 | 1.3 % | █ |
| 10 | `.net` | 530 | 1.3 % | █ |
| 11 | `.shop` | 425 | 1.0 % | █ |
| 12 | `.ph` | 329 | 0.8 % | █ |
| 13 | `.site` | 329 | 0.8 % | █ |
| 14 | `.top` | 291 | 0.7 % | █ |
| 15 | `.xyz` | 274 | 0.6 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 10345
    ".dev" : 9724
    ".app" : 9191
    ".org" : 3179
    ".io" : 1525
    "other" : 8319
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| WhatsApp | 782 | ████████████████████ |
| Meta / Facebook | 758 | ███████████████████ |
| Apple / iCloud | 684 | █████████████████ |
| Instagram | 506 | █████████████ |
| Coinbase | 430 | ███████████ |
| PayPal | 425 | ███████████ |
| Netflix | 392 | ██████████ |
| OpenSea | 353 | █████████ |
| Ledger | 282 | ███████ |
| MetaMask | 237 | ██████ |
| TikTok | 231 | ██████ |
| Telegram | 205 | █████ |
| Microsoft / Office 365 | 168 | ████ |
| LinkedIn | 161 | ████ |
| Google | 142 | ████ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 850 | ████████████████████ |
| `support` | 506 | ████████████ |
| `account` | 425 | ██████████ |
| `secure` | 390 | █████████ |
| `wallet` | 326 | ████████ |
| `service` | 315 | ███████ |
| `update` | 291 | ███████ |
| `auth` | 253 | ██████ |
| `help` | 211 | █████ |
| `security` | 205 | █████ |
| `claim` | 198 | █████ |
| `verify` | 189 | ████ |

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
