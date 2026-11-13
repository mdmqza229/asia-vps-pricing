# Asia VPS: What Does It Cost, Which City Do You Need, and How Much RAM Is Enough? (JustHost.asia's Full Plan List, the Prepay Math, and What the Pricing Page Leaves Out)

JustHost.asia's VPS line starts at $1.99/mo for 512 MB of RAM, 5 GB of NVMe and a 10 Mbps port, and runs to $47.40/mo for 8 cores and 24 GB. The "from $2.25/month" figure in the company's own marketing is not the entry price. It is the 12-month prepay rate on the Sirius Special, a plan that costs $2.81 month to month.

This article covers every plan on both of the provider's plan pages, the location rules that decide whether an Asia VPS is actually faster for your users, how much RAM each common workload needs, and three places where the sticker price and the real bill come apart.

> **Quick pick:** if you are running a small WordPress site, a couple of bots or a proxy endpoint for a handful of people, take the 2 GB tier. The **Arcturus Special at $4.01/mo** ($3.21/mo if you prepay 12 months) is the best value on the list: 1 core, 2 GB RAM, 30 GB NVMe, 300 Mbps fair-share port. 👉 [See the Arcturus Special and the other 2 GB plans](https://justhost.asia/en/vps?ref=196392)

## Every JustHost.asia VPS plan, side by side

Two official pages carry plans. The tariff list at `/en/services/vps/tariffs-all` has the named "star" line; `/en/vps` carries the Special line plus storage-type variants. Prices below are US dollars as shown on the English pages.

| Plan | CPU / RAM | NVMe + port speed | Price | Order |
| --- | --- | --- | --- | --- |
| VPS Promo | 1 core / 512 MB | 5 GB / 10 Mbps (~4 TB) | $1.99/mo; 12-month rate blank on page | [ See plan](https://justhost.asia/en/services/vps/tariffs/promo-c1r512nvme?ref=196392) |
| New Star | 1 core / 1 GB | 10 GB / 100 Mbps (~31 TB) | $3.81/mo, $3.05 on 12 months | [ See plan](https://justhost.asia/en/services/vps/tariffs/new-star-c1r1024nvme?ref=196392) |
| Sirius | 1 core / 1 GB | 20 GB / 300 Mbps (~93 TB) | $4.85/mo, $3.88 on 12 months | [ See plan](https://justhost.asia/en/services/vps/tariffs/sirius?ref=196392) |
| Arcturus | 1 core / 2 GB | 30 GB / 300 Mbps (~93 TB) | $6.92/mo, $5.53 on 12 months | [ See plan](https://justhost.asia/en/services/vps/tariffs/arcturus?ref=196392) |
| Double Star | 2 cores / 2 GB | 20 GB / 200 Mbps (~62 TB) | $7.08/mo, $5.67 on 12 months | [ See plan](https://justhost.asia/en/services/vps/tariffs/double-star-c2r2048nvme?ref=196392) |
| Alpha Centauri | 2 cores / 2 GB | 40 GB / 400 Mbps (~124 TB) | $8.99/mo, $7.19 on 12 months | [ See plan](https://justhost.asia/en/services/vps/tariffs/alpha_centauri?ref=196392) |
| Bright Star | 4 cores / 4 GB | 30 GB / 300 Mbps (~93 TB) | $9.80/mo, $7.84 on 12 months | [ See plan](https://justhost.asia/en/services/vps/tariffs/bright-star-c4r4096nvme?ref=196392) |
| Vega | 2 cores / 4 GB | 80 GB / 500 Mbps (~155 TB) | $13.44/mo, $10.75 on 12 months | [ See plan](https://justhost.asia/en/services/vps/tariffs/vega?ref=196392) |
| Capella | 4 cores / 4 GB | 120 GB / 750 Mbps (~232 TB) | $18.30/mo, $14.64 on 12 months | [ See plan](https://justhost.asia/en/services/vps/tariffs/capella?ref=196392) |

The list continues past Capella with Rigel (4 cores, 8 GB, 200 GB NVMe) and larger configurations. Rigel's price was cut off in the version of the page I read, so confirm it on the page before you plan around it.

"Unmetered" here means no monthly traffic allowance, with a port speed cap and fair-share scheduling. The "~93 TB" style figures are what the port would move if it ran flat out for a month, not a promise of sustained throughput.

The second pricing page carries a near-identical hardware line under different names and, in most cases, a much lower price:

| Plan | CPU / RAM | NVMe + port speed | Price | Order |
| --- | --- | --- | --- | --- |
| Sirius Special | 1 core / 1 GB | 20 GB / 300 Mbps | $2.81/mo, $2.25 on 12 months | [ See plan](https://justhost.asia/en/vps?ref=196392) |
| Arcturus Special | 1 core / 2 GB | 30 GB / 300 Mbps | $4.01/mo, $3.21 on 12 months | [ See plan](https://justhost.asia/en/vps?ref=196392) |
| Vega Special | 2 cores / 4 GB | 80 GB / 500 Mbps | $7.79/mo, $6.23 on 12 months | [ See plan](https://justhost.asia/en/vps?ref=196392) |
| Yildun Special | 4 cores / 8 GB | 200 GB / 750 Mbps | $16.20/mo, $12.96 on 12 months | [ See plan](https://justhost.asia/en/vps?ref=196392) |
| Betelgeuse Special | 6 cores / 12 GB | 400 GB / 750 Mbps | $26.40/mo, $21.12 on 12 months | [ See plan](https://justhost.asia/en/vps?ref=196392) |
| Altair Special | 8 cores / 24 GB | 600 GB / 750 Mbps | $47.40/mo, $37.92 on 12 months | [ See plan](https://justhost.asia/en/vps?ref=196392) |

Compare Vega with Vega Special: same 2 cores, same 4 GB, same 80 GB NVMe, same 500 Mbps port. $13.44 against $7.79, a 42% difference. Sirius and Sirius Special differ by the same 42%. Whatever the Special line is (promotional stock, a different billing pipeline, a limited run), it is the same hardware and it is the one to check first. Start there and fall back to the named plans if a Special is out of stock.

The same page also sells the 512 MB and 4 GB sizes by disk type. At 512 MB, 1 core and 5 GB of storage: HDD $3.25/mo ($2.60 on 12 months), SSD $3.90 ($3.12), NVMe $4.22 ($3.38). At 4 cores and 4 GB with 50 GB of disk: HDD $22 ($17.60), SSD $26.40 ($21.12), NVMe $28.60 ($22.88). NVMe over HDD costs $0.78/mo more at the bottom and $5.28/mo more at 4 GB. On a database or a container host, pay it. On a static site or a proxy, the HDD tier is $9.36 a year cheaper and nothing you do will notice.

There is also an IPv6-only line advertised "from $1.60", with IPv4+IPv6 "from $2.60". Those are starting figures without a spec attached, so treat them as a signpost rather than a price.

## Which city do you need, and can you even get it?

A VPS in Asia helps because of distance, and only because of distance. Every request from a visitor to your server and back costs time; when the server sits in Virginia or Frankfurt, a round trip crosses an ocean twice before PHP starts working. Put the same box in Singapore and users in Jakarta, Kuala Lumpur or Manila get an answer in tens of milliseconds instead of hundreds.

The city rule of thumb for Asian traffic:

- **Southeast Asia** (Indonesia, Malaysia, Thailand, Vietnam, Philippines, Singapore): Singapore. It has the densest carrier and peering footprint in the region and sits within a short hop of all of the above.
- **Northeast Asia** (Japan, Korea, Taiwan, northern China): Tokyo or Seoul, or Hong Kong if you want one box for both.
- **Greater China with international traffic as well**: Hong Kong. A reviewer for a competing provider makes the point that Hong Kong's status lets a server reach mainland users while keeping international routing, which is why it shows up so often in this segment.
- **South Asia**: Mumbai.
- **Australia and New Zealand**: Sydney, and don't try to serve them from Singapore if latency matters.

Coverage varies a lot between providers in this bracket, so check before you assume. LightNode advertises 23 Asian regions and names Singapore, Korea, Hong Kong, Vietnam, Cambodia, the Philippines, Thailand, Bangladesh, Malaysia, Indonesia and Myanmar. Cloudzy's only deployable Asian region is Singapore, with Sydney as the other APAC option and Tokyo listed as coming but not open yet. If your users are in Japan or Korea, that last detail rules Cloudzy out for now.

JustHost.asia is harder to pin down, and this is the part to sort out before you pay for a year. The pricing pages sell configurations, not cities. The company's own Trustpilot profile claims 45 server locations worldwide plus optimised CN2 routing for access from mainland China; a third-party review puts the figure at 77 locations and describes a builder that lets you switch location instantly. Those two numbers can't both be current, and neither tells you whether the specific city you need is in stock on the plan you picked. CN2 is a China Telecom premium route, so if mainland access is your reason for being here, ask support to confirm which locations actually carry it.

Do that check first. Location is the one thing you cannot fix later with an upgrade.

## How much RAM and disk for what you're running

The 5 GB of disk on the entry plans is a tighter constraint than the 512 MB of RAM. A Linux install plus a Docker image or two will fill it. Size the disk before you size the CPU.

- **Static site, cron job, single-purpose bot, monitoring node**: 512 MB is genuinely enough. VPS Promo at $1.99 works, though the 10 Mbps port makes it a poor fit for anything serving images. The HDD Start at $2.60 on 12 months is the same money with a more usable disk type trade.
- **Small WordPress with a cache plugin, one bot with a browser, WireGuard for a few people**: 1 GB. Sirius over New Star, because $1.04/mo buys you double the disk (20 GB vs 10 GB) and three times the port speed (300 vs 100 Mbps).
- **WooCommerce with a few hundred SKUs, a Docker host with three or four containers, a scraper that runs headless Chrome, a vanilla Minecraft server for a handful of players**: 2 GB. Arcturus Special at $4.01 is the value pick. If your workload is multithreaded rather than single-threaded, Double Star's second core costs $3.07/mo more at list.
- **Modded Minecraft or a small voice server, a database plus an API, a CI runner**: 4 GB. Bright Star ($9.80) is the cheap way in with 4 cores and only 30 GB of disk; Vega Special ($7.79) costs less and gives you 80 GB but half the cores. Pick by whether you are short of threads or short of disk.
- **Several game instances, a mid-size Postgres, a build farm**: 8 GB and up. Yildun Special at $16.20 for 4 cores and 200 GB is the step where this provider stops being obviously cheap and starts being ordinary.
- **CPU-only model inference**: a 7B parameter model at 4-bit quantization needs roughly 5 to 6 GB of RAM, so the 8 GB tier fits it. Expect batch-job speeds, not chat speeds. No amount of cores makes CPU inference feel interactive.

One trap in the plan ladder: RAM is not the axis the prices follow. Bright Star gives you 4 cores and 4 GB for $9.80; Vega gives you 2 cores and 4 GB for $13.44. The cheaper plan has twice the cores and less than half the disk. Decide which of the two you actually need before you sort the table by price.

## The real bill: list price, prepay price, and the plan you nearly bought twice

The 20% discount requires paying 12 months up front, and on New Star, Double Star and Bright Star the page notes the plan is only available on orders of three months or more. Month to month you pay the list price.

Take Vega Special. At $7.79/mo you pay $93.48 over a year. At $6.23/mo prepaid you pay $74.76, a saving of $18.72, and you have handed over a year of hosting before you know whether the location performs. On the cheap end the stakes are small (Sirius Special saves $6.72 a year). On Altair the same 20% is $113.76 a year, which is real money to risk on an unverified city.

That is the argument for one month at list price first, then committing once you have pinged the server from where your users actually are.

The same trap shows up across this whole market, and it is why price lists in this segment are so hard to compare:

- Cloudzy advertises "plans from $2.48/mo, 50% off". The $2.48 is the discounted rate on a 512 MB plan whose list price is $4.95, and the page contradicts itself on whether the 50% applies to monthly or annual billing.
- Exabytes lists "$27.99/mo" for a 4 GB plan, but the order link bills triennially, so that figure is a three-year contract divided by 36. The page behind it dates from 2021. Neither number belongs in the same column as a monthly price from 2026.

Compare at the same spec, the same billing cycle and the same currency. Here is the 2 GB tier, where most small sites land:

| Plan | CPU / RAM | Disk and bandwidth model | Price |
| --- | --- | --- | --- |
| JustHost.asia Arcturus | 1 core / 2 GB | 30 GB NVMe / 300 Mbps fair-share, unmetered | $6.92/mo, $5.53 on 12 months |
| JustHost.asia Double Star | 2 cores / 2 GB | 20 GB NVMe / 200 Mbps fair-share, unmetered | $7.08/mo, $5.67 on 12 months |
| LightNode Start | 1 core / 2 GB | 50 GB NVMe / 1 TB transfer | $7.71/mo, hourly billing |
| Cloudzy 2 GB | 1 core / 2 GB | 60 GB NVMe / 3 TB transfer | $7.48/mo, discounted from $14.95 |

The bandwidth models are not equivalent: JustHost caps port speed and lets volume run free, LightNode and Cloudzy cap monthly volume at a fixed port speed. For a site with steady traffic and no big transfers, the port model is generous. For anything that bursts, the monthly allowance is easier to reason about.

Two costs that don't show up in the table: the 5 GB disk on the entry tiers, and IP changes if you ever move regions. A provider's own docs are usually where the second one hides; Cloudzy states plainly that relocating a server changes its IP and you have to update DNS.

👉 [Open the full plan list with the 12-month rates](https://justhost.asia/en/services/vps/tariffs-all?ref=196392)

## Refunds, uptime and support: what the record shows

I could not find a published money-back guarantee on either JustHost.asia pricing page. That is not proof there isn't one, but it does mean you should not assume the 14-day refund that Cloudzy offers, or the cancel-anytime hourly billing that LightNode runs, applies here. Ask support in writing before you prepay 12 months, and keep the reply.

The public review record is the other thing to weigh. On Trustpilot, the company replies to 57% of negative reviews and typically takes up to two weeks to do it. The reviews themselves describe slow ticket responses, a live chat that behaves like a bot, a full outage on 2 March 2026 with no status page and no updates for around 15 hours, and a port sold as 1000 Mbit delivering 100 to 200 Mbit under load. These are individual accounts, not a measured average, and unhappy customers write reviews far more often than happy ones. But the support-latency theme repeats across several of them, which is the kind of pattern that matters more than any single complaint.

What that means in practice: this is a provider to use for things that can survive a day of downtime. A staging environment, a scraper, a personal VPN endpoint, a side project. It is a poor fit for a store taking payments, or anything where you need an answer from a human within the hour.

👉 [Check the plan page and confirm the terms before you prepay](https://justhost.asia/en/vps?ref=196392)

## FAQ

**Which plan for a small WordPress site?**
Start at 2 GB. Arcturus Special at $4.01/mo ($3.21 prepaid) if it is in stock, Arcturus at $6.92 otherwise. Below 1 GB, PHP and MySQL will fight over memory the first time a plugin misbehaves.

**Sirius or New Star?**
Both are 1 core and 1 GB. Sirius costs $1.04/mo more and gives you 20 GB instead of 10 GB of NVMe and 300 Mbps instead of 100 Mbps. Take Sirius.

**Arcturus or Double Star?**
Same RAM, same price bracket. Arcturus is 1 core with 30 GB of disk and a 300 Mbps port; Double Star is 2 cores with 20 GB and 200 Mbps. Single-threaded work (PHP, most bots) prefers Arcturus. Anything that parallelises prefers Double Star.

**Can I install Windows?**
Not confirmed. A third-party review lists Ubuntu, Debian and MikroTik RouterOS among the templates, and MikroTik is genuinely useful if you want a router-style VPN endpoint. Nothing I checked mentions Windows licensing, so ask support before you count on it.

**Can I move to another city or a bigger plan later?**
A third-party review describes instant location switching in the order builder, but the official pages don't document it. Assume a region change means a new IP and a DNS update, and confirm the upgrade path with support.

**Do I need an ICP filing?**
Only if the server itself sits in mainland China. Hong Kong and Singapore do not require one, which is part of why Hong Kong is the usual compromise for reaching both mainland and international users.

## Pick by situation

- **Cheapest thing that works, for a bot or a static site**: VPS Promo at $1.99, or HDD Start at $2.60 on 12 months if you want a payment term you can plan around.
- **Small site or a couple of services, best value**: Arcturus Special, $4.01/mo ($3.21 prepaid), 2 GB and 30 GB NVMe.
- **Multithreaded work on a budget**: Bright Star, $9.80/mo, 4 cores and 4 GB, accepting only 30 GB of disk.
- **Game servers or a database with room to grow**: Yildun Special, $16.20/mo, 4 cores and 8 GB.
- **Need a human on support within the hour, or a refund window**: look elsewhere. Cloudzy publishes a 14-day money-back guarantee; LightNode bills hourly so you can leave after a day.

Before you pay, confirm four things in writing: the exact city your plan will deploy in, whether CN2 routing applies to that city, whether the plan you picked is billed monthly or requires a 12-month commitment, and what happens to your money if you cancel in week two. The pricing page answers none of those.

👉 [Compare all JustHost.asia VPS plans and current rates](https://justhost.asia/en/services/vps/tariffs-all?ref=196392)
