---
name: Gardenia Night Gold
colors:
  surface: '#111317'
  surface-dim: '#111317'
  surface-bright: '#37393d'
  surface-container-lowest: '#0c0e11'
  surface-container-low: '#1a1c1f'
  surface-container: '#1e2023'
  surface-container-high: '#282a2d'
  surface-container-highest: '#333538'
  on-surface: '#e2e2e6'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#e2e2e6'
  inverse-on-surface: '#2f3034'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#e1c46b'
  on-secondary: '#3c2f00'
  secondary-container: '#6a5500'
  on-secondary-container: '#e9cb71'
  tertiary: '#e9ca93'
  on-tertiary: '#402d04'
  tertiary-container: '#ccaf7a'
  on-tertiary-container: '#564217'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#ffe084'
  secondary-fixed-dim: '#e1c46b'
  on-secondary-fixed: '#231b00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#fedea5'
  tertiary-fixed-dim: '#e1c38c'
  on-tertiary-fixed: '#261900'
  on-tertiary-fixed-variant: '#584419'
  background: '#111317'
  on-background: '#e2e2e6'
  surface-variant: '#333538'
  night-charcoal: '#0B0D10'
  deep-onyx: '#11151B'
  surface-card: '#141A22'
  border-divider: '#2A3442'
  text-primary: '#F5F2EA'
  text-secondary: '#CFC8BC'
  gold-foil: '#D4AF37'
  gold-highlight: '#F0D277'
  gold-glow: '#FFDFA6'
  feedback-success: '#3DDC97'
  feedback-warning: '#F6C177'
  feedback-danger: '#FF5A6A'
typography:
  display-hero:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 64px
  display-hero-mobile:
    fontFamily: Noto Serif
    fontSize: 38px
    fontWeight: '700'
    lineHeight: 52px
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 44px
  headline-lg-mobile:
    fontFamily: Noto Serif
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 38px
  headline-md:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 34px
  headline-sm:
    fontFamily: Noto Serif
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 30px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 30px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 18px
  caption:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '400'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  margin: 1.25rem
  margin-mobile: 1.125rem
  margin-desktop: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  space-3xl: 4.5rem
---

## Brand & Style
This design system defines an intimate, cinematic, and deeply refined Arabic wedding invitation experience engineered for mobile-first interactions (RTL). Designed as an intentional departure from generic digital invitation templates, cliché stock flourishes, hearts, or overt nuptial kitsch, it treats the celebration as an editorial narrative of quiet luxury. 

The aesthetic is built around a nocturnal atmosphere: rich charcoal, deep onyx, and basalt textures illuminated by restrained touches of warm, metallic gold foil and subtle ambient glows. The visual movement draws from Modern Arabic Editorial Minimalism combined with Tactile Depth—employing hair-thin gold borders, deep atmospheric layering, generous vertical breathing room, and bespoke astronomical or geometric micro-motifs. The user experience prioritizes smooth single-column scrolling, gesture-driven horizontal storytelling cards, and immediate emotional resonance through poetic Arabic typography and filmic transitions.

## Colors
The color architecture relies strictly on an immersive dark spectrum. High-contrast stark whites and loud, hyper-saturated gradients are excluded in favor of warm, low-glare organic tones.

- **Background & Canvas:** The root environment uses `night-charcoal` (`#0B0D10`). Elevated layers shift sequentially into `deep-onyx` (`#11151B`) for floating panels/modals and `surface-card` (`#141A22`) for interactive cards and narrative blocks.
- **Gold Foil Accents:** Reserved strictly for focal hierarchy—primary call-to-action buttons, active navigation markers, key dates, names, and hairline structural borders. `gold-foil` (`#D4AF37`) functions as the baseline metallic hue, enriched with `gold-highlight` (`#F0D277`) for soft directional gradients, and `gold-glow` (`#FFDFA6`) used sparingly for focused ambient lighting.
- **Typography Tones:** Primary typography renders in warm ivory `text-primary` (`#F5F2EA`), maintaining WCAG AAA contrast against charcoal surfaces without harsh optical vibration. Secondary details, timestamps, and subtitles use `text-secondary` (`#CFC8BC`).
- **Dividers & Structural Borders:** Outlines rely on muted steel slate `border-divider` (`#2A3442`) or translucent gold hairline strokes (`rgba(212, 175, 55, 0.18)`), avoiding dense opaque fills.

## Typography
The typographic pairing honors Arabic calligraphic harmony alongside crisp contemporary mobile legibility.

- **Headings & Hero Displays:** Uses traditional serif forms (`Amiri` in production, mapped to `Noto Serif` token standards). Headings demand a stately cadence with ample leading to let extended descenders breathe naturally. Never apply positive letter-spacing (`tracking`) to connected Arabic headline typography, as it severs cursive ligatures.
- **Body, UI & Meta:** Driven by a balanced humanist sans-serif (`Cairo` in production, structured through `Plus Jakarta Sans` metrics). Designed for clean rendering across all mobile viewports, high legibility in dense Arabic diacritics, and stable numeric alignment for calendar dates and countdown blocks.
- **Hierarchy Rules:** Hero titles (e.g. bride & groom names) utilize `display-hero` with warm metallic text gradients. Sub-headers and venue details prioritize comfortable vertical rhythm with a 1.5–1.7x line-height ratio.

