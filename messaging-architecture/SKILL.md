---
name: messaging-architecture
description: Guides product marketers through building a complete messaging architecture that translates positioning into usable copy. Use when creating a new messaging framework, refreshing messaging that isn't resonating, or aligning messaging across teams. Produces a layered hierarchy from company-level story through messaging pillars to proof points, with audience variants.
---

# Messaging Architecture Skill

## Overview
This skill helps product marketers build a complete messaging architecture — the structured system of words and claims that translates positioning into actual copy. Positioning answers "where do we play and how do we win?" Messaging architecture answers "what do we say, to whom, and in what order?"

Without a messaging architecture, every team member writes their own version of the company story. With one, messaging is consistent, layered, and purposeful.

## When to Use This Skill
- Positioning work is done but messaging feels inconsistent across teams
- Different people describe the product differently
- Website, sales decks, and demand gen assets tell different stories
- Entering a new market or audience segment
- Post-rebrand or product pivot
- Sales reps are writing their own pitches because official messaging doesn't land
- Refreshing messaging that isn't resonating with target buyers

## The Messaging Architecture Structure

A complete messaging architecture has five layers, each building on the one above:

```
Layer 1: Company-Level Message
         (The headline — what we do and for whom)
              ↓
Layer 2: Primary Value Proposition
         (What transformation we enable)
              ↓
Layer 3: Messaging Pillars (3-4)
         (The main themes that prove our value)
              ↓
Layer 4: Proof Points
         (Evidence that each pillar is true)
              ↓
Layer 5: Audience Variants
         (How the message shifts for different buyers)
```

**Key Principle:** Each layer serves a different purpose and a different audience. The company-level message is for awareness. Pillars are for evaluation. Proof points are for conviction. Variants are for personalization.

## Systematic Development Process

### Phase 1: The Foundation

**Before building messaging, confirm you have positioning.**

If positioning isn't clear, run `/dunford-positioning` first. Messaging architecture without positioning is decoration without architecture.

From positioning, extract:
- What is the market category?
- Who is the target customer (specifically)?
- What are the competitive alternatives?
- What are the unique attributes?
- What are the value themes?

**Claude should ask:**
- "Walk me through your current positioning. Who is this for, what alternatives exist, and what unique value do you deliver?"
- "What's the one thing customers who love you understand that customers who don't understand?"
- "If you had to describe your company in one sentence to someone who'd never heard of you, what would you say?"

### Phase 2: The Company-Level Message

**Key Question:** What is the single most important thing we want someone to understand about us?

This is the message at the top of the hierarchy. It should:
- Identify the target customer and their context
- Name the outcome or transformation you enable
- Signal the category you compete in
- Be specific enough to be believed, broad enough to apply across all products/segments

**Types of company-level messages:**

**The Transformation Statement:**
"[Company] helps [target] [achieve outcome] so they can [higher-order goal]."

**The Category Claim:**
"[Company] is the [category] for [target customer who cares about this]."

**The Contrast Statement:**
"[Company] gives [target] [our approach] instead of [old approach]."

