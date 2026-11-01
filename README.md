# sharepoint backup: what Microsoft 365 won't restore for you, and how Sharktech's $4/month Acronis plan covers SharePoint, Teams and OneDrive

Most people searching for a SharePoint backup option have already had a small scare: a deleted document library, an overwritten folder, or a ransomware warning. And the uncomfortable answer is that Microsoft 365's built-in safety nets are thin. Deleted items in SharePoint and OneDrive are only retained for a limited time, and version history doesn't help when data is encrypted or systematically wiped. That's why the actual fix for "sharepoint backup" is a third-party, cloud-to-cloud backup service — and Sharktech's Acronis-based plan is one of the cheapest entry points we've verified, starting at $4/month with 200GB of storage included.

> **Quick pick:** For a small business backing up one or a few SharePoint sites plus Teams and OneDrive files, Sharktech's Acronis Cloud Backup at **$4/month (200GB included, $0.02/GB for extra storage)** is the plan to start with. Storage is billed per GB with no long-term contracts, and you can scale up to 100TB. 👉 [Configure the monthly plan with 200GB included](https://portal.sharktech.net/cart.php?a=add&pid=648&configoption%5B1862%5D=200&configoption%5B1863%5D=0&billingcycle=monthly&aff=1626)

## Why the Microsoft 365 recycle bin isn't a SharePoint backup

SharePoint Online gives you a two-stage recycle bin, version history, and a retention framework. These are undo features, not backups. The distinction matters in three specific situations:

1. **Retention windows expire.** Once the retention period passes, deleted content is gone from Microsoft's side. Microsoft runs the service and retains deleted items for a limited time only — long-term protection is explicitly left to you.
2. **Ransomware doesn't respect version history.** Modern attacks encrypt or delete files across entire sites. Rolling back through versions file-by-file after a tenant-wide attack isn't realistic; you need point-in-time snapshots you can restore wholesale.
3. **Sync and automation amplify mistakes.** A bad script or a misconfigured sync client can propagate deletions across libraries faster than anyone notices. Recycle bins help; they don't give you yesterday's clean state of an entire site.

This is the gap every serious SharePoint backup product fills, and it's the same gap Sharktech's offering addresses through Acronis Cyber Protect, which backs up SharePoint Online, OneDrive for Business, Exchange Online and Teams into off-site Acronis cloud storage.

## What a SharePoint backup service actually needs to do

Before comparing vendors, it helps to know what the top guides in this space all converge on, because the requirements are fairly consistent:

- **Granular restore.** The most common recovery job is small: one deleted file, one corrupted list. Your backup needs searchable snapshots with versioning so an admin can pull a single document without restoring the whole site.
- **Full-site restore.** After ransomware or mass accidental deletion, you need to restore an entire site with its structure and permissions intact, to a chosen point in time.
- **Off-site and immutable copies.** Backup industry best practice (as documented by vendors like Veeam and NinjaOne) calls for at least one copy kept off-site, ideally immutable or air-gapped, so a compromise of your Microsoft 365 tenant can't reach the backups too.
- **M365 coverage beyond SharePoint.** Teams files actually live inside SharePoint document libraries, so a SharePoint backup that also handles Teams, OneDrive and Exchange mailboxes saves you from buying separate tools.

Sharktech's Acronis platform checks these boxes at the platform level: Acronis Cyber Protect's cloud deployment backs up SharePoint Online, Teams, OneDrive for Business and Exchange Online into Acronis Cloud Storage, with file-level and full-machine restore options, customizable schedules and retention periods, encryption, and access controls. Its Active Protection feature also monitors processes and blocks ransomware-style encryption behavior — which is preventive, on top of the backup itself.

## Sharktech's Acronis Cloud Backup: plans and pricing

Sharktech sells its Acronis backup as a single configurable product (a per-GB storage model) rather than tiered packages, so the real "plans" are the billing cycles. Here is the complete price list as published on Sharktech's site:

