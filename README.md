# Is ScraperAPI Free? What 1,000 Monthly Credits Buy, How the 7-Day 5,000-Credit Trial Works, and When You Have to Pay (All 8 Plans Compared)

Yes. ScraperAPI runs a permanent free plan at $0: **1,000 API credits per month, 5 concurrent connections, no credit card at signup**. Separately, the first 7 days after you register come with **5,000 credits** so you can test at a larger scale before committing to anything.

The harder question is what 1,000 credits means in actual pages, because ScraperAPI prices requests by domain and by the features you switch on. It's 1,000 plain HTML pages, 200 Amazon pages, or 40 Google searches. The tables below convert the free allowance into real request counts, list every plan with current pricing, and cover the limits that only appear in the billing documentation.

> **Quick pick:** spend the trial on the URLs you actually plan to scrape. If they come back clean and you need volume, **Hobby at $49/month** (100,000 credits, 20 threads) is the first paid step, and annual billing brings it to **$44.10/month, or $529.20 a year**.
> 👉 [Start the free 7-day trial with 5,000 credits](https://www.scraperapi.com/signup/?fp_ref=coupons)

## Every ScraperAPI plan and price

Annual billing takes 10% off each self-serve tier, and ScraperAPI hands over the full year's credits upfront so you can spend them on any schedule. Run out early and you can renew the same annual plan for a fresh allocation. These are the prices showing on the official pricing page.

| Plan | Credits per month | Concurrent threads | Price (monthly / annual per month) | Get started |
| --- | --- | --- | --- | --- |
| Free | 1,000 | 5 | $0 | [Start on the free plan](https://www.scraperapi.com/signup/?fp_ref=coupons) |
| Hobby | 100,000 | 20 | $49 / $44.10 ($529.20 per year) | [See Hobby pricing](https://www.scraperapi.com/pricing/?fp_ref=coupons) |
| Startup | 1,000,000 | 50 | $149 / $134.10 ($1,609.20 per year) | [See Startup pricing](https://www.scraperapi.com/pricing/?fp_ref=coupons) |
| Business | 3,000,000 | 100 | $299 / $269.10 ($3,229.20 per year) | [See Business pricing](https://www.scraperapi.com/pricing/?fp_ref=coupons) |
| Scaling | 5,000,000 | 200 | $475 / $427.50 ($5,130 per year) | [See Scaling pricing](https://www.scraperapi.com/pricing/?fp_ref=coupons) |
| Professional | 10,500,000 (limited offer: +250K bonus) | 300 | $975 / $877.50 ($10,530 per year) | [See Professional pricing](https://www.scraperapi.com/pricing/?fp_ref=coupons) |
| Advanced | 21,500,000 (limited offer: +500K bonus) | 500 | $1,975 / $1,777.50 ($21,330 per year) | [See Advanced pricing](https://www.scraperapi.com/pricing/?fp_ref=coupons) |
| Enterprise | 22,000,000+ | 500+ | Custom quote | [See enterprise options](https://www.scraperapi.com/pricing/?fp_ref=coupons) |

Two features change at the higher tiers but don't show up in the numbers above:

| Plan | Geotargeting | Analytics history | Support |
| --- | --- | --- | --- |
| Hobby | US & EU only | Last 30 days | Standard |
| Startup | US & EU only | Last 30 days | Standard |
| Business | Country-level | Unlimited | Standard |
| Scaling | Country-level | Unlimited | Standard |
| Professional | Country-level | Unlimited | Priority queue |
| Advanced | Country-level | Unlimited | Priority routing |
| Enterprise | Country-level | Unlimited | Dedicated team and Slack |

ScraperAPI's comparison table starts at Hobby, so there's no published geotargeting or analytics figure for the free plan. Don't assume it matches Hobby.

## How many pages do 1,000 credits actually buy?

ScraperAPI charges a different number of credits per request depending on the target and the parameters you pass. The free plan's 1,000 credits convert like this:

| Request type | Credits per request | Covered by 1,000 free credits |
| --- | --- | --- |
| Standard HTML page | 1 | 1,000 requests |
| Amazon, Walmart, eBay | 5 | 200 requests |
| Google or Bing, including subdomains | 25 | 40 requests |
| LinkedIn | 30 | 33 requests |
| JavaScript rendering (`render=true`) | 10 | 100 requests |
| Premium proxies (`premium=true`) | 10 | 100 requests |
| Screenshot (`screenshot=true`) | 10 | 100 requests |
| Premium proxies + JS rendering together | 25 | 40 requests |

Bot-protection bypass for Cloudflare, Cloudflare Turnstile, DataDome, PerimeterX/HUMAN and Akamai adds 10 credits per request. Geotargeting, sessions, device type, output format and auto parsing add nothing. Ultra Premium requests (30 credits, or 75 with JS rendering) are restricted to paid plans, so those rates never apply on the free tier.

The trial multiplies all of it by five: 5,000 standard pages, 1,000 Amazon pages, 200 Google searches, 500 rendered pages. Spread across seven days that's roughly 714 credits a day, about 28 Google searches or 140 Amazon product pages daily.

👉 [Check what each tier costs before you commit](https://www.scraperapi.com/pricing/?fp_ref=coupons)

## Trial versus free plan: sequential, not stacked

Signing up gives you 5,000 credits for the first 7 days. That's the trial. When it ends, the account either upgrades or drops to the 1,000-credit free plan, in ScraperAPI's own words: "When the trial ends, you can upgrade to a paid plan or keep scraping for free."

The two allowances don't stack, so don't plan a 6,000-credit first month. If your targets are expensive (SERPs, LinkedIn, JS-heavy sites), the trial is where you'll use most of your testing budget. Point it at the five URLs that matter most instead of spreading it over everything.

## The limits that decide whether free is enough

**Concurrency overflow is rejected, not billed.** Push past 5 simultaneous requests and you get a 429, and the request is turned away rather than queued. There's no extra charge, but a scraper that fires 20 requests at once will mostly collect 429s. Throttle to 5 in flight.

**Credits reset instead of rolling over.** Whatever is unused disappears when the subscription renews. Banking a quiet month to cover a busy one doesn't work. Annual plans are the exception, since the whole year's credits arrive at once.

**Pay-as-you-go is not available on the free plan.** ScraperAPI limits PAYG to Scaling, Professional, Advanced and Enterprise. Free, Hobby, Startup and Business get auto-upgrade instead, an opt-in that moves you to the next tier when credits run out. Leave it off and scraping pauses until the reset. For free-plan users this settles what happens at request 1,001: nothing runs until the month turns over.

Auto-upgrade itself isn't universal either. It's available on Hobby, Startup, Business, Scaling and Professional. Advanced is the highest self-serve tier, so it has no next plan to move to, and Enterprise goes through sales.

👉 [Compare Hobby and Startup side by side](https://www.scraperapi.com/pricing/?fp_ref=coupons)

## What ScraperAPI doesn't charge you for

You're billed for successful responses (HTTP 200 and 404) and for requests you cancel after 70 seconds. Timeouts, errors and attempts that fail outright cost nothing, which matters when you're probing a difficult site on a 1,000-credit budget.

Every response carries an `sa-credit-cost` header showing what that request consumed. The dashboard has a Domain Cost Estimator for pricing a URL before you build a job around it, and the `max_cost` parameter caps what any single request is allowed to spend. Set it before you turn on JS rendering on an unknown domain, because that parameter alone moves a request from 1 credit to 10.

## Who can stay free, and who should go straight to Hobby

The free plan holds up indefinitely if your monthly work fits one of these: under 1,000 plain HTML pages, under 200 marketplace product pages, under 40 search result pages, or under 100 rendered pages, with no more than 5 requests running at once. A weekly check on 50 plain HTML pages is 200 requests a month at 1 credit each, which fits with room to spare.

Move to Hobby when you cross those numbers but stay under 100,000 credits. At $49/month the effective rate is $0.49 per 1,000 standard pages, and 20 threads is four times the free ceiling. Two caveats before you pay: Hobby geotargeting covers the US and EU only, and country-level targeting starts at Business ($299/month, 3,000,000 credits, 100 threads). If your data has to come from outside those regions, Hobby won't do it even though the credit count looks generous.

Google and Bing are where the free plan runs dry fastest. At 25 credits a search, a single daily rank check costs 750 credits a month, leaving 250 for everything else. The same math applies to LinkedIn at 30 credits a request. Plain pages are cheap; search results are not.

## FAQ

**Do I need a credit card to use ScraperAPI for free?**
No. Both the 7-day trial and the ongoing free plan are $0 with no card required.

**What happens when the trial ends?**
ScraperAPI's stated options are to upgrade to a paid plan or continue on the free plan. The trial doesn't ask for card details, so nothing is on file unless you add it during an upgrade.

**Do unused credits roll over to the next month?**
No. The balance resets at each renewal. Annual plans receive the full year's credits upfront instead.

**Can I get a refund on a paid plan?**
Yes. ScraperAPI offers a 7-day no-questions-asked refund policy, handled through support.

**Can I cancel anytime?**
Yes, from the dashboard or by contacting support, with no cancellation fee.

**Can I get extra credits for testing?**
ScraperAPI's documentation says to contact support if you need additional credits for testing purposes.

👉 [Start with the free plan, no card needed](https://www.scraperapi.com/signup/?fp_ref=coupons)

## Before you pick a plan

Match the tier to the workload rather than to the credit number:

- Plain HTML pages under 1,000 a month and 5 threads or fewer: stay on the free plan.
- Up to 100,000 credits and 20 threads: Hobby at $49/month, or $44.10/month on annual billing.
- Country-level geotargeting or unlimited analytics history: Business at $299/month is the cheapest route, since Hobby and Startup are US and EU only.
- Unpredictable volume where a mid-month stop breaks something: Scaling at $475/month, the first plan with pay-as-you-go as a safety net.

Before entering card details, run your five heaviest URLs through the Domain Cost Estimator and multiply by your monthly volume. The per-domain multiplier decides the bill far more than the plan name does. If the estimate lands within about 10% of a plan's limit, take the tier above or trim the expensive parameters, because nothing below Scaling gives you an overage buffer.

👉 [Open the free plan and test your own targets first](https://www.scraperapi.com/?fp_ref=coupons)
