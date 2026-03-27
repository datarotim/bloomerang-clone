# Bloomerang Brand & Visual Design Guide
## For Figma Reconstruction

---

## 1. Brand Overview

Bloomerang is a nonprofit CRM and Giving Platform. Their 2025 brand refresh (by Emotive Brand) uses the concept **"Pushing Purpose Higher"**. They have TWO design contexts:

- **Marketing site** (bloomerang.com) — bold, editorial, black-heavy
- **CRM application** (crm.bloomerang.co) — clean, light, functional

For the Figma mockup of the **platform**, use the CRM application style.

---

## 2. Color Palette

### Primary Colors
| Name | Hex | RGB | Usage |
|------|-----|-----|-------|
| Bloomerang Green (Primary) | `#3f9107` | 63, 145, 7 | Primary brand, active states, CTA buttons, success |
| Lime Green (Accent) | `#94cf35` | 148, 207, 53 | Hover states, highlights, logo mark |
| Light Green | `#d7f5c3` | 215, 245, 195 | Active sidebar bg, tags, success bg |
| Black | `#000000` | 0, 0, 0 | Marketing site primary (not used in CRM app) |
| White | `#ffffff` | 255, 255, 255 | Card backgrounds, main content bg |

### Secondary Colors
| Name | Hex | Usage |
|------|-----|-------|
| Royal Blue | `#2a80e4` | Info states, links, secondary accent |
| Light Blue | `#bae7ff` | Info backgrounds |
| Tangerine Orange | `#f4913c` | Warning states, engagement "hot" |
| Supernova Yellow | `#ffc600` | Engagement "warm", logo accent |
| Pink | `#f37cec` | Decorative accent |
| Purple | `#c396de` | Decorative accent |

### Gray Scale (CRM App)
| Name | Hex | Usage |
|------|-----|-------|
| Gray 900 | `#252b37` | Darkest text, headings |
| Gray 700 | `#535862` | Secondary text, sidebar text |
| Gray 600 | `#6c757d` | Muted text, icons |
| Gray 500 | `#a4a7ae` | Placeholder text, disabled |
| Gray 400 | `#717680` | Border hover |
| Gray 300 | `#d5d7da` | Borders, dividers |
| Gray 200 | `#e9eaeb` | Light borders, table borders |
| Gray 100 | `#f4f5f5` | Page background, input bg |
| Gray 50 | `#f8f9fa` | Table header, lightest bg |

### Engagement Meter Colors
| Level | Color | Hex |
|-------|-------|-----|
| Cold | Blue | `#2a80e4` |
| Cool | Light Blue | `#bae7ff` |
| Warm | Yellow | `#ffc600` |
| Hot | Orange | `#f4913c` |
| On Fire | Red | `#dc3545` |

### Semantic Colors
| Purpose | Hex |
|---------|-----|
| Success | `#3f9107` |
| Info | `#2a80e4` |
| Warning | `#f4913c` |
| Danger/Error | `#dc3545` |

---

## 3. Typography

### CRM Application (Use This for Mockup)
- **Font Family:** Quicksand (Google Fonts)
- **Style:** Geometric sans-serif with rounded terminals
- **Weights:** 300 (Light), 400 (Regular), 500 (Medium), 600 (SemiBold), 700 (Bold)
- **Character:** Friendly, approachable, modern

### Type Scale (CRM App)
| Element | Size | Weight | Color |
|---------|------|--------|-------|
| Page Title (H1) | 28px / 1.75rem | 700 Bold | `#252b37` |
| Section Header (H2) | 22px / 1.375rem | 600 SemiBold | `#252b37` |
| Card Header (H3) | 18px / 1.125rem | 600 SemiBold | `#252b37` |
| Sub Header (H4) | 16px / 1rem | 600 SemiBold | `#535862` |
| Body Text | 15px / 0.9375rem | 400 Regular | `#535862` |
| Secondary Text | 14px / 0.875rem | 400 Regular | `#6c757d` |
| Caption / Label | 12px / 0.75rem | 500 Medium | `#a4a7ae` |
| Overline | 11px / 0.6875rem | 600 SemiBold | `#a4a7ae` (uppercase) |

### Marketing Site (Reference Only)
- **Headings:** PP Right Serif (Pangram Pangram), weights 300-500
- **Body/UI:** PP Right Grotesk (Pangram Pangram), weights 200-900

---

## 4. Button Styles

### CRM App Buttons
| Type | Background | Text | Border | Radius | Height |
|------|-----------|------|--------|--------|--------|
| Primary | `#3f9107` | `#ffffff` | none | 6px | 36px |
| Primary Hover | `#357a06` | `#ffffff` | none | 6px | 36px |
| Secondary | `#ffffff` | `#535862` | 1px `#d5d7da` | 6px | 36px |
| Secondary Hover | `#f4f5f5` | `#535862` | 1px `#717680` | 6px | 36px |
| Danger | `#dc3545` | `#ffffff` | none | 6px | 36px |
| Ghost | transparent | `#3f9107` | none | 6px | 36px |
| Icon Button | `#ffffff` | `#6c757d` | 1px `#d5d7da` | 6px | 36px |

