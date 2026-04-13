# SEO/GEO Blog Sources Collector

**Automated pre-writing research for SEO & GEO-optimized blog content** 鈥� powered by [Sai](https://www.sai.work/), an autonomous AI agent.

Give Sai a keyword. It researches 10+ platforms, collects competitive intelligence, user questions, expert quotes, hard data, and social trend signals 鈥� then outputs everything to a structured Google Sheet ready for the writing phase.

---

## What This Skill Does

This skill automates the **entire research pipeline** that happens before writing an SEO/GEO blog article. Instead of manually searching across a dozen platforms and copy-pasting into docs, Sai runs 6 research modules autonomously and delivers structured, write-ready source material.

### Module 1: AI Visibility Audit
- Queries **ChatGPT**, **Perplexity**, and **Google AI Overview** with your target keyword
- Records which products/brands each AI engine cites
- Identifies citation gaps 鈥� what your product does that nobody mentions
- Determines if your brand is already visible in AI-generated answers

### Module 2: User Question Mining
- Scrapes **AnswerSocrates** for question clusters organized by type (what, how, why, which, can)
- Expands **Google PAA** (People Also Ask) boxes from SERPs
- Searches **Reddit** for authentic user pain points and discussions
- Outputs 15鈥�20 real questions that become H2 heading candidates for your article

### Module 3: Competitor Article Analysis
- Opens top 5 organic Google results for your keyword
- Extracts: word count, H2 headings, products covered, comparison tables, FAQ sections, methodology
- Identifies content gaps 鈥� what no competitor covers (your opportunity)
- Maps the common format patterns across top-ranking articles

### Module 4: Data & Statistics Harvesting
- Searches for industry reports, market data, and statistics related to your keyword
- Collects hard numbers with full source attribution
- Finds recent (2024鈥�2026) data points to strengthen article authority
- Provides citable statistics with original source URLs

### Module 5: Expert Quote Collection
- Searches **Twitter/X** for expert opinions from verified/high-follower accounts
- Searches **LinkedIn** for thought leader posts and insights
- Records: expert name, credentials, verbatim quote, and source link
- Targets 5鈥�8 quotable experts per article

### Module 6: Social Media Trend Scan
- Finds viral posts on **Twitter/X** related to the keyword (sorted by engagement)
- Analyzes top **YouTube** videos 鈥� title patterns, view counts, publish dates
- Surfaces trending **Reddit** discussions and audience sentiment
- Extracts viral hook formulas and content angles that perform

---

## Output

All research is exported to a **structured Google Sheet** with the following columns:

| Column | Content |
|---|---|
| A | Target Audience / Segment |
| B | Primary Keywords |
| C | AI Visibility Report (ChatGPT, Perplexity, Google AI) |
| D | User Questions (AnswerSocrates + PAA + Reddit) |
| E | SERP Intent Classification |
| F | Top Competitor Articles (URLs + analysis) |
| G | Statistics & Data Points |
| H | Expert Quotes |
| I | Social Media Trends |
| J | Recommended Blog Title + Outline |

---

## Platforms Researched

| Platform | What Sai Collects |
|---|---|
| Google Search | SERP analysis, competitor articles, PAA questions |
| ChatGPT | AI visibility 鈥� what does ChatGPT cite for this keyword? |
| Perplexity | AI visibility 鈥� what does Perplexity cite? |
| Google AI Overview | AI visibility 鈥� what appears in Google's AI panel? |
| AnswerSocrates | User question clusters by type |
| Twitter/X | Viral content, expert opinions, trend signals |
| Reddit | User pain points, authentic discussions, sentiment |
| YouTube | Video content trends, title format research |
| LinkedIn | Expert quotes, industry insights |

---

## Example Usage

```
"Research sources for a blog about AI meeting note takers"
"Prepare blog writing resources for best CRM tools 2026"
"Do a competitive analysis for 'email automation' before I write"
"Find data, quotes, and user questions about GUI automation"
```

Sai will autonomously:
1. Search across all 9 platforms
2. Collect and organize findings by module
3. Write everything to Google Sheets in a structured format
4. Flag content gaps and opportunities your article should exploit

---

## Setup & Requirements

### Prerequisites
- **Sai** 鈥� an autonomous AI agent by [Simular](https://www.sai.work/)
- A Google account (for Sheets output)

### Getting Started

1. **Get access to Sai** at [sai.work](https://www.sai.work/)
2. Connect your Google account in Sai (for Sheets read/write access)
3. Trigger the skill by telling Sai what keyword to research:
   ```
   "Research sources for a blog about [your keyword]"
   ```
4. Sai runs all 6 modules autonomously and outputs results to your Google Sheet

### Safety
- **Read-only on all platforms** 鈥� Sai does not post, comment, or engage on any social platform
- **Rate-limited** 鈥� maximum 20 Google searches and 10 social media searches per platform per session
- **Respects robots.txt** 鈥� does not scrape blocked pages

---

## License

MIT
