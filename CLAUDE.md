# Landing Page Project

A repository for producing professional, responsive, conversion-focused landing pages.
The current goal is a pre-launch "coming soon" page that captures email addresses for a
new UK consumer brand.

## How to work here
- For any landing page, apply the `landing-page-quality` skill for design direction and the
  `coming-soon-pattern` skill for the email-capture section. Apply the `uk-consent` skill
  whenever the page collects email addresses from people in the UK.
- State a one-line design plan (palette, fonts, layout concept, signature element) before coding.
- Build mobile-first. Preview in the browser and screenshot at 375px and 1440px to self-check.

## Brand tokens (FILL IN, replace placeholders)
- Primary: #______   Accent: #______   Ink/text: #______   Surface/bg: #______
- Display font: ______   Body font: ______ (max two families; load from Google Fonts)
- Type scale ratio: 1.25   Base body size: 1rem
- Spacing scale (px): 4, 8, 16, 24, 32, 40, 48, 56, 64
- Corner radius: ______   Shadow: subtle, one or two levels only

## Non-negotiables (IMPORTANT)
- NEVER use Inter, Roboto, Arial, Open Sans, Lato or default system fonts. Do not default to Space Grotesk.
- NEVER use purple-on-white gradients, three identical feature cards, or cookie-cutter layouts.
- Semantic HTML. Every form input has a visible, associated <label> (not placeholder-only).
- Text contrast at least 4.5:1 (WCAG AA). Visible keyboard focus states at 3:1 or better.
- Fluid type with clamp() using rem + vw so browser zoom still works.
- Respect prefers-reduced-motion.
- British English in all copy. No em dashes.
