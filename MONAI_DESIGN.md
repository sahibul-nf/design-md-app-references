---
version: "alpha"
name: MonAi Expense Tracker Design System
description: Mobile-first design system for MonAi, the AI-powered expense tracker built around effortless natural-language logging, Apple Pay automation, budget clarity, and calm financial habits.

colors:
  primary: "#F05B53"
  secondary: "#FF7161"
  tertiary: "#FFAD61"
  neutral: "#363636"

  brand-coral: "#F05B53"
  brand-coral-light: "#FF7161"
  brand-coral-dark: "#D94A42"
  brand-orange: "#FFAD61"
  brand-yellow: "#FFB800"

  canvas: "#FFFFFF"
  canvas-soft: "#F3F3F3"
  surface: "#FFFFFF"
  surface-muted: "#F3F3F3"
  surface-soft: "#F0F0F0"
  surface-green: "#E1F295"
  surface-blue: "#CBE7FF"
  surface-orange: "#FCCC8E"

  ink: "#363636"
  ink-strong: "#000000"
  text-primary: "#1A1A1A"
  text-secondary: "#666666"
  text-tertiary: "#999999"
  text-muted: "#B3B3B3"
  text-inverse: "#FFFFFF"
  text-on-accent: "#FFFFFF"
  text-on-coral: "#000000"

  border: "#E5E5E5"
  border-soft: "#F3F3F3"
  star: "#FFB800"
  success: "#74A800"
  warning: "#FFB800"
  error: "#F05B53"
  focus: "#F05B53"

typography:
  hero-display:
    fontFamily: "Nunito"
    fontSize: 60px
    fontWeight: "900"
    lineHeight: 65px
    letterSpacing: -1.8px
  display-lg:
    fontFamily: "Nunito"
    fontSize: 56px
    fontWeight: "800"
    lineHeight: 62px
    letterSpacing: -1.5px
  heading-lg:
    fontFamily: "Nunito"
    fontSize: 40px
    fontWeight: "800"
    lineHeight: 48px
    letterSpacing: -0.8px
  heading-md:
    fontFamily: "Nunito"
    fontSize: 32px
    fontWeight: "800"
    lineHeight: 38px
    letterSpacing: -0.5px
  heading-sm:
    fontFamily: "Nunito"
    fontSize: 24px
    fontWeight: "700"
    lineHeight: 31px
    letterSpacing: -0.2px
  title-md:
    fontFamily: "Nunito"
    fontSize: 20px
    fontWeight: "700"
    lineHeight: 28px
    letterSpacing: 0px
  body-lg:
    fontFamily: "Nunito"
    fontSize: 18px
    fontWeight: "400"
    lineHeight: 29px
    letterSpacing: 0px
  body-md:
    fontFamily: "Nunito"
    fontSize: 16px
    fontWeight: "400"
    lineHeight: 26px
    letterSpacing: 0px
  body-md-medium:
    fontFamily: "Nunito"
    fontSize: 16px
    fontWeight: "600"
    lineHeight: 24px
    letterSpacing: 0px
  body-sm:
    fontFamily: "Nunito"
    fontSize: 14px
    fontWeight: "400"
    lineHeight: 22px
    letterSpacing: 0px
  body-sm-semibold:
    fontFamily: "Nunito"
    fontSize: 14px
    fontWeight: "700"
    lineHeight: 20px
    letterSpacing: 0px
  caption:
    fontFamily: "Nunito"
    fontSize: 12px
    fontWeight: "600"
    lineHeight: 17px
    letterSpacing: 0px
  micro:
    fontFamily: "Nunito"
    fontSize: 10px
    fontWeight: "700"
    lineHeight: 14px
    letterSpacing: 0.4px

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  xxxl: 64px
  section: 96px
  mobile-gutter: 20px
  desktop-gutter: 24px

rounded:
  xs: 2px
  sm: 6px
  md: 8px
  lg: 12px
  xl: 16px
  xxl: 20px
  xxxl: 24px
  message: 20px
  phone: 28px
  full: 9999px

