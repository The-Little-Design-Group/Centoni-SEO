# Keyword Strategy Educational Guide

**Document Purpose:** Educational reference for team members new to search engine marketing
**End Client:** Centoni Design-Build
**Partner Agency:** Websight Design
**Executed By:** The Little Design Group
**Author:** Dan Ceresia, CIO/CTO
**Last Updated:** 2025-12-05

---

## Introduction

This guide provides foundational knowledge for understanding the keyword strategy implemented in this project. Whether you are new to search engine marketing (SEM) or need a refresher, this document explains the concepts, terminology, and reasoning behind our approach.

---

## Part 1: Understanding Search Marketing

### What is Search Engine Marketing (SEM)?

Search Engine Marketing refers to paid advertising on search engines like Google. When users search for terms related to our client's services, our ads can appear at the top of search results. We pay when users click on these ads (Pay-Per-Click or PPC model).

### Why SEM for Centoni?

**High Intent:** People searching "kitchen remodel San Francisco" are actively looking for services. Unlike social media advertising where we interrupt users, search ads meet users at their moment of need.

**Local Targeting:** San Francisco has a specific, defined market. SEM allows precise geographic targeting.

**Measurable ROI:** Every click, conversion, and cost is trackable. We can calculate exact return on ad spend.

**Competitive Necessity:** Competitors bid on these terms. Without presence, Centoni loses visibility to competitors.

---

## Part 2: Keyword Fundamentals

### What is a Keyword?

A keyword is a word or phrase that triggers your ad to appear. When a user's search query matches (or relates to) your keyword, your ad may show.

**Example:**
- Keyword: "historic home renovation san francisco"
- User searches: "who does historic home renovation in san francisco"
- Result: Our ad may appear

### Keyword Intent

Not all searches indicate the same level of purchase readiness. Understanding intent helps us bid appropriately.

#### Informational Intent
User wants information, not necessarily a service.
- "how much does kitchen remodel cost"
- "victorian home renovation ideas"
- Lower conversion rate, lower bid priority

#### Navigational Intent
User seeks a specific company or website.
- "centoni reviews"
- "centoni san francisco"
- Brand defense, moderate bid priority

#### Transactional Intent
User is ready to take action (hire, contact, purchase).
- "kitchen remodel contractor san francisco"
- "hire historic home renovation company sf"
- Highest conversion rate, highest bid priority

#### Commercial Investigation
User is comparing options before deciding.
- "best home renovation contractors san francisco"
- "top rated design build firms sf"
- High value, competitive bidding

---

## Part 3: Match Types Explained

Google Ads offers different ways to match your keywords to user searches. Each has tradeoffs between reach and precision.

### Exact Match

**Syntax:** [keyword in brackets]
**Example:** [kitchen remodel san francisco]

**Behavior:** Ad shows only when the search closely matches the exact keyword (allows minor variations like plurals, typos, and reordering).

**Pros:**
- Highest precision
- Best Quality Scores
- Most efficient spend

**Cons:**
- Lowest reach
- May miss valuable variations

**When to Use:** High-intent, high-value terms where precision matters most.

### Phrase Match

**Syntax:** "keyword in quotes"
**Example:** "kitchen remodel san francisco"

**Behavior:** Ad shows when the search includes the meaning of your keyword, potentially with words before or after.

**Matches:**
- "affordable kitchen remodel san francisco"
- "kitchen remodel san francisco contractor"
- "best kitchen remodel in san francisco"

**Does Not Match:**
- "san francisco bathroom remodel" (different service)
- "kitchen renovation san francisco" (may match with close variants)

**Pros:**
- Balanced reach and relevance
- Captures valuable variations

**Cons:**
- Less control than exact
- Requires negative keyword management

**When to Use:** Core service terms where variations carry similar intent.

### Broad Match Modified (Historical Reference)

**Note:** Google deprecated pure broad match modified in 2021, but the concept remains relevant and phrase match now incorporates much of this behavior.

