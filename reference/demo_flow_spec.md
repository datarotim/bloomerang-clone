# Demo Flow Specification
## Bloomerang + Dataro Interactive Mockup for Dennis Fois

---

## Target Audience
Dennis Fois, CEO of Bloomerang + leadership team

## Key Messages to Convey
1. Intelligence embedded IN Bloomerang — users never leave
2. One-click simplicity for solo fundraisers
3. Penny + Dataro = "the engine behind every Penny moment at scale"
4. ProspectAI embeddable — search, discover, one-click add as constituent
5. Churn killer — "the product helped me raise more money"
6. Premium SKU justification for Segments 3 & 4

---

## Flow: 4 Screens

### Screen 1: Home Dashboard
**File:** `01_home_dashboard.html`

**Layout:** Standard Bloomerang Home page with all normal widgets PLUS the "Fundraising Brain" card.

**Key Elements:**
- Full Bloomerang sidebar navigation
- Top header with "Ask Penny" button
- Metric cards: Donations This Month, New Constituents, Active Campaigns
- **HERO: Fundraising Brain card** (Dataro-branded, teal accent)
  - Badge: "Fundraising Brain — Powered by Dataro"
  - Title: "We identified 3 event attendees with a HIGH chance of giving a major gift"
  - Subtitle: Names from Spring Gala Preview, outreach within 48 hours recommended
  - 3 prospect rows with: avatar, name, details, propensity score, ask amount, "View Profile" button
  - Insight strip: At-Risk Donors (12), Upgrade Revenue ($47K), Monthly Convert (23), Lapsed Win-Back (8)
- Donor Retention Wheel (68% rate)
- Tasks, Recent Donations, Campaign Progress

**User Action:** Click "View Profile" on Sarah Mitchell → goes to Screen 2

---

### Screen 2: ProspectAI Constituent View
**File:** `02_prospect_ai_view.html`

**Layout:** Bloomerang constituent profile page with Dataro intelligence embedded seamlessly.

**Key Elements:**

**Constituent Header:**
- Sarah Mitchell, Individual
- Profile photo, engagement level (On Fire), generosity score
- Action buttons: Edit, Email, Log Interaction, Add Note

**Tabs:** Summary | Profile | Timeline | Relationships | **ProspectAI** (new tab, Dataro-branded)

**Summary Tab (default view) — Enhanced with Dataro:**
- **Giving Summary** (standard Bloomerang)
  - Lifetime giving: $18,750
  - Last gift: $2,500 (Dec 2025)
  - Average gift: $625
  - Giving trend: Increasing
- **Dataro Intelligence Panel** (new section, teal accent border)
  - Major Gift Propensity: 94/100 (green traffic light)
  - Recommended Ask Amount: $25,000
  - Lapse Risk: Low (green)
  - Recurring Conversion: 78/100
  - Next Best Action: "Schedule personal meeting to discuss Spring Gala sponsorship"
- **Engagement Level:** On Fire (standard Bloomerang meter)
- **Generosity Score:** Hot (standard Bloomerang from Dataro)
- **Recent Timeline** (abbreviated)
- **Relationships**

**ProspectAI Tab (Dataro-branded):**
- Full ProspectAI report embedded in Bloomerang
- Capacity Assessment: $500K+ estimated wealth
- Affinity Assessment: Strong alignment with education and youth causes
- Professional Background: Board member, Riverside Corp
- Philanthropic History: 15+ organizations, major gift history
- News & Articles: Recent mentions
- Due Diligence: Clean
- Family Connections: Spouse also donor
- Interests: Education, arts, youth development
- One-click "Add sources" or "Regenerate report"
- All text clickable to see source URLs

**User Action:** Click "Ask Penny" in toolbar → opens Penny panel (Screen 3)

---

### Screen 3: Penny AI Chat Panel (Overlay on Screen 2)
**File:** `03_penny_chat.html` OR overlay within `02_prospect_ai_view.html`

**Layout:** Right-side slide-out panel overlaying the constituent view.