components:
  button-primary:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.text-inverse}"
    typography: "{typography.body-sm-semibold}"
    rounded: "{rounded.full}"
    height: 44px
    padding: "0 24px"
  button-accent:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.text-on-coral}"
    typography: "{typography.body-sm-semibold}"
    rounded: "{rounded.full}"
    height: 44px
    padding: "0 24px"
  store-badge-button:
    backgroundColor: "{colors.ink-strong}"
    textColor: "{colors.text-inverse}"
    typography: "{typography.caption}"
    rounded: "{rounded.md}"
    height: 48px
    padding: "0 18px"
  app-phone-frame:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    rounded: "{rounded.phone}"
    padding: "{spacing.md}"
  expense-input-bar:
    backgroundColor: "{colors.surface-muted}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.full}"
    height: 56px
    padding: "0 18px"
  voice-entry-card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.xxl}"
    padding: "{spacing.lg}"
  chat-message-sent:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.text-inverse}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.message}"
    padding: "{spacing.md}"
  chat-message-received:
    backgroundColor: "{colors.surface-muted}"
    textColor: "{colors.ink}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.message}"
    padding: "{spacing.md}"
  feature-card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.text-primary}"
    typography: "{typography.body-md}"
    rounded: "{rounded.xxl}"
    padding: "{spacing.xxl}"
  automation-pill:
    backgroundColor: "{colors.surface-green}"
    textColor: "{colors.ink}"
    typography: "{typography.body-sm-semibold}"
    rounded: "{rounded.full}"
    height: 40px
    padding: "0 16px"
  budget-progress-card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.xl}"
    padding: "{spacing.md}"
  review-card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.text-primary}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.xl}"
    padding: "{spacing.lg}"
  rating-star:
    backgroundColor: "transparent"
    textColor: "{colors.star}"
    typography: "{typography.body-md-medium}"
    rounded: "{rounded.xs}"
  shared-list-card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.xxl}"
    padding: "{spacing.lg}"
---

## Overview

MonAi is a calm AI-powered expense tracker for people who do not want to "manage finances" in a heavy dashboard. Its promise is simple: type naturally, speak naturally, or let Apple Pay and Apple Shortcuts trigger entries automatically. The brand is practical and friendly, with a soft white/gray canvas, rounded cards, Nunito typography, and a warm coral-to-orange accent system.

The product language avoids finance-app anxiety. It focuses on daily habit formation: logging should take seconds, insights should feel like asking a friend, and budgets should be visible before overspending happens. The design system should make every surface feel lightweight, fast, and slightly delightful without hiding the user's numbers.

**Key Characteristics:**
- Warm coral primary (`{colors.brand-coral}`) and coral-orange gradient moments for AI/automation emphasis.
- White and soft gray surfaces (`{colors.canvas}`, `{colors.canvas-soft}`) rather than dark dashboards.
- Rounded pills and cards everywhere: app-store badges, nav buttons, chat messages, expense input, automation chips.
- Nunito variable font across every surface; friendly, legible, habit-forming.
- Phone mockups and app screenshots are central evidence, not decorative afterthoughts.
- The app UX centers on natural input, Apple Pay automation, AI chat, budgets, recurring transactions, shared lists, and multi-currency tracking.
- Copy is direct and reassuring: "No forms, no friction", "Speak your expenses", "Ask your finances anything."

## Colors

> Source pages: `get-monai.app/`, site `styles.css?v=24`, `fonts.css`, App Store and Google Play badge links, and public landing-page screenshots.

### Brand & Accent

- **Brand Coral** (`{colors.brand-coral}`): Primary MonAi action color. Used for focus, AI extraction, send/submit actions, and highlighted title words.
- **Brand Coral Light** (`{colors.brand-coral-light}`): Gradient end color and hover/action lift.
- **Brand Coral Dark** (`{colors.brand-coral-dark}`): Pressed and emphasis state for coral actions.
- **Brand Orange** (`{colors.brand-orange}`): Start of the primary gradient, used to make automation and AI feel warm instead of technical.
- **Brand Yellow / Star** (`{colors.brand-yellow}`, `{colors.star}`): Review stars, rating emphasis, and positive social proof.

