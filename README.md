# RackNerd Shared Hosting: What Do the 30 GB, 100 GB and 200 GB Plans Cost, Which One Do You Need, and What Does $5.59/Month Actually Buy?

RackNerd's shared hosting comes in three tiers: **30 GB at $5.59/month, 100 GB at $9.59/month and 200 GB at $15.59/month**. All three run cPanel on LiteSpeed, include unlimited domains and databases, and carry no contract. Most people should start on the 30 GB plan and move up later if they outgrow it, since upgrading happens inside the client area without a migration.

Below you'll find the full line-up, what each feature means in day-to-day use, how the billing cycles and the five datacenters work, and the parts of the deal that don't appear in the sales copy.

> **Quick pick:** the 30 GB plan at **$5.59/month** handles a blog, a brochure site or a few small WordPress installs. Take 100 GB if you host client sites or a large media library; 200 GB is for content-heavy sites with years of images and video.
> 👉 [See the three RackNerd shared hosting plans](https://bit.ly/RacKnerd)

## All three plans side by side

| Plan | Storage & bandwidth | Domains / databases | Price | Billing | Order |
| --- | --- | --- | --- | --- | --- |
| Shared 30 GB | 30 GB SSD, 2 TB/month | Unlimited / Unlimited | **$5.59/mo** | Monthly, or prepay 1–3 years | [Start with 30 GB](https://bit.ly/RacKnerd) |
| Shared 100 GB | 100 GB SSD, 3 TB/month | Unlimited / Unlimited | **$9.59/mo** | Monthly, or prepay 1–3 years | [Choose the 100 GB plan](https://bit.ly/RacKnerd) |
| Shared 200 GB | 200 GB SSD, 5 TB/month | Unlimited / Unlimited | **$15.59/mo** | Monthly, or prepay 1–3 years | [Go with 200 GB](https://bit.ly/RacKnerd) |

Every plan also lists free SSL, CloudLinux, Softaculous, LiteSpeed, free daily backups and cPanel. None of the three has a domain cap, which matters if you're consolidating several small sites under one account instead of paying per site.

One pricing caveat. These figures come from RackNerd's own plan breakdown published in July 2025, and the product pages themselves list the three tiers without displaying prices until you reach the cart. Independent price trackers were still showing $5.59 / $9.59 / $15.59 in late 2026, so the numbers have held, but the cart is the final word on what you'll be charged.

## What the $5.59 actually buys

The software stack is identical across all three tiers. Only disk space and monthly transfer change, so the cheapest plan isn't a cut-down version of the expensive one.

**cPanel.** The standard panel most shared-hosting users already know. Email accounts, DNS zones, file manager, cron jobs, SSL management and the backup restore screen all live here. If you're moving from another cPanel host, nothing about your workflow changes.

**LiteSpeed Web Server with LSCache.** RackNerd runs LiteSpeed rather than Apache on shared servers. For WordPress this means the LiteSpeed Cache plugin can work at the server level, serving cached pages before PHP is invoked at all, which is the difference between a page that loads in a second and one that loads in a fraction of it under traffic.

**CloudLinux and KernelCare.** CloudLinux caps what a single account can consume, so one runaway plugin on a neighbour's site doesn't drag your response times down. KernelCare applies kernel security patches without rebooting the server, which removes the usual late-night maintenance window.

**Daily backups you can restore yourself.** Backups are handled by JetBackup inside cPanel, stored fully off-site and replicated to multiple disaster-recovery datacenters. RackNerd's FAQ confirms account holders can view and restore their own files, databases and mail. That's more than many budget hosts offer, where "backups included" means you open a ticket and hope.

**Free SSL.** Let's Encrypt certificates issued and renewed automatically. No separate purchase, no annual re-issue chore.

**Softaculous.** One-click installs for WordPress, Joomla, Drupal, Magento and the rest. Useful if you spin up test sites often.

**Free migration, cPanel to cPanel.** Submit a ticket after ordering with your old host's login details and RackNerd's team moves the sites. The limit is real: the migration is cPanel-to-cPanel, so if your current provider runs a custom panel, you're exporting and importing manually.

**DDoS protection.** Network-level filtering, stated on the product page. Shared hosting rarely gets targeted, but it's there.

**Support.** 24/7 ticket and email coverage; RackNerd's ordering guide quotes a 10-minute average response time. On the third-party side, Trustpilot shows **4.1 out of 5 across 371 reviews**, though most of those reviews are about VPS and Black Friday deals rather than shared hosting specifically, so read them as a signal about support responsiveness and pricing rather than about this product.

## Billing, contracts, and whether annual prepay saves anything

Shared hosting is **month-to-month with no contract**. At checkout you can switch to annual, biennial or triennial prepayment, and payment goes through PayPal, credit card, cryptocurrency or wire transfer.

Here's the part that's easy to get wrong. Annual prepayment doesn't appear to come with a discount. Price trackers list the 200 GB plan at **$187.08/year**, which is exactly $15.59 × 12, and the 100 GB plan at **$115.08/year**, exactly $9.59 × 12. The 30 GB plan lists at $67.50/year against $67.08 at the monthly rate, a few cents above, not below. Prepaying is a convenience and a hedge against future price changes, not a saving you can point to today.

Two things RackNerd doesn't publish on the shared hosting pages: a renewal rate and a refund policy. The plan pages say month-to-month and leave it there. A third-party summary of RackNerd's terms, revised in July 2026, states that refunds aren't issued by default once a service is paid for. If a refund window matters to you, ask sales in writing before you prepay anything longer than a year. Three years of prepaid hosting with no documented exit is a bad first purchase.

👉 [Check the current plans and billing options](https://bit.ly/RacKnerd)

Upgrades are self-service. If you start on 30 GB and hit the ceiling, you move to 100 GB or 200 GB from inside the client area, or open a sales ticket and let them do it. No new account, no DNS changes.

## Choosing a datacenter

RackNerd deploys shared hosting in five locations: **Los Angeles, New York City, Germany (Frankfurt), France (Strasbourg) and Singapore**. You pick one during checkout, and it's worth picking deliberately because you can't casually move afterwards.

For a mostly US audience, Los Angeles covers the West Coast and Asia-Pacific traffic reasonably well, while New York City is the better pick for the East Coast and Europe. European visitors are best served from Germany or France. Singapore is the only sensible option for Southeast Asia, Australia and India.

The other half of the latency equation is your own admin experience. If you'll be logging into cPanel daily from one country, put the server near you even if your visitors are spread out.

## Who this fits, and who should look elsewhere

**It fits** personal sites and blogs that have outgrown a free tier, small business brochure sites, WordPress installs that want server-level caching without a VPS bill, and anyone consolidating four or five small domains into a single cPanel account. People already on a cPanel host get the smoothest ride, since the free migration covers them directly.

**It doesn't fit** anyone who needs root access, custom daemons, guaranteed CPU cores or a fixed RAM allocation. Shared hosting is shared; RackNerd doesn't publish per-plan CPU, memory or process limits, so if your project needs predictable resources, a VPS is the right product line. The same goes for anyone who wants a contractual uptime SLA with service credits, which isn't published for these plans.

One more warning worth having. You may run into RackNerd shared hosting offers around $10 per year on coupon and price-tracking sites, advertised with NVMe storage and a two- or ten-domain cap. Those listings don't match the 30/100/200 GB SSD line-up with unlimited domains sold on RackNerd's own pages, and I couldn't confirm them from RackNerd directly. Don't build a budget around them.

## FAQ

**How long until the account is live?**
RackNerd's product page says plans are activated instantly after ordering; the ordering guide says typically within 5 to 15 minutes. Expect minutes, not hours, and contact support if an hour passes.

**Can I upgrade later without losing anything?**
Yes. Upgrades happen from the client area, or through a sales ticket if you want help. Files, databases and mail stay in place.

**Is SSL really free on the cheapest plan?**
Yes, Let's Encrypt certificates on all three tiers. Nothing to buy separately.

**Can I restore my own backups?**
Yes. JetBackup runs inside cPanel, backups are stored off-site and replicated, and you can pull back a file, database or mailbox without a ticket.

**Is migration free?**
Free for cPanel-to-cPanel moves. Submit a ticket after your order with the source host's login details. Non-cPanel panels aren't covered.

**Do I have to sign a contract?**
No. Monthly billing with no commitment, and optional annual, biennial or triennial prepayment if you'd rather not think about it every month.

**How many websites can I host?**
Unlimited, on every plan. Storage and bandwidth are the only things that scale with price.

## Before you order

Match the plan to what you're actually storing. A text-heavy blog with 1,500 posts uses a couple of gigabytes; a photography portfolio with full-resolution galleries can burn through 30 GB in a year. That's the whole decision between the tiers.

Then confirm two things at checkout: the datacenter closest to your visitors, and the billing cycle you actually want. Given that prepaying doesn't come with a verified discount, starting monthly and moving to annual once the service has proven itself is the lower-risk path. If the site is already earning money and you know you're staying, prepay and forget it.

👉 [Start with the 30 GB plan, or compare all three tiers](https://bit.ly/RacKnerd)
