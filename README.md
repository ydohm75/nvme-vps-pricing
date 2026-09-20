# NVMe SSD VPS cheap: real prices compared, where NVMe actually comes standard, and when CN2 GIA bandwidth is worth the premium

Type "NVMe SSD VPS cheap" into a search engine and you'll get two kinds of results. The first kind advertises $3–5/month servers with NVMe slapped in the headline. The second kind is forum threads where someone with a $20/year budget asks for 100GB of NVMe and gets politely told it doesn't exist. Both point at the same underlying question: what does cheap NVMe actually cost, and where is the marketing line between "SSD" and "NVMe SSD"?

This article works through that question with real, currently listed prices, using BandwagonHost (often called 搬瓦工 or BWH) as the concrete example — because it's one of the few budget hosts that is completely unambiguous about which plans run NVMe and which don't. By the end you'll know which storage type you're actually buying at each price point, what the full current plan list looks like, and where paying more gets you something real instead of just a bigger number.

## What NVMe actually changes

NVMe is the protocol that lets an SSD talk to the CPU at PCIe speeds instead of going through the older SATA controller. In a VPS context, this shows up less in sequential read benchmarks and more in I/O-heavy tasks: database queries, Docker image pulls, log-heavy applications, WordPress admin pages on a busy site. A well-loaded SATA SSD array can still feel fine for a small blog. The same site on NVMe tends to stop thinking about disk I/O as a bottleneck at all.

The catch is that "SSD" and "NVMe SSD" are not interchangeable terms, and plenty of cheap providers use them loosely. So the first thing worth doing with any budget VPS — including BandwagonHost's — is checking which hardware generation each plan actually runs on. Hosts usually don't hide this, but they don't always put it in the headline either.

## The full plan list and current prices

BandwagonHost currently organizes everything into a few product lines: **Basic** (budget plans on regular network routes), **E-Commerce** (plans on the CN2 GIA and other premium routes, with newer hardware), **E-Commerce SLA** (the same idea plus a contractual 99.99% uptime guarantee), and **Ultra** (fixed-location premium plans for Hong Kong, Tokyo, and Osaka). Here is the full current lineup, with prices as listed on the official order pages and consistently confirmed across third-party plan trackers.

Basic line — KVM, 1 Gbps port, multiple US and EU locations, switchable after purchase:

