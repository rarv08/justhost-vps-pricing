# Cheap VPS: Is $2 a Month Enough, What Do the Port Caps and Add-Ons Hide, and Which JustHost.Asia Plan Should You Pick? (Full Price Table)

Two dollars a month still buys a working VPS in 2026: one vCPU, 512 MB to 1 GB of RAM, NVMe storage, root access and a dedicated IPv4. It does not buy headroom, fast support, or your money back if you change your mind.

The “$1 VPS” label deserves a warning before anything else. LightNode's landing page is literally titled “1 Dollar VPS,” and the cheapest configuration you can actually order on that page is $7.71/month (2 GB RAM, 1 vCPU, 50 GB NVMe, 1 TB bandwidth; page checked 28 October 2026). The dollar figure is a search keyword, not a checkout price. JustHost.Asia runs a similar trick in miniature, and its real entry price, plan ladder and fine print are what this page is about, along with the total cost after add-ons and the support record you should know before paying for a year upfront.

> **Quick pick:** most readers buying their first cheap VPS for one small site should take **New Star** at **$3.81/month** (1 vCPU, 1 GB RAM, 10 GB NVMe, 100 Mbps fair-share port, $3.05/month if you prepay 12 months). It has four times the RAM of the $1.99 plan and a port fast enough for real traffic. If you already know you need 2 GB, skip to Arcturus at $6.92. 👉 [Order the New Star plan](https://justhost.asia/en/services/vps/tariffs/new-star-c1r1024nvme?ref=196392)

## The full JustHost.Asia VPS ladder, as listed on the official tariff page

JustHost.Asia sells KVM VPS with NVMe storage and an “unmetered” port, which in practice means a capped port speed shared fairly between users rather than a traffic allowance. That distinction matters more than the RAM column at the cheap end, so it gets its own column below.

Prices are the dollar figures on the all-tariffs page. The second figure is the rate shown when you pay 12 months upfront.

| Plan | vCPU / RAM / NVMe | Port (fair-share) | Price | Order |
| --- | --- | --- | --- | --- |
| VPS Promo | 1 core / 512 MB / 5 GB | 10 Mbps (~4 TB/mo) | **$1.99/mo** | [Order VPS Promo](https://justhost.asia/en/services/vps/tariffs/promo-c1r512nvme?ref=196392) |
| New Star | 1 core / 1 GB / 10 GB | 100 Mbps (~31 TB/mo) | $3.81/mo, $3.05 at 12-month prepay | [Order New Star](https://justhost.asia/en/services/vps/tariffs/new-star-c1r1024nvme?ref=196392) |
| Sirius | 1 core / 1 GB / 20 GB | 300 Mbps (~93 TB/mo) | $4.85/mo, $3.88 at 12-month prepay | [Order Sirius](https://justhost.asia/en/services/vps/tariffs/sirius?ref=196392) |
| Arcturus | 1 core / 2 GB / 30 GB | 300 Mbps (~93 TB/mo) | $6.92/mo, $5.53 at 12-month prepay | [Order Arcturus](https://justhost.asia/en/services/vps/tariffs/arcturus?ref=196392) |
| Double Star | 2 cores / 2 GB / 20 GB | 200 Mbps (~62 TB/mo) | $7.08/mo, $5.67 at 12-month prepay | [Order Double Star](https://justhost.asia/en/services/vps/tariffs/double-star-c2r2048nvme?ref=196392) |
| Alpha Centauri | 2 cores / 2 GB / 40 GB | 400 Mbps (~124 TB/mo) | $8.99/mo, $7.19 at 12-month prepay | [Order Alpha Centauri](https://justhost.asia/en/services/vps/tariffs/alpha_centauri?ref=196392) |
| Bright Star | 4 cores / 4 GB / 30 GB | 300 Mbps (~93 TB/mo) | $9.80/mo, $7.84 at 12-month prepay | [Order Bright Star](https://justhost.asia/en/services/vps/tariffs/bright-star-c4r4096nvme?ref=196392) |
| Vega | 2 cores / 4 GB / 80 GB | 500 Mbps (~155 TB/mo) | $13.44/mo, $10.75 at 12-month prepay | [Order Vega](https://justhost.asia/en/services/vps/tariffs/vega?ref=196392) |
| Capella | 4 cores / 4 GB / 120 GB | 750 Mbps (~232 TB/mo) | $18.30/mo, $14.64 at 12-month prepay | [Order Capella](https://justhost.asia/en/services/vps/tariffs/capella?ref=196392) |

Two things in that table are worth pausing on.

The $1.99 VPS Promo has a **10 Mbps port**. That is about 1.25 MB/s at full tilt, roughly 4 TB of transfer across a month if you maxed it continuously. A 2 GB backup restore or a software update pulling a few hundred megabytes will feel slow, and a page with a large hero video will feel worse. It is a fine box for a static page, a monitoring node or a tunnel endpoint. It is a poor box for anything that serves files.

Arcturus and Double Star land within 16 cents of each other at $6.92 and $7.08, but they are not the same product. Double Star gives you a second core and a 200 Mbps port; Arcturus gives you 10 GB more disk and a 300 Mbps port on a single core. Single-threaded work such as a default WordPress install with no caching plugin tends to prefer the faster core and port. Anything that runs parallel processes prefers the second core.

## The second price list, and a headline you can't order

JustHost.Asia's VPS landing page advertises “VPS server from $1.16,” and the cheapest configuration on the all-tariffs page is $1.99. Neither page explains the gap, so budget $1.99 and treat $1.16 as a headline.

The same landing page lists a **“Special” line** that duplicates several plans at lower prices:

- Sirius Special: 1 core / 1 GB / 20 GB NVMe, 300 Mbps at **$2.81/mo** ($2.25 on 12-month prepay)
- Arcturus Special: 1 core / 2 GB / 30 GB, 300 Mbps at **$4.01/mo** ($3.21)
- Vega Special: 2 cores / 4 GB / 80 GB, 500 Mbps at **$7.79/mo** ($6.23)
- Yildun Special: 4 cores / 8 GB / 200 GB, 750 Mbps at **$16.20/mo** ($12.96)
- Betelgeuse Special: 6 cores / 12 GB / 400 GB, 750 Mbps at **$26.40/mo** ($21.12)
- Altair Special: 8 cores / 24 GB / 600 GB, 750 Mbps at **$47.40/mo** ($37.92)

Sirius Special and Sirius are the same specs at $2.81 versus $4.85, a 42% difference. Before you check out on any plan above Sirius, look at both pages; the cheaper listing is not the one the tariff page leads with. 👉 [Check the Special VPS lineup](https://justhost.asia/en/services/vps?ref=196392)

The site also sells storage-type variants of the same tiers, and the disk type moves the price: HDD VPS Start (1 core / 512 MB / 5 GB HDD) at $3.25/mo, SSD VPS Start+ at $3.90, NVMe VPS Start++ at $4.22. At the middle tier it is SSD VPS Standard+ (2 cores / 2 GB / 25 GB) at $13.20 versus NVMe VPS Standard++ at $14.30. There is an IPv6-only line from $1.60 and an IPv4+IPv6 line from $2.60, which is the cheapest way in if you don't need a dedicated IPv4.

JustHost.Asia's own Trustpilot profile says VPS plans start at $2.25/month. That number is the Sirius Special 12-month rate, not the $1.99 Promo and not a price you pay on a monthly term. It's a useful reminder that every “from” price on this site assumes a long prepay.

## What the sticker price leaves out

Cheap VPS pricing is usually honest about the CPU and RAM and quiet about everything around them. The recurring extras, per HostAdvice's buying guide (26 October 2026), are control-panel licences, backups and snapshots, extra IPv4 addresses, renewal increases after the intro term, managed support on an unmanaged plan, migration fees, security add-ons and bandwidth overage.

Real examples from providers' own pricing pages: Liquid Web charges extra for cPanel on top of its $11–$55/month VPS range; IONOS sells backups as a paid add-on; Namecheap's basic VPS tier includes no off-site backup storage. A $2 VPS with cPanel bolted on is closer to a $10–$12 VPS, which is why HostAdvice puts cPanel-ready entry VPS at roughly $8–$10/month.

For JustHost.Asia specifically, the plan specs list NVMe, the port, root access and DDoS protection. They do **not** mention automated backups, snapshots or a control-panel licence, and the tariff page shows no money-back window. Ask support what a backup costs and whether a refund exists before you commit; neither answer is on the page.

Then do the two-year arithmetic instead of the one-month comparison. With this provider the discount is tied to a 12-month prepay (about 20% off the monthly rate), so the cheapest per-month number is also the longest commitment. Take New Star: $3.81 monthly is $45.72 for a year; $3.05 monthly on a 12-month prepay is $36.60. You save $9.12 and lose the ability to walk away after two months. On a $3.81 plan that trade is not worth much, and on a provider with no published refund policy it is worth less than nothing.

## What a 1 GB or 2 GB box actually handles

HostAdvice's spec baseline for low-cost VPS is a reasonable yardstick: 1 GB RAM for testing or a tiny site, 2 GB for a small WordPress install, 4 GB and up for WooCommerce or several sites; 20–50 GB of SSD or NVMe; around 1 TB/month of transfer on typical plans.

Their capacity estimate for a small VPS (1–2 GB RAM, one core) is 10,000–50,000 visits a month, or 5–10 lightweight sites. A mid-range box (4–8 GB, 2–4 cores) covers 100,000–500,000 visits. And the threshold where a VPS starts to make sense over shared hosting is around 90,000 monthly visits.

So the $1.99 Promo with 512 MB is below every one of those bands. It is a lab machine: a WireGuard endpoint, an uptime monitor, a cron runner, a place to learn SSH. It will run a static HTML page behind Nginx comfortably and it will fall over on a WordPress install with a page builder and three plugins.

The RAM number also decides whether you can use a panel at all. cPanel on a 1 GB box is tight; 2 GB is the working minimum, which puts you on Arcturus at $6.92, not the $1.99 plan.

Cheap VPS is the wrong purchase in four situations, and it's worth saying so plainly: you're still learning FTP and WordPress; you can't afford the real total after add-ons; you have no intention of patching a Linux server yourself; or the site is low-traffic and non-critical, where shared hosting at $2–$5 does the same job with a support desk behind it.

## How the entry price compares

All figures below are the cheapest listed entry price at the time of capture, which in every case is a first-term or promotional rate, not a long-run price. HostAdvice data is from 26 October 2026; Vultr, Hetzner and Netcup figures are from Liquid Web's roundup dated 14 October 2026.

| Provider | Cheapest listed entry | Notes |
| --- | --- | --- |
| IONOS | $2.00/mo | Virtual Server S+, 1 core / 2 GB / 60 GB, 30-day money-back |
| Network Solutions | $2.09/mo | 30-day money-back |
| HostGator | $2.24/mo | 30-day money-back |
| Cloudzy | $2.48/mo | 7-day refund window |
| Vultr | $2.50/mo | SSD instances, hourly billing |
| FastHosts | $2.68/mo | 30-day money-back |
| InterServer | $3.00/mo | 30-day money-back |
| Netcup | €3.35/mo | 2 vCore / 2 GB / 64 GB |
| eVPS.net | $3.36/mo | 7-day refund window |
| Kamatera | $4.00/mo | 30-day trial worth up to $100 |
| Hetzner Cloud | €4.35/mo | NVMe plus AMD EPYC, Germany/Finland/US |
| MVPS | $4.48/mo | 3-day refund window |

JustHost.Asia's $1.99 sits at the bottom of that list, and the comparison that matters is with IONOS at $2.00: IONOS gives you 2 GB of RAM and 60 GB of disk for one cent more, with a 30-day money-back guarantee and a 4.5/5 Trustpilot rating. JustHost.Asia's advantage is not the entry price. It's the port speed at higher tiers (750 Mbps on Capella, where most budget hosts cap far lower), the 45 locations including CN2-optimised routes into mainland China, and support for crypto, PayPal, Alipay and UnionPay at checkout.

## Refunds and support: the part that decides the purchase

Refund terms across cheap VPS are far less uniform than the marketing suggests. Most of the names above run 30 days. Cloudzy gives 7. MVPS gives 3. eVPS.net gives 7. Hostwinds runs a three-day return policy. DigitalOcean offers no refunds at all.

JustHost.Asia doesn't publish a money-back period on the plan pages, so the safe way to buy is a short term: monthly, or the three-month minimum where the discount applies. Spend the first week testing exactly what you'd test a used car for. Boot time, disk I/O, whether the port delivers the advertised speed at your location, and how long a support ticket actually takes.

That last one is where the public record is thin and unflattering. Reviewers on Trustpilot in 2026 describe a live chat that is a bot, one of them saying it took a screenshot of their own account page before the bot accepted that an IP belonged to the company. The same reviewer describes a full outage on 2 March 2026 affecting servers and the control panel, with 15 hours of silence across chat and tickets and no status page. Another reports 10 VPS instances that would not connect, with no resolution after contacting support. A third puts operational support at up to 48 hours and notes that relocating to another datacenter is manual and requires reconfiguring the server from scratch.

None of that makes the hardware bad. A March 2026 third-party review of the São Paulo node measured roughly 509 MB/s I/O and a Geekbench 6 single-core score of 705, which is modest, and found the location better suited to transit and region-unlocking than to latency-sensitive work. The pattern across reviews is a cheap, configurable box with a thin support layer. If you can administer a server and keep your own backups, that's a workable trade at $2–$7 a month. If you'll need someone to fix it at 2 a.m., this is not the provider, and no price makes it one.

## Which plan to order

Match the plan to the job rather than to the price:

- A tunnel, monitor, cron box or a page you could rebuild in ten minutes: **VPS Promo, $1.99**. Accept 512 MB and a 10 Mbps port.
- One small WordPress site, or five static sites: **New Star, $3.81**, or **Sirius Special at $2.81** if the 20 GB disk and 300 Mbps port matter more than the discount page's existence.
- A site with a control panel, a small WooCommerce store, or 2 GB of RAM as a floor: **Arcturus, $6.92**. If you run parallel workloads, **Double Star, $7.08** for the second core.
- Several client sites or a busy application: **Vega, $13.44** (4 GB, 80 GB), then **Capella, $18.30** (4 cores, 120 GB), then **Altair Special, $47.40** (8 cores, 24 GB).

Before you pay, confirm two things that the plan pages don't settle. First, the term: whether the price in your cart is the monthly rate or the 12-month rate, and what the next invoice will be. Second, the location and backups: pick the datacenter nearest your visitors (45 locations means you have a choice, and the wrong continent costs more in load time than any plan upgrade), and ask in writing whether automatic backups exist and what they cost, because nothing in the specs says they do.

If both answers are acceptable, the cheapest honest entry into a KVM VPS with NVMe and root access is one click away. 👉 [Start with the New Star plan at $3.81/month](https://justhost.asia/en/services/vps/tariffs/new-star-c1r1024nvme?ref=196392)
