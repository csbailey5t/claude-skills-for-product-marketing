# Product Marketing Toolkit for Claude

A collection of Claude skills for product marketing work, based on proven frameworks from April Dunford, Emily Kramer, Andy Raskin, Bob Moesta, Christopher Lochhead, and more.

AI should help us think, so these skills are written to help Claude ask you questions guided by expertise to achieve discrete goals.

## Skills Included

Each skill is a self-contained directory with a `SKILL.md` file:

### Research & Insights
- **`switch-interview/`** - Bob Moesta's Jobs-to-be-Done Switch Interview methodology for understanding why customers change products, what forces drive and block decisions, and what "job" they hired your product to do
- **`win-loss-analysis/`** - Systematic program for designing, conducting, and synthesizing win/loss interviews to understand why you win and lose deals, based on Clozd and Pragmatic Institute methodologies
- **`icp-builder/`** - Framework for building an Ideal Customer Profile across firmographic, technographic, psychographic, and behavioral dimensions, including buying triggers and anti-ICP signals

### Positioning & Strategy
- **`dunford-positioning/`** - April Dunford's systematic positioning framework for identifying competitive alternatives, unique attributes, value, target market, and market category
- **`category-design/`** - Play Bigger framework (Ramadan, Peterson, Lochhead, Maney) for creating and dominating a new market category through POV, ecosystem design, and lightning strikes

### Messaging & Content
- **`messaging-architecture/`** - Layered messaging hierarchy from company-level message through value proposition, pillars, and proof points, with audience variants
- **`creative-intent-interrogation/`** - Deep questioning framework to clarify WHO/FEELING/TAKEAWAY/EXPERIENCE for any creative work
- **`content-multiplication/`** - Strategic framework for transforming existing content into multiple formats optimized for different channels and audiences

### Sales & Go-to-Market
- **`dunford-sales-pitch/`** - April Dunford's 8-component sales pitch structure that helps buyers make confident decisions
- **`raskin-pitch/`** - Andy Raskin's strategic narrative framework (the big change → winners/losers → promised land → magic gifts → proof)
- **`battlecard-builder/`** - Competitive battlecard framework that sales reps will actually use, covering competitor positioning, talk tracks, discovery questions, and proof points
- **`launch-planning/`** - Product launch framework with T1/T2/T3 tiering, launch brief, cross-functional alignment, and success measurement

### Campaign Planning
- **`kramer-fuel-engine/`** - Emily Kramer's framework for balancing content creation (fuel) with distribution (engine)

## How to Use

### With Claude Code (CLI)

1. **Clone this repository:**
   ```bash
   git clone https://github.com/csbailey5t/claude-skills-for-product-marketing.git
   cd claude-skills-for-product-marketing
   ```

2. **Invoke skills using the slash command:**
   ```bash
   /dunford-positioning    # Start a positioning exercise
   /raskin-pitch          # Develop a strategic narrative
   /content-multiplication # Transform existing content
   /switch-interview      # Run buyer research
   /win-loss-analysis     # Design a win/loss program
   /battlecard-builder    # Build a competitive battlecard
   /launch-planning       # Plan a product launch
   /messaging-architecture # Build a messaging hierarchy
   /icp-builder          # Define your ideal customer
   /category-design      # Design a new market category
   ```

### With Claude Desktop

1. **Open Claude Desktop Settings**
2. **Add this repository** to your Skills directories
3. **Use the skills** in any conversation - Claude will apply them when relevant or you can invoke them explicitly with `/skill-name`

Available skills:
- `dunford-positioning` - Product positioning methodology
- `dunford-sales-pitch` - 8-component sales pitch framework
- `raskin-pitch` - Strategic narrative framework
- `kramer-fuel-engine` - Marketing fuel vs engine balance
- `creative-intent-interrogation` - Deep creative intent questioning
- `content-multiplication` - Strategic content transformation
- `switch-interview` - Jobs-to-be-Done buyer research
- `win-loss-analysis` - Win/loss interview program
- `icp-builder` - Ideal Customer Profile development
- `messaging-architecture` - Messaging hierarchy and pillars
- `battlecard-builder` - Competitive battlecards for sales
- `launch-planning` - Product launch planning and tiering
- `category-design` - New market category creation
