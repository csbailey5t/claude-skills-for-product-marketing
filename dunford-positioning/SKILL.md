---
name: dunford-positioning
description: Guides product marketers through April Dunford's systematic positioning framework from "Obviously Awesome". Use when positioning a new product, repositioning existing products, developing competitive positioning, clarifying market category, or creating positioning documents. Helps discover competitive alternatives, unique attributes, value propositions, target markets, and market categories through structured questioning.
---

# April Dunford Positioning Framework Skill

## Overview
This skill implements April Dunford's positioning methodology from "Obviously Awesome" to help product marketers systematically develop strong product positioning. The framework is built around five interdependent components that must be determined in a specific order.

## When to Use This Skill
- Positioning a new product or feature
- Repositioning an existing product
- Entering a new market segment
- Responding to competitive shifts
- Clarifying messaging that isn't resonating

## The Positioning Framework

Positioning consists of five components that build on each other in sequence:

1. **Competitive Alternatives** - What customers would do if your solution didn't exist
2. **Unique Attributes** - Features/capabilities you have that alternatives don't
3. **Value (and Proof)** - The business outcomes those attributes enable
4. **Target Market Characteristics** - Who cares most about that value
5. **Market Category** - The context that makes your value obvious

## Systematic Discovery Process

### Phase 1: Understanding Competitive Alternatives

**Key Question:** "What would customers use/do if our product didn't exist?"

Ask these questions:
- What did customers use before adopting your product?
- What do prospects currently use when they say "no" to you?
- What alternatives do customers mention when comparing options?
- Are there manual processes or DIY approaches customers would fall back on?
- Are there "do nothing" scenarios where customers just live with the problem?

**Important Notes:**
- Competitive alternatives are NOT the same as your sales competitors
- Include non-obvious alternatives like spreadsheets, manual processes, or simply accepting the status quo
- The goal is to understand the real decision context customers face

**Example Output:**
```
Competitive Alternatives for [Product]:
1. Manual process using spreadsheets and scripts
2. Building in-house solution with data engineering team
3. Using legacy ETL tool + separate activation tools
4. Point solutions for each individual use case
5. Not solving the problem (accepting data silos)
```

### Phase 2: Identifying Unique Attributes

**Key Question:** "What capabilities do we have that those alternatives don't?"

Ask these questions:
- What can customers do with our product that they can't do with alternatives?
- What do we make easier, faster, or more reliable?
- What technical capabilities differentiate us?
- What integration or ecosystem advantages do we have?
- What about our approach/architecture is fundamentally different?

**Important Notes:**
- Focus on attributes that are genuinely unique vs. alternatives identified in Phase 1
- Include both feature-level and architectural/approach-level differences
- Be specific and defensible - avoid generic claims
- Consider capabilities customers might not immediately recognize as valuable

**Example Output:**
```
Unique Attributes vs. Alternatives:
1. Direct reads/writes to customer's data warehouse (no data copying)
2. Reverse ETL architecture vs. traditional ETL
3. Git-based version control and CI/CD for data pipelines
4. No-code visual modeling interface for non-technical users
5. Real-time sync capabilities without infrastructure overhead
```

### Phase 3: Mapping Attributes to Value

**Key Question:** "What business value do these unique attributes enable?"

For each unique attribute, ask:
- What business problem does this solve?
- What outcome does this enable?
- How does this save time, money, or reduce risk?
- What strategic capability does this unlock?
- What pain does this eliminate?

**Important Notes:**
- Value should be outcome-focused, not feature-focused
- Connect technical attributes to business outcomes
- Consider different value themes (speed, cost, quality, risk, strategic enablement)
- Include proof points (metrics, customer quotes, case studies)
- Different attributes may ladder up to the same value theme

**Example Output:**
```
Attribute → Value Mapping:

Unique Attribute: Warehouse-native architecture
Value Theme: Data Freshness & Accuracy
- Eliminates data sync delays (real-time access)
- Single source of truth (no divergent copies)
- Reduced data engineering overhead (no ETL pipelines to maintain)
Proof: "Reduced time-to-activation from weeks to hours" - Customer X

Unique Attribute: Git-based version control
Value Theme: Operational Excellence
- Reduced risk of breaking changes
- Clear audit trail for compliance
- Faster development cycles
Proof: 50% reduction in rollback incidents
```

### Phase 4: Defining Target Market Characteristics

**Key Question:** "Who cares a LOT about this value?"

Ask these questions:
- What characteristics make someone care intensely about our value?
- What's happening in their business/role that makes this urgent?
- What pain are they currently experiencing?
- What buying triggers indicate they're ready for our solution?
- What makes them willing to change from their current alternative?

**Important Notes:**
- Focus on characteristics, not demographics
- Describe what makes them care, not just who they are
- Include both firmographic and psychographic attributes
- Consider the "best-fit" customer who gets maximum value
- This should feel narrow and specific, not broad

**Example Output:**
```
Target Market Characteristics:

Companies/Teams Who:
- Have data stored in modern cloud data warehouses (Snowflake, BigQuery, Databricks)
- Need to activate that data in 10+ downstream marketing/sales tools
- Experience delays with current ETL/data engineering approaches
- Have limited data engineering resources or want to reduce dependency
- Value data freshness and accuracy over cost optimization
- Are comfortable with warehouse-centric architecture
- Have mature data teams but want to empower business users

Buying Triggers:
- Recent warehouse migration
- Failed DIY activation projects
- Marketing/sales complaining about stale data
- Data engineering backlog growing unsustainably
```

### Phase 5: Selecting Market Category

