---
name: messaging-architecture
description: Guides product marketers through building a complete messaging architecture that translates positioning into usable copy. Use when creating a new messaging framework, refreshing messaging that isn't resonating, or aligning messaging across teams. Produces a layered hierarchy from company-level story through messaging pillars to proof points, with audience variants. Requires positioning work first — use dunford-positioning if positioning is unclear. Do NOT use for sales pitch creation (use dunford-sales-pitch or raskin-pitch).
compatibility: Works across Claude.ai, Claude Code, and API. No external tools or MCP servers required.
metadata:
  author: Scott Bailey
  version: 1.0.0
  category: product-marketing
---

# Messaging Architecture Skill

## Overview
A messaging architecture is the structured system of words and claims that translates positioning into actual copy. Positioning answers "where do we play and how do we win?" Messaging architecture answers "what do we say, to whom, and in what order?" Without one, every team member writes their own version of the company story. With one, messaging is consistent, layered, and purposeful.

## When to Use This Skill
- Positioning work is done but messaging feels inconsistent across teams
- Website, sales decks, and demand gen assets tell different stories
- Entering a new market or audience segment, or post-rebrand/pivot
- Sales reps are writing their own pitches because official messaging doesn't land
- Refreshing messaging that isn't resonating with target buyers

**Prerequisite:** messaging builds on positioning. If positioning isn't clear — the market category, target customer, competitive alternatives, unique attributes, and value themes — run `dunford-positioning` first. Messaging architecture without positioning is decoration without architecture.

## Approach
Work through the layers top-down: confirm the positioning foundation, develop the company-level message, expand it into the value proposition, identify and name pillars, audit proof, then build audience variants and run the coherence test. Interview the user as you go rather than generating a document from assumptions — first answers are usually too vague; probe for specificity, but recognize a real answer when you hear one. Challenge generic language ("better" than what? "powerful" how?), and if the product's positioning turns out to be unsettled mid-conversation, say so and route back to positioning work.

## The Five Layers

```
Layer 1: Company-Level Message   (the headline — what we do and for whom)
Layer 2: Primary Value Proposition (what transformation we enable)
Layer 3: Messaging Pillars (3-4)  (the main themes that prove our value)
Layer 4: Proof Points             (evidence that each pillar is true)
Layer 5: Audience Variants        (how the message shifts by buyer)
```

Each layer serves a different purpose and audience: the company-level message is for awareness, pillars for evaluation, proof points for conviction, variants for personalization.

### Layer 1: Company-Level Message
The single most important thing someone should understand about the company. It identifies the target customer and their context, names the outcome or transformation, signals the category, and is specific enough to be believed while broad enough to cover all products and segments.

Three common archetypes:
- **The Transformation Statement** — company + target + outcome + higher-order goal
- **The Category Claim** — company as the [category] for [target who cares about this]
- **The Contrast Statement** — our approach instead of the old approach

A useful test: would a competitor be embarrassed to use your line with their name swapped in? If any competitor could say it comfortably, it's too generic.

Red flags to challenge:
- "We help companies do [thing] better" — better than what? for whom?
- Category jargon ("enterprise SaaS platform") that means nothing to a buyer
- Too many and/ors — picking three things means picking none
- Features dressed up as outcomes ("powerful analytics" is not an outcome)

### Layer 2: Primary Value Proposition
Expands the company message into 2-4 sentences: acknowledge the problem or old way, name the transformation, describe the outcome. This becomes the most important paragraph on the homepage and in the pitch — enough for a target buyer to decide whether to learn more.

Common failures: too long (a paragraph plus bullets is a section, not a value prop); too abstract ("transform the way you work"); future tense ("will enable you to..." — if it can't be said in present tense, it isn't real yet); self-referential ("our platform provides..." — focus on the customer, not the product).

### Layer 3: Messaging Pillars
The 3-4 supporting themes that prove the value proposition is real. Each pillar addresses a distinct value theme, is defensible and differentiated, connects directly to the value proposition, and has proof behind it.

Name pillars for what they enable, not what they are:
- "Real-time buying signals" is a feature. "Stop guessing who to call" is a pillar.

