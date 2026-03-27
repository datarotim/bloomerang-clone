# Pixel-Accurate UI Observations
## From Actual Bloomerang CRM Screenshots (TrustRadius + SoftwareConnect)

---

## CRITICAL: Font Discovery

The actual CRM product uses **mixed typography**:
- **Dollar amounts / large metrics:** Serif font (appears to be Georgia or similar) — large, bold, high contrast, dark charcoal
- **Labels and headers:** Sans-serif, uppercase, letter-spaced, gray
- **Body text:** Clean sans-serif (system fonts or Open Sans-style)
- **Navigation labels:** Sans-serif, regular weight

NOTE: The Quicksand font may be used in the NEWER version (post-2025 rebrand). These screenshots may be from an earlier version. The current version likely uses Quicksand for all UI elements. For the mockup, use Quicksand throughout but keep serif for large dollar amounts as an option.

---

## Screenshot 1: Giving Summary (constituent_summary.png)

### Layout
- White card with very subtle green-tinted border/shadow
- Top-right: minimize (—), maximize (square), close (X) icons in green
- Title: "Giving Summary" in large dark serif text

### Toggle Buttons (top-right of card)
- Three pill buttons in a row:
  - "Revenue" — GREEN background (#4AA74B), white text, rounded
  - "Raised" — BLUE/TEAL background (#2B8C96), white text, rounded
  - "Soft Credits" — BLUE/TEAL background, white text, rounded

### Chart
- Area chart with green solid line + filled green area (Revenue)
- Blue dashed line (Raised/Soft Credits)
- Circle data points at each year
- X-axis: Years ('13 through '22) in gray
- Y-axis: Dollar amounts (55000, 110000) in gray
- Green area fill is a soft sage/lime green

### Metrics Below Chart
- Two-column layout:
- **Lifetime:** Two green badges — dark green ($576,502.50) and lighter green ($610,252.50)
  - Badges: rounded rectangles with green backgrounds, white text
- **Average:** Same two-badge format
- **First Transaction:** Dollar amount in green text + date in dark text
- **Latest Transaction:** Same format
- **Largest Transaction:** Same format

### Colors Observed
- Green badges: ~#4AA74B (dark), ~#7BC67E (lighter)
- Chart fill: Sage green with transparency
- Blue/teal: ~#2B8C96

---

## Screenshot 2: Constituent Timeline (constituent_timeline.png)

### Header Bar
- **Profile photo:** Gray circle placeholder with person silhouette
- **Name:** "Sarah Jane Smith" in large bold dark text
- **ID:** "#1" in gray after name
- **Email:** "sarahjane@thetardis.com" in teal/green clickable text
- **Address section:** "9120 Otis Ave" / "Indianapolis, IN 46216-2207" in teal/green text
- **Phone section:** "Work (866) 332-2999" in dark text
- **Relationship Manager:** "Diana Otero" in dark text
- **Action button:** Teal circle with white down chevron (dropdown) at far right

### Tab Navigation
- Horizontal row of 4 tabs:
  - **Summary** — gray text, no background (inactive)
  - **Profile** — gray text, no background (inactive)
  - **Timeline** — GREEN filled rectangle, white text, rounded corners (ACTIVE)
  - **Relationships** — gray text, no background (inactive)
- Active style: Solid green (#4AA74B) background, white text, rounded rectangle shape
- Inactive style: Dark gray text, no background, just text

### Timeline Layout
- **Year header:** "2025" in green rounded rectangle at top center
- **Central vertical gray line** running down the page
- **Timeline entries on LEFT side:**
  - White card with left green/gray border
  - Entry title in teal/green bold text (clickable)
  - Description/details in gray text below
  - Date on right side of card (e.g., "September 3")
- **Icons on center line:**
  - Blue speech bubble = emails/interactions
  - Green gift/present icon = payments/donations
- **Highlights card** (between timeline entries):
  - Yellow/cream background (#FFF8E1 or similar)
  - "Highlights" header in bold
  - Bullet points: "Upgraded from $26,597.21 to $57,913.85", "Has donated 15 years in a row", "Has upgraded 2 years in a row"

### Right Sidebar (Timeline)
- **Year navigation:** "2025" and "Older" with green dot indicators
- **Filter buttons (vertical stack, pill/oval shape):**
  - "All" — GREEN filled circle (active)
  - "Transactions" — gray outlined oval
  - "Interactions" — gray outlined oval
  - "Tasks" — gray outlined oval
  - "Notes" — gray outlined oval
  - "Attachments" — gray outlined oval
- **"List View" button:** Gray outlined, top-right

---

## Screenshot 3: Donor Retention (donor_retention.png)

### Layout
- White card with subtle green-tinted shadow
- Header: "DONOR RETENTION" in gray uppercase tracking
- Pencil/edit icon at top-right

### Donut Chart
- Large centered donut ~200px
- **Filled portion:** Dark green (#3F9107)
- **Unfilled portion:** Light sage green (#D4E8C4)
- **Center:** Large bold "58%" in dark charcoal + "CUSTOM" in gray uppercase below
- Left chevron (<) for navigating between retention views

### Below Chart
- "83 out of 142 donors retained" in dark text
- Two pagination dots at bottom (one dark/active, one light/inactive)

---

## Screenshot 4: Amount Raised (amount_raised.png)

### Layout
- White card with subtle shadow
- Header: "AMOUNT RAISED" in gray uppercase tracking (letter-spaced)
- Three rows separated by thin light gray horizontal lines:

### Row 1: This week
- "This week" label in small gray sans-serif
- "$15" in VERY LARGE bold serif font, dark charcoal
- "1 transactions" / "$15.00 avg" in smaller gray text (right-aligned)

### Row 2: This month
- "$10,304" in large bold serif
- "69 transactions" / "$149.34 avg"

### Row 3: This fiscal year
- "$33,596" in large bold serif
- "305 transactions" / "$110.15 avg"

### Typography Detail
- Dollar amounts: ~36-40px, bold, serif (Georgia-like), dark charcoal (#333)
- Labels: ~12px, regular weight, gray
- Transaction details: ~13px, regular weight, gray, right-aligned

---

## Screenshot 5: Tasks Widget (tasks_widget.png)

### Layout
- White card with subtle shadow
- Header: "TASKS" in gray uppercase + clock icon on left
- Top-right: Dark circle with white "+" (add button)

### Tab Navigation
- Two tabs: "ALL" (bold, dark text, green underline) and "MY" (gray text)
- Active underline: Thick green (#3F9107) bar below "ALL"

### Section Label
- "DUE LATER" in gray uppercase tracking

### Task Entries
Each task entry shows:
- **Title:** Bold dark text (e.g., "Send out e-vites to upcoming virtual open house/tour")
- **Organization:** Regular dark text (e.g., "Will and Belinda Grapes Foundation")
- **Channel:** Gray text (e.g., "Mass Email", "Email", "Phone")
- **Assignee:** Gray text (e.g., "Assignee: Westley")
- **Date:** Gray uppercase on right (e.g., "DEC 01", "DEC 10", "JAN 01")
- **Chevron:** Gray ">" on right

---

## Screenshot 6: Generosity Score (generosity_score.png)

### Layout
- White card with subtle shadow

### Header Row
- **Dataro icon:** Dataro logo (teal #2B8C96)
- **Title:** "Generosity" in large dark serif text
- **"Update" button:** Gray outlined, rounded corners, right-aligned

### Score Bar
- **Horizontal segmented bar** with 5 equal segments
- **Color:** All segments filled with RED (#E74C3C or similar)
- Segments have subtle separators/borders
- Full bar = "On Fire!" level
- Gradient effect: slightly varying red shades across segments

### Score Label
- "On Fire!" in large dark text below bar

### CTA Button
- **"View Generosity Details"** button
- Full-width
- TEAL background (#2B8C96 or similar)
- White text
- Rounded corners
- Generous padding

---

## Summary of Actual UI Colors (from screenshots)

| Element | Approximate Color |
|---------|------------------|
| Active nav/tab green | #4AA74B |
| Brand dark green | #3F9107 |
| Teal (Dataro/CTA) | #2B8C96 |
| Generosity bar red | #E74C3C |
| Chart green fill | #7BC67E (with transparency) |
| Retention donut filled | #3F9107 |
| Retention donut empty | #D4E8C4 |
| Highlights card bg | #FFF8E1 (cream/yellow) |
| Card border/shadow | Very subtle green-gray tint |
| Header text | #333333 (dark charcoal) |
| Label text | #999999 (gray, uppercase) |
| Body text | #535862 |
| Timeline icon blue | #2B8C96 (teal) |
| Timeline icon green | #4AA74B |
| Badge green dark | #4AA74B |
| Badge green light | #7BC67E |

---

## Card Style Details

### Border/Shadow
- Very subtle: appears to be a 1px light green-gray border plus very subtle shadow
- Not a heavy drop shadow — clean and minimal
- Green tint in the border is very subtle (#E8EDE5 or similar)

### Padding
- Card internal padding: ~20-24px
- Widget header to content: ~16px
- Content sections separated by thin gray lines

### Typography Hierarchy
1. Widget headers: UPPERCASE, letter-spaced, gray, ~12px, sans-serif
2. Dollar/metric values: Large bold serif, ~32-40px, dark charcoal
3. Subtitles/labels: Regular weight sans-serif, ~13px, gray
4. Clickable items: Teal/green color (#4AA74B), regular weight
5. Dates: Uppercase, gray, ~12px, monospace-like