**Panel Elements:**
- Header: "Penny" with AI sparkle icon, close (X) button
- Suggested prompts at top:
  - "Prepare me for my meeting with Sarah"
  - "What's the best ask amount?"
  - "Show upgrade opportunities this week"
  - "Create a cultivation plan"
- Chat conversation (pre-populated demo):

**User asks:** "Prepare me for my meeting with Sarah Mitchell tomorrow"

**Penny responds:**
"Here's your meeting brief for Sarah Mitchell:

**Key Facts:**
- 3-year donor, lifetime giving $18,750
- Board member at Riverside Corp (estimated revenue $50M+)
- Attended Spring Gala Preview last week — stayed 2 hours, spoke with your ED
- Engagement level: On Fire

**Dataro Intelligence:**
- Major gift propensity: 94/100 — she's in your top 5% of prospects
- Recommended ask: $25,000 for Spring Gala sponsorship
- Her interests align strongly with your youth education programs

**Talking Points:**
1. Thank her for attending the Gala Preview — mention you noticed she connected with your ED
2. Share impact update on the youth mentoring program (her top interest area)
3. Present the $25,000 Platinum Sponsorship opportunity for the Spring Gala
4. Mention that sponsorship includes naming rights on the youth stage

**Risk Factors:**
- None identified. She's highly engaged and giving trajectory is upward.

Would you like me to draft a meeting agenda or follow-up email?"

- Input bar at bottom: "Ask Penny anything..."
- "New Conversation" button

---

### Screen 4: ProspectAI Search & Add Flow
**File:** `04_prospect_search.html`

**Layout:** New page accessible from sidebar ("Fundraising Brain" → "Find Prospects") or from constituent search.

**Key Elements:**
- **Search bar:** "Search for new prospects..."
- **Search by:** Name, Company, Location, Interests, or Affinity to your cause
- **Results grid:** Cards showing prospect matches
  - Each card: Name, title, company, location, wealth capacity estimate, affinity score
  - **One-click "Add to CRM" button** on each card (green, prominent)
- **Expanded prospect card** (when clicked):
  - ProspectAI mini-report: bio, capacity, affinity, interests
  - "Add as Constituent" button (large, green)
  - Clicking adds them directly as new Bloomerang constituent
  - Pre-fills: name, contact info, employer, wealth markers, custom fields from ProspectAI
  - Confirmation: "Sarah Mitchell added to your database. View Profile →"

**The "OMG" moment:**
User searches "tech executives Austin TX education" → gets 5 results → clicks "Add to CRM" on one → they're instantly in Bloomerang with full data. No manual entry. No switching apps. One click.

---

## Visual Design Rules

### Bloomerang Elements (majority of UI)
- Font: Quicksand
- Background: #f4f5f5
- Cards: white, 1px #e9eaeb border, 8px radius
- Primary buttons: #3f9107 bg, white text
- Sidebar: white bg, green active states
- Header: white, 56px

### Dataro Elements (embedded intelligence)
- **Visual distinction:** Teal accent color (#00B4D8)
- **"Powered by Dataro" badge** — subtle, bottom-right or header of Dataro sections
- Teal left border on Dataro cards/sections
- Gradient badge: linear-gradient(135deg, #00B4D8, #48CAE4)
- Score colors: Green (high), Yellow (medium), Red (low) — matches Bloomerang semantic colors
- Dataro sections feel NATIVE to Bloomerang, not bolted on

### Penny AI Panel
- White background panel, ~380px wide
- Green accent (#3f9107) for Penny branding
- User messages: #f4f5f5 bubbles
- Penny messages: #d7f5c3 bubbles (light green)
- Suggested prompts: pill-shaped buttons
- Sparkle icon for AI indicator

---

## Success Criteria
- Dennis says "holy sh*t" when he sees the one-click add
- Feels like Bloomerang built this, not a 3rd-party bolted on
- Solo fundraiser with no training could use this on Day 1
- Every screen answers: "The product helped me raise more money"
- Penny + Dataro feels like "the engine behind every Penny moment at scale"
