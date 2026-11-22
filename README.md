# Cheap KVM VPS: How Much RAM €2–€10 Buys, Which Plan Fits WordPress or Docker, and Where the Extra Charges Hide (Full Plan Table)

A cheap KVM VPS runs from about $0.75 to $26 per GB of RAM per month, and the number on the plan card won't tell you which end you're on. InterServer puts 2GB in a $3/month slice; Koddos charges $12.95 for 512MB; ucartz's annual VPS Lite works out to $36 a year for 4GB. Ava Hosting starts at €2/month for 1GB and €5/month for 2GB, both on NVMe with unlimited transfer.

The rest of this page does three things: lists every Ava Hosting plan with its price, converts those prices into cost per GB of RAM so they can be compared with anyone else, and points out the refund clause that quietly disappears when you use a discount code.

> **Most people should buy Ava Hosting's VPS One at €5/month.** It gives 1 vCPU, 2GB ECC RAM, 25GB NVMe, a 1Gbps port, free DDoS protection and weekly backups, which is enough for a small WordPress site, a Docker playground or a CI runner. If you need 4GB, VPS Basic at €10/month is the same product with double the resources. If €2 is the whole budget, the Self-hosted Start plan gets a 1 vCPU / 1GB / 15GB box.
>
> 👉 [Open Ava Hosting's plan pages and compare VPS One against the rest](https://my.ava.hosting/aff.php?aff=15562)

## Ava Hosting sells two near-identical plan lines, and only one of them is the obvious pick

The VPS/VDS line is the one to buy between €5 and €15. It carries the same specs as the cheaper Self-hosted line at the same price, plus free DDoS protection, weekly backups and a 1Gbps port. The Self-hosted line only pulls ahead at €20 and above, where it hands you 10 to 40GB more disk for the same money.

### VPS/VDS line

| Plan | vCPU | RAM (ECC) | NVMe | Price | Order |
| --- | --- | --- | --- | --- | --- |
| VPS Nano | 1 | 512MB | 20GB | €11.00/year | [Order VPS Nano](https://my.ava.hosting/aff.php?aff=15562) |
| VPS One | 1 | 2GB | 25GB | €5.00/month | [Order VPS One](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Basic | 2 | 4GB | 50GB | €10.00/month | [Order VPS Basic](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Lucky | 2 | 6GB | 70GB | €15.00/month | [Order VPS Lucky](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Power | 4 | 8GB | 90GB | €20.00/month | [Order VPS Power](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Extra | 6 | 12GB | 120GB | €30.00/month | [Order VPS Extra](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Ultra | 8 | 16GB | 160GB | €40.00/month | [Order VPS Ultra](https://my.ava.hosting/aff.php?aff=15562) |

Every plan in this line lists full root access, a control panel, 99.9% SLA uptime, 24/7 support, unlimited bandwidth and free DDoS protection. The hardware line is Intel Xeon E5 with NVMe storage. Two exceptions on the Nano: its port is 100Mbps instead of 1Gbps, port 25 is closed, and the order page showed zero units available when I checked, so treat it as a stock-dependent entry point rather than a reliable €11 option.

### Self-hosted line

| Plan | vCPU | RAM | NVMe | Price | Order |
| --- | --- | --- | --- | --- | --- |
| Start | 1 | 1GB | 15GB | €2.00/month | [Order Start](https://my.ava.hosting/aff.php?aff=15562) |
| Mini | 1 | 2GB | 25GB | €5.00/month | [Order Mini](https://my.ava.hosting/aff.php?aff=15562) |
| Basic | 2 | 4GB | 50GB | €10.00/month | [Order Basic](https://my.ava.hosting/aff.php?aff=15562) |
| Pro | 4 | 8GB | 100GB | €20.00/month | [Order Pro](https://my.ava.hosting/aff.php?aff=15562) |
| Business | 6 | 12GB | 150GB | €30.00/month | [Order Business](https://my.ava.hosting/aff.php?aff=15562) |
| Power | 8 | 16GB | 200GB | €40.00/month | [Order Power](https://my.ava.hosting/aff.php?aff=15562) |

These pages list only vCPU, RAM, NVMe and unlimited transfer. DDoS protection and backups are not mentioned here, so confirm them on a ticket if you pick this line. The Start plan also carries a free-trial label on its order page.

Three things the plan pages don't state, all of which matter before you pay. Prices are "starting from" figures in euro, so your card issuer's conversion applies. No renewal rate is published, which means the €5 you see may not be the €5 you're billed in month thirteen. And the hypervisor is never named. If KVM specifically is the reason you're shopping (own kernel, Docker without workarounds, custom ISO), ask pre-sales to confirm it before you order rather than assuming from the specs.

## What a euro actually buys, in GB of RAM

Sort the market by cost per GB of RAM per month and the same phrase covers a 30-fold spread. The figures below are the published starting prices as of late October and early November 2026.

| Provider and plan | Price | RAM | Cost per GB RAM/month |
| --- | --- | --- | --- |
| ucartz VPS Lite (annual) | $36/year | 4GB | ~$0.75 |
| InterServer Linux KVM | $3.00/month | 2GB | ~$1.50 |
| Ava Hosting Start | €2.00/month | 1GB | ~€2.00 |
| Ava Hosting VPS One | €5.00/month | 2GB | ~€2.50 |
| Koddos KVM B | $29.95/month | 2GB | ~$15.00 |
| Koddos KVM MINI A | $12.95/month | 512MB | ~$25.90 |

Storage tells a similar story. Koddos gives 10GB for $12.95, InterServer gives 30GB for $3, and Ava gives 25GB for €5.

Ava's own ladder is flat. Every plan from VPS One to VPS Ultra costs €2.50 per GB of RAM, and the Self-hosted line lands on the same figure from Mini upward. Buying the €40 plan doesn't lower your unit cost, and buying the €5 plan doesn't raise it. That's unusual, and it's convenient: pick the size your workload needs and stop hunting for a volume discount that doesn't exist. The one exception is Start at €2 for 1GB, the cheapest RAM in Ava's catalogue.

Watch for discounts that are really just prepayment. ucartz's plan table shows VPS Lite at "$120.00" struck through next to "$10.00/mo", with "Save 70%" alongside. The $120 is twelve monthly payments. The annual price on the same page is $36, and the page also says it renews at the same price, so the 70% is the gap between paying monthly and paying for a year up front, not a countdown you have to beat. Two consequences: nobody is going to take the offer away tomorrow, and the real question is whether you want to hand over twelve months of cash to save $84.

For context on what "cheap" means overall, HostAdvice's late-October round-up puts the average VPS at roughly $10/month when prepaid annually, and up to $20 or more on monthly billing, while its provider table lists entry prices from $2.00 to $5.52. Averages and starting prices measure different things, and a €2 plan is a starting price.

## Charges that appear after checkout

Every item below exists on real price lists, and each one has a specific place where you can check it before paying.

| Extra | Where to confirm it |
| --- | --- |
| Control panel licence (cPanel, Plesk, DirectAdmin) | The add-on step of the order form. Ava lists "Control Panel" as included but doesn't name which one; ask which |
| Backups | The plan's feature list. Ava includes weekly backups on VPS/VDS plans and mentions none on the Self-hosted line |
| Extra IPv4 addresses | The add-on step. One address is standard; additional ones are usually paid |
| Renewal price | Not published on Ava's plan pages. Ask pre-sales, or read the renewal line on your first invoice |
| Managed support scope | Ava advertises 24/7 support; confirm whether it covers application work. ucartz, for comparison, gives about five free minutes and then bills $8 per 15 minutes or $28 per hour |
| Migration of an existing site | Ask before ordering whether moving your files and databases costs anything |
| DDoS protection | Free on Ava's VPS/VDS line. It is not part of ucartz's standard KVM plans, where game-server workloads go to a separate product |
| Bandwidth fair use | "Unlimited" sits under an acceptable-use policy. Read it if you expect to push multiple terabytes |
| Monitoring | Rarely bundled on budget plans; plan to run your own |

## Refunds: 30 days, minus four exceptions

Ava Hosting offers a full refund within 30 days of purchase, and VPS plans are covered by it. The conditions are where it gets specific. Only first-time accounts qualify, so a second purchase isn't refundable. Third-party licences such as cPanel or Softaculous are excluded. Domains and purchased subnets are excluded. And services bought with a promotional code or a discount are non-refundable, with special offers and limited-time deals treated as final regardless of product type.

That last clause is the one to read twice. It means a discount code can cost you the refund window, so weigh a modest saving against 30 days of escape. Refunds go back to the original payment method, and Ava reserves the right to ask for identification through its payment gateway before processing one.

The window isn't standard across the market either. Most providers in HostAdvice's comparison offer 30 days, MVPS offers 3, eVPS.net offers 7, HostArmada 45, and ucartz's 30 days excludes domain fees and third-party licences. If you plan to test a host properly, a 3-day window is not a test.

👉 [Check Ava Hosting's current plan prices and place an order](https://my.ava.hosting/aff.php?aff=15562)

## Does this price range need KVM at all?

KVM is a Type 1 hypervisor running on the hardware, and each virtual machine gets its own kernel. That's the practical difference from container-based OpenVZ, where every VPS shares the host kernel. With your own kernel you can install Docker without arguing with the host, load a kernel module, boot a custom ISO, or reinstall a different distribution from the control panel when a project changes shape. Isolation is stronger too, which matters if you're running something that other tenants shouldn't be able to touch.

The costs are real. KVM plans are more expensive than shared hosting for identical traffic, setup requires some Linux confidence, and a static five-page site with 200 visitors a month is over-provisioned on any VPS.

The dividing line is whether you need root. If you're installing WordPress plugins through a dashboard and never open a terminal, shared hosting at a similar price will do more for you, with support included. If you need cron jobs you control, a database you can tune, Docker, a VPN endpoint, a game server or a build runner, a €5 KVM box beats a €5 shared plan on every count.

## Pick a plan by workload

- **Static site, portfolio, or a box to learn Linux on:** Self-hosted Start at €2, or VPS One at €5 if you want the backups and DDoS cover. 1GB handles a static site; it does not handle a database-backed CMS with plugins.
- **One small WordPress site:** 2GB is the floor, so VPS One at €5. Below that, MySQL and PHP will fight over memory.
- **WooCommerce, a membership site, or several sites on one box:** 4GB and up. VPS Basic at €10, or VPS Lucky at €15 if you'd rather have 6GB and 70GB of disk than 4GB and 50GB.
- **Docker, CI runners, staging environments:** VPS Basic at €10 is the comfortable starting point, since you'll be running more than one container.
- **Windows:** neither Ava line lists a Windows option. ucartz offers Windows Server on its Pro and Elite plans as an evaluation edition, with a full licence sold separately, and InterServer's Windows VPS starts at $10/month because it requires a two-slice minimum. Confirm licensing in writing before you order anywhere.
- **Sending mail:** the Nano closes port 25, and budget providers generally restrict outbound SMTP. Use a relay rather than fighting it.

## Two checks before you pay

Settle the billing cycle first. Ava's prices are monthly starting figures in euro with no published renewal rate, so ask what the plan renews at and whether an annual option exists for the plan you want, rather than extrapolating from the Nano's €11/year. Then check your refund eligibility: first purchase, no promo code, no third-party licence in the basket.

With those two answered, the choice is short. A single site with no shell access belongs on shared hosting. Anything that needs root, cron or Docker starts at VPS One for €5/month, and a store with a database and real traffic starts at VPS Basic for €10.

👉 [Start with VPS One at €5/month on monthly billing at Ava Hosting](https://my.ava.hosting/aff.php?aff=15562)
