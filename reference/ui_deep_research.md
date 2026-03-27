# Bloomerang CRM UI Deep Research
## Comprehensive Platform Interface Documentation

---

## 1. CRM Application Overview

- **URL:** crm.bloomerang.co
- **Type:** Cloud-hosted web application (JavaScript-rendered SPA)
- **Font:** Quicksand (Google Fonts) — geometric sans-serif with rounded terminals
- **Style:** Clean, light, functional, friendly. Gray background with white cards.
- **Target Users:** Small-medium nonprofits, <5K records, solo fundraisers, $500K-$10M orgs

---

## 2. Navigation Structure

### Left Sidebar
- White background, collapsible (240px expanded, ~64px collapsed)
- Bloomerang CRM logo at top (green leaf mark + "Bloomerang CRM" text)
- Collapse Side Navigation icon attached to side navigation menu
- Apps icon for switching between Bloomerang products (CRM, Fundraising, Volunteer)
- Product logo shows "Bloomerang CRM" to indicate current product
- Active item: green background (#d7f5c3), green text/icon (#3f9107), left border accent
- Hover: light gray (#f4f5f5) background

### Sidebar Menu Items — TWO VERSIONS IDENTIFIED

#### Version A: Older UI (from SoftwareConnect/TrustRadius screenshots)
1. Dashboard (house icon, green active state with left border)
2. Constituents (person icon)
3. Reports (bar chart icon)
4. Letters (envelope icon, with sub-arrow)
5. Emails (email icon)
6. Social Hub (connected circles icon)
7. Data Tools (database icon)
8. Settings (gear icon)
9. Kindful (integration link at bottom)

#### Version B: Current UI (2025-2026, from help center + changelog + agent research)
1. **Home** (Dashboard renamed to "Home" in 2025)
2. **Constituents** — donor/contact management
3. **Transactions** — donation management (renamed from "Donations")
4. **Campaigns** — campaign tracking
5. **Communications** section:
   - Emails
   - Letters
   - Tasks
   - Interactions
6. **Fundraising** section:
   - Online Forms
   - Journeys (Journey Automation, added July 2025)
   - Memberships
7. **Reports** — filter-based reporting
8. **Settings** — org and user configuration

### Additional Sidebar Items (from agent research, current version)
- **Groups** — constituent segmentation
- **Online Forms** — web forms
- **Payments** — payment processing
- **Journey Automation** — automated workflows

### Top Header Bar (Fixed)
- White background, ~56px height
- Left: Breadcrumb navigation (Organization Name > Current Page)
- Center: Global search bar (accessible from any page)
- Right actions:
  - Notifications bell (red dot indicator, not number; two tabs: hidden/unhidden)
  - Help icon
  - **"Ask AI" button** — appears on EVERY page toolbar; opens Penny AI
  - User avatar/profile menu

---

## 3. Home Page (Dashboard)

### Donor Retention Wheel
- Circular/radial visualization of retention metrics
- Shows overall retention rate prominently
- Updates daily
- Shows first-time vs repeat donor retention rates
- Industry average comparison

### First-Time Donor Calls
- Tile on dashboard
- Automatically shows top 5 first-time donors to call
- Includes gift details directly on dashboard
- Can delegate outreach to team members

### Incoming Donations
- Real-time donation feed
- View by week/month/year
- Shows donor name, amount, timestamp, method

### Campaign Progress
- Active campaigns with progress bars
- Goal vs. raised amounts

### Engagement Scoring
- At-a-glance constituent engagement scores
- Based on giving, volunteerism, marketing engagement

### Suggestions for Improvement
- AI/system-generated recommendations

---

## 4. Constituent Profile Page

### Source: Bloomerang Academy Training PDF

The constituent page has **4 main tabs** plus a persistent header:

### Constituent Header (Always Visible)
- Constituent name, type (Individual/Organization)
- Profile picture with pencil icon to edit
- Constituent type indicator
- Quick-action dropdown ("New Relationship" from any tab)
- Assigned groups displayed

### Tab 1: Summary
- **Giving Summary** — total giving, recent gifts, giving trends
- **Recent Timeline** — abbreviated latest interactions
- **Engagement Level** — Cold → Cool → Warm → Hot → On Fire
  - Algorithm by Dr. Adrian Sargeant
  - Based on giving, volunteerism, marketing engagement
- **Generosity Score** — from DonorSearch wealth screening
  - Same scale: Cold → Cool → Warm → Hot → On Fire
- **Relationships** — linked contacts, households

### Tab 2: Profile
- **Information area** — contact details, demographics
  - Edit, merge, change type, or delete
- **Custom Fields** — user-defined fields
- **Created/Modified info** at bottom

### Tab 3: Timeline
- Chronological view of every touchpoint
- "Social media timeline" format — vibrant, interactive
- Toggle: timeline view / list view
- Filter by type on right side
- Icons match type (donations, emails, calls, events, etc.)
- Year navigation on right
- Highlights show major moments
- Filter: "Interactions (No Mass Emails)"

### Tab 4: Relationships
- Household relationships
- Employer relationship
- Other database relationships

---

## 5. Penny AI Interface

- **"Ask AI" button** in toolbar on EVERY page
- Currently in **BETA**
- **Right-side slide-out panel** (chat-based)
- Can start new conversations or continue past ones
- Suggested prompts + free-text input
- Grounded in org's CRM data + 2,000+ consulting wins
- Identifies at-risk donors, surfaces opportunities, prepares for meetings
- Explains WHY she makes recommendations

---

## 6. Recent Updates (2025-2026)

- Dashboard renamed to "Home"
- Communications menu added to navigation
- Journey Automation (July 2025)
- SSO across CRM + Fundraising
- Bloomerang Payments consolidation
- Penny AI beta launch (2026)
- 6 additional wealth screening markers
- Prospective Donor Automation
- Brand refresh by Emotive Brand

---

## 7. Design System (CRM App)

| Element | Value |
|---------|-------|
| Font | Quicksand (Google Fonts) |
| Background | #f4f5f5 |
| Card bg | #ffffff |
| Primary accent | #3f9107 |
| Lime accent | #94cf35 |
| Active bg | #d7f5c3 |
| Text primary | #252b37 |
| Text secondary | #535862 |
| Text muted | #6c757d |
| Borders | #e9eaeb |
| Danger | #dc3545 |
| Info | #2a80e4 |
| Warning | #f4913c |
| Card shadow | 0 1px 3px rgba(0,0,0,0.08) |
| Card radius | 8px |
| Button radius | 6px |
| Sidebar width | 240px |
| Header height | 56px |
