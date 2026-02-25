---
name: icp-builder
description: Guides product marketers through building a rigorous Ideal Customer Profile (ICP) that drives targeting, messaging, and sales qualification. Use when targeting is too broad, pipeline quality is low, messaging isn't resonating, or entering a new segment. Covers firmographic, technographic, psychographic, and behavioral attributes, plus buying triggers, anti-ICP signals, and activation across marketing and sales.
---

# Ideal Customer Profile (ICP) Builder Skill

## Overview
This skill helps product marketers build an Ideal Customer Profile that is specific enough to actually change marketing and sales behavior. Most ICPs are too broad to be useful ("mid-market B2B SaaS companies") or focus only on firmographics that describe who a customer *is* rather than what makes them *ready and likely to buy*.

A well-built ICP answers four questions:
1. Who has the most acute version of the problem we solve?
2. Who gets the most value from our solution?
3. What characteristics identify them before they raise their hand?
4. What triggers indicate they're ready to buy now?

## When to Use This Skill
- Pipeline volume is fine but quality is low (too many dead-end deals)
- Sales reps are qualifying everything and closing little
- Messaging is diffuse ("we help everyone who...")
- Entering a new segment or market
- ABM program needs sharper account targeting
- Repositioning after finding product-market fit in a new segment
- Marketing spend is generating leads but not customers

## Why Most ICPs Fail

**They describe existing customers, not best-fit customers.**
The customer base often includes "okay" customers who bought for legacy reasons, enterprise logos pursued for prestige rather than fit, and SMB customers who churn quickly. The ICP should be built around the customers with highest lifetime value, lowest churn, fastest time-to-value, and highest expansion — not the average customer.

**They stop at firmographics.**
"Mid-market SaaS, 100-500 employees, Series B-C" describes thousands of companies, most of whom aren't ready to buy. The firmographic layer tells you who *could* be a good customer. The psychographic and behavioral layers tell you who *is* one.

**They're built without customer input.**
ICPs built from internal data miss the buyer's perspective on why they bought, what made them ready, and what alternative they were coming from. The best ICPs combine CRM data with customer research.

**They're never activated.**
An ICP document that lives in a Google Drive folder doesn't change targeting or qualification. An ICP needs to be operationalized into scoring models, ad targeting criteria, and sales qualification questions.

## The ICP Framework: Five Layers

### Layer 1: Firmographics — Who They Are
The observable, data-available characteristics of the account.

**Key dimensions:**
- **Industry/vertical**: Which industries have the problem most acutely?
- **Company size**: Employees, revenue, or ARR? What range?
- **Growth stage**: Startup, growth-stage, established, enterprise?
- **Geography**: Domestic vs. international, specific regions?
- **Business model**: SaaS, marketplace, services, hybrid?
- **Ownership**: Venture-backed, PE-backed, bootstrapped, public?

**Questions to ask:**
- "When you look at your top 20 customers by LTV, what do they have in common firmographically?"
- "Is there a company size where win rate or retention is notably better?"
- "Are there industries where you consistently win and industries where you consistently lose? What's different?"
- "At what funding stage or revenue level do companies typically 'get it' and the deal closes fast?"

### Layer 2: Technographics — What They Use
The technology stack signals both fit and competitive context.

**Key dimensions:**
- **Current tech stack**: What tools do they already use that you integrate with or compete with?
- **Technology maturity**: Are they early adopters, fast followers, or laggards?
- **Data infrastructure**: What's their data warehouse, CDP, or analytics environment?
- **Incumbent tools**: What are they likely coming from (your real competitive alternatives)?

**Questions to ask:**
- "What tools do your best customers have in their stack that correlates with being a good fit?"
- "Is there a tool they're using that signals they're in the right infrastructure? Or the wrong one?"
- "What does the technology environment look like at companies that churn? How is it different?"

**Example technographic signals:**
- "Company uses Salesforce" → they have a mature CRM practice and integration is easy
- "Company uses HubSpot (not Salesforce)" → likely smaller, different integration priority
- "Company recently adopted Snowflake" → modern data infrastructure, likely to value our warehouse-native approach

### Layer 3: Psychographics — How They Think
The mindset, values, and organizational approach that make a company receptive.

This is the hardest layer to measure but often the most predictive. Psychographic fit determines whether the company *values* what you do, not just whether they have the problem.