**Ask these questions:**
- What's the headline outcome customers achieve?
- Does this message work for every customer segment you care about?
- Would your best customer nod at this?
- Would a competitor be embarrassed if you used their company name instead of yours? (If not, it's too generic)

**Red Flags to Challenge:**
- "We help companies do [thing] better" — better than what? who?
- Category jargon: "enterprise SaaS platform" means nothing
- Too many and/ors: picking three things means picking none
- Features dressed up as outcomes: "powerful analytics" is not an outcome

**Example Output:**
```
Company-Level Message Options:

Option A (Transformation):
"[Company] helps revenue teams turn buyer signals into pipeline before competitors
do — without adding headcount or tools."

Option B (Category Claim):
"[Company] is the buyer intent platform for B2B teams that need to know
who's in-market right now, not who exists."

Option C (Contrast):
"[Company] gives sales teams real-time buying signals instead of static
contact databases — so they reach the right buyers at the right moment."

Recommended: Option C. It names the contrast clearly, is differentiated from
ZoomInfo/Apollo, and is specific to the pain we solve.
```

### Phase 3: Primary Value Proposition

**Key Question:** What's the fuller story — the setup, the transformation, and the outcome?

The primary value proposition expands the company message into 2-4 sentences. It should:
- Acknowledge the problem or old way
- Name the transformation you enable
- Describe the outcome customers reach
- Give someone enough to decide if they want to learn more

This becomes the most important paragraph on your homepage and in your pitch.

**Ask these questions:**
- What was life like before your product? What's broken about the old way?
- What do you uniquely make possible?
- What does success look like for customers who use you well?
- Can a target buyer read this and immediately know it's for them?

**Common Failures:**
- Too long: If it's a paragraph plus bullet points, it's not a value proposition — it's a section
- Too abstract: "Transform the way you work" — doing what, for whom?
- Future tense: "Will enable you to..." — if you can't say it in present tense, it's not real yet
- Self-referential: "Our platform provides..." — focus on the customer, not the product

**Example Output:**
```
Primary Value Proposition:

"Most sales teams are guessing who to call. They blast the same outreach
to thousands of contacts and hope to catch someone at the right moment.

[Company] identifies which companies are actively researching solutions
like yours right now — and surfaces the right contacts at those accounts.
So instead of spray-and-pray, your team focuses on buyers who are already
in-market, reaching them before competitors do.

The result: faster pipeline, shorter sales cycles, and a team that knows
its next move every morning."
```

### Phase 4: Messaging Pillars

**Key Question:** What are the 3-4 themes that prove our value proposition is real?

Messaging pillars are the main supporting claims. Each pillar should:
- Address a distinct value theme (not the same benefit rephrased)
- Be defensible and differentiated (ideally unique to you, or at least where you lead)
- Connect directly to the value proposition
- Have proof points to support it

**How to identify pillars:**
1. List the unique value themes from your positioning
2. Group them into 3-4 distinct themes (not 8 individual features)
3. Ask: does this pillar matter to our target customer? Can we prove it? Does it differentiate us?
4. Name each pillar with outcome language, not feature language

**Pillar naming principles:**
- Name pillars for what they enable, not what they are
- "Real-time buying signals" is a feature. "Stop guessing who to call" is a pillar.
- "AI-powered" is a capability. "Your team knows their next move" is a pillar.

**For each pillar, develop:**
- Pillar headline (outcome-focused, 5-8 words)
- Supporting claim (1-2 sentences expanding the headline)
- 3-5 proof points (specific evidence)
- Feature or capability that delivers this pillar

**Ask these questions:**
- If these are our 3 pillars, do they collectively prove the value proposition?
- Does each pillar address a different buyer concern?
- Are any pillars overlapping? Could two become one?
- Which competitors can also claim this pillar? Can we still own it through proof?

**Example Output:**
```
Messaging Pillar 1: "Know who's buying before they raise their hand"
Claim: [Company] surfaces intent signals from companies researching your
       category right now — not after they fill out a form.
Delivers: Primary value prop promise of reaching buyers before competitors
Evidence:
  • 12+ behavioral signals tracked across company and contact level
  • Average 47-day buying window captured before competitors
  • [Customer] identified 67 in-market accounts that never engaged inbound

Messaging Pillar 2: "Stop wasting outreach on the wrong accounts"
Claim: Reps spend 60% of their time on prospects who'll never buy.
       [Company] focuses effort on the accounts most likely to close.
Delivers: Efficiency and pipeline quality outcomes
Evidence:
  • Average 3x improvement in response rates for intent-targeted outreach
  • [Customer] reduced outreach volume 35% while increasing pipeline 40%
  • Intent-prioritized accounts close 2.3x faster on average

Messaging Pillar 3: "Your whole team moves from one prioritized signal"
Claim: [Company] routes buying signals into your existing workflow —
       CRM, sequences, alerts — so the right rep acts at the right moment.
Delivers: Speed-to-contact, reduces manual overhead
Evidence:
  • Native integrations with [CRM 1], [CRM 2], [Outreach/Salesloft]
  • [Customer] reduced research time from 3 hours/rep/day to 20 minutes
  • Signals route to CRM automatically; no manual list-building
```

### Phase 5: Proof Points

**Key Question:** What evidence makes each pillar believable?

Proof points are the most underinvested layer in most messaging architectures. Without proof, pillars are just claims.

**Types of proof points:**
- **Customer outcomes**: Specific, quantified results from real customers
- **Comparative data**: How outcomes compare to before/alternative
- **Volume/adoption proof**: How many customers, how much usage
- **Third-party validation**: Analyst recognition, awards, certifications
- **Process proof**: What makes the outcome possible (mechanism, not just result)

**Evaluating proof points:**
- Is it specific? "Customers see results" is not proof. "Customers reduced X by 40%" is.
- Is it believable? Extraordinary claims need extraordinary proof.
- Is it relevant to this pillar? Proof for the wrong thing doesn't help.
- Is it current? Proof from 3 years ago may be outdated.

**Ask these questions:**
- Do we have at least 3 proof points per pillar?
- Can we attribute the outcome to our specific differentiator, not just "using our product"?
- Do we have proof for enterprise AND mid-market (if we serve both)?
- What proof do we wish we had and how do we get it?

**Example Output:**
```
Proof Point Audit:

Pillar 1 ("Know who's buying"):
✓ 12+ signals tracked — documented in product
✓ 47-day average window — based on customer data, publishable
✗ Missing: a named customer quote about discovering in-market accounts

Pillar 2 ("Stop wasting outreach"):
✓ 3x response rate improvement — aggregate across customer base
✓ [Customer name] case study with 35%/40% data
✗ Missing: proof that connects specifically to intent signals, not just our product generally

Pillar 3 ("Whole team moves"):
✓ Integration list verifiable
✓ [Customer] time savings quote
✗ Missing: proof of signal routing speed/reliability at scale

Gap plan: 3 customer interviews needed. Target: [Customer A] (Pillar 1), [Customer B] (Pillar 2 specificity), [Customer C] (Pillar 3 enterprise scale).
```

### Phase 6: Audience Variants

**Key Question:** How does the message need to shift for different buyers?

The core message hierarchy stays consistent. But emphasis, language, and proof shift by audience.

**Common variant dimensions:**
- **Role**: Economic buyer (CFO/CRO/VP) vs. practitioner (sales rep, SDR, RevOps)
- **Segment**: Enterprise vs. mid-market vs. SMB
- **Vertical**: Different industries with different proof and terminology
- **Stage**: Awareness-stage buyer vs. late-stage evaluator
- **Competitive situation**: Against no solution vs. against a specific competitor

**Variant principles:**
- Don't change the pillars — change the emphasis, language, and proof
- Economic buyers care about business outcomes and risk; practitioners care about their day-to-day
- Match vocabulary to how they describe the problem, not how you describe your solution
- The more specific the variant, the more effective (but the more work)

**Ask these questions:**
- What does the economic buyer worry about that the practitioner doesn't?
- What does a practitioner need to hear to bring this up to leadership?
- What language do different roles use for the same problem?
- Are there segments where different pillars become most important?

**Example Output:**
```
Audience Variants:

VP of Sales / CRO:
Primary concern: Pipeline coverage, quota attainment, rep productivity
Lead with: Pillar 2 ("Stop wasting outreach") — ROI, efficiency, pipeline math
Language: "pipeline coverage," "rep productivity," "cost per pipeline dollar"
Proof: Revenue outcomes, pipeline metrics, ROI calculations
De-emphasize: Technical integration details (that's for RevOps)

Sales Rep / SDR:
Primary concern: Who to call, what to say, hitting number
Lead with: Pillar 3 ("Your whole team moves") — daily workflow, clarity
Language: "know exactly who to call," "get a signal in your CRM every morning"
Proof: Individual rep productivity stories, time savings
De-emphasize: Company-level ROI metrics (not their problem)

RevOps / Sales Operations:
Primary concern: CRM hygiene, integration complexity, workflow reliability
Lead with: Pillar 3 details — integrations, routing rules, data quality
Language: "no manual entry," "clean data," "automated routing"
Proof: Integration specs, uptime/reliability, implementation time
De-emphasize: Sales outcomes until after they're satisfied with technical fit
```

## The Coherence Test

Once the full architecture is built, test for coherence:

1. **Does each pillar prove the value proposition?** If the pillars are all true, does the value proposition follow?
2. **Does the company message accurately summarize the pillars?** Would reading the company message and the three pillar headlines tell a coherent story?
3. **Do proof points address likely skepticism?** What would a skeptical prospect challenge, and do you have proof for it?
4. **Do audience variants stay true to the core?** Each variant should feel like the same product told through a different lens, not a different product.
5. **Could a competitor use this messaging?** If yes, it's not differentiated enough.

## Output Template

```
# [Product/Company] Messaging Architecture
Version: [X.X] | Owner: [PMM name] | Last updated: [Date]

---

## Company-Level Message
[One sentence. Target customer + outcome + category signal.]

---

## Primary Value Proposition
[2-4 sentences. Problem/old way → transformation → outcome.]

---

## Messaging Pillars

### Pillar 1: [Outcome-focused headline]
Claim: [1-2 sentences expanding the headline]
Proof:
  • [Specific evidence]
  • [Specific evidence]
  • [Specific evidence]
Enabling feature/capability: [What makes this possible]

### Pillar 2: [Outcome-focused headline]
Claim: [1-2 sentences]
Proof:
  • [Specific evidence]
  • [Specific evidence]
  • [Specific evidence]
Enabling feature/capability: [What makes this possible]

### Pillar 3: [Outcome-focused headline]
Claim: [1-2 sentences]
Proof:
  • [Specific evidence]
  • [Specific evidence]
  • [Specific evidence]
Enabling feature/capability: [What makes this possible]

---

## Audience Variants

### For [Role/Segment A]
Lead pillar: [Pillar X]
Key language shift: [How vocabulary changes]
Primary proof: [Which proof points resonate most]

### For [Role/Segment B]
Lead pillar: [Pillar X]
Key language shift: [How vocabulary changes]
Primary proof: [Which proof points resonate most]

---

## Proof Gaps
Missing proof we need to close:
• [Gap 1] — plan to get it: [how]
• [Gap 2] — plan to get it: [how]

---

## What This Messaging Is NOT
• [Claim we're explicitly not making]
• [Audience we're explicitly not targeting]
• [Competitor position we're not trying to occupy]
```

## Best Practices

### Do's
- **Build on positioning, not instead of it** — If positioning isn't clear, do that first
- **Name pillars for outcomes** — What does the customer get, not what the product does
- **Gather real proof before finalizing** — Placeholder proof is worse than no proof
- **Create audience variants** — One message for everyone is a message for no one
- **Test with real buyers** — Read the value proposition to a customer and watch their reaction

### Don'ts
- **Don't create messaging in a vacuum** — Sales, CS, and execs should validate the language
- **Don't over-engineer it** — Three pillars done well beats five pillars weakly supported
- **Don't use internal language** — Your category jargon isn't your buyer's category jargon
- **Don't confuse features with pillars** — "AI-powered" is not a pillar. What does AI enable the customer to do?
- **Don't skip the proof audit** — Pillars without proof are just claims

## Common Pitfalls

**Pitfall 1: Messaging as a writing exercise**
Creating polished language without verifying whether it resonates with buyers
→ Solution: Share drafts with sales reps and 2-3 customers before finalizing. "Does this sound like your problem?" is the test.

**Pitfall 2: Pillar proliferation**
Six pillars that cover everything, prove nothing specific
→ Solution: If you have more than four pillars, combine or cut. What are the three things you most want a buyer to believe?

**Pitfall 3: Value proposition that's really a mission statement**
"We believe every team deserves better tools" — that's not a value proposition
→ Solution: A value proposition is for buyers, not your team. It should make them think "yes, this is for me."

**Pitfall 4: Audience variants that change the core**
Different segments get completely different stories
→ Solution: Variants should shift emphasis and language, not create separate narratives. If segments need completely different stories, you may have a positioning problem, not a messaging problem.

**Pitfall 5: Messaging that lives in a document**
A beautiful messaging architecture that no one uses
→ Solution: The architecture is only valuable if it makes writing faster. Create clear guidance for how copywriters, SDRs, and sales use it.

## Interactive Approach

When guiding someone through this framework, Claude should:

1. **Verify positioning exists** — Don't build on sand; confirm the positioning foundation
2. **Challenge generic language** — "Better" than what? "Powerful" how? Force specificity
3. **Push for three distinct pillars** — If two pillars feel similar, they're probably one
4. **Demand real proof** — A proof point without a source isn't a proof point
5. **Build audience variants** — Who is the economic buyer vs. the practitioner?
6. **Test coherence** — Read the architecture back as a story: does it hold together?

## References
- Aventi Group. ["Messaging Framework."](https://aventigroup.com/blog/messaging-framework/) 2024.
- Wynter. ["Why You Need a Messaging Hierarchy."](https://wynter.com/post/messaging-hierarchy) 2024.
- Cascade Insights. ["What is a Messaging Framework?"](https://www.cascadeinsights.com/what-is-a-messaging-framework) 2024.
- Product School. ["Product Messaging Framework."](https://productschool.com/blog/product-marketing/product-messaging-framework) 2024.

## Skill Invocation Strategy

When invoked, guide the user through:
1. Confirming the positioning foundation
2. Developing the company-level message through options and critique
3. Building the primary value proposition
4. Identifying and naming the 3-4 pillars with outcome language
5. Auditing proof points and identifying gaps
6. Developing audience variants for key buyer roles
7. Running the coherence test
8. Producing the complete messaging architecture document

The goal is a usable system that makes every person who writes about the product sound consistent — not a document that lives in a Google Drive folder.
