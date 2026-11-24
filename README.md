# Cheap Japan VPS: Is $2.99/mo Enough, Which Plan Fits Your Workload, and What Happens at Renewal? (Full Evoxt Plan Table)

Evoxt's Tokyo VPS starts at **$2.99/month** for 1 core, 512 MB RAM, 5 GB storage and 500 GB of transfer, and that $2.99 is also the renewal rate. The floor elsewhere sits lower still: the aggregator vpsls currently lists a 512 MB Tokyo plan at $16.88/year, and a 1 GB Tokyo plan at $2.00/month ($24/year) on a 1 Gbps port. So "cheap" in this market means somewhere between roughly $1.40 and $8 a month, and the spread has almost nothing to do with the word cheap and everything to do with how much RAM and disk you get, how long you prepay, and what the provider quietly leaves out.

This page works through the Evoxt plan list in full, then the three variables that actually move the price, then the two things cheap Japan VPS shoppers get burned by: whether the IP is really Japanese, and what the invoice looks like after month one.

> **Most readers should buy VM-1 at $5.99/month**: 1 core, 2 GB RAM, 20 GB storage, 1,000 GB transfer, Tokyo. It runs a small site, an API backend, a bot, or a proxy with headroom.
> **Want only a Japanese exit IP or a probe?** VM-0.5 at $2.99/month is enough. 512 MB will not run WordPress with a database comfortably.
> **Two or three services on one box, or a small team?** VM-2 at $11.99/month: 2 cores, 4 GB.
> 👉 [See the current Evoxt Japan plans and pick a location](https://bit.ly/EvoXt)

## Every Evoxt plan currently on the price list

Evoxt sells 11 VPS plans on one price sheet. All of them use the same CPU generation, advertised as up to 6.0 GHz per core, and all include a weekly offsite backup at no extra charge. Japan appears in two tiers: Tokyo on the standard network, Osaka on what Evoxt calls its Premium Network. Location availability is listed per plan, so confirm your tier's location on the order page before paying.

| Plan | CPU / RAM | Storage / Monthly transfer | Price | Order |
| --- | --- | --- | --- | --- |
| VM-0.5 | 1 core / 512 MB | 5 GB / 500 GB | $2.99/mo | [Deploy VM-0.5](https://bit.ly/EvoXt) |
| VM-0.75 | 1 core / 1 GB | 10 GB / 750 GB | $4.99/mo | [Deploy VM-0.75](https://bit.ly/EvoXt) |
| VM-1 | 1 core / 2 GB | 20 GB / 1,000 GB | $5.99/mo | [Deploy VM-1](https://bit.ly/EvoXt) |
| VM-1.5 | 2 cores / 2 GB | 20 GB / 1,500 GB | $6.95/mo | [Deploy VM-1.5](https://bit.ly/EvoXt) |
| VM-2 | 2 cores / 4 GB | 30 GB / 2,000 GB | $11.99/mo | [Deploy VM-2](https://bit.ly/EvoXt) |
| VM-3 | 4 cores / 4 GB | 30 GB / 3,000 GB | $14.99/mo | [Deploy VM-3](https://bit.ly/EvoXt) |
| VM-4 | 4 cores / 8 GB | 60 GB / 4,000 GB | $23.99/mo | [Deploy VM-4](https://bit.ly/EvoXt) |
| VM-6 | 8 cores / 8 GB | 60 GB / 5,000 GB | $29.99/mo | [Deploy VM-6](https://bit.ly/EvoXt) |
| VM-8 | 8 cores / 16 GB | 80 GB / 6,000 GB | $47.99/mo | [Deploy VM-8](https://bit.ly/EvoXt) |
| VM-12 | 16 cores / 16 GB | 80 GB / 8,000 GB | $60.95/mo | [Deploy VM-12](https://bit.ly/EvoXt) |
| VM-16 | 16 cores / 32 GB | 100 GB / 10 TB | $95.99/mo | [Deploy VM-16](https://bit.ly/EvoXt) |

Two things about that table are worth pausing on. The jump from VM-1 to VM-1.5 costs $0.96 and buys a second core but no extra RAM or disk, which suits something CPU-bound and light on memory. The jump from VM-1 to VM-2 costs $6 and doubles RAM, adds a core, and adds 500 GB of transfer, which is the better $6 on this sheet for almost any real workload.

Evoxt also sells dedicated servers from $219/month, but those carry no refund window and are a different purchase entirely. Everything above is unmanaged: full root, self-service OS reinstall, VNC and rescue mode in the control panel, and no hosting panel bundled.

## What separates a $1.40 VPS from an $8 VPS

Three variables explain nearly the whole price spread in this market.

**Resources scale unevenly between providers.** LightNode's Tokyo line starts at $7.71/month for 1 vCPU, 2 GB DDR4, 50 GB NVMe and 1 TB of transfer, and all four of its tiers keep storage at exactly 50 GB while CPU, RAM and transfer climb to 8 vCPU, 16 GB and 4 TB at $52.70. Evoxt's VM-1 is $1.72/month cheaper for the same 2 GB, but ships 20 GB of disk instead of 50 GB. Neither is a trick; they made different bets about what a cheap Japan box is for. If you are storing media, LightNode's storage-per-dollar wins. If you are running a service that mostly needs RAM and CPU, Evoxt's does.

**Billing period changes the number a lot.** JUSTG's Tokyo line publishes both: 1 core, 512 MB, 10 GB SSD and 500 GB of traffic costs $19.99/month or $119.99/year. Twelve monthly payments come to $239.88, so the annual option is about 50% off. But that $119.99 buys a 512 MB machine, while the $16.88/year aggregator listing buys 512 MB with 8 GB of NVMe, and Evoxt's $2.99/month works out to $35.88/year for 512 MB with 5 GB. Same rough spec, three prices spanning 7x. Anyone quoting "Japan VPS from $X" without the billing term and the RAM figure is telling you nothing.

**Bundles hide in the fine print.** Evoxt includes a weekly offsite backup on every plan and does not count it against your disk. KernelHost's Tokyo Edge line includes unlimited traffic at up to 1 Gbps and 3.2 Tbps DDoS protection, but no IPv6 and no Windows. HOSTKEY bills hourly or monthly with discounts up to 40%, gives free DDoS protection only in Europe, and meters outbound traffic according to the plan you selected. The sticker price is the least interesting part of the comparison.

## The renewal question, answered

Evoxt's renewal price is the same as its introductory price on all 17 plans it lists, VPS and dedicated alike, according to CrowsNest's tracking last checked on 8 November 2026. That is the single most useful fact on this page if you have been burned by a $2.99 first-year offer before.

You can prepay up to three years, and Evoxt also lets you top up account credit and have the system draw future invoices from it. Longer terms are not published with a discount, so prepaying on Evoxt mostly locks a price rather than lowering it. If you want a real term discount, the JUSTG math above is the shape of it: roughly half off for paying a year up front, on hardware that costs four to six times as much per month.

👉 [Check Evoxt's plan list and current renewal terms](https://bit.ly/EvoXt)

## Is the IP actually Japanese?

This is where cheap Japan VPS listings differ most, and where the marketing language gets slippery.

JUSTG states plainly that every Tokyo cloud VPS plan includes one native Japanese IPv4 address registered and geolocated in Japan, plus free IPv6. KernelHost states the opposite kind of thing about its own Tokyo Edge line: the VPS gets an IPv4 from the Tokyo data center's network, but each geolocation service applies its own rules, so the company cannot promise a particular result, and Edge VPS does not include IPv6 at all.

Evoxt's published pages describe the data center location and the network tier, Tokyo on standard and Osaka on Premium Network. They do not make a geolocation promise for either. If the reason you want a Japan VPS is a Japan-only account, a streaming catalogue, or an API that checks where the request comes from, treat the location label as a starting point and verify the IP yourself. Evoxt's 7-day money-back window on VPS plans, for new customers from the first deployment, is enough time to boot the box, check what the IP resolves to, and walk away if it fails.

One more thing that trips people up: JUSTG lets you move a VPS between Tokyo and Seoul once every 30 days from the client area, and the move gives you a new IP while the old VPS is deleted. Convenient if you planned for it, disruptive if you did not. Nothing in Evoxt's published material describes moving an existing VM between Tokyo and Osaka, so decide the location before you deploy.

## Costs that are not in the plan price

Evoxt publishes its add-on rates, which is rarer than it should be:

- **Extra transfer:** $3/TB on the standard network, $12/TB on Premium, $24/TB on Premium Plus. A Tokyo box that overshoots by 2 TB costs you $6. The same overshoot in Osaka costs $24, four times as much, for a network tier difference most buyers will not read about before ordering.
- **Extra IPv4:** $3/month. **Extra vCore:** $3/month. **Extra 1 GB RAM:** $2/month. Scaling individual resources without changing plan is genuinely useful if you outgrow VM-1 by a little rather than a lot.
- **Paid backup plans** are priced by VM storage size and add daily backups, an on-demand manual backup and five rotation copies on top of the included weekly copy.
- **The firewall is inbound-only.** Useful, but it will not stop anything your server initiates.

On the unlimited-traffic side of the market, KernelHost's Tokyo Edge plans run from €23.99/month with no data cap, no per-terabyte charge and up to 1 Gbps, across 11 plans from 1 vCPU/2 GB to 32 vCPU/128 GB, all with 20 GB SSD expandable to 300 GB. KernelHost also says its Edge series delivers slightly less performance per euro than its classic Unlimited Bandwidth line, which has four Tokyo plans at 500 Mbit/s to 3 Gbit/s. Cheap and unlimited are not the same purchase.

## Picking by what you are actually running

**A small site, API, or bot.** VM-1 at $5.99 for 2 GB. Add the $2/month RAM upgrade if your stack is heavy; it is cheaper than jumping to VM-2 at $11.99 unless you also need the second core.

**Only a Japanese exit IP.** VM-0.5 at $2.99. A proxy, a monitoring probe, a single scheduled job, or a region-locked login does not need more. Paying $20 a month for 512 MB elsewhere buys you nothing you can use here.

**A game server for a handful of players.** VM-2 or VM-3. Evoxt's single-core clock claim is the relevant spec, and 4 GB is the practical floor once the game server plus its database are both resident.

**Mainland China latency.** Neither of Evoxt's Japan tiers is marketed with a China-route claim on the pages I checked. The aggregator vpsls groups HostDare, GreenCloud (IIJ and SoftBank lines), VMISS (IIJ and BGP) and 666clouds (SoftBank) as its China-access picks. If that is your requirement, ask for a test IP before you buy anything, from anyone.

**Unmetered bandwidth.** KernelHost's Tokyo line is the honest unlimited option, with the trade-offs stated on its own page: no Windows, no IPv6, the data center location cannot be changed after ordering, and the geo result is not guaranteed.

## Four checks before you pay

1. **Renewal price.** Evoxt matches intro and renewal on every plan. Ask every other provider the same question in writing.
2. **Refund window and who qualifies.** Evoxt: 7 days, new customers only, from the first deployment. Its six dedicated server plans have none.
3. **A test IP or Looking Glass.** JUSTG publishes a Looking Glass and hands out test IPs by ticket. vpsls's own buying checklist lists test IP results, Looking Glass data, latency, packet loss, routing, bandwidth limits, refund policy and renewal pricing as the things to compare, and that list is better than most reviews.
4. **Whether the location can change later.** Some providers charge nothing but delete your old machine and hand you a new IP. Confirm before you build anything you would have to rebuild.

If your budget is the deciding factor and you want a Tokyo box with a published price sheet, per-resource upgrades, an included weekly offsite backup and a renewal rate that does not move, start with VM-1 at $5.99: 2 GB is the point where a cheap Japan VPS stops being a toy. If you only need the IP, take VM-0.5 at $2.99 and put the difference toward something you will actually notice. If you need unlimited transfer, buy the provider that says unlimited in writing on the plan page, not the one whose name sounds cheap.

👉 [Start with Evoxt's VM-1 in Tokyo at $5.99/month](https://bit.ly/EvoXt)