### Surface

- **Canvas** (`{colors.canvas}`): Main page and app background.
- **Canvas Soft** (`{colors.canvas-soft}`): Alternating sections, feature bands, tab backgrounds, and muted app surfaces.
- **Surface** (`{colors.surface}`): Cards, app panels, phone content, review cards.
- **Surface Soft** (`{colors.surface-soft}`): Small inactive controls and row dividers.
- **Surface Green** (`{colors.surface-green}`): Automation success pill, habit confirmation, and "logged automatically" moments.
- **Surface Blue** (`{colors.surface-blue}`): Informational automation/tutorial moments.
- **Surface Orange** (`{colors.surface-orange}`): Warm prompt, receipt, or payment trigger accents.

### Text

- **Ink** (`{colors.ink}`): Primary heading and CTA text.
- **Ink Strong** (`{colors.ink-strong}`): App-store badge black, strong button hover, maximum emphasis.
- **Text Primary** (`{colors.text-primary}`): Body and feature copy.
- **Text Secondary** (`{colors.text-secondary}`): Supporting copy, metadata, navigation, review text.
- **Text Tertiary** (`{colors.text-tertiary}`): Placeholder text, timestamps, quiet helper copy.
- **Text Inverse** (`{colors.text-inverse}`): Text on dark buttons and sent chat bubbles.

### Semantic

- **Success** (`{colors.success}`): Budget remaining, automation completed, synced shared list, and positive habit feedback.
- **Warning** (`{colors.warning}`): Budget approaching limit or review/rating highlight.
- **Error** (`{colors.error}`): Failed parsing, missing amount, invalid recurring setup, or overspend state.
- **Focus** (`{colors.focus}`): Caret, input focus, and active AI extraction state.

## Typography

### Font Family

**Nunito** is used as the sole typeface. It is rounded, highly readable, and more encouraging than a typical finance sans. That matters for MonAi: the user is trying to build a habit, not audit a ledger.

Nunito's wide weight range supports the whole product: 900 for friendly hero display, 800 for section headers, 700 for card titles and feature labels, 600 for buttons and chips, 400 for explanatory copy.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
|---|---:|---:|---:|---:|---|
| `{typography.hero-display}` | 60px | 900 | 65px | -1.8px | Homepage hero |
| `{typography.display-lg}` | 56px | 800 | 62px | -1.5px | Major app/feature hero |
| `{typography.heading-lg}` | 40px | 800 | 48px | -0.8px | Section headline |
| `{typography.heading-md}` | 32px | 800 | 38px | -0.5px | Feature title |
| `{typography.heading-sm}` | 24px | 700 | 31px | -0.2px | Card title, app module title |
| `{typography.title-md}` | 20px | 700 | 28px | 0 | Compact module title |
| `{typography.body-lg}` | 18px | 400 | 29px | 0 | Lead body and feature descriptions |
| `{typography.body-md}` | 16px | 400 | 26px | 0 | Default body |
| `{typography.body-md-medium}` | 16px | 600 | 24px | 0 | Active labels and strong rows |
| `{typography.body-sm}` | 14px | 400 | 22px | 0 | Navigation, row labels, review text |
| `{typography.body-sm-semibold}` | 14px | 700 | 20px | 0 | Button labels and pills |
| `{typography.caption}` | 12px | 600 | 17px | 0 | App badges, timestamps, metadata |
| `{typography.micro}` | 10px | 700 | 14px | 0.4px | Tiny labels and compact badges |

### Principles

- **Friendly heavy headings:** Use 800-900 display weights for big promises; MonAi should feel confident but not corporate.
- **Generous body leading:** Body text uses 1.6-ish rhythm, making feature explanations comfortable.
- **No second display face:** Nunito carries all roles; do not add a serious finance font.
- **Numbers stay readable:** Amounts and budgets should use clear weight and tabular-number rendering where available.
- **Microcopy matters:** Helper text should explain parsing, automation, and budget states in plain language.

