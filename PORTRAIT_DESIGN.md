---
version: "alpha"
name: Portrait Product Design System
description: Full-product design system for Portrait, covering personal pages, identity grids, creator commerce, Portrait Wallet, username payments, Plus, and decentralized hosting.

colors:
  primary: "#26C0FF"
  secondary: "#E600C2"
  tertiary: "#FF494E"
  neutral: "#141414"

  rainbow-blue: "#26C0FF"
  rainbow-pink: "#E600C2"
  rainbow-red: "#FF494E"
  rainbow-orange: "#FFA13E"
  rainbow-yellow: "#FFC837"
  rainbow-green: "#00CC3D"

  canvas: "#FFFFFF"
  canvas-warm: "#F7F7F7"
  surface: "#FFFFFF"
  surface-muted: "#EEEEEE"
  surface-soft: "#DEDEDE"
  surface-dark: "#141414"
  surface-ink: "#000000"

  ink: "#141414"
  ink-strong: "#000000"
  text-primary: "#202020"
  text-secondary: "#585858"
  text-tertiary: "#797979"
  text-muted: "#9F9F9F"
  text-inverse: "#FFFFFF"
  text-brand: "#08304C"

  gray-10: "#F7F7F7"
  gray-25: "#EEEEEE"
  gray-50: "#DEDEDE"
  gray-100: "#C7C7C7"
  gray-200: "#9F9F9F"
  gray-300: "#797979"
  gray-400: "#585858"
  gray-500: "#484848"
  gray-600: "#353535"
  gray-700: "#2C2C2C"
  gray-800: "#202020"
  gray-900: "#1B1B1B"
  gray-1000: "#141414"

  brand-blue-50: "#EFF9FF"
  brand-blue-100: "#DFF3FF"
  brand-blue-400: "#26C0FF"
  brand-blue-700: "#036EA7"
  brand-blue-900: "#084E72"
  brand-blue-1000: "#08304C"

  brand-green-50: "#EEFFF2"
  brand-green-600: "#00CC3D"
  brand-green-800: "#0B7A2D"
  brand-green-1000: "#003411"

  brand-pink-700: "#CF00AA"
  brand-red-700: "#C80D12"
  brand-orange-600: "#FF8400"
  brand-yellow-600: "#FAB700"

  wallet-blue: "#2775CA"
  wallet-green: "#26A17B"
  success: "#00CC3D"
  success-dark: "#0B7A2D"
  warning: "#FFA13E"
  error: "#FF494E"
  focus: "#26C0FF"
  border: "#DEDEDE"
  border-dark: "#2C2C2C"

typography:
  hero-display:
    fontFamily: "Basier Circle"
    fontSize: 76px
    fontWeight: "600"
    lineHeight: 76px
    letterSpacing: -3.8px
  display-lg:
    fontFamily: "Basier Circle"
    fontSize: 61px
    fontWeight: "600"
    lineHeight: 63px
    letterSpacing: -2px
  heading-lg:
    fontFamily: "Basier Circle"
    fontSize: 49px
    fontWeight: "600"
    lineHeight: 53px
    letterSpacing: -1.25px
  heading-md:
    fontFamily: "Basier Circle"
    fontSize: 39px
    fontWeight: "600"
    lineHeight: 43px
    letterSpacing: -1px
  heading-sm:
    fontFamily: "Basier Circle"
    fontSize: 31px
    fontWeight: "600"
    lineHeight: 34px
    letterSpacing: -0.64px
  title-md:
    fontFamily: "Basier Circle"
    fontSize: 25px
    fontWeight: "600"
    lineHeight: 29px
    letterSpacing: -0.41px
  body-lg:
    fontFamily: "Switzer"
    fontSize: 20px
    fontWeight: "400"
    lineHeight: 30px
    letterSpacing: 0px
  body-md:
    fontFamily: "Switzer"
    fontSize: 16px
    fontWeight: "400"
    lineHeight: 24px
    letterSpacing: 0px
  body-md-medium:
    fontFamily: "Switzer"
    fontSize: 16px
    fontWeight: "500"
    lineHeight: 24px
    letterSpacing: 0px
  body-sm:
    fontFamily: "Switzer"
    fontSize: 14px
    fontWeight: "400"
    lineHeight: 20px
    letterSpacing: 0px
  label:
    fontFamily: "Open Runde"
    fontSize: 14px
    fontWeight: "540"
    lineHeight: 18px
    letterSpacing: 0px
  caption:
    fontFamily: "Switzer"
    fontSize: 12px
    fontWeight: "500"
    lineHeight: 16px
    letterSpacing: 0px
  micro:
    fontFamily: "Switzer"
    fontSize: 10px
    fontWeight: "600"
    lineHeight: 14px
    letterSpacing: 0.8px
  editorial-accent:
    fontFamily: "Junicode"
    fontSize: 20px
    fontWeight: "400"
    lineHeight: 20px
    letterSpacing: 0px
  mono:
    fontFamily: "JetBrains Mono"
    fontSize: 13px
    fontWeight: "500"
    lineHeight: 18px
    letterSpacing: 0px

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 20px
  xl: 24px
  xxl: 32px
  xxxl: 40px
  section-sm: 56px
  section: 80px
  section-lg: 112px
  hero: 144px
  mobile-gutter: 20px
  desktop-gutter: 48px

