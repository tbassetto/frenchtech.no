---
name: La French Tech Oslo
description: Community landing page for Oslo's La French Tech chapter.
colors:
  campaign-magenta: "oklch(41.9% 0.168 7.5)"
  campaign-wine: "oklch(35.8% 0.155 340.9)"
  campaign-violet: "oklch(28.1% 0.169 280.4)"
  campaign-blue: "oklch(59.7% 0.215 258.0)"
  campaign-cyan: "oklch(62.2% 0.202 255.1)"
  french-tech-red: "oklch(61.5% 0.252 29.2)"
  french-tech-red-deep: "oklch(52.3% 0.215 29.2)"
  map-pin-grey: "oklch(93.1% 0.000 89.9)"
  ink: "oklch(24.4% 0.000 89.9)"
  black: "oklch(0.0% 0.000 0.0)"
  white: "oklch(100.0% 0.000 89.9)"
typography:
  display:
    fontFamily: "Montserrat, Arial, sans-serif"
    fontWeight: 800
    lineHeight: 0.95
    letterSpacing: "-0.025em"
  body:
    fontFamily: "Montserrat, Arial, sans-serif"
    fontWeight: 400
    lineHeight: 1.55
  condensed:
    fontFamily: "Oswald, Arial Narrow, sans-serif"
    fontWeight: 500
    lineHeight: 1.05
rounded:
  sm: "4px"
  md: "8px"
  badge: "999px"
spacing:
  sm: "8px"
  md: "16px"
  lg: "32px"
  xl: "64px"
components:
  button-primary:
    backgroundColor: "{colors.french-tech-red}"
    textColor: "{colors.white}"
    rounded: "{rounded.sm}"
    padding: "12px 18px"
  button-secondary:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    rounded: "{rounded.sm}"
    padding: "12px 18px"
  campaign-band:
    backgroundColor: "{colors.campaign-violet}"
    textColor: "{colors.white}"
    rounded: "{rounded.sm}"
    padding: "32px 64px"
---

# Design System: La French Tech Oslo

<!-- SEED: re-run $impeccable document once the site has real CSS to capture actual implementation tokens and components. -->

## 1. Overview

**Creative North Star: "Local-to-Global Signal"**

The banner reference is the primary brand extraction source. The system is not only the rooster logo: it is a high-energy campaign field that moves from saturated magenta-red through deep violet into electric blue, with white knockout typography, a faint world-map texture, and a compact circular chapter badge. It feels official because it uses the La French Tech identity confidently; it feels startup because the gradient, compressed layout, and strong type create forward motion.

The landing page should translate that campaign language into a usable community site. Use the gradient as a major brand moment, not as a decorative wash everywhere. Keep the chapter badge/logo visible, use white text on saturated campaign surfaces, and make the Oslo chapter feel connected to a global network.

**Key Characteristics:**
- Local-to-global narrative: Oslo is one node in a global French Tech network.
- Saturated campaign gradient: magenta/red to violet to electric blue.
- White knockout typography on campaign surfaces.
- Bold geometric display type paired with compact condensed support copy.
- Official circular badge treatment for the chapter mark.
- Subtle map/network texture is allowed when it supports global reach.

## 2. Colors

The brand palette is a campaign gradient, not a single logo red. Red remains the La French Tech identity anchor, but violet and blue carry the global/network atmosphere.

### Primary
- **Campaign Magenta** (`oklch(41.9% 0.168 7.5)`): Left side of hero/campaign bands and energetic local chapter moments.
- **Campaign Violet** (`oklch(28.1% 0.169 280.4)`): Central depth color. Use it to make the page feel institutional and global, not playful.
- **Campaign Blue** (`oklch(59.7% 0.215 258.0)`): Right side of campaign bands, global network cues, and high-energy highlights.

### Secondary
- **Campaign Cyan** (`oklch(62.2% 0.202 255.1)`): Bright edge highlight pulled from the blue side of the banner. Use for glints, thin network lines, or hover energy.
- **La French Tech Red** (`oklch(61.5% 0.252 29.2)`): Logo, badge detail, primary CTAs, and core identity moments.
- **Deep La French Tech Red** (`oklch(52.3% 0.215 29.2)`): Hover, pressed, and deeper brand moments.

### Neutral
- **White** (`oklch(100.0% 0.000 89.9)`): Knockout campaign text, badge interiors, and default page background.
- **Ink** (`oklch(24.4% 0.000 89.9)`): Body text on light surfaces.
- **Black** (`oklch(0.0% 0.000 0.0)`): Heavy emphasis and logo-aligned wordmark weight.
- **Map Pin Grey** (`oklch(93.1% 0.000 89.9)`): Badge support, quiet dividers, and neutral map-pin echoes.

### Named Rules
**The Campaign Gradient Rule.** When the page needs a brand moment, use a deliberate magenta -> violet -> blue composition. Do not substitute generic purple-blue gradients.

**The Knockout Rule.** White text belongs on saturated campaign surfaces. Dark text on these colors looks muddy and is prohibited.