## Layout & Spacing
The layout model is mobile-first, centered, and RTL-native (`dir="rtl"`). 

- **Column Constraints:** On mobile viewports, the canvas spans full bleed with `18px–22px` (`margin-mobile`) horizontal edge safe areas. On desktop, tablet, or landscape devices, the entire experience locks to an elegant, centered portrait channel with a strict max-width of `560px` to mirror the tactile proportions of a physical luxury wedding invitation envelope.
- **Rhythm & Grid:** Built upon a standard 8pt vertical cadence (`space-sm` = 8px, `space-md` = 16px, `space-lg` = 24px, etc.). Component padding internally adheres strictly to these steps.
- **Section Pacing:** Generous structural spacing (`space-2xl` to `space-3xl`) isolates key milestones—the Opening Reveal, Event Date, Story Cards, Venue Map, and Schedule—preventing cognitive overload and maintaining theatrical cadence during vertical scroll.

## Elevation & Depth
Depth is created through luminosity and warm metallic luminance rather than thick, muddy black drop-shadows.

- **Base Layer (Level 0):** Pure `night-charcoal` (`#0B0D10`), serving as the background abyss.
- **Mid Layer (Level 1):** Floating sheets, modal containers, and navigation backdrops set to `deep-onyx` (`#11151B`) with 1px border stroke of `rgba(255, 255, 255, 0.05)`.
- **Card & Story Layer (Level 2):** Primary cards use `surface-card` (`#141A22`) encapsulated by a hairline metallic rim (`1px solid rgba(212, 175, 55, 0.18)`).
- **Active & Highlight State (Level 3):** Active cards, hovered touch targets, and primary CTA buttons cast an ambient, ultra-diffused gold glow: `0 8px 32px -4px rgba(212, 175, 55, 0.22), 0 2px 8px -2px rgba(240, 210, 119, 0.15)`.
- **Modal Lightbox Layer:** Full viewport backdrop overlay using `rgba(11, 13, 16, 0.82)` supplemented with an 8px blur (`backdrop-filter: blur(8px)`) for a cinematic focus shift.

## Shapes
Geometry balances tailored elegance with modern mobile ergonomics. 

- **Primary Cards & Modals:** Standardized to a `16px` radius (`rounded-lg`), softening content boundaries without feeling childish.
- **Buttons & Interactive Touch Targets:** Standardized to `14px` radius to nest harmoniously inside card padding.
- **Chips, Category Tags, & Progress Nodes:** Full pill treatment (`999px` / `rounded-full`) to differentiate metadata tags from structural interactive cards.
- **Hairline Accents:** Decorative borders remain strictly `1px` to maintain a jewelry-grade metallic finish.

## Components

### Primary Buttons
- **Style:** High-impact call to action featuring a subtle diagonal metallic gradient from `gold-foil` (`#D4AF37`) to `gold-highlight` (`#F0D277`).
- **Typography:** Bold `Cairo` / `label-md` rendered in deep `night-charcoal` (`#0B0D10`) for punchy contrast.
- **Height & Sizing:** Minimum 52px height for thumb-friendly reach across handheld displays.
- **Interactions:** Depressed scale effect (`transform: scale(0.98)`) on tap, with an active gold halo ring (`rgba(255, 223, 166, 0.35)`).

### Story Swipe Cards
- **Structure:** Horizontal snap-scrolling viewport (`scroll-snap-type: x mandatory`) showcasing the couple's milestone narrative.
- **Surface:** `surface-card` (`#141A22`) background framed by `1px solid rgba(212, 175, 55, 0.18)`.
- **Active State:** Focused center card transitions via scale (`scale(1.02)`) paired with a heightened gold border opacity (`rgba(212, 175, 55, 0.45)`).
- **Indicators:** Segmented top indicator bar, where the active segment fills with metallic gold and inactive segments remain `border-divider`.

### Countdown Unit
- **Display:** Monolithic numeric counter blocks configured in a centered 4-part grid (Days, Hours, Minutes, Seconds) with crisp tabular figures.
- **Background:** Encased in `deep-onyx` pill-like or soft rectangular modules with gold hairline separators.
- **Labels:** Arabic micro-labels (`label-sm`) situated below each value in `text-secondary`.

### Accordion (Details & Schedule)
- **Styling:** Minimalist bottom-bordered dividers using `border-divider` (`#2A3442`).
- **Header:** Clean typographic trigger with gold-accented chevron indicator placed consistently at the left edge for RTL orientation.
- **Expansion:** Seamless height reveal with smooth ease-out curve, elevating the active header into `text-primary`.

### Location & Direction Card
- **Layout:** Dedicated venue showcase presenting a single unified gathering hall.
- **Action:** Single prominent CTA button ("فتح في خرائط Google" / Open in Maps) anchoring the card, bypassing clutter and external redirects.