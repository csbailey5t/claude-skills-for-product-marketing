---
name: launch-planning
description: Guides product marketers through planning and executing product launches. Use when scoping a launch, building a launch brief, aligning cross-functional teams, or creating the launch asset plan. Covers launch tiering, goal-setting, stakeholder alignment, asset planning, and success measurement. Based on T1/T2/T3 launch tiering and Martina Lauchengco's LOVED framework.
compatibility: Works across Claude.ai, Claude Code, and API. No external tools or MCP servers required.
metadata:
  author: Scott Bailey
  version: 1.0.0
  category: product-marketing
---

# Product Launch Planning Skill

## Overview
This skill helps product marketers plan and execute launches that actually move the business. Most launches fail not because of bad products or bad marketing, but because of misaligned expectations, unclear goals, and assets created for their own sake rather than to drive a specific outcome. The framework starts with the question most teams skip: what does success look like, and what tier of launch is right for this?

## When to Use This Skill
- A product, feature, or major update is being released
- Engineering/product is asking "when are we launching this?"
- Launch goals, ownership, or assets are unclear or contested
- Cross-functional alignment is breaking down
- Planning a quarterly launch calendar
- Post-mortem of a launch that didn't land

## Core Insight: Launches Fail at the Scoping Stage

Most launch problems trace back to one of two failures:
1. **Over-investing in small launches** — building a PR campaign for a minor feature update, burning resources on things that don't move metrics
2. **Under-investing in big launches** — treating a category-defining product as a minor release, missing the window to create market momentum

The tiering decision — made before any work begins — determines resource allocation, asset requirements, timeline, and success criteria. Getting the tier right is the most important launch planning decision.

## Launch Tiers

### Tier 1: Landmark Launch
A major market moment. Everything fires. Cross-functional, externally visible, executive-sponsored.

**When to use T1:** New product that creates a new revenue line; major repositioning or category entry; feature set that changes competitive dynamics; strategic company milestone (first enterprise offering, international expansion).

**T1 indicators:** CEO/exec is involved and accountable; press and analyst relations activated; customer events, webinars, or keynote moments; pipeline and revenue goals attached; multi-quarter preparation window needed.

**T1 typical assets:** press release and media outreach; analyst briefings; executive keynote or launch event; new or heavily updated website section; full sales enablement package (deck, demo, battlecard, objection handling); customer story built for the launch; demand gen campaign (paid, email, webinar); customer and partner comms; launch video or demo film; social campaign.

### Tier 2: Notable Launch
Externally visible, generates awareness and pipeline, but scoped to core marketing channels without PR and executive events.

**When to use T2:** Significant feature expansion that expands ICP or use cases; feature addressing a top customer request across many accounts; capability that creates new competitive advantage; update that materially changes product value for a large customer segment.

**T2 typical assets:** blog post or product update announcement; updated website section or landing page; sales enablement update (email templates, FAQ, demo talking points); customer communications to affected users; social posts; a demand gen touchpoint or two (email or webinar); optionally a short video or GIF demo.

### Tier 3: Ongoing Release
Minimal external communication. Updates existing customers, keeps sales informed, no outbound push.

**When to use T3:** Bug fixes with meaningful customer impact; small UX improvements; updates to existing features; backend improvements customers won't notice directly.

**T3 typical deliverables:** in-app notification or release notes; internal sales bulletin or Slack update; updated support documentation; changelog entry.

### The Tier Decision

Questions that determine the tier:
1. Does this create net-new revenue opportunity? (T1 indicator)
2. Does this change the competitive landscape? (T1 or T2)
3. Does this affect a majority of our customers? (T2 if yes, T3 if narrow)
4. Is there press-worthy news here? (T1 only)
5. What's the pipeline/revenue goal this launch is meant to support? (T1 or T2 if there's a goal, T3 if not)

Common misalignments worth challenging:
- "We want T1 impact with T3 resources" — doesn't exist, pick one
- Product team wants every release treated as major — push back on scoping
- "We'll do a small launch and see how it goes" — if there's a revenue goal, there's no such thing as a small launch for that
- "The CEO wants a big announcement" — does the product merit it? Overpromising is worse than under-promoting.

## The Launch Brief

Every T1 and T2 launch needs a launch brief — the single source of truth every cross-functional team references. Write it before any assets; brief alignment prevents asset rework. Its sections:

