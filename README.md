# Cheap US VPS: how low does the monthly price go, what does the $7 tier actually include, and which JustHost plan fits your workload? (full plan table + billing checks)

JustHost's VPS list starts at **$1.99/month**: one core, 512 MB RAM, 5 GB of NVMe and a 10 Mbps fair-share port. The tier most readers end up needing sits a few rows down, at Sirius (1 core, 1 GB RAM, 20 GB NVMe, 300 Mbps), which costs **$4.85/month**, or **$3.88/month** if you pay for a year up front.

Two prices per plan is the first thing to understand about this list, and the rest of this article covers the full tariff table, what $7–8 buys from three other US hosts, and the billing details that decide what you pay in month 13.

> **Quick pick.** Running a bot, proxy, DNS resolver or a small API? The $1.99 Promo is enough. Running one WordPress site? Sirius at $4.85 ($3.88 prepaid) gives you 20 GB of NVMe and a 300 Mbps port. Running a store or several sites? Double Star at $7.08 ($5.67 prepaid) adds a second core and 2 GB RAM. SaaS with a real database: Vega, 2 cores / 4 GB / 80 GB, at $13.44.
>
> 👉 [Check the Double Star plan and its 12-month price](https://justhost.asia/en/services/vps/tariffs/double-star-c2r2048nvme?ref=196392)

## JustHost VPS plans and prices, all tiers

Every plan below is KVM with NVMe storage and DDoS protection on the network. Ports are unmetered but fair-share, and JustHost prints its own monthly transfer estimate next to each one.

| Plan | vCPU · RAM · NVMe | Port (fair-share) | Price | Order |
| --- | --- | --- | --- | --- |
| VPS Promo | 1 · 512 MB · 5 GB | 10 Mbps (≈4+ TB/mo) | $1.99/mo; no 12-month rate listed | [Order VPS Promo](https://justhost.asia/en/services/vps/tariffs/promo-c1r512nvme?ref=196392) |
| New Star | 1 · 1 GB · 10 GB | 100 Mbps (≈31+ TB/mo) | $3.81/mo · $3.05/mo on 12-month prepay | [Order New Star](https://justhost.asia/en/services/vps/tariffs/new-star-c1r1024nvme?ref=196392) |
| Sirius | 1 · 1 GB · 20 GB | 300 Mbps (≈93+ TB/mo) | $4.85/mo · $3.88/mo prepaid | [Order Sirius](https://justhost.asia/en/services/vps/tariffs/sirius?ref=196392) |
| Arcturus | 1 · 2 GB · 30 GB | 300 Mbps (≈93+ TB/mo) | $6.92/mo · $5.53/mo prepaid | [Order Arcturus](https://justhost.asia/en/services/vps/tariffs/arcturus?ref=196392) |
| Double Star | 2 · 2 GB · 20 GB | 200 Mbps (≈62+ TB/mo) | $7.08/mo · $5.67/mo prepaid | [Order Double Star](https://justhost.asia/en/services/vps/tariffs/double-star-c2r2048nvme?ref=196392) |
| Alpha Centauri | 2 · 2 GB · 40 GB | 400 Mbps (≈124+ TB/mo) | $8.99/mo · $7.19/mo prepaid | [Order Alpha Centauri](https://justhost.asia/en/services/vps/tariffs/alpha_centauri?ref=196392) |
| Bright Star | 4 · 4 GB · 30 GB | 300 Mbps (≈93+ TB/mo) | $9.80/mo · $7.84/mo prepaid | [Order Bright Star](https://justhost.asia/en/services/vps/tariffs/bright-star-c4r4096nvme?ref=196392) |
| Vega | 2 · 4 GB · 80 GB | 500 Mbps (≈155+ TB/mo) | $13.44/mo · $10.75/mo prepaid | [Order Vega](https://justhost.asia/en/services/vps/tariffs/vega?ref=196392) |
| Capella | 4 · 4 GB · 120 GB | 750 Mbps (≈232+ TB/mo) | $18.30/mo · $14.64/mo prepaid | [Order Capella](https://justhost.asia/en/services/vps/tariffs/capella?ref=196392) |

Three things the table doesn't show. New Star, Double Star and Bright Star carry a note that the discounted rate is available when you order three months or more, so those three have a minimum term rather than a true monthly option. Rigel (4 cores / 8 GB / 200 GB NVMe) sits above Capella; its price wasn't on the part of the tariff page I could read, so it isn't in the table. And the main /en/vps page carries a separate block of "Special" SKUs priced well below the tariff list for identical headline specs, which I'll come back to.

## What $7–8 a month buys from other US hosts

The $7–8 bracket is where budget US VPS pricing clusters, which makes it the honest place to test whether a host is cheap or just looks cheap.

| Provider | Cheapest listed US plan | What it includes | Caveat on the page |
| --- | --- | --- | --- |
| LightNode | $7.71/mo, or $0.012/hour | NVMe, KVM, full root, Washington DC and Silicon Valley | Windows VPS with RDP sold as a separate product |
| OmneHosting | $7.99/mo (Entry) | 2 vCPU, 4 GB RAM, 40 GB NVMe, Oregon or Virginia | No refunds on VPS; plans can't be resized in place |
| HostFinch | $7.99/mo (US-VPS-1) | 1 vCPU, 2 GB RAM, 40 GB SSD, 300 Mbps, unmetered, 1 IPv4 + 5 IPv6 | Largely unmanaged unless you buy support |

Put JustHost's Double Star next to OmneHosting's Entry and the trade is clear: same $7–8, same 2 cores, but JustHost gives 2 GB RAM and 20 GB of disk where OmneHosting gives 4 GB and 40 GB. If your workload is RAM-hungry (a database, WooCommerce, anything with PHP workers), the other hosts in this bracket sell more RAM per dollar.

Below $7 the picture reverses. Nothing from those three starts under $7.71, while JustHost sells working tiers at $1.99, $3.05 and $3.88 on prepay. For a proxy, a monitoring box, a Telegram bot or a single low-traffic site, that gap is the whole decision, and paying $7.99 to run a 200 MB script is wasted money.

## The billing details that decide the real price

**The discount is a prepayment, not a price.** Every card on the tariff list shows two numbers, and the second only applies when you pay for 12 months at once. Double Star costs $7.08 on monthly billing and $5.67 on the annual prepay. The cards don't state what you're charged after the prepaid term ends, so if you plan to stay past 12 months, ask support for the renewal rate in writing before you commit.

**The same specs appear twice, at different prices.** The /en/vps page runs a "Special offers" block that duplicates plans from the tariff list at lower rates: Sirius Special (1 core / 1 GB / 20 GB / 300 Mbps) at $2.81, or $2.25 prepaid, against $4.85 for the regular Sirius; Vega Special (2 cores / 4 GB / 80 GB / 500 Mbps) at $7.79, or $6.23 prepaid, against $13.44. Larger Special SKUs run up to Altair (8 cores / 24 GB / 600 GB) at $47.40. Promo stock rotates, so open both lists before checkout. If the Special version of the tier you want is available, that's the same hardware for less.

**The port figure is fair-share, and the terabyte number is JustHost's own conversion.** That 10 Mbps on the Promo plan works out to the "4+ TB/mo" printed beside it, which is plenty for a bot and painful for anything that serves files. A fair-share port also means peak-hour throughput isn't guaranteed. If your plan involves video, mirrors or backup targets, buy on the port number (400 Mbps and up), not on the RAM.

Big advertised discounts deserve the same scrutiny elsewhere. Contabo's US VPS page quotes CLOUD VPS 8 at €39.20/month "for the first 24 months", while a footnote on the same page says the displayed figure is the effective monthly rate for a 12-month subscription including applicable taxes. Two different terms, in euros, from a company that also bills in US dollars. Whatever host you're comparing, get the no-commitment monthly price and the renewal price in writing first.

👉 [Compare every JustHost VPS tariff side by side](https://justhost.asia/en/services/vps/tariffs-all?ref=196392)

## Who shouldn't start at $1.99

**Anyone who wants a control panel.** Licences cost more than the server at this end of the market. HostFinch lists LiteSpeed at $38.99/month for one CPU, Nginx with cPanel at $69.99/month, and an extra IPv4 at $5.00/month. On a $1.99 VPS, the panel is twenty to thirty-five times the price of the machine. If you need cPanel, budget for it as the main cost and treat the VPS as an accessory.

**Anyone who needs Windows.** The JustHost tariff cards list CPU, RAM, disk and port, not operating systems. If your plan is RDP into a Windows desktop, confirm that the tier you're buying supports it before paying; LightNode, for instance, sells Windows VPS with RDP as a separate product line in its US locations.

**Anyone buying for compliance reasons.** A US data centre doesn't make you HIPAA- or PCI-DSS-compliant on its own; that depends on what the provider actually offers, including the paperwork. HostAdvice's US VPS guide states the requirement plainly: compliance depends on the provider, not on the server's postcode. Ask for evidence before you put regulated data on a $5 box.

**Anyone who needs to phone support.** Contabo runs 24/7 phone support with English-speaking staff. JustHost's tariff cards don't list support channels, so if reaching a human by phone is a hard requirement, ask before you order rather than after.

## Pick by workload

- **DNS resolver, proxy, uptime monitor, one small bot:** VPS Promo, $1.99. 512 MB rules out most panels, and that's fine for a single process.
- **Static site, WireGuard endpoint, tiny API:** New Star, $3.81 ($3.05 prepaid). Watch the 10 GB disk; logs and a Node install will eat a third of it.
- **One WordPress site:** Sirius, $4.85 ($3.88 prepaid). The 20 GB of NVMe matters more than the extra 200 Mbps here.
- **WooCommerce or four or five small sites:** Double Star, $7.08 ($5.67 prepaid) for the second core. If product images and the database need room, Alpha Centauri at $8.99 ($7.19 prepaid) doubles the disk to 40 GB and the port to 400 Mbps for $1.91 more.
- **SaaS, API with a real database, anything running containers:** Vega, $13.44 ($10.75 prepaid), 2 cores / 4 GB / 80 GB. Capella at $18.30 ($14.64 prepaid) doubles the cores and triples the disk but stays at 4 GB RAM.
- **Agency hosting, game servers, CI runners:** Capella or the Rigel tier above it.

One oddity worth knowing: Bright Star gives you 4 cores and 4 GB for $9.80, while Vega gives 2 cores and 4 GB for $13.44. More cores are cheaper than more disk on this list. If your workload is compile jobs or game servers, Bright Star is the better buy; if it's a growing site, Vega's 80 GB and 500 Mbps port are worth the extra $3.64.

## Three checks before you pay

**Location.** The tariff cards don't name a data centre. Confirm where the server will sit for the specific plan you're ordering and that it's the US location you want, since latency to your users is the entire reason to buy a US VPS.

**Term.** Decide between the monthly rate and the 12-month prepay, and get the post-promo renewal price in writing. The gap on Double Star is $1.41/month, which is $16.92 a year, roughly what a mid-tier plan costs for two months.

**Refunds.** The tariff pages don't publish a refund window. If you're unsure whether 512 MB or 1 GB is enough, start on the monthly term with the smaller plan and upgrade once you've watched real memory usage for a week. Upgrading later costs less than prepaying a year of the wrong size.

For most readers the rule is: buy the smallest plan whose RAM covers your peak, not the smallest plan on the page. A $1.99 box that OOM-kills your database every night costs more in lost hours than the $4.85 tier would have.

👉 [Start with the $1.99 Promo plan and move up when you outgrow it](https://justhost.asia/en/services/vps/tariffs/promo-c1r512nvme?ref=196392)
