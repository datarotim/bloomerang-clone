# Bloomerang CRM Component Inventory
## Complete UI Component Catalog for Figma Reconstruction

---

## Navigation Components

### 1. Left Sidebar
- **Width:** 240px expanded, ~64px collapsed
- **Background:** White (#ffffff)
- **Border:** 1px solid #e9eaeb (right)
- **Logo area:** Top section with green leaf mark + "Bloomerang CRM" text
- **Collapse toggle:** Chevron icon attached to sidebar
- **Menu items:** Icon (20px) + Label text, 10px vertical padding, 20px horizontal padding
- **Active state:** #d7f5c3 background, #3f9107 text/icon, 3px left green border
- **Hover state:** #f4f5f5 background
- **Section dividers:** 1px #e9eaeb, 8px margin
- **Section labels:** 11px uppercase, #a4a7ae, 600 weight
- **Apps switcher:** Bottom of sidebar, icon button

### 2. Top Header Bar
- **Height:** 56px
- **Background:** White (#ffffff)
- **Border:** 1px solid #e9eaeb (bottom)
- **Sticky:** yes
- **Left:** Breadcrumb (Org Name > Page Name)
- **Center-left:** Search input (36px height, #f8f9fa bg, search icon left)
- **Right:** Notification bell (red dot), Help icon, "Ask AI" button, User avatar

### 3. Breadcrumb
- **Font:** 14px Quicksand
- **Separator:** >
- **Color:** #a4a7ae for path, #252b37 bold for current page

---

## Dashboard Components

### 4. Metric Card
- **Background:** White
- **Border:** 1px solid #e9eaeb
- **Radius:** 8px
- **Padding:** 20px
- **Shadow:** 0 1px 3px rgba(0,0,0,0.08)
- **Label:** 12px, 600 weight, #a4a7ae, uppercase
- **Value:** 32px, 700 weight, #252b37
- **Change indicator:** 13px, green (#3f9107) for up, red (#dc3545) for down, with arrow icon

### 5. Donor Retention Wheel
- **Type:** Circular donut chart
- **Size:** ~180px diameter
- **Fill color:** #3f9107 (filled portion)
- **Empty color:** #e9eaeb
- **Center:** Percentage value (36px bold) + "Overall Rate" label
- **Below:** Detail rows (key-value pairs separated by 1px lines)

### 6. First-Time Donor Calls Tile
- **Card with list:** Top 5 donors with gift details
- **Each row:** Avatar, name, gift amount, date, call action button
- **Priority ordering**

### 7. Campaign Progress Bar
- **Name:** 14px, 600 weight
- **Bar:** 8px height, #e9eaeb background, #3f9107 filled
- **Stats row:** Flex space-between, 12px, #a4a7ae

### 8. Task List
- **Checkbox:** 18px square, 2px border #d5d7da, 4px radius
- **Checked:** #3f9107 fill with white checkmark
- **Text:** 14px, strikethrough + gray when done
- **Due date:** 12px, right-aligned, red for overdue

### 9. Recent Donations Feed
- **Avatar:** 36px circle, #d7f5c3 bg, green initials
- **Name:** 14px, 600 weight
- **Timestamp:** 12px, #a4a7ae
- **Amount:** 16px, 700 weight, #3f9107

---

## Constituent Components

### 10. Constituent Header
- **Height:** ~80px
- **Background:** White, bottom border
- **Profile photo:** 64px circle
- **Name:** 22px, 700 weight
- **Type badge:** Individual/Organization
- **Action buttons:** Edit, Email, Log Interaction, Add Note, More (...)

### 11. Tab Bar
- **Tabs:** Summary | Profile | Timeline | Relationships
- **Active tab:** #3f9107 text, 2px bottom border #3f9107
- **Inactive:** #535862 text
- **Font:** 14px, 600 weight

### 12. Engagement Meter
- **Visual:** Horizontal bar or gauge
- **Scale:** Cold (blue) → Cool (light blue) → Warm (yellow) → Hot (orange) → On Fire (red)
- **Score display:** Text label + visual indicator
- **Size:** Full card width

### 13. Generosity Score
- **Same visual style** as Engagement Meter
- **Same scale:** Cold → On Fire
- **Source label:** "Powered by Dataro"

### 14. Giving Summary
- **Card with metrics:**
  - Lifetime giving (large number)
  - Last gift (amount + date)
  - Average gift
  - Giving trend (up/down indicator)

### 15. Timeline Entry
- **Icon:** 32px circle, color-coded by type
- **Content:** Entry title, description, date
- **Types with icons:**
  - Donation: dollar sign (green)
  - Email: envelope (blue)
  - Phone call: phone (orange)
  - Meeting: people (purple)
  - Event: calendar (yellow)
  - Note: document (gray)
  - Letter: mail (gray)
  - Task: checkmark (green)

---

## Dataro Integration Components (NEW)

### 16. Fundraising Brain Card (Dashboard)
- **Border:** 2px solid #00B4D8
- **Background:** White to #F0FBFF gradient
- **Badge:** "Fundraising Brain" — gradient pill (#00B4D8 to #48CAE4), white text
- **Powered by:** "Powered by Dataro" — 11px, #a4a7ae
- **Shadow:** 0 4px 16px rgba(0,180,216,0.12)

### 17. Prospect Opportunity Row
- **Layout:** Avatar + Info + Scores + Action button + Chevron
- **Avatar:** 44px circle, colored initials
- **Propensity score:** Pill shape, color-coded (green for high)
- **Ask amount:** Pill shape, green for recommended
- **Hover:** #00B4D8 border, slight lift shadow

### 18. Insight Mini Cards (Dashboard strip)
- **Grid:** 4 columns
- **Each card:** Icon (28px), value (22px bold), label (11px)
- **White bg, 8px radius, 1px border**

### 19. Dataro Intelligence Panel (Constituent Summary)
- **Left border:** 3px solid #00B4D8
- **Background:** #F0FBFF subtle
- **Contents:**
  - Score rows: label + value + traffic light
  - Recommended ask amount
  - Next Best Action text
  - Lapse risk indicator

### 20. ProspectAI Report (Constituent tab)
- **Sections:** Capacity, Affinity, Professional, Philanthropic, News, Due Diligence, Family, Interests
- **Each section:** Card with header, expandable content
- **Source links:** Clickable citations
- **Actions:** Add sources, Regenerate, Export

### 21. Prospect Search Card
- **Search bar:** Full-width, with filter dropdowns
- **Result card:** Name, title, company, location, capacity, affinity score
- **One-click "Add to CRM" button:** Green (#3f9107), prominent
- **Expanded view:** Mini ProspectAI report

---

## Penny AI Components

### 22. Ask AI Button (Header)
- **Height:** 36px
- **Border:** 1px solid #3f9107
- **Background:** White, hover #d7f5c3
- **Text:** "Ask Penny" — 13px, 600 weight, #3f9107
- **Icon:** Sparkle/auto_awesome (18px)

### 23. Penny FAB (Optional floating)
- **Size:** 56px circle
- **Background:** Linear gradient #3f9107 to #94cf35
- **Shadow:** 0 4px 16px rgba(63,145,7,0.3)
- **Icon:** Sparkle, white

### 24. Penny Chat Panel
- **Width:** 380px
- **Position:** Right-side slide-out
- **Background:** White
- **Header:** "Penny" + AI icon + Close (X)
- **Suggested prompts:** Pill buttons, 1px border, #f4f5f5 bg
- **User messages:** Right-aligned, #f4f5f5 bg bubble, 12px radius
- **Penny messages:** Left-aligned, #d7f5c3 bg bubble, 12px radius
- **Input bar:** Bottom, full-width, placeholder "Ask Penny anything..."
- **Send button:** Green circle with arrow

---

## Form Components

### 25. Text Input
- **Height:** 38px
- **Border:** 1px solid #d5d7da
- **Radius:** 6px
- **Font:** 15px Quicksand
- **Focus:** #3f9107 border, green shadow ring

### 26. Primary Button
- **Height:** 36px
- **Background:** #3f9107
- **Text:** White, 14px, 600 weight
- **Radius:** 6px
- **Hover:** #357a06

### 27. Secondary Button
- **Height:** 36px
- **Background:** White
- **Border:** 1px solid #d5d7da
- **Text:** #535862, 14px, 600 weight
- **Hover:** #f4f5f5 bg

### 28. Dropdown/Select
- **Same as text input** with chevron icon
- **Menu:** White bg, 8px radius, shadow-md, 1px border

### 29. Checkbox
- **Size:** 16x16px
- **Border:** 2px solid #d5d7da, 3px radius
- **Checked:** #3f9107 fill, white checkmark

### 30. Toggle
- **Track:** 40x20px
- **Off:** #d5d7da track
- **On:** #3f9107 track
- **Thumb:** White circle

---

## Data Display Components

### 31. Data Table
- **Header:** #f8f9fa bg, 600 weight text
- **Borders:** 1px #e9eaeb
- **Row hover:** #f4f5f5
- **Alternating:** Optional #fafbfb stripe

### 32. Badge/Tag
- **Padding:** 2px 8px
- **Radius:** 10px
- **Variants:** Green (#d7f5c3), Blue (#bae7ff), Gray (#f4f5f5), Red (light), Orange (light)

### 33. Avatar
- **Sizes:** 32px (small), 44px (medium), 64px (large)
- **Shape:** Circle
- **Initials:** White text on colored background
- **Colors rotate:** Green, Blue, Orange, Purple

### 34. Tooltip
- **Background:** #252b37
- **Text:** White, 12px
- **Radius:** 4px
- **Arrow:** Pointing to trigger