**Key dimensions:**
- **Attitude toward [your category]**: Do they see this as strategic or operational?
- **Buy vs. build mentality**: Do they prefer to purchase solutions or build in-house?
- **Data/analytics maturity**: How do they make decisions?
- **Change appetite**: Early adopter or risk-averse? How long do they evaluate?
- **Champion presence**: Is there someone internally who advocates for this problem?

**Questions to ask:**
- "What do your best customers believe about [your category] that average customers don't?"
- "Is there an attitude or mindset that characterizes companies who 'get it' immediately?"
- "Are there companies that have the problem but don't see it as a priority? What's different about them vs. the ones who do?"
- "What's the personality type of the champion inside your best customers?"

**Example psychographic signals:**
- "Leadership team views data as a competitive advantage" — vs. "data as cost center"
- "Team has tried to build this internally and hit limits" — indicates problem awareness and buy-over-build shift
- "Champion has done this job before at a larger company and knows what good looks like"

### Layer 4: Buying Triggers — What Creates Readiness
The events and circumstances that move a company from "this would be nice" to "we need this now."

Buying triggers are the most powerful and underutilized dimension of the ICP. A company that perfectly matches your firmographic and psychographic profile may still not be ready to buy. A trigger is what makes them ready.

**Types of triggers:**

**Organizational events:**
- New hire in a key role (new CMO, new VP Sales, new Head of Data)
- Funding round (Series A signals early go-to-market buildout; Series B signals scale)
- Acquisition (new parent company requirements or integration needs)
- Rapid headcount growth (team scaling past threshold where current tools break)

**Business events:**
- Product launch into a new segment (new ICP, need to understand new buyers)
- Sales team expansion (more reps need more enablement)
- Revenue target increase (CFO pressuring efficiency)
- Competitive pressure intensifying (competitor winning deals)

**Technology events:**
- Migrating off a legacy platform
- Outgrowing current tooling
- New data infrastructure adoption (moved to Snowflake, now need activation layer)

**Failure events:**
- DIY approach failed ("we tried to build this and it didn't work")
- Tool consolidation needed (too many point solutions)
- Prior vendor failure (churned from competitor, now evaluating)

**Questions to ask:**
- "Think about the last 5 deals that closed fastest — what was happening in those companies at the time?"
- "Is there a specific hire that tends to appear before a deal closes? (New VP Sales, new CMO, new Head of X?)"
- "Are there funding rounds or company milestones that correlate with companies entering your pipeline?"
- "What's the failure mode that makes someone finally act? What had to go wrong before they started looking?"

### Layer 5: Anti-ICP Signals — Who to Disqualify
Equally important: who is NOT a good-fit customer.

Anti-ICP signals help sales reps disqualify quickly and prevent PMM from targeting the wrong companies.

**Categories of anti-ICP:**

**Firmographic disqualifiers:**
- Below-minimum company size where value can't be demonstrated
- Industries where regulation prevents adoption
- Geographies where you can't support or serve

**Behavioral disqualifiers:**
- "We're evaluating 10 vendors" — procurement-driven, will optimize for price
- No dedicated owner for the problem — will buy and never implement
- "We want to pilot with no commitment" — low urgency, high risk of indefinite pilot

**Psychographic disqualifiers:**
- "We prefer to build everything in-house" — not a buyer mentality
- No data culture — won't value data-driven features
- Change-averse leadership — long sales cycle with high loss-to-no-decision risk

**Questions to ask:**
- "Think about your worst customers — high churn, hard to work with, low expansion. What did they have in common?"
- "Are there company sizes or types that look like they could be good customers but aren't?"
- "What does a prospect say or do early in the sales process that predicts a bad outcome?"

## The Research Process

### Step 1: CRM Analysis

Start with data. Pull your top customers (by LTV or expansion revenue, not just initial deal size) and analyze patterns.

**What to look for:**
- Firmographic clusters: Which industries, sizes, and stages appear most?
- Time to value: Which segments achieve value fastest?
- Expansion rate: Which segments expand most reliably?
- Retention: Which segments churn least?
- Sales cycle: Which segments close fastest?

**Red flags in the data:**
- Wide distribution with no clear cluster → ICP is too broad
- Your "best" customers by LTV have poor expansion → may be one-time use cases, not recurring need
- Consistent churn in a specific segment → that's an anti-ICP signal