| Plan | CPU | RAM | Storage | Traffic/mo | Price | Billing cycle | Buy |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Basic 20G | 2x | 1 GB | 20 GB | 1 TB | $49.99 | annual | [ Get Basic 20G](https://bandwagonhost.com/aff.php?aff=79616#the-full-plan-list-and-current-prices) |
| Basic 40G | 3x | 2 GB | 40 GB | 2 TB | $52.99 / $99.99 | semi-annual / annual | [ Get Basic 40G](https://bandwagonhost.com/aff.php?aff=79616#the-full-plan-list-and-current-prices) |
| Basic 80G | 4x | 4 GB | 80 GB | 3 TB | $19.99 / $199.99 | monthly / annual | [ Get Basic 80G](https://bandwagonhost.com/aff.php?aff=79616#the-full-plan-list-and-current-prices) |
| Basic 160G | 5x | 8 GB | 160 GB | 4 TB | $39.99 / $399.99 | monthly / annual | [ Get Basic 160G](https://bandwagonhost.com/aff.php?aff=79616#the-full-plan-list-and-current-prices) |
| Basic 320G | 6x | 16 GB | 320 GB | 5 TB | $79.99 / $799.99 | monthly / annual | [ Get Basic 320G](https://bandwagonhost.com/aff.php?aff=79616#the-full-plan-list-and-current-prices) |
| Basic 480G | 7x | 24 GB | 480 GB | 6 TB | $119.99 / $1199.99 | monthly / annual | [ Get Basic 480G](https://bandwagonhost.com/aff.php?aff=79616#the-full-plan-list-and-current-prices) |

E-Commerce line — premium CN2 GIA routing, 2.5 Gbps port and up, a pool of roughly 14 switchable locations including Los Angeles DC6/DC9, Tokyo Softbank (JPOS_1), and Dubai:

| Plan | CPU | RAM | Storage | Traffic/mo | Port | Price | Buy |
| --- | --- | --- | --- | --- | --- | --- | --- |
| E-Commerce 20G (CN2 GIA-E) | 2x | 1 GB | 20 GB | 1 TB | 2.5 Gbps | $49.99/quarter or $169.99/year | [ Order CN2 GIA-E 20G](https://bandwagonhost.com/aff.php?aff=79616#the-full-plan-list-and-current-prices) |
| E-Commerce 40G | 3x | 2 GB | 40 GB | 2 TB | 2.5 Gbps | $89.99/quarter or $299.99/year | [ Order CN2 GIA-E 40G](https://bandwagonhost.com/aff.php?aff=79616#the-full-plan-list-and-current-prices) |
| E-Commerce 80G | 4x | 4 GB | 80 GB | 3 TB | 2.5 Gbps | $56.99/month or $549.99/year | [ Order CN2 GIA-E 80G](https://bandwagonhost.com/aff.php?aff=79616#the-full-plan-list-and-current-prices) |
| E-Commerce 160G | 6x | 8 GB | 160 GB | 5 TB | 5 Gbps | $86.99/month or $879.99/year | [ Order CN2 GIA-E 160G](https://bandwagonhost.com/aff.php?aff=79616#the-full-plan-list-and-current-prices) |
| E-Commerce 320G | 8x | 16 GB | 320 GB | 8 TB | 5 Gbps | $159.99/month or $1599.99/year | [ Order CN2 GIA-E 320G](https://bandwagonhost.com/aff.php?aff=79616#the-full-plan-list-and-current-prices) |
| E-Commerce 640G | 10x | 32 GB | 640 GB | 10 TB | 10 Gbps | $289.99/month or $2759.99/year | [ Order CN2 GIA-E 640G](https://bandwagonhost.com/aff.php?aff=79616#the-full-plan-list-and-current-prices) |
| E-Commerce 1280G | 12x | 64 GB | 1280 GB | 12 TB | 10 Gbps | $549.99/month or $5399.99/year | [ Order CN2 GIA-E 1280G](https://bandwagonhost.com/aff.php?aff=79616#the-full-plan-list-and-current-prices) |
| E-Commerce 1280G HICPU | 24x | 64 GB | 1280 GB | 12 TB | 10 Gbps | $749.99/month or $7599.99/year | [ Order CN2 GIA-E 1280G HICPU](https://bandwagonhost.com/aff.php?aff=79616#the-full-plan-list-and-current-prices) |

Ultra line — fixed-location premium plans on CN2 GIA routing; hardware on AMD EPYC with NVMe RAID-10:

| Plan (location) | CPU | RAM | Storage | Traffic/mo | Port | Price | Buy |
| --- | --- | --- | --- | --- | --- | --- | --- |
| HK CN2 GIA 40G | 2x | 2 GB | 40 GB | 500 GB | 1 Gbps | $89.99/month or $899.99/year | [ Order Hong Kong 40G](https://bandwagonhost.com/aff.php?aff=79616#the-full-plan-list-and-current-prices) |
| HK CN2 GIA 80G | 4x | 4 GB | 80 GB | 1 TB | 1 Gbps | $155.99/month | [ Order Hong Kong 80G](https://bandwagonhost.com/aff.php?aff=79616#the-full-plan-list-and-current-prices) |
| HK CN2 GIA 160G | 6x | 8 GB | 160 GB | 2 TB | 1 Gbps | $299.99/month | [ Order Hong Kong 160G](https://bandwagonhost.com/aff.php?aff=79616#the-full-plan-list-and-current-prices) |
| HK CN2 GIA 320G | 8x | 16 GB | 320 GB | 4 TB | 1 Gbps | $589.99/month | [ Order Hong Kong 320G](https://bandwagonhost.com/aff.php?aff=79616#the-full-plan-list-and-current-prices) |
| HK CN2 GIA 640G | 10x | 32 GB | 640 GB | 6 TB | 1 Gbps | $989.99/month | [ Order Hong Kong 640G](https://bandwagonhost.com/aff.php?aff=79616#the-full-plan-list-and-current-prices) |
| HK CN2 GIA 1280G | 12x | 64 GB | 1280 GB | 8 TB | 1 Gbps | $1889.99/month | [ Order Hong Kong 1280G](https://bandwagonhost.com/aff.php?aff=79616#the-full-plan-list-and-current-prices) |
| Tokyo CN2 GIA 40G | 2x | 2 GB | 40 GB | 500 GB | 1.2 Gbps | $89.99/month | [ Order Tokyo 40G](https://bandwagonhost.com/aff.php?aff=79616#the-full-plan-list-and-current-prices) |
| Tokyo CN2 GIA (80G–1280G) | 4x–12x | 4–64 GB | 80–1280 GB | 1–8 TB | 1.2 Gbps | $155.99–$1889.99/month | [ Order Tokyo Ultra plans](https://bandwagonhost.com/aff.php?aff=79616#the-full-plan-list-and-current-prices) |
| Osaka CN2 GIA 40G | 2x | 2 GB | 40 GB | 500 GB | 1.5 Gbps | from $49.99/month | [ Order Osaka Ultra](https://bandwagonhost.com/aff.php?aff=79616#the-full-plan-list-and-current-prices) |

The E-Commerce line also exists for Tokyo and Fremont as standalone NVMe locations (Tokyo's listing, for example, runs AMD EPYC with NVMe RAID-10 at an Equinix IX-connected site, from $49.99 per 3 months), and there's a separate Singapore CN2 GIA line at 1.5 Gbps ports with prices starting around $49.99/month. Those fill specific regional needs rather than the "cheap" end of this search, so the rest of the article focuses on the plans above.

## Where the NVMe plans actually are

Here's the part most "cheap NVMe VPS" searchers need to hear: **on BandwagonHost, the cheapest plan is not an NVMe plan.** The Basic line — including the well-known $49.99/year 20G plan — runs on older Intel Xeon E5 processors with SSD storage in RAID-10, which the order pages still describe as "RAID-10 SAS disks and E5 CPUs." It's solid, proven hardware, and at roughly $4.17 a month equivalent it's one of the cheapest credible KVM VPS deals anywhere. But the storage on those boxes is not what anyone means by NVMe.

The NVMe hardware shows up in three places, all confirmed by BandwagonHost's own announcements and order pages:

- **E-Commerce CN2 GIA-E (Los Angeles DC9 and the migration pool):** the entry E-Commerce 20G plan at $49.99/quarter or $169.99/year runs on the newer AMD EPYC generation, and third-party hardware trackers identify DC9 as the most mature NVMe location in the lineup. If you want NVMe storage plus China-optimized routing, this is the standard recommendation, and for good reason — see the latency numbers below.
- **Ultra Hong Kong (HK3 and HK8):** BandwagonHost's own news page announced the move to "AMD EPYC servers with NVMe RAID-10 storage in Hong Kong," so every HK Ultra plan is genuine NVMe — with pricing to match, starting at $89.99/month.
- **E-Commerce SLA Los Angeles:** the SLA line pairs dedicated AMD EPYC cores with local NVMe RAID-10 storage, from $239.99/year for the 20G tier (1 GB RAM, 2x dedicated cores, 1 TB traffic at 2.5 Gbps) up to a 1280G flagship with 12 dedicated AMD cores, 64 GB RAM, and 12 TB of monthly traffic at $699.99/month. The same family includes a 15 TB "HIBW" variant at the top end.

One practical note on the Ultra plans: the Hong Kong and Tokyo NVMe boxes go out of stock periodically, sometimes for weeks. If a specific location matters to you, stock-watching is part of the buying process, not a sign something is wrong.

If you're deciding between these lines right now, it helps to see them side by side — you can [👉 compare the full NVMe and CN2 GIA lineup on the official order pages](https://bandwagonhost.com/aff.php?aff=79616#where-the-nvme-plans-actually-are) and check live stock before committing to a location.

## CPU limits: the fine print that changes the value

BandwagonHost's service terms publish CPU share limits per plan, and they matter more than the core count in the plan name. On the Basic line, the 20G plan gets 50% of one core, the 40G plan 75%, the 80G plan a full core, and the 160G plan a full core plus half of a second one. These are measured as rolling hourly averages, and the limits are tighter on limited-edition and promo plans than on the standard line.

Two things follow from this. First, the "2x CPU" on a $49.99/year plan is not the same resource as "2x CPU" on a dedicated-core SLA plan — the latter gives you all allocated cores around the clock with no shared cap. Second, for anything continuously CPU-hungry, the effective price per usable core-hour is much better on the 80G Basic and up, or on the SLA line, than the headline prices of the smallest plans suggest. For a lightweight proxy, a small website, or a test box, the entry plans are fine. For a busy database, they're not the right tool.

## The network is the real product

Storage aside, the thing that actually differentiates BandwagonHost from other cheap VPS providers is routing — specifically CN2 GIA, which is China Telecom's premium transit product. Regular plans route through congested transit networks; CN2 GIA routes carry traffic on dedicated, lightly loaded paths from the datacenter all the way into China Telecom's domestic backbone. It's expensive infrastructure — the official CN2 GIA page openly discusses transit pricing that can reach the ballpark of $120 per megabit — which is exactly why the CN2 GIA plans cost several times what the Basic line does.

What that buys you, according to third-party testing published in 2026: CN2 GIA-E plans measured at roughly 130–150 ms latency from China Telecom lines with packet loss under 0.5% during evening peak hours, while the Hong Kong CN2 GIA plans measure around 30–60 ms. One long-term user writeup puts the DC6 CN2 GIA-E experience at 150–180 ms. Numbers like these are why Chinese users, cross-border e-commerce operators, and anyone serving visitors from mainland China keep this host on their shortlist despite the modest specs — and why competitors with better raw hardware but ordinary routing aren't substitutes for this use case.

A useful comparison for calibration: the same 80 GB SSD / 4 GB RAM configuration runs $19.99/month on the Basic tier but $56.99/month on the E-Commerce CN2 GIA tier. That $37 difference isn't buying storage — it's buying the route. If your users aren't in China, the Basic tier is the rational buy. If they are, the E-Commerce tier is often cheaper than any alternative that delivers comparable China latency.

## SLA plans: paying for uptime, not speed

The E-Commerce SLA line deserves its own paragraph because the guarantee is contractual, not marketing. The SLA promises 99.99% monthly availability — which works out to under five minutes of unplanned downtime in a month — and if the service falls short, the compensation scales up to a full month of prepaid service time for sustained outages. The line also includes a free IP change every two weeks, which matters for anyone whose IP gets burned by an unrelated blocklist.

The price gap is real: the SLA 20G sits at $65.89/quarter or $239.99/year against $49.99/quarter or $169.99/year for the equivalent CN2 GIA-E plan. That premium buys you dedicated CPU cores, the NVMe RAID-10 storage, the uptime contract, and the IP rotation. For a hobby box, skip it. For anything that earns money — a storefront, a client site, an API endpoint — $70 a year is a reasonable insurance premium.

## Buying notes: stock, cycles, and coupons

A few practical things worth knowing before you order:

- **Billing cycles are per-plan.** The cheapest 20G Basic price exists only at annual billing; some plans only offer quarterly; the HK and Tokyo Ultra plans are effectively monthly-commitment products at high monthly rates. Always check which cycles your specific plan allows — the entry-tier advice from third-party reviews is consistent: annual billing on the entry plans, because quarterly on the same box costs meaningfully more per month.
- **Payment:** BandwagonHost accepts Alipay alongside cards, and everything is handled through their in-house KiwiVM control panel, which covers start/stop, OS reloads, an emergency console, rDNS management, snapshots, datacenter migration, and an API. There are 20+ OS templates (AlmaLinux, Rocky, Debian, Ubuntu, Fedora, and others), plus bootable ISOs. It's a self-managed service — support is infrastructure support, not "please install WordPress for me."
- **Coupons:** as of September 2026, multiple Chinese-language coupon trackers report that no conventional public discount code is reliably working; older codes like BWHCGLUKKB (a recurring ~6.77% code that circulated for years) are widely listed but also widely flagged as expired. The consistent advice across those same trackers: the real savings come from catching limited-edition restocks, which periodically undercut the standard plans by 30–60% at equivalent specs. If your timing is flexible, watching stock beats hunting coupons.

When you've picked a tier, the cleanest path is to [👉 check current plan stock and pricing directly on the BandwagonHost order pages](https://bandwagonhost.com/aff.php?aff=79616#buying-notes-stock-cycles-and-coupons), since availability changes weekly on the popular locations.

## Which plan for which job

Collapsing all of this into decisions:

- **Absolute cheapest credible VPS:** Basic 20G at $49.99/year. Old CPU, SATA-class SSD, regular routes — and still one of the best price-to-reliability ratios in the budget VPS market for learning Linux, running a small site, or a personal proxy.
- **Cheap + NVMe + China-optimized routing:** E-Commerce 20G CN2 GIA-E at $49.99/quarter or $169.99/year. This is the plan most people actually want when they search for a cheap NVMe VPS with China in mind, and it's the one third-party reviewers keep calling the best value in the catalog.
- **NVMe + guaranteed uptime + dedicated CPU:** E-Commerce SLA, from $239.99/year. For anything commercial.
- **Lowest possible latency to China, budget secondary:** Ultra Hong Kong on AMD EPYC/NVMe, from $89.99/month. Expensive, occasionally out of stock, and by most accounts worth it if latency is the whole point.

The broader market context: 2026 roundups of cheap NVMe VPS providers consistently name Hostinger, Hetzner, Contabo, Vultr, and RackNerd as the value picks for generic workloads — and if your visitors are in Europe or the Americas and you just want maximum NVMe gigabyte per dollar, those are genuinely strong options worth comparing. BandwagonHost's position is different: it's the budget host you pick when the *route* is the product, with NVMe hardware now standard across everything above the entry tier. Match the plan to where your users actually are, and the pricing above tells you exactly what that decision costs.