| Billing cycle | Base price | Included storage | Extra storage | Order |
| --- | --- | --- | --- | --- |
| Monthly | $4.00/mo | 200 GB | $0.02/GB | [Start monthly backup](https://portal.sharktech.net/cart.php?a=add&pid=648&configoption%5B1862%5D=200&configoption%5B1863%5D=0&billingcycle=monthly&aff=1626) |
| Quarterly | $8.00/quarter | 200 GB | $0.04/GB | [Start quarterly backup](https://portal.sharktech.net/cart.php?a=add&pid=648&configoption%5B1862%5D=200&configoption%5B1863%5D=0&billingcycle=quarterly&aff=1626) |
| Semi-annual | $12.00/6 months | 200 GB | $0.06/GB | [Start semi-annual backup](https://portal.sharktech.net/cart.php?a=add&pid=648&configoption%5B1862%5D=200&configoption%5B1863%5D=0&billingcycle=semiannually&aff=1626) |
| Annual | $24.00/year | 200 GB | $0.12/GB | [Start annual backup](https://portal.sharktech.net/cart.php?a=add&pid=648&configoption%5B1862%5D=200&configoption%5B1863%5D=0&billingcycle=annually&aff=1626) |

Details that matter when you configure the plan:

- **Storage range:** Cloud Backup & Protection is configurable from 0 to 100,000 GB (100TB) in the order form, defaulting to 200 GB. The final total is confirmed at checkout in the customer portal.
- **Optional File Sync & Share add-on:** priced separately per GB — $0.03/mo (monthly cycle) up to $0.24/yr (annual cycle). If you don't need file syncing, leave it at zero; you're not charged for it.
- **Data center choice:** you pick where your backups live — Los Angeles, Las Vegas, Denver, Chicago or Amsterdam. Most backup write-ups never mention location choice; for backup data, picking a region away from your production infrastructure is a small but real resilience win.
- **No long-term contracts**, per Sharktech's own service page, and the company advertises 24/7 human support with in-house engineering teams at its data centers.

Sharktech claims its Acronis service costs "half the price compared to competitors" — that's the company's own marketing claim, not an independently verified figure, but the published per-GB rates are unusually low for managed Acronis hosting either way.

### The billing-cycle math most reviews skip

Here's the detail worth doing arithmetic on, because the pricing table hides a trade-off. The listed overage rates mean:

- On the **monthly** plan, each extra GB costs $0.02 *per month* — so 100GB of overage for a full year costs $24 on top of your $48 base ($72 total).
- On the **annual** plan, each extra GB costs $0.12 *per year* — so the same 100GB of steady overage costs $12 on top of your $24 base ($36 total).

Run it at a realistic scale: if your SharePoint archive settles at 500 GB (300GB over the included amount) and stays there, the monthly plan costs roughly $4 × 12 + 300 × $0.02 × 12 = **$120/year**, while the annual plan costs $24 + 300 × $0.12 = **$60/year**. The annual cycle wins clearly for storage that grows steadily and stays.

The monthly plan earns its keep when your usage is unpredictable. You configure storage month to month and only pay overage in the months you actually exceed 200GB — useful if you're still figuring out how much your SharePoint sites, Teams files and OneDrive data add up to. A sensible approach: start monthly for the first couple of months to learn your real footprint, then switch to annual once the number is stable. 👉 [Set up the monthly plan and check your actual storage footprint](https://portal.sharktech.net/cart.php?a=add&pid=648&configoption%5B1862%5D=200&configoption%5B1863%5D=0&billingcycle=monthly&aff=1626)

### What Acronis covers for SharePoint specifically

The Acronis Cyber Protect platform Sharktech resells supports backing up Microsoft 365 workloads — Exchange Online, OneDrive for Business, SharePoint Online and Teams — with data stored in Acronis Cloud Storage in the cloud deployment. A few platform-level facts from Acronis's own licensing documentation help you size this:

- One protected user's data covers their mailbox, OneDrive, and unlimited SharePoint Online sites and Teams they use.
- Backing up SharePoint Online and Teams requires relatively little licensing overhead on the Acronis platform itself — Acronis's FAQ states that just one seat is required to back up SharePoint Online and Teams.
- Acronis's licensing guide notes Microsoft 365 and Google Workspace backups include unlimited Acronis cloud storage on Acronis's own per-seat plans.

One honest caveat: Sharktech's portal sells this as a per-GB storage configuration rather than itemizing per-seat Microsoft 365 SKUs, so your exact cost for M365 workloads gets confirmed when you configure the cart and check out. Don't assume a specific seat count translates into a specific invoice without checking the configurator — and if anything is unclear, Sharktech's 24/7 support can confirm before you pay.

## Who this plan fits — and who should keep looking

**Good fit:**

- Small businesses (roughly 1–10 machines plus M365 data) that want SharePoint, Teams and OneDrive backed up without juggling multiple subscriptions.
- Anyone who wants off-site Acronis cloud storage with a choice of five US/EU locations, encryption and ransomware protection built in.
- IT consultants and MSPs who want Acronis-grade protection at published per-GB rates instead of negotiating reseller agreements.
- Budgets under ~$10/month that still need a real third-party backup, not just recycle bins.

**Not a good fit:**

- Organizations needing thousands of TB, multi-region custom retention policies, or enterprise compliance workflows — Acronis's own ecosystem positions those users toward large-scale platforms, and Sharktech's product targets the small-to-mid range.
- Teams that must retain full control of storage location on their own infrastructure. Acronis's on-premises deployment mode allows any storage, but Sharktech's service is built around Acronis cloud storage in its data centers.
- Buyers who need a published free trial or refund window. Sharktech doesn't publish either on its backup pages, so if a trial matters to you, ask support before ordering.

For comparison context, the alternatives in this space work differently: dedicated Microsoft 365 backup tools like MSP360 run cloud-to-cloud through the Microsoft Graph API with per-tenant SharePoint/Teams licenses; Veeam protects SharePoint through its broader data platform; and Microsoft's own Azure Backup handles SharePoint only via DPM/MABS infrastructure, which means running and licensing your own backup server. Those are all viable routes — they simply cost more to set up or manage, which is exactly the gap a flat $4/month managed plan occupies. If your environment is large or compliance-heavy, one of those platforms is the better tool; for everyone else, keep reading.

## How to order, step by step

1. **Open the configurator.** The product lives in Sharktech's client portal cart. The order page lists the plan as "Acronis Cloud Backup."
2. **Pick a data center.** Choose among Los Angeles, Las Vegas, Denver, Chicago and Amsterdam.
3. **Set your storage.** Configure Cloud Backup & Protection in GB (default 200). Add Files Sync & Share only if you actually want syncing — it's a separate line item.
4. **Choose the billing cycle** and confirm the full price in the portal before paying. The displayed total is the final number; Sharktech advertises transparent pricing with no hidden fees.

The whole flow takes a few minutes, and there's no infrastructure to deploy — backups run through the Acronis web console, where you register systems, apply protection plans and monitor backup activity independently of any server control panel.

## FAQ

**Does Microsoft 365 include SharePoint backup on its own?**
No. Microsoft 365 provides retention and recycle-bin features that undo recent deletions within limited windows, but Microsoft doesn't keep long-term independent backups of your tenant data. Third-party backup is the standard recommendation for anything you'd need to recover weeks or months later.

**How much storage do I need for a SharePoint backup?**
Depends on your libraries, but document-heavy sites are usually far smaller than people expect. Since Sharktech includes 200GB in every billing cycle and charges $0.02/GB monthly beyond that, a modest SharePoint site with Teams files will typically fit in the included allowance — start there and adjust.

**Can the same plan back up Teams and OneDrive files too?**
Yes, at the platform level. Teams files are stored in SharePoint document libraries, and Acronis Cyber Protect backs up SharePoint Online, Teams, OneDrive for Business and Exchange Online under the same product umbrella.

**Is there a free trial or refund?**
Sharktech's published backup pages don't advertise either. Storage and pricing are confirmed at checkout, and the monthly plan ($4) is the cheapest way to evaluate the service without committing to a longer cycle.

## Before you click buy

Match the cycle to your storage pattern: stable or steadily growing SharePoint data → annual at $24/year is the better deal despite the steeper $0.12/GB overage; fluctuating or not-yet-measured data → monthly at $4 with $0.02/GB overage keeps your options open. Leave the Files Sync & Share slider at zero unless you'll use it, and pick a backup region different from where your production Microsoft 365 traffic lives.

If that matches your situation, 👉 [configure your Acronis SharePoint backup plan on Sharktech](https://portal.sharktech.net/cart.php?a=add&pid=648&configoption%5B1862%5D=200&configoption%5B1863%5D=0&billingcycle=monthly&aff=1626) — and confirm the final price in the portal before completing the order.