For each pillar, develop an outcome-focused headline, a supporting claim of a sentence or two, proof points, and the feature or capability that delivers it. If two pillars feel similar, they're probably one. Worth probing: if these three pillars are all true, does the value proposition follow? Which competitors could claim the same pillar, and can you still own it through proof?

### Layer 4: Proof Points
The most underinvested layer. Without proof, pillars are just claims.

Types of proof:
- **Customer outcomes** — specific, quantified results from real customers
- **Comparative data** — outcomes vs. before, or vs. the alternative
- **Volume/adoption proof** — how many customers, how much usage
- **Third-party validation** — analyst recognition, awards, certifications
- **Process proof** — the mechanism that makes the outcome possible, not just the result

Evaluating proof: is it specific ("customers see results" is not proof; "customers cut onboarding time 40%" is)? Believable — extraordinary claims need extraordinary proof? Relevant to this pillar? Current?

Run a proof audit: for each pillar, list the proof that exists, flag what's missing, and make a plan to close the gaps (usually customer interviews or case-study work). A proof point without a source isn't a proof point.

### Layer 5: Audience Variants
The core hierarchy stays consistent; emphasis, language, and proof shift by audience. Common variant dimensions: role (economic buyer vs. practitioner), segment (enterprise vs. mid-market vs. SMB), vertical, buying stage, and competitive situation.

Variant principles:
- Don't change the pillars — change the emphasis, language, and proof
- Economic buyers care about business outcomes and risk; practitioners care about their day-to-day
- Match vocabulary to how each audience describes the problem, not how you describe the solution
- The more specific the variant, the more effective — and the more work

Worth probing: what does the economic buyer worry about that the practitioner doesn't? What does a practitioner need to hear to bring this to leadership?

## The Coherence Test

Once the full architecture is built, test it:

1. **Does each pillar prove the value proposition?** If the pillars are all true, does the value proposition follow?
2. **Does the company message accurately summarize the pillars?** Would the company message plus the pillar headlines tell a coherent story?
3. **Do proof points address likely skepticism?** What would a skeptical prospect challenge, and is there proof for it?
4. **Do audience variants stay true to the core?** Each variant should feel like the same product through a different lens, not a different product.
5. **Could a competitor use this messaging?** If yes, it's not differentiated enough.

## Deliverable Shape

A messaging architecture is a document. A sensible default structure:

```
# [Product/Company] Messaging Architecture
Version / owner / last updated

## Company-Level Message
One sentence: target customer + outcome + category signal.

## Primary Value Proposition
2-4 sentences: problem/old way → transformation → outcome.

## Messaging Pillars (3-4)
Per pillar: outcome-focused headline, 1-2 sentence claim,
specific proof points, enabling feature/capability.

## Audience Variants
Per role/segment: lead pillar, key language shifts, primary proof.

## Proof Gaps
Missing proof and the plan to get it.

## What This Messaging Is NOT
Claims we're not making, audiences we're not targeting,
competitor positions we're not trying to occupy.
```

## Common Pitfalls

**Messaging as a writing exercise.** Polished language nobody verified with buyers. Share drafts with sales reps and 2-3 customers before finalizing — "does this sound like your problem?" is the test.

**Pillar proliferation.** Six pillars that cover everything and prove nothing. More than four means combine or cut: what are the three things you most want a buyer to believe?

**Value proposition that's really a mission statement.** "We believe every team deserves better tools" is for your team, not buyers. A value proposition should make a buyer think "yes, this is for me."

**Audience variants that change the core.** If segments need completely different stories, that's a positioning problem, not a messaging problem.

**Messaging that lives in a document.** The architecture is only valuable if it makes writing faster. Give copywriters, SDRs, and sales clear guidance on how to use it — and validate the language with sales, CS, and execs rather than creating it in a vacuum.

## References
- Aventi Group. ["Messaging Framework."](https://aventigroup.com/blog/messaging-framework/) 2024.
- Wynter. ["Why You Need a Messaging Hierarchy."](https://wynter.com/post/messaging-hierarchy) 2024.
- Cascade Insights. ["What is a Messaging Framework?"](https://www.cascadeinsights.com/what-is-a-messaging-framework) 2024.
- Product School. ["Product Messaging Framework."](https://productschool.com/blog/product-marketing/product-messaging-framework) 2024.