rounded:
  xs: 2px
  sm: 4px
  md: 6px
  lg: 8px
  xl: 12px
  xxl: 16px
  xxxl: 20px
  frame: 24px
  panel: 28px
  canvas: 32px
  wallet: 48px
  full: 9999px

components:
  button-primary-rainbow:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.text-brand}"
    typography: "{typography.label}"
    rounded: "{rounded.full}"
    height: 56px
    padding: "0 20px"
  button-secondary-dark:
    backgroundColor: "{colors.gray-700}"
    textColor: "{colors.text-inverse}"
    typography: "{typography.label}"
    rounded: "{rounded.full}"
    height: 44px
    padding: "0 18px"
  username-input:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    typography: "{typography.body-lg}"
    rounded: "{rounded.full}"
    height: 72px
    padding: "0 32px"
  portrait-grid:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    rounded: "{rounded.canvas}"
    padding: "{spacing.xl}"
  frame-card:
    backgroundColor: "{colors.gray-25}"
    textColor: "{colors.text-primary}"
    rounded: "{rounded.frame}"
    padding: "{spacing.md}"
  add-content-tile:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.text-secondary}"
    typography: "{typography.label}"
    rounded: "{rounded.full}"
    height: 44px
    padding: "0 16px"
  commerce-card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.frame}"
    padding: "{spacing.lg}"
  wallet-balance-card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.wallet}"
    padding: "{spacing.xxl}"
  wallet-action-pill:
    backgroundColor: "{colors.gray-1000}"
    textColor: "{colors.text-inverse}"
    typography: "{typography.label}"
    rounded: "{rounded.full}"
    height: 44px
    padding: "0 18px"
  activity-row:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.text-primary}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.xxl}"
    padding: "{spacing.md}"
  smart-send-panel:
    backgroundColor: "{colors.gray-10}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.panel}"
    padding: "{spacing.xl}"
  plus-card:
    backgroundColor: "{colors.gray-1000}"
    textColor: "{colors.text-inverse}"
    typography: "{typography.body-md}"
    rounded: "{rounded.canvas}"
    padding: "{spacing.xxl}"
  hosting-network-diagram:
    backgroundColor: "{colors.gray-10}"
    textColor: "{colors.text-primary}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.canvas}"
    padding: "{spacing.xxl}"
  footer-link-column:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.text-secondary}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.sm}"
    padding: "{spacing.xs}"
---

## Overview

Portrait is an editorial identity product with embedded fintech, not a generic crypto wallet. It presents a personal page as a "forever space" - a decentralized canvas for story, work, commerce, identity, and payments - then hides the blockchain machinery behind human concepts: usernames, dollars, friends, cards, savings, hosting peers, and owned data.

