# xRuffKez CTI (Cyber Threat Intelligence)

![Active domains](https://img.shields.io/badge/active_domains-194%2C672-c0392b?style=flat-square) ![Added 24h](https://img.shields.io/badge/added_%2824_h%29-8%2C200-e67e22?style=flat-square) ![Updated](https://img.shields.io/badge/updated-2026--11--06_00%3A48_UTC-2c7be5?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--2.0--only-6c757d?style=flat-square)

A continuously maintained blocklist of **active malicious domains**: phishing, malware delivery, scams, fraudulent shops and investment schemes, and the infrastructure behind them. Every entry is verified before it is published, and removed again once it is offline or no longer malicious, so the list stays current instead of growing forever.

> [!TIP]
> Subscribe to one of the files below in your DNS filter, ad blocker or resolver. The lists are refreshed several times per hour; polling every 1 to 6 hours is plenty.

## At a glance

<sub>as of 2026-11-06 00:48 UTC</sub>

| | |
|---|---:|
| Active domains | **194,672** |
| Added in the last 24 hours | 8,200 |
| Added in the last 7 days | 50,175 |
| Added in the last 30 days | 255,373 |
| Retired in the last 30 days (offline or cleaned up) | 734,190 |
| Top-level domains represented | 513 |
| Internationalized (IDN / punycode) domains | 0.1 % |
| Domains containing digits | 34.5 % |
| Domains containing hyphens | 30.7 % |
| Average domain length | 20.7 characters |

## Activity, last 30 days

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#c0392b"}}}}%%
xychart-beta
    title "New domains per day, Oct 8 – Nov 6 (UTC)"
    x-axis ["8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28", "29", "30", "31", "1", "2", "3", "4", "5", "6"]
    y-axis "domains" 0 --> 100000
    bar [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1227, 14240, 21381, 90492, 13281, 13149, 36078, 15350, 11978, 0, 0, 13504, 4877, 6808, 4640, 7419, 949]
```

```mermaid
%%{init: {"themeVariables": {"xyChart": {"plotColorPalette": "#2c7be5"}}}}%%
xychart-beta
    title "Active domains on the list, Oct 21 – Nov 6 (UTC)"
    x-axis ["21", "22", "23", "24", "25", "26", "27", "28", "29", "30", "31", "1", "2", "3", "4", "5", "6"]
    y-axis "domains"
    line [472713, 588659, 629951, 748222, 574614, 473331, 457795, 371010, 376945, 376945, 376945, 224607, 190603, 189609, 186630, 193931, 194672]
```

<details><summary>Last 7 days as a table</summary>

| Day (UTC) | Added | Retired |
|---|---:|---:|
| 2026-11-06 | 949 | 7 |
| 2026-11-05 | 7,419 | 16,700 |
| 2026-11-04 | 4,640 | 9,435 |
| 2026-11-03 | 6,808 | 5,460 |
| 2026-11-02 | 4,877 | 38,101 |
| 2026-11-01 | 13,504 | 173,332 |
| 2026-10-31 | 0 | 0 |

</details>

## Top-level domains

| # | TLD | Domains | Share | |
|---:|---|---:|---:|---|
| 1 | `.com` | 63,004 | 32.4 % | ████████████████████ |
| 2 | `.dev` | 22,541 | 11.6 % | ███████ |
| 3 | `.shop` | 8,735 | 4.5 % | ███ |
| 4 | `.net` | 6,985 | 3.6 % | ██ |
| 5 | `.top` | 5,896 | 3.0 % | ██ |
| 6 | `.cc` | 4,590 | 2.4 % | █ |
| 7 | `.org` | 4,582 | 2.4 % | █ |
| 8 | `.cn` | 4,351 | 2.2 % | █ |
| 9 | `.click` | 4,326 | 2.2 % | █ |
| 10 | `.app` | 4,290 | 2.2 % | █ |
| 11 | `.live` | 4,115 | 2.1 % | █ |
| 12 | `.xyz` | 4,094 | 2.1 % | █ |
| 13 | `.digital` | 4,039 | 2.1 % | █ |
| 14 | `.info` | 3,916 | 2.0 % | █ |
| 15 | `.pro` | 3,849 | 2.0 % | █ |

```mermaid
pie showData title Share of the 5 most common TLDs
    ".com" : 63004
    ".dev" : 22541
    ".shop" : 8735
    ".net" : 6985
    ".top" : 5896
    "other" : 87511
```

## Most imitated brands

Listed domains whose name contains a well-known brand. Brand names are trademarks of their owners; the brands themselves are of course not listed.

| Brand | Domains | |
|---|---:|---|
| WhatsApp | 4,653 | ████████████████████ |
| Coinbase | 931 | ████ |
| Meta / Facebook | 834 | ████ |
| Amazon | 609 | ███ |
| Apple / iCloud | 543 | ██ |
| Netflix | 508 | ██ |
| Telegram | 489 | ██ |
| Ledger | 449 | ██ |
| Google | 421 | ██ |
| Instagram | 354 | ██ |
| TikTok | 305 | █ |
| PayPal | 266 | █ |
| MetaMask | 264 | █ |
| Microsoft / Office 365 | 233 | █ |
| American Express | 233 | █ |

## Most common lure words

| Word | Domains | |
|---|---:|---|
| `trade` | 2,237 | ████████████████████ |
| `casino` | 1,448 | █████████████ |
| `login` | 1,096 | ██████████ |
| `support` | 936 | ████████ |
| `service` | 727 | ██████ |
| `invest` | 699 | ██████ |
| `bet` | 575 | █████ |
| `secure` | 522 | █████ |
| `wallet` | 501 | ████ |
| `account` | 465 | ████ |
| `update` | 447 | ████ |
| `token` | 433 | ████ |

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