## Layout

### Spacing System

- **Base unit:** 4px.
- **Tokens:** `{spacing.xxs}` (4px), `{spacing.xs}` (8px), `{spacing.sm}` (12px), `{spacing.md}` (16px), `{spacing.lg}` (24px), `{spacing.xl}` (32px), `{spacing.xxl}` (48px), `{spacing.xxxl}` (64px), `{spacing.section}` (96px).
- **Container:** 1200px max-width with 24px desktop gutters and 20px mobile gutters.
- **Section rhythm:** Alternating white and soft gray sections, with 96px desktop vertical spacing and tighter 48-64px mobile spacing.
- **Card padding:** Feature cards use 48px on desktop, 24px on mobile; app cards use 16-24px.

### Product Layout

- The landing page uses a fixed transparent nav that turns white/blurred on scroll.
- Hero layout: large left copy with store badges, app screenshot phone mockup on the right.
- How It Works section uses a three-step rhythm: enter effortlessly, build the habit, see the full picture.
- Feature section uses large alternating cards with text on one side and phone screenshots on the other.
- Automation section is a grid of shortcut recipes: Apple Pay, photo to transaction, Action Button Voice, screenshot, email, message trigger.
- Reviews are many small cards, emphasizing real social proof over a single oversized testimonial.

### App Layout

- App screens should feel like a focused note-taking/chat app for money.
- Primary logging surface should be a single input bar, voice action, or automation prompt, not a form stack.
- Expense lists show amount, category, date, source, and recurrence only when useful.
- Budget cards use progress bars and remaining amounts with visual clarity.
- AI chat surfaces use familiar message bubbles: user question in dark bubble, answer in soft gray/white.

### Whitespace Philosophy

MonAi deliberately removes bloat. Each screen should have one obvious next action. Use whitespace to make logging feel easy and budgets feel digestible. Avoid dense accounting tables unless the user explicitly exports or audits.

## Elevation & Depth

MonAi uses soft shadows for cards and phone mockups, not heavy glass or neon.

| Level | Treatment | Use |
|---|---|---|
| 0 Flat | No shadow | Page background, simple text blocks |
| 1 Subtle | `0 1px 2px rgba(0,0,0,0.05)` | Small controls, tabs, badges |
| 2 Card | `0 4px 12px rgba(0,0,0,0.04)` | App cards, review cards |
| 3 Feature | `0 10px 30px -10px rgba(0,0,0,0.10)` | Large feature panels |
| 4 Phone | `0 20px 40px -10px rgba(0,0,0,0.15)` | Phone mockups and app screenshots |

### Decorative Depth

- Coral action shadows may appear under primary accent buttons, but should stay soft.
- Phone mockups can have more depth than in-app cards.
- Automation pills and budget progress bars should rely on color and shape, not shadow.

## Shapes

### Border Radius Scale

| Token | Value | Use |
|---|---:|---|
| `{rounded.xs}` | 2px | Progress fill, tiny separators |
| `{rounded.sm}` | 6px | Compact badges and small image corners |
| `{rounded.md}` | 8px | Store badges, nav logo icon |
| `{rounded.lg}` | 12px | Inputs and compact cards |
| `{rounded.xl}` | 16px | Review cards, budget cards |
| `{rounded.xxl}` | 20px | Feature cards and app modules |
| `{rounded.xxxl}` | 24px | Large panels |
| `{rounded.message}` | 20px | Chat bubbles, with one corner optionally tighter |
| `{rounded.phone}` | 28px | Phone/app screenshot frame |
| `{rounded.full}` | 9999px | Pills, category chips, toggles, automation prompts |

### Geometry Principles

- Use full pills for actions, language toggles, automation chips, and segmented controls.
- Feature cards should be soft rectangles, usually 20-24px.
- Chat bubbles can use asymmetric rounding: `20px 20px 6px 20px` for sent messages.
- Progress bars are pill tracks with pill fills.

## Components

> Per the no-hover policy, hover states are not documented. Default, active, disabled, loading, empty, and error states are included where relevant.

