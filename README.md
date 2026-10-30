# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-47%2C875-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-16%2C975-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--10--30_17%3A06_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-10-30 17:06 UTC</sub>

| | |
|---|---:|
| Active domains | **47,875** |
| Added in the last 24 hours | 16,975 |
| Added in the last 7 days | 50,331 |
| Added in the last 30 days | 50,331 |
| Retired in the last 30 days (offline or cleaned up) | 810 |
| Top-level domains represented | 249 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 50.6 % |
| Domains containing hyphens | 59.4 % |
| Average domain length | 29.8 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Oct 1 – Oct 30 (UTC)"
    x-axis ["1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28", "29", "30"]
    y-axis "domains" 0 --> 50000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 41794, 8537]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Oct 29 – Oct 30 (UTC)"
    x-axis ["29", "30"]
    y-axis "domains"
    line [40447, 47875]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-10-30 | 8,537 | 810 |
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
| 1 | `.com` | 12,172 | 25.4 % | ████████████████████ |
| 2 | `.dev` | 9,841 | 20.6 % | ████████████████ |
| 3 | `.app` | 9,055 | 18.9 % | ███████████████ |
| 4 | `.org` | 3,254 | 6.8 % | █████ |
| 5 | `.io` | 1,538 | 3.2 % | ███ |
| 6 | `.cn` | 1,273 | 2.7 % | ██ |
| 7 | `.club` | 1,057 | 2.2 % | ██ |
| 8 | `.pro` | 798 | 1.7 % | █ |
| 9 | `.shop` | 661 | 1.4 % | █ |
| 10 | `.host` | 659 | 1.4 % | █ |
| 11 | `.ph` | 623 | 1.3 % | █ |
| 12 | `.net` | 617 | 1.3 % | █ |
| 13 | `.link` | 569 | 1.2 % | █ |
| 14 | `.top` | 513 | 1.1 % | █ |
| 15 | `.xyz` | 430 | 0.9 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 12172
    ".dev" : 9841
    ".app" : 9055
    ".org" : 3254
    ".io" : 1538
    "other" : 12015
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| WhatsApp | 2,232 | ████████████████████ |
| Meta / Facebook | 943 | ████████ |
| Coinbase | 926 | ████████ |
| Apple / iCloud | 872 | ████████ |
| PayPal | 827 | ███████ |
| Netflix | 580 | █████ |
| Instagram | 554 | █████ |
| Telegram | 512 | █████ |
| TikTok | 386 | ███ |
| OpenSea | 358 | ███ |
| Ledger | 310 | ███ |
| MetaMask | 295 | ███ |
| Google | 225 | ██ |
| LinkedIn | 205 | ██ |
| Microsoft / Office 365 | 188 | ██ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `login` | 891 | ████████████████████ |
| `support` | 571 | █████████████ |
| `account` | 467 | ██████████ |
| `secure` | 451 | ██████████ |
| `wallet` | 364 | ████████ |
| `service` | 349 | ████████ |
| `update` | 312 | ███████ |
| `auth` | 262 | ██████ |
| `casino` | 233 | █████ |
| `verify` | 228 | █████ |
| `help` | 224 | █████ |
| `security` | 223 | █████ |

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
