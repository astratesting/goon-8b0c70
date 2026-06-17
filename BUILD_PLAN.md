# Goon — Marketing Landing Page Build Plan

## 1. PRODUCT

Goon is a curated, limited-release line of wooden-and-metal trinkets (keychains, rings, charms) where every piece ships with a laser-engraved storycard describing the artisan's process and material origin. The landing page exists to convert curious browsers — primarily 28–38-year-old professionals who want meaningful, non-mass-produced gifts — into waitlist subscribers before launch. The page must communicate three things fast: the materials (wood + metal), the storycard mechanic (the differentiator no Etsy listing or Pandora page offers), and the curated/subscription rhythm (limited drops, quarterly box). One primary CTA: join the waitlist. Secondary CTA: explore the storycard concept. No invented social proof, no fake review counts, no logo wall.

## 2. WHO IT'S FOR

The ICP from research is a time-poor, story-driven buyer who is skeptical of mass-market "personalized" jewelry (Pandora, Mejuri) and fatigued by Etsy's inconsistent quality. They scroll on mobile, decide in seconds, and want to feel something before they trust. This shapes every decision:

- **Tone:** warm, quiet, confident — not salesy. Lora serif for emotional beats, Geist for utility.
- **Density:** low. One idea per section. Generous vertical rhythm.
- **Honesty:** no fake metrics. Where the research gives real numbers (price ranges, market context), we use them as *category framing*, not as our own claims.
- **Primary action:** waitlist email capture (low commitment, fits pre-launch state).
- **Secondary action:** learn how the storycard works (answers the trust objection from the ICP brief).

## 3. LOOK & FEEL

### Visual system

- **Archetype:** Calm System — airy, soft gradients, low-noise hierarchy, generous whitespace.
- **Palette (from spec):**
  - `--sky: #87CEEB` — primary accent, used sparingly for CTAs and the prism motif
  - `--mint: #98FB98` — secondary accent, used for "in stock / available" states and soft section washes
  - `--sand: #F4E4C1` — warm neutral, used for storycard surfaces and section backgrounds
  - `--soft-white: #FAFAFA` — page background
  - Ink: `#1F2933` (warm near-black) for body text on light; `#FAFAFA` for text on dark washes
- **Typography:**
  - **Geist Sans** — body, UI, buttons, nav
  - **Lora** — serif accent for headlines, pull quotes, storycard text, and the word "storycard" wherever it appears
  - Scale: 14 / 16 / 18 / 20 / 24 / 32 / 44 / 64 (px). Headlines use Lora at 44–64, body Geist at 16–18.
- **Spacing:** 8px base. Section vertical padding 96–128px desktop, 64–80px mobile. Max content width 1120px; reading width 640px.
- **Layout style:** centered single-column narrative with occasional 2-column splits (image + copy). No dense grids. No card stacks.
- **Iconography:** thin 1.5px stroke line icons (Lucide). Used only for utility (menu, close, arrow). No decorative icon clutter.
- **Imagery:** real product photography of wood + metal pieces on sand-tone backgrounds. Where no real photos exist yet, use **honest neutral placeholders**: soft sand-colored rounded rectangles labeled "Product photo — wood + brass keychain" with a small camera icon. Never invent customer photos or lifestyle shots.
- **Motion:** subtle. Fade-up on scroll (200ms, 12px translate). Prism motif gently rotates on hover. No parallax, no autoplay video, no scroll-jacking.
- **Prism motif:** a soft three-color gradient triangle (sky → mint → sand) used as the brand mark, the favicon, and a recurring decorative element. Renders as an SVG, not an emoji.

### Screens / sections (top to bottom on the single landing route)

1. **Top nav (sticky, translucent on scroll)**
   - Left: prism SVG mark + wordmark "Goon" in Lora
   - Right: "Storycard", "Collections", "Pricing", "FAQ" anchor links + primary "Join waitlist" button (sky-blue filled, Geist 14px medium, 8px/16px padding, full radius)
   - Mobile: hamburger opens a full-screen sheet with the same links stacked, CTA pinned to bottom