The visual system combines a white/off-white gallery canvas with a bright six-stop rainbow identity strip. Most product surfaces are quiet: black text, gray UI, white cards, rounded frames, and gentle shadows. The rainbow appears at key identity moments: logo, primary sign-up affordances, wallet announcement, and brand expression. This restraint makes the rainbow feel like a signature rather than a background gimmick.

Typography carries two personalities. Basier Circle and Switzer keep the product clean, contemporary, and SaaS-readable. Open Runde softens buttons and app controls. Junicode italic appears as a small editorial accent that makes Portrait feel personal, literary, and less like another Web3 dashboard.

**Key Characteristics:**
- White editorial canvas with black near-ink typography and soft gray modular surfaces.
- Six-color rainbow identity: blue, pink, red, orange, yellow, green.
- Rounded content grid as the core interaction metaphor: image, video, link, text, commerce, and wallet cards all become movable "frames."
- Username-first onboarding and payments: `portrait.so/username`, `@friends`, and dollars replace addresses, chains, and gas.
- Wallet UX is dollar-denominated: unified balance, send/request/add, smart routing, savings, privacy, and security are framed as everyday money tools.
- Components use very soft geometry: full-pill buttons, 20-32px frame cards, 48px wallet panels.
- Product copy is calm and plain: "Earn it, send it, spend it", "Pay @friends, not addresses", "Your keys. Your control."

## Colors

> Source pages: `portrait.so/`, `portrait.so/pages`, and `portrait.so/wallet`. Token values were cross-checked against the live Tailwind theme and inline SVG/brand colors.

### Brand & Rainbow

- **Rainbow Blue** (`{colors.rainbow-blue}`): First stop in the Portrait identity gradient; also the default primary token. Used for sign-up energy, focus, wallet announcement accents, and brand logo.
- **Rainbow Pink** (`{colors.rainbow-pink}`): Second identity stop. It gives the brand its creator/social energy and appears in the rainbow logo and animated button ring.
- **Rainbow Red** (`{colors.rainbow-red}`): Third identity stop and the most urgent warm accent. Also maps to error/destructive communication when needed.
- **Rainbow Orange** (`{colors.rainbow-orange}`): Commerce, warmth, and pay-flow accent. It should feel creator-economy adjacent, not warning-heavy.
- **Rainbow Yellow** (`{colors.rainbow-yellow}`): Optimistic midpoint for badges, rewards, and playful brand moments.
- **Rainbow Green** (`{colors.rainbow-green}`): Completion, money received, success, and healthy network status.

### Neutrals

- **Canvas** (`{colors.canvas}`): Default page and product background.
- **Canvas Warm** (`{colors.canvas-warm}`): Slightly softened page section and background band.
- **Surface** (`{colors.surface}`): Cards, panels, forms, and framed content.
- **Surface Muted** (`{colors.surface-muted}`): Empty frames, grid placeholders, subdued module backgrounds.
- **Surface Dark** (`{colors.surface-dark}`): Plus card, dark buttons, wallet security moments, and footer contrast.
- **Ink** (`{colors.ink}`): Primary text and brand authority.
- **Text Secondary** (`{colors.text-secondary}`): Body copy, helper labels, inactive links, and low-emphasis wallet metadata.

### Product & Wallet

- **Wallet Blue** (`{colors.wallet-blue}`): USDC, stablecoin, network, and payment infrastructure reference color.
- **Wallet Green** (`{colors.wallet-green}`): USDT/stablecoin reference color and money-positive signal.
- **Success** (`{colors.success}`): Payments received, live status, active hosting, and earned interest.
- **Warning** (`{colors.warning}`): Gradual rollout, pending status, and risk education.
- **Error** (`{colors.error}`): Failed payment, invalid username, unavailable domain, or security warning.
- **Focus** (`{colors.focus}`): Input focus, active control rings, and keyboard navigability.

## Typography

### Font Family

**Switzer** is the default body and product sans. It is neutral, modern, and readable across long FAQ copy, wallet rows, and page-builder controls.

**Basier Circle** is the brand/product display face. It gives hero headlines and product sections their round, friendly directness without feeling childish.