### Buttons & Badges

**`button-primary`** - Main dark pill action.
- Background `{colors.ink}`, text `{colors.text-inverse}`, typography `{typography.body-sm-semibold}`, height 44px, padding `0 24px`, rounded `{rounded.full}`.
- Use for Download, Read more reviews, Continue, Save, Set Budget, and Confirm.

**`button-accent`** - Coral AI/action pill.
- Background `{colors.primary}`, text `{colors.text-on-accent}`, typography `{typography.body-sm-semibold}`, height 44px, rounded `{rounded.full}`.
- Use for Parse, Add Expense, Start Voice Entry, and active AI states.

**`store-badge-button`** - App Store / Google Play badge container.
- Background `{colors.ink-strong}`, text `{colors.text-inverse}`, rounded `{rounded.md}`, height 48px.
- Should preserve official badge artwork when available.

**`automation-pill`** - Apple Pay/Shortcut automation prompt.
- Background `{colors.surface-green}`, text `{colors.ink}`, typography `{typography.body-sm-semibold}`, height 40px, rounded `{rounded.full}`.
- Use for "Logged", "Apple Pay", "Shortcut Ready", or "Automation Active."

### Input & Capture

**`expense-input-bar`** - Natural-language expense input.
- Background `{colors.surface-muted}`, text `{colors.ink}`, placeholder `{colors.text-tertiary}`, height 56px, rounded `{rounded.full}`.
- Accepts plain phrases such as "lunch $12" or "groceries 45.50 yesterday."
- Error state highlights missing amount/date with `{colors.error}` helper copy.

**`voice-entry-card`** - Speech-to-expense capture card.
- Background `{colors.surface}`, text `{colors.ink}`, rounded `{rounded.xxl}`, padding `{spacing.lg}`.
- Includes microphone affordance, waveform/listening state, transcript, and detected expense rows.
- Loading state should say "Listening..." or "Organizing..." instead of technical NLP language.

**`apple-pay-prompt`** - Post-payment logging prompt.
- Soft card appearing immediately after payment.
- Shows amount, suggested category, payment source, and one-tap confirm/edit.
- Should feel instant and low-friction.

### AI Chat & Insights

**`chat-message-sent`** - User question bubble.
- Background `{colors.ink}`, text `{colors.text-inverse}`, rounded `{rounded.message}`, padding `{spacing.md}`.
- Used for questions like "How much did I spend on food this month?"

**`chat-message-received`** - AI insight bubble.
- Background `{colors.surface-muted}`, text `{colors.ink}`, rounded `{rounded.message}`, padding `{spacing.md}`.
- Answers should include plain-language summary first, then optional numbers.

**`insight-card`** - Pattern/trend insight.
- White card with title, short explanation, metric, and optional mini chart.
- Use coral only for emphasis; avoid dashboard clutter.

### Finance UI

**`budget-progress-card`** - Category budget status.
- Background `{colors.surface}`, text `{colors.ink}`, rounded `{rounded.xl}`, padding `{spacing.md}`.
- Contains category icon/name, spent amount, remaining amount, and pill progress bar.
- Approaching limit uses `{colors.warning}`; exceeded uses `{colors.error}`.

**`expense-row`** - Logged transaction row.
- White or transparent row, category icon, title, amount, date/source metadata.
- Recurring or automated entries get a small pill status.

**`recurring-transaction-card`** - Subscription/recurring payment.
- Shows cadence, next date, category, and amount.
- Include pause/edit actions in a compact overflow menu.

**`shared-list-card`** - Couples/groups expense list.
- Background `{colors.surface}`, text `{colors.ink}`, rounded `{rounded.xxl}`, padding `{spacing.lg}`.
- Shows participants, shared balance/split status, recent synced expenses, and invite/manage actions.

### Marketing & Proof

**`feature-card`** - Large landing-page feature block.
- Background `{colors.surface}`, text `{colors.text-primary}`, rounded `{rounded.xxl}`, padding `{spacing.xxl}`.
- Two-column layout: copy + phone screenshot, alternating order.

