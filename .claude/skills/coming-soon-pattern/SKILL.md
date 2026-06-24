---
name: coming-soon-pattern
description: Best-practice pattern for pre-launch coming-soon and waitlist landing pages whose single job is capturing email addresses. Use when building any email-capture, waitlist, or coming-soon page. Covers single-goal focus, minimal-friction form design, microcopy, and the success state.
---

# Coming-Soon / Email-Capture Pattern

The page has one job: capture the email address. Strip navigation. One primary CTA, optionally
repeated at entry and exit. Defer name, role or use-case to the welcome email.

## Above the fold
- Benefit-led headline naming one outcome.
- One-line subhead: what it is and who it is for.
- The signup form.
- One proof or anticipation cue (a signups counter, founder credential, press mention, or a real
  product screenshot). Pick one; do not stack. A soft launch window ("Autumn 2026") beats "coming soon".

## Email capture form
- One email field (type="email", required), with an associated <label> "Email address". Single-column.
- High-contrast primary button with action copy ("Join the waitlist", "Get early access", "Notify me").
  Never "Submit". No secondary CTA.
- Inline validation on blur with a clear, specific error message; preserve input on error.
- Helper microcopy under the field: "No spam. Unsubscribe at any time."
- Consent line under the form: apply the `uk-consent` skill for the wording and rules.

## Success state (highest-intent screen; make it work)
- Confirm: "You're on the list."
- Set expectations: "Check your inbox to confirm your email." (if using double opt-in)
- What next: one line on what they will receive and roughly when.
- Optional: a referral or share prompt, or a single social follow.

## Notes
- British English. No em dashes. Keep copy at a simple reading level; it converts better.