2. **Hero**
   - Eyebrow (Geist 12px uppercase, tracking-wide, ink/60): "Limited drops · Quarterly subscription"
   - Headline (Lora 56–64px, ink): "Small objects. Real stories."
   - Subhead (Geist 18px, ink/70, max 560px): "Wood and metal trinkets, each one laser-engraved with the story of how it was made."
   - Primary CTA: "Join the waitlist" (sky-blue filled, opens inline email form — see flow below)
   - Secondary CTA: "How the storycard works" (text link with arrow, anchors to #storycard)
   - Right side (desktop) / below (mobile): a soft sand-toned product placeholder card showing a stylized storycard mock — front face with a prism mark, back face with three lines of placeholder Lora text reading "Engraved with the maker's notes, material origin, and edition number."

3. **Trust strip (no fake logos)**
   - Single line of honest framing in Geist 14px, ink/60, centered: "A new brand. Made in small batches. No restocks once a drop sells out."
   - This replaces the dishonest logo wall. It states the truth and reinforces scarcity without inventing customers.

4. **Feature section 1 — The storycard (the differentiator)**
   - Two-column: left = enlarged storycard mock (sand background, Lora engraved-style text, prism watermark), right = copy
   - Eyebrow: "The storycard"
   - Headline (Lora 32px): "Every piece arrives with its own story."
   - Body (Geist 18px): "Each trinket is laser-engraved with a card describing the wood source, the maker, and the edition number of the drop. It's the part you keep on the shelf after the trinket is on the keyring."
   - This section directly addresses the ICP's "is this a real artisan brand?" objection.

5. **Feature section 2 — Materials**
   - Two-column reversed: copy left, image right
   - Eyebrow: "Materials"
   - Headline: "Walnut, oak, brass. Nothing else."
   - Body: "We work with two materials and a short list of finishes. The combination is deliberate — warm wood against cool metal, designed to age together."
   - Image: honest placeholder labeled "Walnut + brass keychain — product photo"

6. **Feature section 3 — Limited drops**
   - Full-width sand-tinted band
   - Eyebrow: "Drops"
   - Headline: "Four collections a year. No restocks."
   - Body: "Each drop runs for two to three weeks. When it's gone, it's gone. Subscribers see new drops a week before they go public."
   - Inline mini-timeline: 4 dots labeled "Drop 01", "Drop 02", "Drop 03", "Drop 04" with the current quarter marked

7. **Feature section 4 — Subscription**
   - Two-column: left = copy, right = a simple stacked card showing what's in a quarterly box
   - Eyebrow: "Subscription"
   - Headline: "One curated piece, every quarter."
   - Body: "A single trinket chosen for the season, plus a style card and early access to the next drop. Skip or cancel anytime."
   - Stacked card contents (Geist 14px, sand background): "1 × Curated trinket", "1 × Style card", "Early access to next drop"

8. **Pricing teaser**
   - Three cards on sand background, equal width, no "most popular" badge (we have no customers to justify it)
   - Card 1 — "Single piece": $25–$50, "Keychains, rings, charms from any current drop.", CTA "Join waitlist"
   - Card 2 — "Bundle": $60–$80, "Two or three pieces, paired by the maker.", CTA "Join waitlist"
   - Card 3 — "Quarterly subscription": $55–$quarter, "One curated piece every three months. Skip or cancel anytime.", CTA "Join waitlist"
   - All three CTAs scroll to the waitlist form and pre-select the tier via URL param.

9. **FAQ**
   - 6 questions, accordion (one open at a time), Geist 16px questions, ink/80 answers
   - Questions (derived from ICP objections in research):
     1. "When does Goon launch?" → "Our first drop opens to waitlist subscribers first. Join the list to get the date."
     2. "What materials do you use?" → "Walnut and oak, paired with brass. We publish the source for every drop."
     3. "How does the storycard work?" → "Each piece is laser-engraved with a card describing the maker, the wood source, and the edition number."
     4. "Can I gift a subscription?" → "Yes — gift subscriptions are available at launch. Waitlist members will be notified first."
     5. "What's your return policy?" → "If a piece arrives damaged, we replace it. We don't accept returns on engraved items otherwise."
     6. "Where do you ship?" → "Starting with the US and Canada at launch. International shipping is on the roadmap."

10. **Final CTA band**
    - Sand background, centered
    - Headline (Lora 40px): "Be the first to see the first drop."
    - Inline waitlist form (email + submit)
    - Helper text (Geist 14px, ink/60): "One email when we launch. No newsletter, no spam."

11. **Footer**
    - Three columns: Brand (prism + "Goon" + one-line tagline), Links (Storycard, Collections, Pricing, FAQ), Legal (Privacy, Terms — both link to placeholder pages)
    - Bottom row: copyright, "Made in small batches."

## 4. USER FLOWS

### Flow A — Primary: Join the waitlist

1. User lands on hero, sees headline + CTA.
2. Clicks "Join the waitlist" → form expands inline beneath the button (no modal). Fields: email (required), optional tier interest (radio: "Single pieces", "Bundles", "Subscription", "Not sure yet").
3. On submit:
   - Client-side validation (email format, required).
   - POST to `/api/waitlist` with `{ email, tier }`.
   - Server validates, inserts into Supabase `waitlist` table, returns `{ ok: true, position: null }` (we do not invent a position number).
   - UI swaps form for success state: "You're on the list. We'll email you when the first drop opens." with a small prism mark.
4. Error states: invalid email → inline message under field; duplicate email → "This email is already on the list."; network error → "Something went wrong. Try again." with retry button.

### Flow B — Secondary: Learn about the storycard

1. User clicks "How the storycard works" in hero.
2. Smooth-scroll to `#storycard` section.
3. Section animates in (fade-up), user reads, can click "See materials" to scroll to next section.

### Flow C — Pricing tier selection

1. User clicks a pricing card CTA.
2. Page scrolls to final CTA band, waitlist form auto-focuses the email field, and the tier radio is pre-selected based on `?tier=` query param.

### Flow D — FAQ

1. User clicks a question → accordion expands (200ms), arrow rotates 90°.
2. Clicking another question collapses the previous one.
3. Keyboard accessible: Tab to focus, Enter/Space to toggle.

### Flow E — Mobile nav

1. User taps hamburger → full-screen sheet slides in from right.
2. Links stacked vertically, CTA pinned to bottom.
3. Tap outside or close icon to dismiss.

## 5. PAGES / ROUTES

| Route | Purpose | Layout & key elements |
|---|---|---|
| `/` | The marketing landing page | All sections described above, single scroll |
| `/privacy` | Privacy policy | Simple centered prose page, Geist 16px, max 640px reading width, sand header band |
| `/terms` | Terms of service | Same layout as `/privacy` |
| `/api/waitlist` | POST endpoint for waitlist signup | JSON in/out, validates email, inserts to Supabase |
| `/api/health` | GET endpoint returning `{ ok: true }` | Used by uptime checks |

No other routes. This is a marketing page, not an app — no dashboard, no auth, no user accounts.

## 6. CORE FEATURES

1. **Waitlist capture form**
   - Inline expansion in hero and final CTA band.
   - Fields: email (required, validated), tier (optional radio).
   - Submits to `/api/waitlist`.
   - Success state replaces form; error states shown inline.
   - Honeypot field (`website`) to deter bots; reject if filled.

2. **Smooth-scroll anchor navigation**
   - Nav links scroll to `#storycard`, `#drops`, `#subscription`, `#pricing`, `#faq`.
   - Respects `prefers-reduced-motion` (instant scroll instead of smooth).

3. **FAQ accordion**
   - One open at a time, keyboard accessible, ARIA-compliant (`aria-expanded`, `aria-controls`).

4. **Sticky nav with scroll state**
   - Transparent at top, gains soft-white background + subtle bottom border after 80px scroll.

5. **Prism brand mark**
   - SVG component used in nav, favicon, storycard mock, and footer.

6. **Responsive layout**
   - Breakpoints: mobile (<768px), tablet (768–1024px), desktop (>1024px).
   - All two-column sections stack on mobile. Hero copy always above imagery.

7. **SEO + metadata**
   - `<title>`: "Goon — Wooden and metal trinkets with a story"
   - Meta description: "Curated, limited-release wooden and metal trinkets. Each piece arrives with a laser-engraved storycard. Join the waitlist."
   - Open Graph image: the storycard mock on sand background.
   - JSON-LD `Organization` schema with brand name and a `description` only — no fake `founder`, `foundingDate`, or `address`.

8. **Analytics-ready**
   - Single `track(event, props)` wrapper around a no-op by default; ready to wire to Plausible or PostHog via env var. No third-party scripts loaded by default.

## 7. DATA MODEL

Single Supabase table. No auth, no user accounts.

**`waitlist`**
| Field | Type | Notes |
|---|---|---|
| `id` | uuid, PK, default `gen_random_uuid()` | |
| `email` | text, unique, not null, lowercased | |
| `tier` | text, nullable, check in (`'single'`, `'bundle'`, `'subscription'`, `'unsure'`) | |
| `source` | text, nullable | e.g. `'hero'`, `'pricing-single'`, `'pricing-bundle'`, `'pricing-subscription'`, `'final'` |
| `referrer` | text, nullable | `document.referrer` |
| `created_at` | timestamptz, default `now()` | |

RLS: enabled, no policies (only service role key inserts from server route).

## 8. AUTH

**None.** This is a public marketing page. The waitlist form is anonymous. No Supabase Auth, no NextAuth, no Clerk. The `/api/waitlist` route uses the Supabase service role key (server-only env var) to insert into the `waitlist` table.

## 9. FILES

```
app/
  layout.tsx              Root layout: fonts, metadata, prism favicon
  page.tsx                Landing page composing all sections
  globals.css             Tailwind directives + CSS variables for palette
  privacy/page.tsx        Privacy policy
  terms/page.tsx          Terms of service
  api/
    waitlist/route.ts     POST handler: validate, insert, respond
    health/route.ts       GET handler: { ok: true }

components/
  Nav.tsx                 Sticky nav with scroll state + mobile sheet
  Hero.tsx                Headline, subhead, inline waitlist form
  TrustStrip.tsx          Honest "new brand" framing line
  StorycardSection.tsx    Two-column storycard explainer + mock
  MaterialsSection.tsx    Materials copy + placeholder image
  DropsSection.tsx        Limited drops band with mini-timeline
  SubscriptionSection.tsx Subscription copy + box contents card
  PricingTeaser.tsx       Three pricing cards with tier-param CTAs
  FAQ.tsx                 Accordion with 6 questions
  FinalCTA.tsx            Final waitlist band
  Footer.tsx              Three-column footer
  WaitlistForm.tsx        Reusable form (email + tier radio + states)
  StorycardMock.tsx       SVG/CSS storycard visual used in hero + section
  PrismMark.tsx           SVG brand mark
  Section.tsx             Shared section wrapper (padding, max-width)

lib/
  supabase.ts             Server-side Supabase client (service role)
  validate.ts             Email + tier validation helpers
  track.ts                Analytics wrapper (no-op by default)

supabase/
  schema.sql              CREATE TABLE waitlist + RLS enable

public/
  favicon.svg             Prism mark favicon
  og.png                  Open Graph image (storycard mock)

.env.example              NEXT_PUBLIC_SUPABASE_URL, SUPABASE_SERVICE_ROLE_KEY
```

## 10. ACCEPTANCE

- [ ] Page renders at `/` with all 11 sections in order, on mobile and desktop.
- [ ] Palette uses exactly `#87CEEB`, `#98FB98`, `#F4E4C1`, `#FAFAFA` as specified.
- [ ] Fonts are Geist (body/UI) and Lora (headlines, storycard text).
- [ ] No fabricated testimonials, customer quotes, logos, user counts, ratings, or revenue claims anywhere on the page.
- [ ] Trust strip states honest framing ("A new brand. Made in small batches.") instead of a fake logo wall.
- [ ] Product imagery uses honest neutral placeholders labeled with what the photo will be.
- [ ] Waitlist form in hero and final CTA band both POST to `/api/waitlist` and show success/error states.
- [ ] Duplicate email submission returns a clear "already on the list" message.
- [ ] Honeypot field blocks bot submissions.
- [ ] Pricing card CTAs pre-select the tier via `?tier=` query param and scroll to the form.
- [ ] FAQ accordion is keyboard accessible and ARIA-compliant.
- [ ] Nav is sticky, gains background on scroll, and opens a mobile sheet on small screens.
- [ ] Smooth-scroll respects `prefers-reduced-motion`.
- [ ] `/privacy` and `/terms` render with consistent layout.
- [ ] `/api/health` returns `{ ok: true }`.
- [ ] No third-party analytics scripts loaded by default.
- [ ] SEO metadata, Open Graph image, and JSON-LD `Organization` schema are present.
- [ ] No auth, no dashboard, no user accounts — this is a marketing page only.
- [ ] `npm run build` completes without errors; `npm run dev` serves the page locally.

FILES: ["app/layout.tsx", "app/page.tsx", "app/globals.css", "app/privacy/page.tsx", "app/terms/page.tsx", "app/api/waitlist/route.ts", "app/api/health/route.ts", "components/Nav.tsx", "components/Hero.tsx", "components/TrustStrip.tsx", "components/StorycardSection.tsx", "components/MaterialsSection.tsx", "components/DropsSection.tsx", "components/SubscriptionSection.tsx", "components/PricingTeaser.tsx", "components/FAQ.tsx", "components/FinalCTA.tsx", "components/Footer.tsx", "components/WaitlistForm.tsx", "components/StorycardMock.tsx", "components/PrismMark.tsx", "components/Section.tsx", "lib/supabase.ts", "lib/validate.ts", "lib/track.ts", "supabase/schema.sql", "public/favicon.svg", ".env.example"]