1. **The who and why** — what problem this solves, for whom specifically, what changes for them, why now vs. six months ago
2. **Goals and success metrics** — primary and secondary goals, how success is measured and by when, what good vs. great looks like
3. **The launch story** — the one-sentence announcement, the narrative (why now, why us, what's next), what we're NOT saying, top objections to handle
4. **Target audiences** — external (segments, prospects, press, analysts) and internal (sales, CS, support, exec, partners), and what each needs to know, believe, or do
5. **Asset plan and owners** — assets with owner, due date, and purpose; channel plan; dependencies
6. **Timeline and launch date** — T-minus milestones working backward from launch day
7. **Risks and contingencies** — what could go wrong, rollback or pivot plans, what happens if the product isn't ready

## Cross-Functional Alignment

Launches fail in handoffs. Each team has something it needs, something it owns, and a readiness checkpoint:

| Team | Needs | Owns | Readiness checkpoint |
|------|-------|------|----------------------|
| Product | Final spec, known limitations | Availability, release notes | Feature complete and stable |
| Sales | Pitch narrative, objection handling, demo | First deals, customer notification (T1) | Enablement reviewed and trained |
| Customer Success | Customer comms, FAQ, known impacts | Existing customer notification, renewal narrative | High-risk accounts prepped |
| Support | Known issues, FAQ, escalation path | Support docs, training | Deflection content live |
| Marketing | Full launch brief | Campaign execution | Assets approved and scheduled |
| Comms/PR (T1) | Press materials | Embargo management, distribution | Journalists briefed, embargo held |
| Leadership | Launch story, approval | Exec amplification | Aligned on narrative |

For contested decisions — launch tier, launch date, external messaging, pricing/packaging, go/no-go — a lightweight RACI (who is Responsible, Accountable, Consulted, Informed) prevents ambiguity. Which roles fill which slots depends on the org; the point is that each decision has exactly one accountable owner agreed in advance.

## The Asset Plan

Don't create assets — create assets with purpose. For every asset, answer:
- **Purpose**: What specific action or belief does this enable?
- **Audience**: Who specifically reads/watches/uses this?
- **Channel**: Where does it live and how does it get distributed?
- **Due date**: When must it be final (not "ready for review")?
- **Owner**: Who is accountable for completing it?

**The go-to-market moment map.** Trace the customer/prospect journey and identify the moments where assets need to exist:

```
AWARENESS MOMENT:
  Where will prospects first hear about this?
  Assets: press release / blog / social / email

EVALUATION MOMENT:
  What do prospects/customers do when they want to learn more?
  Assets: landing page / one-pager / demo video

CONVERSATION MOMENT:
  What do sales reps need when this comes up in a call?
  Assets: talking points / objection handling / updated deck

DECISION MOMENT:
  What do economic buyers need to get comfortable?
  Assets: ROI model / case study / security review

ADOPTION MOMENT (existing customers):
  How do existing customers learn about and activate this?
  Assets: in-app notification / email / CSM talking points
```

## The Launch Timeline

Work backward from launch day. A typical T1 shape looks something like this — treat it as an illustrative default to compress or stretch, not a schedule to enforce:

- **~8 weeks out**: brief approved by all stakeholders, tier confirmed, launch date set, asset plan complete with owners
- **~6 weeks out**: messaging finalized, sales enablement in draft, PR/analyst strategy confirmed
- **~4 weeks out**: draft assets in review, sales training scheduled, embargo briefings begin, customer comms drafted
- **~2 weeks out**: assets final and approved, sales training complete, support docs live, customer comms scheduled
- **Final week**: go/no-go decision, sales bulletins sent, embargo reminders, launch-day war room set up
- **Launch day**: assets live per schedule, exec amplification, monitoring (mentions, traffic, signups, deal activity), real-time response plan active
- **A couple of weeks after**: metrics review, sales feedback, support ticket review, retrospective

T2 launches follow the same backward-planning logic on a shorter runway.

## Success Measurement

Define success before you launch — you can't measure success you didn't define.

- **T1**: pipeline directly attributable to the launch (by a specific date), press coverage (outlets, reach, sentiment), analyst engagement, landing page traffic, trial/demo/signup conversion, social reach and share of voice
- **T2**: email campaign engagement, blog traffic, demo requests attributed to launch, feature adoption in the first month, sales usage of launch assets
- **T3**: release notes views, support ticket volume for the affected feature (should decrease), in-app notification click-through

**Common measurement mistakes:**
- Measuring activity (emails sent, posts published), not outcomes
- No baseline to compare to: "traffic went up" — from what?
- Measuring too early — pipeline impact typically takes a month or more to show
- Attributing everything to the launch that was already in motion

## The Go/No-Go Decision

Shortly before launch, make an explicit go/no-go decision rather than drifting into launch day. Go requires: product stable and feature-complete for the launch scope; assets final and approved; sales trained; CS has prepped high-risk accounts; support has docs and escalation paths; embargo intact (T1); leadership aligned on narrative; a rollback plan exists. Delay if a critical bug is discovered, a major customer incident is unresolved, a key stakeholder isn't aligned on messaging, core assets aren't done, or sales isn't trained.

## Output: Launch Brief Template

```
# [Product/Feature Name] Launch Brief
Tier: [T1 / T2 / T3]
Launch Date: [Date]
PMM Owner: [Name]

## One-Sentence Announcement
[What we're launching, for whom, and why it matters]

## Business Context
Problem we're solving: [For the customer]
Why now: [Why this moment matters]
Strategic importance: [Why this matters for the business]

## Goals and Success Metrics
Primary goal: [Specific outcome]
Success looks like: [Specific metrics, timeframe]
Stretch goal: [Best case]
Minimum bar: [What would make this worthwhile]

## Target Audiences
External: [Segment]: what they need to know/do
Internal: Sales / CS / Support: what each needs

## Launch Story
Headline message: [What we're saying]
Supporting narrative: [Why now, why us]
What we're NOT saying: [Out-of-scope]
Top questions/objections: [And how we address them]

## Asset Plan
| Asset | Purpose | Audience | Owner | Due Date | Channel |
|-------|---------|----------|-------|----------|---------|

## Timeline
[Key milestones working backward from launch day]

## Risks and Contingencies
Risk: [What could go wrong] → Plan: [What we'd do]

## Go/No-Go Criteria
[Must-be-true conditions]

## Stakeholder Sign-off
PMM | Product | Sales | CS | Leadership
```

## Common Pitfalls

**The launch date is really the ship date.** Engineering ships code; marketing launches the product. Separate the "available" date from the "launch" date — products can launch weeks or months after they ship, and the launch date should be a joint product/marketing decision based on readiness, not build completion.

**"Everyone" is the target audience.** The launch message tries to speak to developers, executives, and end users simultaneously. Pick the primary audience for the launch moment; serve others separately.

**Launch = blog post.** A T2 product ships, PMM writes a blog, nothing else happens. Every T2 launch needs a distribution plan, not just an asset plan. Who will read the blog? How will they find it?

**Post-launch silence.** Huge effort up to launch, immediate drop-off after. Plan the 30-day post-launch nurture — launches create awareness; campaigns drive conversion.

**No stakeholder alignment on goals.** PMM measures press coverage, product measures adoption, sales measures pipeline. The goals section of the brief must be agreed before work begins.

**Skipped internal enablement.** The most common failure mode: great external launch, sales doesn't know how to talk about it.

**Over-scoping.** A T2 launch done well beats a T1 launch done poorly.

## Working With Someone on a Launch

Start with the tier decision and challenge the scope — is this really T1, or over-investment in a T2? Force goal specificity ("awareness" is not a goal — what number, by when?). Then build the brief, the asset plan (every asset with an audience, channel, and purpose), the backward timeline, and agreement on what good looks like before launch day. The goal is a launch that moves a business metric, not just a date on a calendar where content goes live.

## References
- Lauchengco, Martina. *Loved: How to Rethink Marketing for Tech Products.* 2022.
- Product Marketing Alliance. ["Launch Tier Framework."](https://www.productmarketingalliance.com/launch-tier-framework/) 2024.
- PMM Camp Newsletter. ["Tiers Over Tears."](https://newsletter.pmmcamp.com/p/edition-28) 2023.
- LaunchNotes. ["The Ultimate Product Launch Plan."](https://www.launchnotes.com/blog/the-ultimate-product-launch-plan-for-new-product-marketers) 2024.