### Step 2: Customer Interviews

CRM data tells you *who* your customers are. Customer interviews tell you *why* they bought and what makes them successful. Use `/switch-interview` for this if you haven't done buyer research yet.

**ICP-specific questions for customer interviews:**
- "What was happening in your company when you decided to evaluate solutions like ours?"
- "What would have to be true about a company for them to get real value from this?"
- "Is there anything about how your team operates that makes you a better fit than other companies you know?"
- "Do you know other companies that use [our product]? What do you think they have in common with you?"

### Step 3: Sales Team Input

Sales reps have patterns in their heads that haven't been articulated. Ask:
- "When you get on a first call and think 'this is going to close,' what do you see?"
- "What do bad-fit customers have in common?"
- "Are there questions you ask that immediately tell you whether a company is a fit?"
- "What does a champion look like when they show up in a deal?"

### Step 4: Churn Analysis

Interview churned customers to understand where fit was absent:
- "What were you hoping this would solve?"
- "What wasn't quite right about the fit?"
- "What kind of company do you think we're really built for?"

## Building the ICP Document

### Primary ICP

Document your highest-confidence, most-likely-to-succeed customer profile.

**Template:**

```
## Primary ICP: [Segment Name]

### Who They Are (Firmographic)
Industry: [Industries that over-index in your best customer base]
Size: [Employee or revenue range]
Stage: [Funding stage, growth rate, maturity]
Model: [Business model, ownership structure]
Geography: [Regions, if relevant]

### What They Use (Technographic)
Signals of fit:
• [Tool or stack that indicates readiness]
• [Tool or stack that indicates readiness]
Incumbent they're coming from: [Most common prior solution]
Technical maturity: [How they think about tech adoption]

### How They Think (Psychographic)
They believe: [Key mindset/value]
They're willing to: [Buy vs. build preference, risk appetite]
Champion profile: [Who advocates internally — role, background, motivation]
They've typically: [Prior experience or context that makes them receptive]

### What Makes Them Ready (Buying Triggers)
High-signal triggers:
• [Specific event that creates urgency]
• [Specific event that creates urgency]
• [Specific event that creates urgency]
How to detect triggers: [What to look for in company signals, job postings, news]

### Who to Disqualify (Anti-ICP)
Firmographic disqualifiers:
• [Characteristic that predicts bad fit]
Behavioral disqualifiers:
• [Pattern that signals misalignment]
Psychographic disqualifiers:
• [Mindset that prevents adoption]

### Why They Buy (Value Connection)
Core job they're hiring us for: [The progress they're trying to make]
Primary value theme: [Which of our messaging pillars resonates most]
Proof that works: [Which customer stories land with them]

### How They Buy
Typical buying committee: [Roles involved and what each cares about]
Average sales cycle: [Time from first contact to close]
Decision style: [Consensus vs. champion-driven, procurement involvement]
```

### Secondary ICP (if applicable)

Some products serve multiple distinct segments. If so, document a secondary ICP following the same structure and note key differences from the primary.

**When to have a secondary ICP vs. one:**
- Secondary ICP: Different buying trigger, different champion, different value proposition, but same product
- Different product/SKU needed: If the secondary segment needs fundamentally different capabilities, this is a product problem, not an ICP variant

## Activating the ICP

An ICP that doesn't change behavior is wasted effort.

### Sales Activation

**Qualification questions** (derived from ICP):
Turn ICP characteristics into discovery questions that qualify or disqualify early:

| ICP Attribute | Discovery Question |
|---------------|-------------------|
| Company has experienced [trigger event] | "What's been driving this initiative? What changed recently?" |
| Champion exists internally | "Is there someone on your team who owns this problem?" |
| Modern data infrastructure | "What does your current data stack look like?" |
| Buy vs. build mindset | "Have you tried to solve this internally? What happened?" |

**Disqualification signals** (to end deals early):
- "No dedicated owner" → "Who on your team is responsible for X today?"
- "Evaluating 10+ vendors" → "Where are you in your evaluation process?"

### Marketing Activation

**Demand gen targeting:**
- Build firmographic targeting in LinkedIn/6sense/Bombora using ICP attributes
- Create trigger-based intent signals from buying triggers (job postings, funding news)
- Exclude anti-ICP attributes in ad targeting

