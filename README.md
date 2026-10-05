# buy residential proxies: how to compare per-GB rates, targeting fees and traffic expiry before you pay

Type "buy residential proxies" into Google and you get a wall of providers all quoting a per-GB price. Bright Data, Oxylabs, Decodo, Webshare, SOAX, a dozen smaller outfits, plus DataImpulse sitting at the budget end at **$1/GB**. The per-GB number is the easiest thing to compare and the least useful on its own.

Two providers can advertise $1/GB and $1/GB and end up costing you wildly different amounts. One expires your unused traffic at the end of the month. One charges double for city-level targeting. One has a $500 minimum. What you actually want to know before paying is: what happens to the GBs I don't use, what does the targeting I need cost, and how much do I have to put down to start?

This is a walkthrough of those three questions, using DataImpulse as the concrete example — partly because the numbers are published openly, partly because it's one of the few providers in this space where the answer to "when does my traffic expire" is "never."

## The per-GB price is a starting point, not a quote

Here's the part that trips people up. Residential proxy pricing is metered, not fixed. You buy a bucket of bandwidth and each HTTP request burns a fraction of it. A single product page might be a few hundred kilobytes. A full SERP scrape across 10,000 keywords is a different conversation entirely.

So the sticker price tells you the rate. It doesn't tell you the bill. To get from one to the other, you need three more numbers:

1. **Traffic expiry** — does your unused balance survive past the billing cycle?
2. **Minimum commitment** — what's the smallest amount you can put down?
3. **Targeting surcharges** — do you pay extra for anything below country level?

Providers bury all three. Some don't mention expiry until the terms of service.

### Traffic expiry is the biggest hidden multiplier

Say you buy 50 GB for a scraping sprint and only burn 30. With expiring traffic, you paid for 50 and got 30. Your effective rate just went up 67%. That's not a discount anymore, that's a rounding error in the vendor's favour.

Non-expiring traffic changes the maths. If your workload is spiky — heavy during a product launch, quiet for three weeks after — a pay-as-you-go model with no expiry means your leftovers are still sitting there when you need them. For anyone doing intermittent work rather than continuous crawling, this matters more than 20 cents off the per-GB rate.

DataImpulse's whole pricing model is built on this. Traffic you buy doesn't expire, there's no subscription, and there's no monthly minimum. Their own comparison page makes the point bluntly against IPRoyal's expiring pay-as-you-go, and TechRadar's review picked out non-expiring traffic as the feature that "separates DataImpulse from a chunk of its competitors."

### Minimums and second-purchase rules

Almost nobody advertises a free tier that's actually useful for real work. DataImpulse doesn't offer a free trial at all — access starts at a **$5 minimum**, which buys 5 GB of residential, 10 GB of datacenter, 2.5 GB of mobile, or 1 GB of premium residential.

Worth flagging: at least one third-party review reports that the minimum top-up rises to $50 from your second purchase onward. DataImpulse's own site leads with the $5 entry point, so if a $5 test is the plan, confirm the follow-up minimum before you commit to a workflow that depends on small top-ups.

## Where the per-GB rate stops being the real rate

The $1/GB residential number is real, but it applies to country-level targeting. Everything below country is a paid add-on, and it's billed at **2× the standard rate**.

That means traffic routed through city, state, ZIP or specific-ASN filters costs you $2/GB, not $1/GB. Country selection and ASN exclusion stay free. If your project needs US city-level data for local SERP tracking or regional price monitoring, your effective rate is double the headline. Budget accordingly — this is exactly the kind of thing that makes a $1/GB provider more expensive in practice than a $2/GB one with targeting bundled in.

> Country targeting is included in the base rate. City, state, ZIP and ASN selection are billed at 2× on standard residential plans. Datacenter product pages list state/city/ZIP/ASN as included features — treat that as something to confirm at checkout rather than assume.

## DataImpulse's full price list

DataImpulse runs four separate proxy products, all pay-as-you-go, all with non-expiring traffic. Here's the current published ladder.

