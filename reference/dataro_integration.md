# Dataro Integration Research
## ProspectAI + PredictAI for Bloomerang Embedding

---

## 1. Dataro Product Suite

### PredictAI (Donor Predictions)
- AI-powered propensity scoring across multiple giving dimensions
- **Prediction types:**
  - Likelihood of one-time giving
  - Likelihood of recurring giving conversion
  - Likelihood of recurring giving upgrade
  - Lapse risk for monthly donors
  - Recapture potential for lapsed supporters
  - Mail appeal response likelihood
  - Telemarketing response likelihood
  - Midlevel giving potential
  - Major gift potential
  - Planned giving potential
- **Inferred data fields:**
  - Age and gender demographics
  - Interest areas and topic preferences
  - Preferred communication channels
  - Preferred giving methods
  - Suggested ask amounts
- **Smart Audiences:** Pre-built segments based on propensity scores
- **Delivery:** Predictive fields (weekly), scores flow into CRM

### ProspectAI (Prospect Research)
- Autonomous AI Agent for prospect research
- Reduces research from hours to minutes
- **How it works:**
  1. Enter prospect details (name, location, etc.)
  2. Google APIs search the web
  3. Content aggregation from top results
  4. Identity resolution via LLMs (99% accuracy)
  5. Structured report generation
  6. Supplementary data source processing
- **Report includes:**
  - Biographical details
  - Wealth indicators / capacity assessment
  - Philanthropic interests / affinity assessment
  - Affiliations and connections
  - News articles for due diligence
  - Family and professional connections
  - Hobbies and interests (conversation starters)
  - Causes of interest
- **Report features:**
  - Fully cited — click any text to see source link
  - Click to edit and mark as reviewed/approved
  - Add or remove sources
  - Regenerate report without additional cost
  - Exportable
  - Customizable donor briefs
- **Pricing:** $250/month

### Fundraising Brain (Insights API)
- Combined intelligence layer
- Weekly insights delivery
- Surfaces: at-risk donors, upgrade opportunities, lapsed win-back, monthly conversion candidates
- Next Best Action recommendations

---

## 2. Dataro Brand & Visual Style

### Colors (extracted from dataro.io)
- **Primary:** Teal/Cyan — approximate #00B4D8
- **Secondary:** Light cyan — approximate #48CAE4
- **Accent:** Pastel blue — approximate #90E0EF
- **Background:** Very light blue — approximate #F0FBFF
- **Dark text:** Deep navy — approximate #023E58
- **Score indicators:**
  - High: Green (align with Bloomerang #3f9107)
  - Medium: Yellow/Amber
  - Low: Red

### Typography
- Clean sans-serif (likely Inter or similar modern font)
- Professional, data-forward aesthetic

### Design Philosophy
- "Decision layer that sits on top of your CRM"
- Modern dashboard with tiled metric cards
- Donor photos surrounded by data visualizations
- Conversion likelihood badges
- Preference indicators

---

## 3. Embedding Strategy for Bloomerang

### Tommy's Request (COO)
"We're thinking about a workflow where a nonprofit could search or browse prospects directly inside Bloomerang, and then with one click, add that prospect as a new constituent in their CRM."

### Required Integration Points

#### A. Dashboard ("Fundraising Brain" Widget)
- Appears on Bloomerang Home page
- Shows: Top donors to call, at-risk donors, upgrade opportunities, lapse win-back, monthly conversion candidates
- Powered by Dataro PredictAI scores
- Branded as "Fundraising Brain" — Powered by Dataro
- Visual distinction: Teal accent border (#00B4D8), "Powered by Dataro" badge

#### B. Constituent Profile (Embedded Scores)
- On Summary tab: add Dataro prediction scores alongside Engagement Level
- Propensity score (0-100 scale, traffic light colors)
- Recommended ask amount
- Lapse risk indicator
- Interest alignment
- Next Best Action recommendation

#### C. ProspectAI Search (New Feature)
- Accessible from Constituents page or dedicated "Prospect Research" sidebar item
- Search by name → get rich profile
- One-click "Add as Constituent" button
- Prospect data flows directly into Bloomerang constituent record
- No app switching required

#### D. Penny AI Integration
- Penny can surface Dataro insights in conversations
- "Show me my top upgrade opportunities" → Penny uses Dataro API
- "Prepare me for my meeting with Sarah Mitchell" → Penny pulls ProspectAI brief
- "Who should I call this week?" → Penny uses Next Best Action from Dataro

---

## 4. V1 Deliverables (from Notion project)

1. **Predictive fields** (weekly) — propensity scores synced to Bloomerang
2. **ProspectAI API** (on-demand) — prospect research endpoint
3. **Fundraising Brain insights API** (weekly) — aggregated intelligence
4. **Smart Audiences** (weekly) — pre-built campaign segments

### Packaging
- **Core tier:** Basic predictions + Smart Audiences
- **Premium tier:** ProspectAI + Fundraising Brain + Advanced predictions

---

## 5. Key Demo Data Points

- Bloomerang ran 4 ProspectAI test profiles: Dennis Fois, Steve Isom, Ron Carson, Warren Buffett
- Nicole confirmed: good source coverage, reasonable capacity values, some minor quirks, no red flags
- 10 product concepts designed for Bloomerang's "solo fundraiser" persona
- UX mockups for simplified predictions completed (Feb 19)

---

## 6. Data Fields to Embed in Bloomerang

### On Constituent Record
| Field | Source | Update Frequency |
|-------|--------|-----------------|
| Major Gift Propensity (0-100) | PredictAI | Weekly |
| Recurring Giving Propensity (0-100) | PredictAI | Weekly |
| Lapse Risk Score (0-100) | PredictAI | Weekly |
| Upgrade Propensity (0-100) | PredictAI | Weekly |
| Recommended Ask Amount ($) | PredictAI | Weekly |
| Next Best Action | Fundraising Brain | Weekly |
| Predicted Interests | PredictAI | Weekly |
| Inferred Age Range | PredictAI | Weekly |
| Capacity Estimate | ProspectAI | On-demand |
| Affinity Score | ProspectAI | On-demand |
| Wealth Indicators | ProspectAI | On-demand |
| Due Diligence Notes | ProspectAI | On-demand |