**Syntax:** +keyword +terms +here
**Example:** +kitchen +remodel +san +francisco

**Behavior:** Ad shows when search contains all modified terms (or close variants) in any order.

**Matches:**
- "san francisco kitchen contractor for remodel"
- "remodel my kitchen in san francisco bay area"

**Pros:**
- Maximum reach
- Discovers new keyword opportunities

**Cons:**
- Requires extensive negative keywords
- Higher risk of irrelevant traffic

**When to Use:** Discovery campaigns, expanding keyword lists, maximum coverage.

---

## Part 4: Geographic Targeting

### Why Geographic Modifiers Matter

Centoni serves San Francisco. Without geographic targeting:
- Ads show to users in other cities
- Budget depletes on non-serviceable clicks
- Conversion rates plummet

### Geographic Strategy for This Project

**Primary Modifiers:**
- "San Francisco" (full city name)
- "SF" (common abbreviation)

**Secondary Modifiers (Use Sparingly):**
- "San Francisco Bay Area"
- "Bay Area" (only with other SF indicators)

**Excluded:**
- Generic "California" without SF
- "Bay Area" alone (too broad)

### Implementation

Keywords should include geographic modifiers:

| Without Geo | With Geo |
|-------------|----------|
| kitchen remodel | kitchen remodel san francisco |
| historic home renovation | historic home renovation sf |
| design build contractor | design build contractor san francisco |

---

## Part 5: Negative Keywords

### What are Negative Keywords?

Negative keywords prevent your ad from showing for specific searches. They protect your budget from unqualified clicks.

**Example:**
- Keyword: "kitchen remodel san francisco"
- Negative: "diy"
- User searches: "diy kitchen remodel san francisco"
- Result: Ad does NOT show (good - this user is not hiring a contractor)

### Negative Keyword Categories for Centoni

#### Budget/Discount Seekers
- cheap
- affordable
- budget
- discount
- low cost
- inexpensive

**Rationale:** Centoni is a premium service. Users seeking cheap options will not convert and waste ad spend.

#### DIY/Self-Help Searches
- diy
- how to
- tutorial
- guide
- tips
- ideas

**Rationale:** These users want to do the work themselves, not hire a contractor.

#### Job Seekers
- jobs
- careers
- hiring
- employment
- salary
- internship

**Rationale:** Job seekers are not potential clients.

#### Educational Searches
- classes
- courses
- certification
- license
- school
- training

**Rationale:** People seeking education, not services.

#### Supply/Tool Searches
- supplies
- tools
- materials
- equipment
- wholesale

**Rationale:** Contractors buying supplies, not homeowners hiring services.

#### Platform/Review Searches
- craigslist
- yelp reviews
- bbb complaints
- lawsuit

**Rationale:** Users researching complaints or seeking Craigslist (typically budget-focused).

---

## Part 6: Ad Group Structure

### What is an Ad Group?

An ad group is a container within a campaign that holds:
- A set of related keywords
- Ads that will show for those keywords
- A shared default bid

### Why Granular Ad Groups?

**Quality Score Improvement**
Google rewards relevance. When your keyword, ad, and landing page all align, Quality Score improves, reducing cost-per-click.

**Example:**
- Ad Group: Kitchen Remodel
- Keywords: All kitchen-related terms
- Ad Copy: "Kitchen Remodel Experts in San Francisco"
- Landing Page: Kitchen services page

The tight alignment improves Quality Score versus a generic ad group.

**Performance Analysis**
Granular groups let you see which segments perform best. If Victorian keywords outperform Mid-Century, you can reallocate budget accordingly.

**Bid Optimization**
Different services have different values. Kitchen remodels may have higher margins than bathroom updates. Separate ad groups allow bid differentiation.

### Ad Group Structure for Centoni

