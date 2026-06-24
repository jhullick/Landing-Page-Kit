# Landing Page Project

A repository for producing professional, responsive, conversion-focused landing pages.
The current goal is a pre-launch "coming soon" page that captures email addresses for the
UK launch of Houston Hot Chicken (HHC). Brand tokens below are taken from hhc.ooo/uk.

## How to work here
- For any landing page, apply the `landing-page-quality` skill for design direction and the
  `coming-soon-pattern` skill for the email-capture section. Apply the `uk-consent` skill
  whenever the page collects email addresses from people in the UK.
- State a one-line design plan (palette, fonts, layout concept, signature element) before coding.
- Build mobile-first. Preview in the browser and screenshot at 375px and 1440px to self-check.
- For brand story, voice, product and proof points (for copy), read `brand/BRAND-CONTEXT.md`.

## Brand tokens (from hhc.ooo/uk)
- Primary: #e30513 (HHC red, the dominant heat colour: announce bar, highlights)
  Accent: #0b68d1 (action blue, used on buttons/CTAs)
  Ink/text: #f9fbfd (light text on dark)   Surface/bg: #0e0e0e (near-black)
- Dark text on light surfaces: #040f19. Supporting greys: #6a7781, #d5e1eb, #f6f9fc.
- Display font: Bitter (serif, 700/900, uppercase headings)
  Body font: Lato (sans-serif). Handwriting accent: Rock Salt. Load from Google Fonts.
- Type scale ratio: 1.25   Base body size: 1rem
- Spacing scale (px): 4, 8, 16, 24, 32, 40, 48, 56, 64
- Corner radius: 0.5em (buttons ~0.35em)   Shadow: subtle, e.g. 0 5px 25px rgba(0,0,0,.25)

## Non-negotiables (IMPORTANT)
- NEVER use Inter, Roboto, Arial, Open Sans or default system fonts. Do not default to Space Grotesk.
  (Lato IS the HHC brand body font here, paired with Bitter. Use it deliberately, not as a fallback.)
- NEVER use purple-on-white gradients, three identical feature cards, or cookie-cutter layouts.
- Semantic HTML. Every form input has a visible, associated <label> (not placeholder-only).
- Text contrast at least 4.5:1 (WCAG AA). Visible keyboard focus states at 3:1 or better.
- Fluid type with clamp() using rem + vw so browser zoom still works.
- Respect prefers-reduced-motion.
- British English in all copy. No em dashes.
