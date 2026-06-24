---
description: Verify responsive behaviour and accessibility, then fix any failures.
---
Verify the page mobile-first. Open it in the browser and screenshot at 375px and 1440px. Confirm:
fluid type via clamp() using rem + vw, visible keyboard focus states at 3:1 or better, every input
has an associated visible label, text contrast at least 4.5:1 (AA), nothing conveys meaning by
colour alone, and prefers-reduced-motion is respected. List any failures with the exact element,
then fix them and re-check.