| Ad Group | Keyword Theme | Example Keywords |
|----------|---------------|------------------|
| Whole Home | Full renovations | whole home remodel sf, complete home renovation |
| Kitchen | Kitchen specific | kitchen remodel sf, kitchen renovation |
| Bathroom | Bathroom specific | bathroom remodel sf, bath renovation |
| Seismic | Earthquake upgrades | seismic upgrade sf, earthquake retrofit |
| Historic General | General historic | historic home renovation sf |
| Victorian | Victorian homes | victorian restoration sf |
| Mid-Century | Mid-Century Modern | mid-century renovation sf |
| Arts and Crafts | Arts and Crafts style | arts crafts home restoration sf |
| Condos/Flats | Multi-unit properties | flat renovation sf, condo remodel |
| Luxury/Premium | High-end positioning | luxury home renovation sf |
| Authority | General contractor | design build contractor sf, licensed gc |
| Investor | Investment focus | flip renovation sf, investor remodel |
| Partnership | B2B targeting | contractor partner sf |

---

## Part 7: Quality Score

### What is Quality Score?

Quality Score is Google's rating (1-10) of your keyword's relevance and quality. Higher scores mean lower costs and better ad positions.

### Quality Score Components

1. **Expected Click-Through Rate (CTR)**
   - How likely users are to click your ad
   - Improved by compelling ad copy
   - Affected by keyword relevance

2. **Ad Relevance**
   - How closely your ad matches the keyword
   - Include keywords in ad headlines
   - Ensure ad copy reflects search intent

3. **Landing Page Experience**
   - Page load speed
   - Mobile friendliness
   - Content relevance to keyword
   - Clear calls-to-action

### Improving Quality Score

| Factor | Action |
|--------|--------|
| CTR | Write compelling headlines, use ad extensions |
| Ad Relevance | Include keywords in ads, create tight ad groups |
| Landing Page | Fast load, mobile-friendly, relevant content |

---

## Part 8: Practical Application

### Building a Campaign - Step by Step

1. **Define Objective:** Generate leads for kitchen remodels
2. **Research Keywords:** kitchen remodel sf, kitchen renovation san francisco
3. **Group by Theme:** Create "Kitchen Remodel" ad group
4. **Write Ads:** "Kitchen Remodel Experts San Francisco - Premium Design-Build"
5. **Add Negatives:** diy, cheap, jobs, ideas
6. **Set Geographic Target:** San Francisco
7. **Choose Match Types:** Exact and Phrase for precision
8. **Assign Landing Page:** Kitchen services page
9. **Set Budget and Bids:** Based on competitive analysis
10. **Launch and Monitor:** Track conversions, optimize

### Ongoing Optimization

- Review search terms report weekly
- Add high-performing queries as keywords
- Add irrelevant queries as negatives
- Pause underperforming keywords
- A/B test ad copy
- Monitor Quality Scores

---

## Glossary

| Term | Definition |
|------|------------|
| CPC | Cost Per Click - amount paid when user clicks ad |
| CTR | Click Through Rate - clicks divided by impressions |
| Impression | One display of your ad |
| Conversion | Desired action (form submit, phone call) |
| Quality Score | Google's 1-10 rating of keyword quality |
| Ad Group | Container for related keywords and ads |
| Campaign | Top-level container for ad groups |
| Negative Keyword | Term that prevents ad from showing |
| Match Type | How closely search must match keyword |
| ROAS | Return on Ad Spend - revenue per dollar spent |

---

## Further Learning

For deeper understanding, team members should explore:

1. Google Ads Help Center (official documentation)
2. Google Skillshop certifications
3. Industry publications (Search Engine Land, Search Engine Journal)
4. Client websites for service understanding

---

## Document Control

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | 2025-12-05 | Dan Ceresia | Initial educational guide |

---

**Note to Team:** This guide provides foundational concepts. Real-world application requires practice and continuous learning. Ask questions, experiment with small budgets, and always analyze results before scaling.

---

**Document Classification:** Internal - The Little Design Group
**Partner Agency:** Websight Design
**End Client:** Centoni Design-Build