**Key Question:** "What market context makes our value obvious to our target customers?"

Consider:
- What category do customers naturally compare us to?
- What category has buying patterns that match how customers buy our solution?
- What category allows us to win based on our unique attributes?
- Do we need to subcategorize or create a new category?
- What category name makes our differentiation clear?

**Important Notes:**
- Category choice affects buyer expectations and competitive set
- Sometimes you need to create a new subcategory or category
- The category should make your strengths obvious, not hidden
- Consider whether existing category names help or hurt you
- Test category names with customers to see if they resonate

**Example Output:**
```
Market Category Analysis:

Option 1: "Customer Data Platform (CDP)"
Pros: Established category, clear buying patterns
Cons: Implies data copying, batch processing, marketing-only focus

Option 2: "Reverse ETL"
Pros: Describes our unique architecture
Cons: Too technical, undefined buyer, emerging category

Option 3: "Data Activation Platform"
Pros: Broader than Reverse ETL, outcome-focused
Cons: Still emerging, requires education

Recommendation: Position as "Data Activation Platform" with explanation of how it differs from traditional CDPs (warehouse-native vs. data copying)
```

## Output Templates

### Complete Positioning Statement Template

```
For [target market with specific characteristics]
Who [have this compelling reason to buy]
[Product name] is a [market category]
That [provides this unique value/benefit]
Unlike [competitive alternatives]
We [key differentiator]
```

### Positioning Document Template

```
# [Product Name] Positioning

## Target Market
[Detailed description of characteristics and buying triggers]

## Market Category
[Category name and why it's the right context]

## Competitive Alternatives
[What customers would use/do without us]

## Unique Attributes
1. [Attribute]
2. [Attribute]
3. [Attribute]

## Value Themes
### [Theme 1]
- Enabled by: [attributes]
- Customer outcome: [specific value]
- Proof: [metrics/quotes]

### [Theme 2]
- Enabled by: [attributes]
- Customer outcome: [specific value]
- Proof: [metrics/quotes]

## Positioning Statement
[Complete statement using template above]

## Key Messages
1. [Message derived from positioning]
2. [Message derived from positioning]
3. [Message derived from positioning]
```

## Best Practices

### Do's
- **Work sequentially** - Each component builds on the previous one
- **Talk to customers** - Real customer language beats assumptions
- **Be specific** - "Data teams at high-growth B2B SaaS companies" beats "enterprises"
- **Test positioning** - Does it resonate with prospects? Does sales use it?
- **Focus value on outcomes** - "Reduce time to market" not "fast syncs"
- **Challenge assumptions** - Your assumed competitors might not be the real alternatives

### Don'ts
- **Don't skip the alternatives step** - It's the foundation for everything else
- **Don't confuse features with value** - "Real-time syncs" is a feature, "up-to-date customer data" is value
- **Don't make target market too broad** - Better to own a small segment than poorly serve everyone
- **Don't force a category** - If existing categories don't fit, consider creating a new one
- **Don't anchor on your sales competitors** - They may not be what customers really compare you to
- **Don't write positioning alone** - Involve sales, product, and talk to customers

## Common Pitfalls

**Pitfall 1: Starting with differentiation**
Many teams start by asking "what makes us different?" This leads to feature-focused positioning disconnected from customer value.
→ Solution: Start with alternatives. Differentiation only matters relative to what customers would otherwise use.

**Pitfall 2: Too many value themes**
Trying to be everything to everyone dilutes positioning.
→ Solution: Prioritize 2-3 core value themes that resonate most with target segment.

**Pitfall 3: Inside-out thinking**
Assuming what you think is valuable matches what customers care about.
→ Solution: Talk to customers who chose you and those who chose alternatives. What mattered in their decision?

**Pitfall 4: Aspirational positioning**
Positioning for who you want to be rather than who you are today.
→ Solution: Position for where the product is now. Repositioning as you evolve is normal.

**Pitfall 5: Category confusion**
Choosing a category because it's trendy rather than because it helps customers understand your value.
→ Solution: Test category names with prospects. Does it help or confuse them?

## Interactive Questioning Approach

When guiding someone through this framework, Claude should:

1. **Work sequentially through the five phases** - Don't jump ahead
2. **Ask clarifying questions** - Dig deeper when answers are vague
3. **Challenge assumptions** - Push back on generic claims or unsubstantiated differentiation
4. **Use customer language** - Encourage specific customer quotes and real scenarios
5. **Look for gaps** - Point out when value doesn't clearly connect to attributes, or when target market is too broad
6. **Provide examples** - Help people understand what "good" looks like
7. **Test coherence** - Does the complete positioning story make sense as a whole?

## Example Dialogue Flow

**Claude:** "Let's start with competitive alternatives. What would your customers use or do if your product didn't exist? Think about the last few deals you lost - what did those prospects choose instead?"

**User:** "They'd probably use Segment or Adobe CDP."

**Claude:** "Those are your sales competitors, but let's go deeper. What about prospects who didn't choose any CDP vendor? What would they use to solve the underlying problem your product addresses?"

**User:** "Oh, some of them would just keep using their existing data warehouse and build custom scripts to push data to tools."

**Claude:** "Good! That's a competitive alternative. What else? Are there prospects who simply accept having stale data in their tools?"

[Continue through each phase with similar depth]

## References
- Dunford, April. "Obviously Awesome: How to Nail Product Positioning so Customers Get It, Buy It, Love It."
- Focus on helping customers understand value in the context of their real alternatives
- Positioning is the foundation for all messaging, not just marketing copy