- Font: Quicksand 600 SemiBold, 14px
- Padding: 8px 16px
- Transition: 0.15s ease

### Marketing Site Buttons (Reference)
- Pill shape: border-radius 45px
- Black bg, white text → lime green bg, black text on hover
- Arrow button variant with animated green circle

---

## 5. Cards & Containers

### Standard Card
- Background: `#ffffff`
- Border: 1px solid `#e9eaeb`
- Border Radius: 8px
- Padding: 20px
- Shadow: `0 1px 3px rgba(0,0,0,0.08)`

### Elevated Card (Dashboard widgets)
- Shadow: `0 4px 6px -2px rgba(10,13,18,0.05), 0 12px 16px -4px rgba(10,13,18,0.1)`

### Section Container
- Background: `#f4f5f5`
- Padding: 24px
- Border Radius: 8px

---

## 6. Form Elements

### Text Input
- Height: 38px
- Border: 1px solid `#d5d7da`
- Border Radius: 6px
- Padding: 8px 12px
- Font: Quicksand 400, 15px
- Placeholder: `#a4a7ae`
- Focus: border `#3f9107`, shadow `0 0 0 3px rgba(63,145,7,0.15)`

### Select / Dropdown
- Same as text input
- Chevron icon right-aligned

### Checkbox
- 16x16px, border-radius 3px
- Checked: `#3f9107` bg with white checkmark

### Toggle
- 40x20px track
- Off: `#d5d7da` track, white circle
- On: `#3f9107` track, white circle

---

## 7. Icons

- **CRM App:** Material Design style icons (outlined), colorblind-accessible
- **Marketing Site:** Font Awesome 6 Pro (Solid, Regular, Duotone, Sharp)
- **Icon Size:** 20px default, 16px small, 24px large
- **Icon Color:** `#6c757d` default, `#3f9107` active

---

## 8. Spacing System

Base unit: 4px

| Token | Value | Usage |
|-------|-------|-------|
| space-1 | 4px | Tight gaps, icon padding |
| space-2 | 8px | Between related elements |
| space-3 | 12px | Small component padding |
| space-4 | 16px | Standard padding, card inner |
| space-5 | 20px | Card padding |
| space-6 | 24px | Section spacing |
| space-7 | 32px | Between cards |
| space-8 | 40px | Large section gaps |
| space-9 | 48px | Page top padding |
| space-10 | 64px | Major section breaks |

---

## 9. Layout

### CRM App Layout
- **Sidebar Width:** 240px (expanded), 64px (collapsed)
- **Header Height:** 56px
- **Content Max Width:** 1200px
- **Page Padding:** 24px
- **Grid:** 12-column responsive
- **Background:** `#f4f5f5`

### Breakpoints
| Name | Width |
|------|-------|
| sm | 576px |
| md | 768px |
| lg | 992px |
| xl | 1200px |
| xxl | 1400px |

---

## 10. Navigation

### Left Sidebar
- White background
- Bloomerang CRM logo at top (green leaf mark + "Bloomerang CRM" text)
- Collapsible via chevron icon
- Active item: `#d7f5c3` background, `#3f9107` text and icon
- Hover: `#f4f5f5` background
- Dividers between sections: 1px `#e9eaeb`
- Apps switcher icon for Bloomerang product switching

### Top Header Bar
- White background, 56px height
- Left: breadcrumb navigation (Org Name > Page Name)
- Center/Right: Global search bar
- Right: Notifications bell (red dot indicator), "Ask AI" button (Penny), User avatar/menu

---

## 11. Penny AI Visual Style

- **Access:** "Ask AI" button in the top toolbar on every page
- **Panel:** Right-side slide-out panel, ~380px wide
- **Background:** White
- **User messages:** `#f4f5f5` bubbles
- **AI messages:** `#d7f5c3` bubbles (green tint)
- **Suggested prompts:** Pill-shaped buttons
- **Avatar:** Penny icon (likely green-themed)
- **Input:** Chat input bar at bottom of panel
- **Conversation history:** Supports past conversations

---

## 12. Logo

- **Mark:** Stylized leaf/petal in green (`#94cf34`) with yellow accent (`#ffc600`)
- **Wordmark:** "Bloomerang" in PP Right Grotesk Bold, black
- **Product Label:** "CRM" appears below/beside wordmark in lighter weight
- **Minimum size:** ~125px width
- **Spacing:** Clear space equal to the height of the "B" character
