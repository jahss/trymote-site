# Mote site theme

This directory documents the reusable visual system used across trymote.com.

## Brand foundation

- Ink: `#080F12`
- Green: `#418727`
- White: `#FFFFFF`
- Soft white: `#F2F3F1`
- Typeface: Montserrat, weights 400–900
- Primary logo: `assets/mote-logo-soft.png` (source: 2.png)
- Footer tagline: `assets/mote-logo-black.png` (source: 3.png)

## Section themes

Apply one modifier to a section or page:

- `.theme-light` — soft-white background with ink text
- `.theme-dark` — ink background with white text
- `.theme-green` — green background with white text

## Shared building blocks

- `.site-shell` — centered page container
- `.site-hero` and `.site-hero__title` — page hero
- `.site-kicker` — green eyebrow label
- `.site-section` — standard vertical section spacing
- `.site-grid` — twelve-column desktop grid
- `.site-card` — white bordered content card
- `.site-button` and `.site-button--outline` — primary and secondary actions
- `.site-footer` — shared footer container

Start new pages from `theme/page-template.html`. Preserve the logo artwork rather than recreating it with text. Use the tagline artwork only where the footer has enough space for it to remain legible.
