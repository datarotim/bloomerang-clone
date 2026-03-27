# Figma Make Prompt — Bloomerang CRM + Dataro Intelligence Demo

## OVERVIEW

Recreate the Bloomerang CRM web application as a pixel-perfect Figma prototype. This is a demo for Bloomerang's CEO showing Dataro AI intelligence embedded natively inside Bloomerang. Create **3 core pages** that form a clickable flow. Match the real Bloomerang CRM interface exactly — then add Dataro elements that feel native, not bolted on.

**Attached reference files you MUST use:**
- `bloomerang_tokens.css` — exact CSS custom properties for every color, spacing, font, shadow, and component token
- `brand_guide.md` — complete typography, color palette, spacing system, and component specs
- `external_screenshots.md` — pixel-level descriptions of every dashboard widget, constituent profile section, and UI element from real product screenshots
- `ACTUAL_SIDEBAR_NAVIGATION.md` — confirmed sidebar menu items with exact icons and states
- `component_inventory.md` — 34 UI components with full specs
- `demo_flow_spec.md` — the 4-screen flow with exact content for each page

**Attached screenshots (use these as primary visual reference):**
- `homepage.jpg` — **CRITICAL: Full Bloomerang CRM homepage** showing sidebar, search bar, constituent Summary tab with Giving Summary chart, Engagement Level meter, Generosity Score, Recent Timeline Activity, and Household Members
- `contact_record.jpg` — **CRITICAL: Full constituent Profile tab** showing sidebar, header with name/ID/status badge, Profile tab active (teal), Basic Info, Addresses, Emails, Phone Numbers, Personal Information with social links
- `reporting.jpg` — Reports list page with sidebar, table layout, search, filters
- `reporting_filters.jpg` — New Report builder with filter UI
- `sustainability/01_scorecard.jpg` — Dashboard showing Donor Retention donut, Raised This Week, First-Time Donor Calls list, Campaign Progress
- `navigation/02_search_bar.png` — The actual sidebar: bloomerang CRM logo, Home/Constituents/Groups/Reports/Communications/Data Tools/Settings
- `navigation/01_sidebar_menu.png` — Search bar with "All" dropdown
- `help_center/35_crm-profile-icon.png` — Top-right header icons: bloomerang logo, bell, help, avatar, apps grid

---

## GLOBAL LAYOUT (applies to all 3 pages)

### Left Sidebar (fixed, 200px wide)
**Match screenshot `navigation/02_search_bar.png` exactly.**