**`app-phone-frame`** - Device mockup/image holder.
- Rounded `{rounded.phone}`, white surface, soft phone shadow, screenshot fills available space.
- Use actual app screenshots rather than abstract UI illustrations.

**`review-card`** - Testimonial tile.
- Background `{colors.surface}`, text `{colors.text-primary}`, rounded `{rounded.xl}`, padding `{spacing.lg}`.
- Star row uses `{colors.star}` and title uses `{typography.body-md-medium}`.

**`rating-star`** - Star glyph token.
- Transparent background, text `{colors.star}`, typography `{typography.body-md-medium}`.
- Use for rating summaries and review cards.

## Do's and Don'ts

### Do

- Keep logging one-step whenever possible: type, speak, or confirm automation.
- Use friendly words: "organizes", "logged", "remaining", "you spent", "this month."
- Make Apple Pay and Shortcuts feel like everyday convenience, not power-user setup.
- Use coral/orange sparingly for AI and action emphasis.
- Keep phone screenshots large and legible in marketing surfaces.
- Use budget progress visuals that clearly show remaining room before overspend.
- Preserve the calm white/soft-gray palette even on feature-heavy screens.

### Don't

- Do not turn MonAi into a dense accounting dashboard.
- Do not require form fields for the primary add-expense flow.
- Do not expose NLP internals, parsers, or automation plumbing in user-facing copy.
- Do not overuse coral as a full-page background.
- Do not make charts more prominent than the user's action or answer.
- Do not use harsh financial red except for true errors or overspending.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---:|---|
| Small Mobile | < 480px | Single-column hero, stacked store badges, one-column feature cards |
| Mobile | 480-768px | Compact nav, phone mockup below copy, cards stack |
| Tablet | 769-1023px | Two-column feature cards when space allows, mobile nav may remain |
| Desktop | 1024-1199px | Full fixed nav, hero copy + phone mockup, alternating feature cards |
| Wide Desktop | >= 1200px | 1200px max container, generous section spacing |

### Touch Targets

- Primary actions: 44px minimum.
- Expense input bar: 56px preferred.
- Voice button: 48px minimum.
- Category chips: 40px minimum.
- Budget cards and rows: 56-64px minimum height.

### Collapsing Strategy

- Nav links collapse behind hamburger on mobile; language and download remain accessible.
- Store badges stack or center under hero copy.
- Feature cards collapse to copy first, screenshot second.
- Review cards move from multi-column grid to horizontal carousel or single-column stack.
- Automation recipe grid becomes a one-column list with icon, title, and description.

### Image Behavior

- App screenshots should remain crisp and readable; do not crop important UI states.
- Phone mockups can scale down but should not become tiny decorative thumbnails.
- Team photo appears as supporting brand evidence, not a hero replacement.

## Iteration Guide

1. Start every new flow with the least-friction input: natural text, voice, automation, or one-tap confirm.
2. Use `{colors.ink}` for primary CTAs and `{colors.primary}` for AI/focus/accent actions.
3. Use `{colors.canvas-soft}` to separate sections without heavy borders.
4. Add new component states explicitly: `-active`, `-listening`, `-parsed`, `-error`, `-empty`, `-synced`.
5. Run `npm exec --yes --package @google/design.md -- design.md lint MONAI_DESIGN.md` after edits.
6. Test with realistic messy input: "coffee this morning was $4, groceries $40", multiple currencies, missing amounts, yesterday/last Friday dates, shared-list expenses, recurring subscriptions.
7. Prefer removing a control over adding explanatory UI when a flow feels complex.

## Known Gaps

- Exact in-app native token values are inferred from public marketing screenshots and web CSS, not an exported iOS/Android design token file.
- Dark mode is mentioned in reviews but not documented in the public landing-page token set.
- Import/export, premium paywall, onboarding, and account settings screens are not fully visible from public pages.
- Charting details are not formalized; use simple progress bars and small trend cards until app evidence is available.
- Animation timings are inferred from web CSS: 150ms fast, 300ms base, 500ms slow.