**Open Runde** is used for rounded app controls and button labels. Its softer construction pairs well with full-pill buttons and touch-first wallet actions.

**Junicode** is the expressive editorial accent, deployed sparingly for personality. It should never become the body font or dominate dense UI.

**JetBrains Mono** is reserved for technical surfaces: addresses, hosting diagnostics, network identifiers, transaction hashes, and developer references.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
|---|---:|---:|---:|---:|---|
| `{typography.hero-display}` | 76px | 600 | 76px | -3.8px | Homepage hero and major launch pages |
| `{typography.display-lg}` | 61px | 600 | 63px | -2px | Large section openers |
| `{typography.heading-lg}` | 49px | 600 | 53px | -1.25px | Product feature headlines |
| `{typography.heading-md}` | 39px | 600 | 43px | -1px | Wallet/page feature titles |
| `{typography.heading-sm}` | 31px | 600 | 34px | -0.64px | Card and module titles |
| `{typography.title-md}` | 25px | 600 | 29px | -0.41px | Compact product card title |
| `{typography.body-lg}` | 20px | 400 | 30px | 0 | Lead copy and explanatory text |
| `{typography.body-md}` | 16px | 400 | 24px | 0 | Body copy, wallet rows |
| `{typography.body-md-medium}` | 16px | 500 | 24px | 0 | Strong body and active labels |
| `{typography.body-sm}` | 14px | 400 | 20px | 0 | Navigation, metadata, compact rows |
| `{typography.label}` | 14px | 540 | 18px | 0 | Button and pill labels |
| `{typography.caption}` | 12px | 500 | 16px | 0 | Badges, timestamps, helper labels |
| `{typography.micro}` | 10px | 600 | 14px | 0.8px | Tiny uppercase labels |
| `{typography.editorial-accent}` | 20px | 400 | 20px | 0 | Junicode italic accent glyphs |
| `{typography.mono}` | 13px | 500 | 18px | 0 | Addresses, hashes, network details |

### Principles

- **Display type is tight and confident:** Portrait uses negative tracking and near-1.0 line height on large hero copy.
- **Body copy breathes:** Use 1.5 line height for explanations, FAQs, and hosting copy.
- **Accent serif is rare:** Junicode should punctuate, not carry.
- **Controls stay rounded and medium-weight:** Use 540/500-style labels for buttons, pills, and input affordances.
- **Wallet numbers are calm:** Dollar amounts should be large and clear, but never trading-terminal aggressive.

## Layout

### Spacing System

- **Base unit:** 4px, with 8px and 16px as the common rhythm.
- **Tokens:** `{spacing.xxs}` (4px), `{spacing.xs}` (8px), `{spacing.sm}` (12px), `{spacing.md}` (16px), `{spacing.lg}` (20px), `{spacing.xl}` (24px), `{spacing.xxl}` (32px), `{spacing.xxxl}` (40px), `{spacing.section}` (80px), `{spacing.section-lg}` (112px), `{spacing.hero}` (144px).
- **Mobile gutters:** 20px.
- **Desktop gutters:** 48px, with centered content and large white air around product demos.
- **Card padding:** Frame cards use 16-24px; wallet panels use 24-32px; Plus and hosting panels use 32px.

### Product Layout

- Homepage and Pages surfaces start with a centered hero, username input, and CTA stack.
- The core product demo is a large rounded white card containing a modular grid of frames.
- Frames use fixed square/rectangular tracks that can span rows/columns: image, video, link, text, product, commerce, and wallet modules all share the same grid language.
- Builder controls appear as bottom-centered or inline pill actions: Add Image, Add Video, Add Link, Add Text.
- Wallet pages use mobile app cards: balance card, send/request/add actions, recent activity, smart-send review, savings, privacy, and security panels.

### Grid & Container

- Portrait grid desktop: 4 columns with roughly equal square tracks and 20-24px gaps.
- Tablet: 2 columns with larger vertical rhythm.
- Mobile: 2 compact columns for content grid previews; wallet flows collapse to a single card stack.
- Marketing copy should alternate between centered editorial sections and side-by-side product demos.