- White background (#ffffff)
- Top: **bloomerang** logo — lowercase dark text "bloomerang" with green leaf icon above the "b", "CRM" below with solid green bar. See `bloomerang_logo.png`.
- Collapse chevron: white circle with "<" at top-right edge of sidebar
- Menu items (top to bottom, each with gray icon 20px + label 14px):
  1. **Home** — house icon — **active state:** light green bg (#d7f5c3), green text (#3f9107), filled green icon
  2. **Constituents** — two-person icon — gray
  3. **Groups** — hexagon cluster icon — gray
  4. **Reports** — half-circle chart icon — gray
  5. **Communications** — speech bubble icon — gray — with dropdown chevron ▾
  6. **Data Tools** — folder icon — gray — with dropdown chevron ▾
  7. **Settings** — gear icon — gray — with dropdown chevron ▾
- Item height: ~48px. Vertical padding between items.
- Active state: light green background that spans full width, green left border accent (3px), green text and icon
- On Page 2 (Constituent view), "Constituents" should be the active item instead of "Home"

### Top Bar (fixed, full width minus sidebar)
**Match screenshot `help_center/35_crm-profile-icon.png` and `contact_record.jpg` header.**

- Height: 56px
- White background (#ffffff), 1px bottom border (#e9eaeb)
- Left: **Search bar** — "All" dropdown + magnifying glass icon + "Search for constituents" placeholder. Light gray border, ~400px wide. See `navigation/01_sidebar_menu.png`.
- Right icons (left to right, each ~36px):
  - Bloomerang "b" green icon (small)
  - Notification bell with red dot badge
  - Help "?" circle icon
  - **"Ask Penny" button** — teal/green outlined button with sparkle icon + text "Ask Penny" (this is the Penny AI trigger — add it between help and avatar)
  - User avatar circle with initial "M" on dark background
  - Apps grid icon (3x3 dots)

---

## PAGE 1: HOME DASHBOARD

**Primary references: `homepage.jpg`, `sustainability/01_scorecard.jpg`, `external_screenshots.md` sections 2 and 4**

### Page Header
- Title: **"Good morning, Jessica"** — large dark text (~24px bold)
- Subtitle: "What's happening with Hope Valley Foundation today" — gray text 14px
- Right side: "Last updated Mar 27, 2026 **Refresh**" link

### Dashboard Widget Grid
4-column layout on first row, then 2-column and 3-column rows. All widgets are white cards with very subtle green-tinted border/shadow (see `external_screenshots.md` Section 5 for exact card styling). Widget headers are UPPERCASE gray letter-spaced text (~11px).

#### Row 1 — 4 equal columns:

**Column 1: RECENT CONSTITUENTS**
- Header: "RECENT CONSTITUENTS" uppercase gray
- List of 5 names as teal/green clickable links (e.g., "Sarah Mitchell", "Robert Jimenez", "Linda Worthington", "Thomas Nguyen", "Karen Phillips")
- Bottom: Green-outlined button **"Add new Constituent"**

**Column 2: AMOUNT RAISED**
Match `amount_raised.png` exactly:
- "AMOUNT RAISED" uppercase gray header
- 3 rows separated by thin gray lines:
  - "This week" → **$12,450** (large bold serif ~36px dark) → "14 transactions, $889.29 avg" (small gray right-aligned)
  - "This month" → **$47,832** → "127 transactions, $376.63 avg"
  - "This fiscal year" → **$312,500** → "1,842 transactions, $169.65 avg"

**Column 3: DONOR RETENTION**
Match `donor_retention.png` exactly:
- "DONOR RETENTION" uppercase gray, pencil icon top-right
- Large donut chart: dark green (#3f9107) fill for retained, light sage (#D4E8C4) for remainder
- Center: **68%** large bold dark + "OVERALL" label below
- Left chevron (<) for navigation
- Below: "386 out of 567 donors retained"
- Two pagination dots

**Column 4: FIRST-TIME DONOR CALLS**
Match `sustainability/01_scorecard.jpg` right side:
- "FIRST-TIME DONOR CALLS" uppercase gray, refresh icon top-right
- List of donors:
  - "Sarah Mitchell" (teal link) / "$2,500 Donation" / "3/15/2026" → **"Enter a Call"** teal button
  - "Thomas Nguyen" / "$1,000 Check" / "3/20/2026" → "Enter a Call"
  - "Amy Liu" / "$75 Online" / "3/22/2026" → "Enter a Call"
- Bottom: green "See full report" link

#### Row 2 — HERO: Fundraising Brain (spans 3 columns) + Tasks (1 column)

**FUNDRAISING BRAIN CARD** (3/4 width) — **THIS IS THE DATARO ELEMENT**
- Border: 2px solid #00B4D8 (teal)
- Background: subtle white-to-#F0FBFF gradient
- Shadow: 0 4px 16px rgba(0,180,216,0.12)
- Top-left badge: "FUNDRAISING BRAIN" — gradient pill (#00B4D8→#48CAE4), white text, sparkle icon, uppercase 11px
- Top-right: "Powered by **Dataro**" in small gray text (#a4a7ae), Dataro in teal
- Title: **"We identified 3 event attendees with a HIGH chance of giving a major gift"** — 18px bold dark
- Subtitle: "These constituents attended your Spring Gala Preview last week. Our models predict strong major gift potential. Recommended: personal outreach within 48 hours." — 14px gray

**3 Prospect Rows** (each a white card within the brain card, 1px border, 8px radius):
Each row: avatar circle (44px, colored initials) | Name (15px bold) + detail line (13px gray) | Propensity score pill (green bg, white text) | Ask Amount pill | "View Profile →" teal button | chevron

Row 1: **SM** green avatar | "Sarah Mitchell" / "Board member, Riverside Corp · 3-year donor · Last gift: $2,500" | Propensity: **94** | Ask: **$25K** | View Profile →
Row 2: **RJ** blue avatar | "Robert Jimenez" / "CEO, Jimenez Holdings · 1st event · Wealth: $500K+" | Propensity: **87** | Ask: **$15K** | View Profile →
Row 3: **LW** orange avatar | "Linda Worthington" / "Retired educator · Lifetime: $18,200 · Monthly since 2022" | Propensity: **82** | Ask: **$10K** | View Profile →

**Insight Strip** below prospects (4 mini cards in a row):
- "12 At-Risk Donors" (red warning icon)
- "$47K Upgrade Revenue" (green up arrow)
- "23 Monthly Convert" (blue refresh icon)
- "8 Lapsed Win-Back" (orange star icon)
Each mini card: white bg, 8px radius, centered icon + large bold number + small gray label

**TASKS CARD** (1/4 width)
Match `tasks_widget.png` exactly:
- "TASKS" uppercase gray + clock icon + dark "+" circle button
- Two tabs: "ALL" (bold, green underline active) and "MY" (gray)
- Section: "DUE SOON" uppercase gray
- Task rows: bold title, gray constituent name, channel ("Phone"/"Email"), "Assignee: [Name]", date on right, chevron
- 4 tasks shown

#### Row 3 — 3 equal columns:

**RECENT REPORTS**
- "RECENT REPORTS" uppercase gray
- List: "LYBUNT", "Spring Gala Donors", "Monthly Giving Report" as links
- Green-outlined button "Go to Reports"

**CAMPAIGNS**
- "CAMPAIGNS" uppercase gray, "View all" link top-right
- 3 campaign progress bars:
  - "Spring Gala 2026" — 73% green bar — "GOAL $100,000"
  - "Annual Fund" — 45% green bar — "GOAL $250,000"
  - "Building Expansion" — 28% orange bar — "GOAL $1,000,000"

**SUSTAINABILITY SCORECARD**
- "SUSTAINABILITY SCORECARD" uppercase gray
- Green button "View Now"

---

## PAGE 2: CONSTITUENT VIEW (Sarah Mitchell) — Summary Tab

**Primary references: `homepage.jpg` (Summary tab layout), `contact_record.jpg` (Profile tab layout), `constituent_timeline.png` (Timeline tab + header)**

### Constituent Header Bar
Match `constituent_timeline.png` header exactly:
- Gray circle avatar placeholder (or photo) — 64px
- **"Sarah Mitchell"** large bold dark text + **"#158"** gray + email "sarah.mitchell@riverside.com" teal link
- **Address:** "4521 Oak Valley Drive" / "Indianapolis, IN 46220" teal text
- **Phone:** "Mobile (317) 555-0184"
- **Relationship Manager:** "Jessica Davis"
- Far right: teal circle dropdown button with white down chevron ▾

### Tab Bar
Match `constituent_timeline.png` tabs:
- 4 tabs + 1 new Dataro tab:
  - **Summary** — ACTIVE: teal/green filled rounded rectangle (#4AA74B), white text
  - **Profile** — gray text
  - **Timeline** — gray text
  - **Relationships** — gray text
  - **ProspectAI** — teal (#00B4D8) text with sparkle icon (Dataro-branded tab)
- Below tabs, right side: "Edit ▾" dropdown

### Summary Tab Content — Two Columns

#### Left Column (~60%)

**Giving Summary**
Match `giving_summary.png` exactly:
- "Giving Summary" title in dark text, window controls (—, □, ×) in green top-right
- Toggle pills: "Revenue" (green bg, white text) | "Raised" "Soft Credits" (teal bg, white text)
- Area/line chart: green solid line + filled green area (Revenue), blue dashed line (Raised)
- X-axis years, Y-axis dollar amounts
- Below chart — metrics grid:
  - **Lifetime:** green badges "$18,750.00" and "$22,400.00"
  - **Average:** green badges "$625.00" and "$746.67"
  - **First Transaction:** "$250.00 3/15/2022" green text
  - **Latest Transaction:** "$2,500.00 12/8/2025"
  - **Largest Transaction:** "$5,000.00 6/20/2024"

**Dataro Intelligence Panel** — NEW SECTION, teal accent
- Left border: 3px solid #00B4D8
- Light teal background: #F0FBFF
- Header: sparkle icon + "AI Intelligence" with "Powered by Dataro" badge (small, right-aligned)
- 4 score rows:
  - "Major Gift Propensity" — **94/100** green traffic light circle
  - "Recommended Ask" — **$25,000** bold dark
  - "Lapse Risk" — **Low** green pill
  - "Recurring Conversion" — **78/100** green-yellow traffic light
- "Next Best Action" box: "Schedule personal meeting to discuss Spring Gala sponsorship — she connected with your ED at the preview event" with teal "Create Task →" button

**Recent Timeline Activity**
- 4-5 recent entries: green gift icon for donations, blue speech bubble for interactions
- Each: date, amount/type, description

#### Right Column (~40%)

**Engagement Level**
- Red heart icon + "Engagement Level" title
- Horizontal segmented bar, FULLY filled red = **"On Fire!"**
- Match `generosity_score.png` bar style

**Generosity**
Match `generosity_score.png` exactly:
- Dataro icon (teal) + "Generosity" title + "Update" outlined button
- Segmented red bar, all segments filled = **"On Fire!"**
- Teal button: **"View Generosity Details"**

**Household Members**
- "Household Members" section
- "David Mitchell" with arrow indicator — "Spouse" relationship
- "Head of Household" label

---

## PAGE 3: PENNY AI CHAT PANEL (overlaid on Page 2)

**Show Page 2 dimmed/overlaid with Penny panel on the right side.**

### Penny Slide-Out Panel
- Width: 380px
- Position: right edge of screen, full height
- White background, left shadow (0 -4px 16px rgba(0,0,0,0.1))
- Top: "Penny" title + sparkle icon + "New Conversation" button + close × button

### Suggested Prompts (shown first, before conversation)
4 pill buttons (1px green border, green text, 8px radius, 12px padding):
- "Prepare me for my meeting with Sarah"
- "What's the best ask amount?"
- "Show upgrade opportunities this week"
- "Create a cultivation plan"

### Conversation (scrollable area, below prompts)

**User message** (right-aligned, #f4f5f5 bg bubble, 12px radius):
"Prepare me for my meeting with Sarah Mitchell tomorrow"

**Penny response** (left-aligned, #d7f5c3 bg bubble, 12px radius):
Use markdown-style formatting within the bubble:

"Here's your meeting brief for Sarah Mitchell:

**Key Facts:**
• 3-year donor, lifetime giving $18,750
• Board member at Riverside Corp (estimated revenue $50M+)
• Attended Spring Gala Preview last week — stayed 2 hours, spoke with your ED
• Engagement level: On Fire 🔥

**Dataro Intelligence:**
• Major gift propensity: 94/100 — she's in your top 5% of prospects
• Recommended ask: $25,000 for Spring Gala sponsorship
• Her interests align strongly with your youth education programs

**Talking Points:**
1. Thank her for attending the Gala Preview
2. Share impact update on the youth mentoring program
3. Present the $25,000 Platinum Sponsorship opportunity
4. Mention naming rights on the youth stage

**Risk Factors:** None identified. Highly engaged, upward trajectory.

Would you like me to draft a meeting agenda or follow-up email?"

Below response: thumbs up / thumbs down icons (match `penny_ai/08_rate_good.jpg`) + copy icon

### Bottom Input Bar
- Full-width input: "Ask Penny anything..." placeholder
- Green send arrow button on right
- "Conversations" link to access past chats

---

## DESIGN TOKENS (from bloomerang_tokens.css)

### Colors
| Token | Value | Usage |
|-------|-------|-------|
| Primary Green | #3f9107 | Active states, primary buttons, chart fills |
| Light Green | #d7f5c3 | Active sidebar bg, Penny AI bubbles |
| Teal | #2B8C96 | CTA buttons ("Enter a Call", "View Generosity Details"), active tabs |
| Background | #f4f5f5 | Page background |
| Card bg | #ffffff | All cards/widgets |
| Border | #e9eaeb | Card borders, dividers |
| Text dark | #252b37 | Headings |
| Text body | #535862 | Body text, sidebar inactive |
| Text muted | #a4a7ae | Labels, placeholders, widget headers |
| Danger | #dc3545 | Engagement "On Fire" bar, at-risk alerts |
| Dataro teal | #00B4D8 | Dataro accent borders, badges |
| Dataro bg | #F0FBFF | Dataro section backgrounds |

### Typography
- **Font family:** System sans-serif (the CRM uses a clean sans — closest to Inter, Roboto, or system default)
- **Widget headers:** 11px, uppercase, letter-spacing 1px, #a4a7ae, font-weight 600
- **Dollar amounts:** Large bold serif (Georgia or similar) for Amount Raised widget; sans-serif bold for other metrics
- **Body text:** 14-15px regular weight
- **Clickable items:** Teal/green #4AA74B color

### Spacing
- Card padding: 20px
- Page padding: 24px
- Widget gap: 16-20px
- Sidebar item height: ~48px

### Cards
- Background: white
- Border: 1px solid with very subtle green-gray tint
- Border radius: 8px for cards, 6px for buttons
- Shadow: extremely subtle (0 1px 3px rgba(0,0,0,0.05))

### Buttons
| Type | Background | Text | Border |
|------|-----------|------|--------|
| Teal CTA | #2B8C96 | white | none |
| Green primary | #3f9107 | white | none |
| Green outlined | white | #3f9107 | 1px #3f9107 |
| Gray outlined | white | dark gray | 1px #d5d7da |
| Active tab pill | #4AA74B | white | none, rounded |
| Dataro badge | gradient #00B4D8→#48CAE4 | white | none |

---

## CRITICAL DESIGN NOTES

1. **Match the real Bloomerang screenshots exactly** for all standard elements. The attached `homepage.jpg` and `contact_record.jpg` are the most important references — they show the complete real UI.

2. **Dataro elements should feel native.** Use teal (#00B4D8) as a subtle accent — left border, small badge — NOT a heavy redesign. The Fundraising Brain card on the dashboard is the one exception where Dataro gets prominent treatment.

3. **The sidebar is simple.** Only 7 items. No sub-menus expanded. Match `navigation/02_search_bar.png` exactly.

4. **"Ask Penny" button** is new and not in all screenshots. Add it to the top-right header bar between the help icon and user avatar. Small teal-outlined button with sparkle icon.

5. **The Penny chat panel** slides over from the right and partially overlays the page content. Page 3 should show Page 2's content visible but dimmed behind the panel.

6. **Use 1440x900 desktop viewport.** Sidebar is 200px. Content area fills the rest.