**The No-Beige Rule.** Do not warm the page into cream, sand, parchment, or beige. Warmth comes from campaign magenta/red, not the background.

## 3. Typography

**Display Font:** Montserrat, Arial, sans-serif
**Body Font:** Montserrat, Arial, sans-serif
**Label/Mono Font:** Oswald or Arial Narrow for compact campaign support copy; no mono by default.

**Character:** The banner uses hard, confident geometric sans typography: heavy rounded display words, tight line-height, and compact condensed support text. The site should feel like a campaign system with official restraint, not a soft community newsletter.

### Hierarchy
- **Display** (800, clamp to be chosen, line-height 0.95): Hero statements and major campaign words such as "From local to global".
- **Headline** (700-800, size to be chosen, line-height 1.05): Section headings and conversion moments.
- **Title** (600-700, size to be chosen, line-height 1.15): Small grouped content headings.
- **Body** (400, 1rem baseline, line-height 1.55): Paragraphs, membership benefits, and explanatory copy. Keep prose at 65-75ch.
- **Condensed Support** (500, compact size, line-height 1.05): Short campaign support lines only. Do not use it for long paragraphs.
- **Label** (700, compact size, normal or slightly tight letter spacing): CTA and navigation text.

### Named Rules
**The Campaign Type Rule.** Display text should be bold, compact, and confident. Avoid delicate editorial type, serif headlines, or thin luxury typography.

**The No-Eyebrow Scaffold Rule.** Do not create repeated tiny uppercase tracked labels above every section. The banner uses direct campaign copy, not templated section eyebrows.

## 4. Elevation

Depth comes from luminous color transitions, map/network texture, badge contrast, and scale. The brand does not need soft card shadows to feel polished.

### Shadow Vocabulary
- **Badge Lift** (`0 8px 24px rgba(0, 0, 0, 0.18)`): Only for circular logo/badge treatment on saturated campaign backgrounds.

### Named Rules
**The Texture-Over-Shadow Rule.** On campaign surfaces, use map texture, light streaks, or gradient depth before using card shadows.

## 5. Components

### Buttons
- **Shape:** Crisp, lightly rounded rectangles (4px).
- **Primary:** La French Tech Red background with white text.
- **Hover / Focus:** Deep La French Tech Red hover; visible focus ring that does not rely on color alone.
- **Campaign Variant:** White background with campaign-violet or ink text when placed on the magenta-violet-blue field.
- **Secondary:** Transparent or white background with ink text and a simple full border.

### Campaign Band
- **Structure:** Wide horizontal section with a magenta -> violet -> blue gradient.
- **Typography:** Bold display phrase on the left; compact support copy; official badge/logo as a circular interruption.
- **Texture:** Subtle world map or network-line texture may sit inside the gradient at low opacity.
- **Rule:** Never use this as a generic decorative banner. It must carry a real chapter/global message.

### Badge / Logo Lockup
- **Shape:** Circular white badge (`999px`) for the logo when placed over saturated gradients.
- **Background:** White interior with optional Map Pin Grey support shape.
- **Shadow Strategy:** Badge Lift only when the badge sits on the campaign gradient.
- **Spacing:** Give the badge enough air; do not crowd it into nav text.

### Cards / Containers
- **Corner Style:** Use only when grouping repeated content; keep radius modest (8px).
- **Background:** White or Map Pin Grey on light pages; avoid nested cards.
- **Shadow Strategy:** Flat by default.
- **Border:** Prefer simple full borders or tonal separation, never side-stripe accents.
- **Internal Padding:** Start from 16px and 32px steps.

### Navigation
- **Style:** Minimal and logo-led. Navigation should not compete with the primary member/follow actions.
- **Mobile Treatment:** Keep CTAs reachable without adding a heavy app-like shell.

## 6. Do's and Don'ts

### Do:
- **Do** extract from the full banner: gradient, typography, badge, map texture, and local-to-global message.
- **Do** preserve La French Tech's logo, red, and official network signal.
- **Do** make the Oslo chapter clear immediately.
- **Do** use white knockout text on saturated campaign surfaces.
- **Do** use the campaign gradient only for high-value brand moments.
- **Do** keep the two primary actions obvious: follow on LinkedIn and become a free member.
- **Do** meet WCAG AA contrast and support keyboard-visible focus states.

### Don't:
- **Don't** reduce the brand to the rooster logo alone.
- **Don't** make it too playful, informal, or mascot-like.
- **Don't** dilute the existing La French Tech identity.
- **Don't** use generic startup landing-page tropes, interchangeable SaaS card grids, gratuitous gradients, or hero metrics.
- **Don't** use a generic purple-blue gradient that ignores the magenta -> violet -> electric blue campaign structure.
- **Don't** use visuals that feel unrelated to Oslo or the French Tech network.
- **Don't** repeat tiny uppercase tracked eyebrows above every section.
- **Don't** use border-left or border-right accents greater than 1px as side-stripe decoration.