### Whitespace Philosophy

Portrait should feel like a personal gallery, not an admin console. Large empty areas are acceptable when they make a profile, card, or wallet moment feel owned and considered. Dense data appears only in wallet transaction lists, hosting network diagrams, and developer-adjacent sections.

## Elevation & Depth

The system uses soft physicality: border, radius, tiny shadows, and layered white cards. Depth should feel tactile, almost paper-like, instead of glassy or futuristic.

| Level | Treatment | Use |
|---|---|---|
| 0 Flat | No shadow; white or gray surface | Text sections, footer, static copy |
| 1 Hairline | `1px solid {colors.border}` | Inputs, grid frames, subtle card bounds |
| 2 Soft Card | Light shadow with white card | Portrait grid shell, commerce card, Plus feature cards |
| 3 Floating | Slightly stronger shadow | CTA buttons, menus, wallet cards |
| 4 Modal | White panel over dim layer | Login, wallet auth, payment confirmation |

### Decorative Depth

- Rainbow buttons use an animated gradient ring around a white or dark inner button, not a full rainbow fill.
- Identity cards may use soft leather, paper, or metallic textures, but the system itself remains clean.
- Wallet security/privacy moments can use darker panels for contrast, but not as the default app background.

## Shapes

### Border Radius Scale

| Token | Value | Use |
|---|---:|---|
| `{rounded.xs}` | 2px | Tiny dividers, underline marks |
| `{rounded.sm}` | 4px | Small inline marks |
| `{rounded.md}` | 6px | Compact technical labels |
| `{rounded.lg}` | 8px | Inputs inside dense tooling |
| `{rounded.xl}` | 12px | Small cards and media controls |
| `{rounded.xxl}` | 16px | Transaction rows and medium cards |
| `{rounded.xxxl}` | 20px | Mobile frame cards |
| `{rounded.frame}` | 24px | Standard Portrait content frames |
| `{rounded.panel}` | 28px | Smart-send and hosting panels |
| `{rounded.canvas}` | 32px | Large grid shells and Plus panels |
| `{rounded.wallet}` | 48px | Major wallet app panels |
| `{rounded.full}` | 9999px | Buttons, avatar circles, username pills |

### Geometry Principles

- Primary controls are always pill-shaped.
- Portrait content lives in rounded rectangles, never sharp boxes.
- Wallet panels can be extra soft because the product is deliberately making money tools feel less intimidating.
- Profile avatars, peer nodes, chain icons, and user handles use circular geometry.

## Components

> Per the no-hover policy, hover states are not documented. Default, active, loading, disabled, and error states are included where they matter.

### Buttons

**`button-primary-rainbow`** - Primary sign-up and launch CTA.
- Outer shell carries the six-stop rainbow ring; inner surface is usually white.
- Component token uses `{colors.primary}` as the parser-safe action base, with text `{colors.text-brand}`, typography `{typography.label}`, height 56px, padding `0 20px`, rounded `{rounded.full}`.
- Use for Sign up, Create your Portrait, Apply for early access, and Get Plus.
- Loading state replaces label with spinner while keeping width stable.

**`button-secondary-dark`** - Dark filled support CTA.
- Background `{colors.gray-700}`, text `{colors.text-inverse}`, typography `{typography.label}`, height 44px, rounded `{rounded.full}`.
- Use for Donate, Buy now, Pay with Portrait Wallet, and wallet secondary actions.

**`button-link-underlined`** - Text action with subtle current-color underline.
- Text `{colors.text-brand}` or `{colors.ink}`, typography `{typography.body-sm}`, underline opacity low by default and full when active.
- Use for Login, Learn more, FAQ actions, and footer links.

### Identity & Page Builder

**`username-input`** - Hero handle claim field.
- Background `{colors.surface}`, text `{colors.ink}`, typography `{typography.body-lg}`, rounded `{rounded.full}`, height 72px, padding `0 32px`.
- Prefix `portrait.so/` is visible on wider mobile and desktop.
- Error state uses `{colors.error}` helper text under the field.

