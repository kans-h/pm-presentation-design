---
brand: Envision AI Labs (Envision Pharma Group)
slug: envision-ai-labs
website: https://www.envisionpharmagroup.com/technology/envision-ai-labs/
extracted_via: Firecrawl (branding format) + Elementor kit CSS (post-30.css, post-978.css)
---

# Envision AI Labs — Brand Style

## Visual Theme & Atmosphere
Light, clinical-but-warm enterprise design for life sciences: a white canvas with soft gray section bands, punctuated by one signature move — a purple→blue brand gradient (`#7119F4` → `#2E69FF`) used for the hero glow, gradient text highlights, and pill CTAs. Deep-violet "product panel" sections (gradient `#4E55D8` → `#4E14A3`) showcase AI platform UI against the light page. Everything is flat (no shadows), generously rounded (24–34px cards, full pills), and paced by Space Grotesk headings over a light-weight rounded body face. The mood: credible pharma authority with a confident, next-generation-AI accent.

## Colors
| Role | Hex | Notes |
|---|---|---|
| Background | `#FFFFFF` | Page canvas |
| Background Alt | `#F8F9FA` | Alternating section bands |
| Background Tint | `#F3F6FF` | Soft blue-tinted cards/callouts |
| Primary | `#7119F4` | Brand purple — links, numbered markers, gradient start (`--e-global-color-primary`) |
| Secondary | `#2E69FF` | Brand blue — CTAs, gradient end (`--e-global-color-secondary`) |
| Accent (one only) | `#7119F4` | Purple is the accent; blue only appears inside the gradient or on CTAs |
| Text Primary | `#222222` | Near-black, never pure black |
| Text Muted | `#636F96` | Blue-gray for captions, secondary copy |
| Border | `#E0E2EA` | Hairline dividers, card borders |
| Dark Panel | `#4E14A3` → `#4E55D8` | Deep-violet immersive sections (gradient 0deg, blue-violet at bottom) |
| Text on Dark | `#FFFFFFDB` | White at 86% opacity; borders on dark: `#FFFFFF26` |

**Brand gradient:** `linear-gradient(115deg, #7119F4 0%, #2E69FF 100%)` — hero glow, gradient text spans, CTA pills.
**Supporting palette** (charts/icons only, sparingly): deep navy `#07289B`, cyan `#00BFE9`, sky `#2BAEE3`, green `#31B787`, coral `#F15839`, magenta `#AA27AA`.

**Color scheme:** light
**Accent rule:** one accent for emphasis — the purple (or the purple→blue gradient as a single unit). Never purple and blue as two separate competing accents on one slide.

## Typography
- **Display / Headings:** Space Grotesk — free, Google Fonts. Weights 300–600. No fallback needed.
- **Body:** museo-sans-rounded (Adobe Typekit `zye8ekh`, weight 300) — licensed. Fallback: Nunito Sans (Google Fonts, weight 300/400) keeps the soft rounded feel.
- **Accent / Labels / Numbers:** Space Mono, weight 500 — the "01 / 02 / 03" numbered markers and technical labels. Free, Google Fonts.

| Role | Size | Font / Weight |
|---|---|---|
| Display hero | 60–68px | Space Grotesk 300 |
| H1 | 40–50px | Space Grotesk 400 |
| H2 | 28–36px | Space Grotesk 400 |
| Subhead | 20–24px | Space Grotesk 300 |
| Lead paragraph | 24–26px | museo-sans-rounded 300 |
| Body | 16px | museo-sans-rounded 300 |
| Caption / label | 12–14px | museo-sans-rounded 500 or Space Mono 500 |

Headlines are sentence case, weight-light, and often carry a gradient-text span on the key phrase (e.g. "next-generation AI").

## Spacing & Shape
- Base grid: 4px (Elementor kit base unit)
- Border radius: 24px standard cards, 26–34px feature panels, 999px / 200px pills (buttons, tags, inputs)
- Shadows: **no** — flat design; depth comes from gradients and section-color contrast
- Framework hint: custom (WordPress/Elementor); CSS variables work well

## Components
- **Primary CTA:** pill (999px radius), brand gradient `#2E69FF`→`#7119F4` background, white text, Space Grotesk
- **Secondary button:** white background, `#7119F4` text, 1px `#7119F4` border, 8px radius (Elementor kit default)
- **Inputs:** white, 1px `#CDCDCD` border, 30px pill radius, no shadow
- **Numbered lists:** oversized `01 02 03` markers in `#7119F4` Space Mono, bold lead-in phrase then regular copy
- **Dark showcase panels:** deep-violet gradient, 24px radius, product-UI imagery with a blue-white glow

## Voice & Personality
- Tone: professional, assured, human-centered — "AI augments, never replaces"
- Energy: medium
- Audience: healthcare and pharmaceutical professionals — medical affairs, publications, commercialization leaders

## Voice samples (real copy from the brand)
- "Where expert thinking meets next-generation AI"
- "One global partner. Smarter, faster solutions for life sciences"
- "This is what we call combined intelligence, enabling us to accelerate and elevate decision-making, scientific strategy, and communication."
- "AI-enabled teams: Augmenting human expertise with intelligent systems that elevate strategy, creativity, and execution."
- "AI-accelerated delivery: Smarter, faster, and more predictive solution delivery powered by advanced analytics and automation."
- "AI-infused platforms: Next-generation platforms built with machine learning at the core to provide real-time insights and future-ready capabilities."
- "Our experts work hand-in-hand with AI engineers to ensure that AI augments, rather than replaces, human judgment."

## Quick Reference (for Claude)
```css
:root {
  --bg: #FFFFFF;
  --bg-alt: #F8F9FA;
  --bg-tint: #F3F6FF;
  --fg: #222222;
  --fg-muted: #636F96;
  --accent: #7119F4;
  --accent-2: #2E69FF;
  --gradient-brand: linear-gradient(115deg, #7119F4 0%, #2E69FF 100%);
  --gradient-dark: linear-gradient(0deg, #4E55D8 19%, #4E14A3 100%);
  --border: #E0E2EA;
  --dark-fg: rgba(255,255,255,0.86);
  --dark-border: rgba(255,255,255,0.15);
  --radius: 24px;
  --radius-pill: 999px;
  --font-display: "Space Grotesk", sans-serif;
  --font-body: "museo-sans-rounded", "Nunito Sans", sans-serif;
  --font-mono: "Space Mono", monospace;
}
```

## Assets
- `logo.svg` — Envision Pharma Group logo (dark text + purple-gradient mark; for **light backgrounds only** — it contains `#222222`/`#6F6F6E` fills that vanish on dark)
- `reference-screenshot.png` — full-page capture of the AI Labs page (1920×1080)
- Typekit kit: `https://use.typekit.net/zye8ekh.css` (museo-sans-rounded / museo-sans)

---

## Reference
**Website:** [https://www.envisionpharmagroup.com/technology/envision-ai-labs/](https://www.envisionpharmagroup.com/technology/envision-ai-labs/)