**Content strategy:**
- Create content mapped to trigger events ("New VP of Sales? Here's how to ramp a team in 90 days")
- Build segment-specific landing pages for top ICPs
- Develop case studies that mirror the ICP in industry, size, and trigger

**ABM account selection:**
- Build target account list by scoring against ICP dimensions
- Tier accounts by ICP fit score for 1:1, 1:few, and 1:many programs

## Validating and Updating the ICP

**ICP is a hypothesis, not a document.** It should be validated with data and updated as the business evolves.

**Review triggers:**
- Win rate drops significantly in a segment → ICP may need refinement
- New competitor entering your best segment → ICP fit needs defensive analysis
- Product expands into new use cases → new ICP tier may emerge
- Company raises funding and moves upmarket/downmarket → ICP recalibration needed

**Validation metrics:**
- Win rate by ICP tier (high-fit accounts should win at higher rate)
- Sales cycle by ICP tier (high-fit accounts should close faster)
- Expansion rate by ICP tier (high-fit accounts should expand)
- Churn rate by ICP tier (high-fit accounts should churn less)

## Best Practices

### Do's
- **Build from best customers, not average customers** — Average obscures what makes the best cases work
- **Include buying triggers** — Firmographics without triggers produce lists, not pipeline
- **Document the anti-ICP explicitly** — Disqualification is as valuable as qualification
- **Get field validation from sales** — PMM builds it, sales validates it; the rep's gut test matters
- **Connect ICP to qualification questions** — An ICP that doesn't become a question or a targeting filter isn't activated

### Don'ts
- **Don't build ICP in isolation** — Sales, CS, and data all have insight PMM doesn't
- **Don't confuse target market with ICP** — Target market is who you could sell to; ICP is who you should focus on
- **Don't ignore the psychographic layer** — Firmographic fit without psychographic fit = hard sell
- **Don't set and forget** — ICP needs quarterly review as market and product evolve
- **Don't over-engineer it** — One primary ICP well-defined beats five ICPs nobody uses

## Common Pitfalls

**Pitfall 1: The "describe our existing customers" trap**
Building ICP from the full customer base instead of the best customers
→ Solution: Filter to top quartile by LTV and retention. Build ICP from that cohort.

**Pitfall 2: Firmographic-only ICP**
"Series B SaaS companies 100-500 employees" — too many companies, no signal of readiness
→ Solution: Add at least one psychographic and two buying triggers.

**Pitfall 3: ICP that describes yesterday**
Built when the product was earlier-stage; doesn't reflect where you're strongest now
→ Solution: Re-run the analysis annually, or whenever win rates shift.

**Pitfall 4: ICP disagreement between teams**
Sales believes ICP is enterprise; marketing is targeting mid-market; CS is onboarding SMB
→ Solution: ICP workshop with all three functions. Disagreement on ICP is usually disagreement on strategy.

## Interactive Approach

When guiding someone through this framework, Claude should:

1. **Start with the CRM question** — Pull your top customers. What do they have in common?
2. **Push beyond firmographics** — Once firmographics are clear, probe for psychographics and triggers
3. **Force the anti-ICP** — Who is NOT a good fit? Disqualification is half the value
4. **Connect to buying triggers** — What creates urgency? Without triggers, ICP doesn't help pipeline timing
5. **Plan activation** — How does this become a qualification question? A targeting filter? A content brief?
6. **Build validation metrics** — How will we know if this ICP is right?

## References
- Gartner. ["The Framework for Ideal Customer Profile Development."](https://www.gartner.com/en/articles/the-framework-for-ideal-customer-profile-development) 2024.
- ZoomInfo. ["How to Create an Ideal Customer Profile."](https://pipeline.zoominfo.com/marketing/ideal-customer-profile) 2024.
- Userpilot. ["ICP Marketing: How to Find, Define, & Activate Your Ideal Customer Profile."](https://userpilot.com/blog/icp-marketing/) 2024.

## Skill Invocation Strategy

When invoked, guide the user through:
1. CRM analysis — who are your best customers and what do they have in common?
2. Customer research — what made them ready to buy?
3. Building each layer: firmographic → technographic → psychographic → triggers → anti-ICP
4. Documenting the primary ICP in the template
5. Planning activation across sales qualification and marketing targeting
6. Defining validation metrics

The goal is an ICP that's specific enough to immediately disqualify poor-fit accounts and sharpen targeting — not a description of who you've sold to before.