**`portrait-grid`** - Signature modular canvas.
- Background `{colors.surface}`, rounded `{rounded.canvas}`, padding `{spacing.xl}`.
- Contains fixed-rhythm frames that can span rows/columns.
- Empty frame placeholders use `{colors.gray-25}`.

**`frame-card`** - Image, video, link, text, or embedded card frame.
- Background `{colors.gray-25}`, text `{colors.text-primary}`, rounded `{rounded.frame}`, padding `{spacing.md}`.
- Media fills the frame edge-to-edge but inherits the same radius.
- Text frames use centered or top-left text depending on user content.

**`add-content-tile`** - Builder add action.
- Background `{colors.surface}`, text `{colors.text-secondary}`, typography `{typography.label}`, rounded `{rounded.full}`, height 44px.
- Use for Add Image, Add Video, Add Link, Add Text.

**`profile-header-card`** - Portrait owner identity block.
- White surface, avatar circle, name, bio, badges, and optional Donate/Follow style action.
- Use Basier/Switzer for name and bio; reserve Junicode for expressive symbols.

### Commerce & Plus

**`commerce-card`** - Creator product card.
- Background `{colors.surface}`, text `{colors.ink}`, rounded `{rounded.frame}`, padding `{spacing.lg}`.
- Includes product type, title, short description, price, and `button-secondary-dark`.
- Buyer payment language should say dollars and Portrait Wallet before crypto.

**`plus-card`** - Membership and support panel.
- Background `{colors.gray-1000}`, text `{colors.text-inverse}`, rounded `{rounded.canvas}`, padding `{spacing.xxl}`.
- Feature bullets: custom domain, Plus badge, early access, founder chat.
- Price row uses `{typography.heading-sm}` and strong contrast.

### Wallet

**`wallet-balance-card`** - Main Portrait Wallet balance.
- Background `{colors.surface}`, text `{colors.ink}`, rounded `{rounded.wallet}`, padding `{spacing.xxl}`.
- Center value uses `{typography.heading-lg}` or `{typography.display-lg}`.
- Supporting copy explains movement in dollars: `+$8.16 this month`.

**`wallet-action-pill`** - Send, Request, Add.
- Background `{colors.gray-1000}`, text `{colors.text-inverse}`, rounded `{rounded.full}`, height 44px.
- Use as a three-action row under the balance.

**`activity-row`** - Recent payment or commerce activity.
- Background `{colors.surface}`, text `{colors.text-primary}`, typography `{typography.body-sm}`, rounded `{rounded.xxl}`, padding `{spacing.md}`.
- Pattern: avatar pair, `@sender -> @recipient`, purpose, amount, timestamp.
- Received amounts use `{colors.success}`; outgoing amounts use `{colors.text-primary}`.

**`smart-send-panel`** - Payment routing preview.
- Background `{colors.gray-10}`, text `{colors.ink}`, rounded `{rounded.panel}`, padding `{spacing.xl}`.
- Shows recipient, amount, stablecoin/network split, network cost, gas inclusion, and slide-to-send action.
- Use plain language: "Gas for Rowan included", not "sponsored native token execution."

**`slide-to-send-control`** - Irreversible payment action.
- Full-width pill track with a draggable knob.
- Label states: `Slide to send $50.00`, `Confirm with Face ID to send`, `Sent`.
- Must preserve amount visibility until completion.

**`privacy-card`** - Private balance and activity panel.
- Dark or light raised panel depending on context.
- Communicates hidden balances, invisible transfers, and zero on-chain footprint without technical overload.

**`security-layer-list`** - Security architecture module.
- Rows for self-custodial, Secure Enclave, zero knowledge, biometrics, iOS Keychain encryption, and no tracking.
- Use green/active status labels and calm explanatory text.

### Hosting & Network

**`hosting-network-diagram`** - Peer hosting explanation.
- Background `{colors.gray-10}`, rounded `{rounded.canvas}`, padding `{spacing.xxl}`.
- Nodes are circular peer avatars; lines or repeated labels communicate redundancy and mutual hosting.
- Use copy like "you host" and "peers you host" instead of infrastructure jargon.