| Product | Plan | Traffic | Price | Per GB | Buy |
| --- | --- | --- | --- | --- | --- |
| Residential | Intro | 5 GB | $5 | $1.00 | [ Start with the $5 residential intro](https://bit.ly/dataimPulse) |
| Residential | Basic | 50 GB | $50 | $1.00 | [ Get the 50 GB residential plan](https://bit.ly/dataimPulse) |
| Residential | Advanced | 1 TB | $800 | $0.80 | [ Buy the 1 TB residential tier](https://bit.ly/dataimPulse) |
| Residential | Custom | 5 TB+ | from $0.70/GB | custom | [ Request residential volume pricing](https://bit.ly/dataimPulse) |
| Premium Residential | Intro | 1 GB | $5 | $5.00 | [ Try premium residential from $5](https://dataimpulse.com/premium-residential-proxies/?aff=86938) |
| Premium Residential | Basic | 10 GB | $50 | $5.00 | [ Get 10 GB of premium residential](https://dataimpulse.com/premium-residential-proxies/?aff=86938) |
| Premium Residential | Custom | 5 TB+ | from $20,000 | custom | [ Ask about premium residential scale pricing](https://dataimpulse.com/premium-residential-proxies/?aff=86938) |
| Mobile | Intro | 2.5 GB | $5 | $2.00 | [ Start with 2.5 GB of mobile proxies](https://bit.ly/dataimPulse) |
| Mobile | Basic | 25 GB | $50 | $2.00 | [ Get 25 GB of mobile traffic](https://bit.ly/dataimPulse) |
| Mobile | Advanced | 1 TB | $1,600 | $1.60 | [ Buy the 1 TB mobile tier](https://bit.ly/dataimPulse) |
| Mobile | Custom | 5 TB+ | from $8,000 | custom | [ Request mobile volume pricing](https://bit.ly/dataimPulse) |
| Datacenter | Intro | 10 GB | $5 | $0.50 | [ Start with 10 GB of datacenter proxies](https://dataimpulse.com/datacenter-proxies/?aff=86938) |
| Datacenter | Basic | 100 GB | $50 | $0.50 | [ Get 100 GB of datacenter traffic](https://dataimpulse.com/datacenter-proxies/?aff=86938) |
| Datacenter | Advanced | 1 TB | $450 | $0.45 | [ Buy the 1 TB datacenter tier](https://dataimpulse.com/datacenter-proxies/?aff=86938) |
| Datacenter | Custom | 5 TB+ | from $2,250 | custom | [ Request datacenter volume pricing](https://dataimpulse.com/datacenter-proxies/?aff=86938) |

The residential ladder is unusually flat. From roughly 5 GB up to around 700 GB, you're at $1/GB. The first real discount step lands at 1 TB, where it drops to $0.80 — a 20% cut that also applies to mobile ($2.00 → $1.60). Below that, buying 50 GB instead of 5 GB doesn't change your rate at all, it just means you're holding more non-expiring credit.

## Which proxy type should you actually buy

This is where most buyers waste money. The instinct is to buy residential for everything, because that's what the keyword told you to do. Not always the right call.

**Residential ($1/GB)** is for defended targets. Real ISP-assigned IPs from actual household devices, so a site's bot detection sees an ordinary home connection instead of a datacenter range. DataImpulse's pool is 90M+ IPs across 195 countries, sourced from first-party pools rather than resold networks — which the company leans on heavily as the reason its IPs aren't already blacklisted.

**Premium residential ($5/GB)** is the same idea with a faster, cleaner pool, a dedicated account manager, and all targeting options included rather than surcharged. If you're running city-level campaigns at volume, the 5× premium can actually wash out against 2× surcharges on standard residential. Run the numbers on your own mix before assuming premium is the expensive option.

**Mobile ($2/GB)** is for the hardest targets — mobile app data, social platforms, anything with aggressive anti-fraud checks. It's the tier people reach for when residential gets blocked.

**Datacenter ($0.50/GB)** is the cheapest and fastest, and it's the right answer whenever the target doesn't care. If your scraping job is hitting public pages with no bot protection, paying $1/GB for residential IPs is paying for credibility you don't need.

A reasonable approach for a mixed workload: route each job to the cheapest tier that still gets a clean response, and only escalate when you see blocks. DataImpulse publishes a 99.51% success rate across the network, which is a vendor-reported figure rather than an independently audited one — measure your own cost per successful request before scaling.

## What you get once you've paid

Setup is genuinely short. Sign up, add a plan, top up the balance, and generate an endpoint. Country targeting is passed as a URL parameter rather than configured per-location in the dashboard, which keeps things manageable when you're hitting a dozen regions.

The connection format looks like this:


# Rotating — new IP per request
http://user:pass@gw.dataimpulse.com:823

# Sticky session
http://user:pass_session-abc123@gw.dataimpulse.com:823

# Country targeting
http://user:pass_country-us@gw.dataimpulse.com:823

# City targeting
http://user:pass_country-us_city-newyork@gw.dataimpulse.com:823


Rotating sessions use **port 823** for HTTP/HTTPS and **824** for SOCKS5. Sticky sessions run across ports 10000–20000, lasting anywhere from 1 to 120 minutes, defaulting to 30 if you don't specify an interval. Rotating is the default choice for high-volume crawling. Sticky is what you want when a target site behaves better with a bit of session continuity — login flows, multi-step checkouts, anything with state.

Both HTTP(S) and SOCKS5 are supported on every product line. There are integrations for Scrapy, Selenium, Puppeteer and the usual browser extensions, plus proxy manager support.

## Refunds, trials and the honest caveats

There's no free trial. The $5 intro is the trial, effectively.

The intro plans do carry a **7-day money-back guarantee** on card payments, with a condition: you need to have consumed less than 80% of the traffic. Pay by crypto and the intro plan is non-refundable. Read that before you burn through your test budget in an afternoon.

Two more things worth knowing up front:

- **No ISP/static residential product.** If you need dedicated static IPs for multi-account management — running many social profiles, for instance — this isn't the provider for that. Residential and mobile rotate; datacenter IPs are shared subnets. Multi-account work usually needs static residential, and you'd be looking elsewhere.
- **Advanced targeting costs double.** Repeating this because it's the single most likely way to be surprised by your invoice.

## How it stacks up against the market

Third-party price tracking in 2026 puts the fair range for residential at roughly **$1–8/GB**. Decodo sits at $2/GB on its enterprise tier and $2.75–3.75/GB on monthly plans. CatProxies launched a residential network starting at $2.50/GB. IPRoyal's pay-as-you-go is around $7.35/GB. Bright Data and Oxylabs play in the enterprise band, often with monthly commitments in the hundreds.

Against that, $1/GB pay-as-you-go with non-expiring traffic is at the floor of the market, and the gap isn't small. DataImpulse's own comparison puts 1 TB at $800 versus IPRoyal's $3,310 for the same volume. Vendor-run comparisons deserve scepticism, but the underlying public rate cards do support the general direction.

The trade-off you're accepting at that price: no free trial, a paid add-on for sub-country targeting, and a thinner enterprise feature set than Oxylabs or Bright Data offer. If you need SOCKS5, rotating and sticky sessions, country targeting and a working API — the essentials — you're covered. If you need SSO, custom SLAs and a named solutions architect on day one, you're not the target customer.

Independent coverage is generally positive. TechRadar's review found residential proxies delivered a consistently high scraping success rate and called the unexpiring pay-as-you-go traffic and the $1/GB baseline standout features. The service holds a **4.8/5 rating on G2**. HostAdvice's 2026 review concluded the flat rate, 90M+ first-party pool, no-expiry traffic and fast human support hold up to scrutiny. Take all three as directional — reviews age, and pool quality shifts.

## Common questions people ask before buying

**Is there a free trial?** No. Minimum purchase is $5, which covers 5 GB of residential traffic.

**Does unused traffic expire?** No. Purchased GBs stay in your account indefinitely.

**What's the minimum?** $5 for the first purchase. Some reviews report the minimum rising to $50 from the second purchase — worth verifying at checkout.

**Can I target a specific city?** Yes, but city, state, ZIP and ASN targeting are billed at 2× the base rate on residential plans.

**Do I need SOCKS5?** Supported on all products, port 824 for rotating sessions.

**What happens if the proxies don't work for my use case?** Intro plans carry a 7-day money-back guarantee on card payments, provided less than 80% of traffic has been used. Crypto purchases on intro plans aren't refundable.

## What to do with all this

If you came here to buy residential proxies and you want the short version: work out your targeting needs first, because that's what sets your true rate. Country-level only, and $1/GB is $1/GB. City-level at volume, and you're at $2/GB — at which point premium residential at $5/GB with targeting bundled may be worth pricing out, or you may want a provider that includes sub-country targeting in the base rate.

Then check expiry and minimums against how you actually work. Spiky, intermittent scraping favours non-expiring pay-as-you-go. Continuous, predictable monthly volume favours whoever gives you the best rate at your scale, expiry or not.

DataImpulse fits the first profile well and the price floor is hard to argue with. Start small, measure cost per successful request on your own targets, and scale only if the number works. That's a more useful test than any comparison table — including this one.