**`footer-link-column`** - Dense footer navigation.
- Background transparent/white, text `{colors.text-secondary}`, typography `{typography.body-sm}`.
- Section headers use `{typography.body-md-medium}` and `{colors.ink}`.

## Do's and Don'ts

### Do

- Use the rainbow only for brand identity, primary CTA framing, and high-signal launch moments.
- Make user-owned content the visual center: profile, grid, wallet balance, product, or hosting peer diagram.
- Speak in human terms: dollars, usernames, friends, balance, card, savings, hosted by people.
- Keep blockchain concepts present but behind the curtain unless the user is in a developer or security context.
- Preserve the modular frame grid; it is the clearest visual signature of Portrait Pages.
- Use large, soft radii for wallet and page-builder panels.
- Use Junicode accents sparingly to make the system feel personal and editorial.

### Don't

- Do not turn every surface into a rainbow gradient.
- Do not make Portrait Wallet look like a token trading app.
- Do not expose wallet addresses as the primary payment affordance when usernames can do the job.
- Do not use sharp rectangular cards for content frames.
- Do not over-darken the product; dark panels are accents, not the default canvas.
- Do not crowd the hero with multiple product claims. One identity claim plus the username field is enough.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---:|---|
| Small Mobile | < 440px | Single-column hero CTA stack, compact username input, 2-column mini grid |
| Mobile | 440-767px | Prefix appears in username field, grid remains 2 columns, wallet cards stack |
| Tablet | 768-1023px | Larger username input, 2-column content demos, wider wallet panels |
| Desktop | 1024-1279px | 4-column Portrait grid, side-by-side feature sections, full nav |
| Wide Desktop | >= 1280px | Large editorial hero, expanded product demos, generous page gutters |

### Touch Targets

- Primary CTA: 44px minimum on mobile, 56px preferred.
- Wallet actions: 44px minimum.
- Grid controls: 44px minimum.
- User/avatar nodes: 40px minimum for tap and recognition.
- Slide-to-send knob: 48px minimum.

### Collapsing Strategy

- Hero username input becomes stacked with the Sign up button below on very small screens.
- Portrait grid keeps two columns on mobile so the frame metaphor remains visible.
- Wallet actions stay grouped in a single row when possible; if labels wrap, switch to icon+label tiles.
- Hosting diagrams simplify to fewer visible peers on mobile while preserving the concept of redundancy.
- Footer columns collapse into stacked groups.

### Image Behavior

- Real uploaded content should fill frames and inherit frame radius.
- Profile avatars use 1:1 circular crops.
- Product card media can be square or portrait depending on creator content.
- Wallet card imagery should stay secondary to balances and transaction copy.

## Iteration Guide

1. Start any new screen from its product mode: page-builder, wallet, commerce, Plus, or hosting.
2. Use `{colors.primary}` or the six rainbow colors only when the action or brand moment deserves it.
3. Keep the core grid and wallet patterns named exactly: `portrait-grid`, `frame-card`, `wallet-balance-card`, `smart-send-panel`.
4. Add variants as separate components: `-active`, `-loading`, `-disabled`, `-error`, `-confirmed`.
5. Run `npm exec --yes --package @google/design.md -- design.md lint PORTRAIT_DESIGN.md` after edits.
6. Test with realistic user content: long usernames, empty bios, many images, long product titles, zero balance, pending payment, failed payment, private balance hidden.
7. When in doubt, simplify the blockchain language before adding visual complexity.

## Known Gaps

- Exact production app screens may evolve because Portrait Wallet is presented as early access/TestFlight.
- Motion values are inferred from live CSS defaults: 150ms for small UI transitions and 600-700ms for hero/rainbow effects.
- The full logged-in builder UI is not publicly captured here; frame and add-tile behavior is inferred from public marketing demos.
- Dark mode exists in parts of the site and wallet/auth surfaces, but a complete dark theme is not documented as the primary product language.
- Payment compliance, identity verification, and recovery flows are not visible from the public pages and should be documented separately if implemented.
