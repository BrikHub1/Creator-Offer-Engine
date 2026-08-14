# Design System

## Visual Direction

Premium-minimal meets youth energy. A founder aesthetic that shops at Uniqlo, uses linear.app, and has strong opinions about typography — not startup-dark, not pastel-blogger. The layout breathes; the copy does the selling.

**Signature choice:** a bold, slightly wide display font for headlines against ample white space, with a single electric accent color reserved for CTAs and hover states.

---

## Color Palette

| Name | Hex | Use |
|---|---|---|
| Midnight | `#0F0F12` | Body text, section backgrounds |
| Off-White | `#F7F6F2` | Main background |
| Signal Orange | `#F4511E` | Primary CTAs, active elements |
| Pale Stone | `#E8E5DF` | Card backgrounds, dividers |
| Warm Gray | `#7A7873` | Secondary text, captions |
| Pure White | `#FFFFFF` | Component interiors |

**Design rule:** Signal Orange appears only on buttons and one accent element per section. Everything else stays Midnight, Off-White, or Warm Gray — this contrast directs the eye.

---

## Typography

- **Display:** Syne (Google Fonts), weight 700, wide tracking on large sizes. Used for H1, H2, section titles.
- **Body:** Inter, weight 400–500. Clean, neutral, readable at all sizes.
- **Mono (optional):** JetBrains Mono, for code, prompt examples, or system labels.

### Type scale

| Element | Size | Line-height | Font |
|---|---|---|---|
| H1 | 56–64px | tight | Syne Bold |
| H2 | 36–44px | tight | Syne Bold |
| H3 | 24–32px | normal | Inter SemiBold |
| Body | 17px | 28px | Inter Regular |
| Caption | 13px | 20px | Inter Regular, Warm Gray |
| CTA | 16px | — | Inter SemiBold, all-caps tracking |

---

## Page Layout / Section Order

1. **Navigation** — logo left, "Get Access" CTA right, sticky
2. **Hero** — H1, subhead, primary CTA, mockup right-aligned
3. **Social proof bar** — scrolling ticker (once real results exist)
4. **Problem** — text left, visual/quote right
5. **Transformation** — 2-column before/after cards
6. **What's Inside** — 3-column feature grid (icon, title, description)
7. **How It Works** — 3-step horizontal timeline
8. **Who It's For / Not For** — 2-column callout
9. **Pricing** — 3-tier card row, middle tier highlighted
10. **Guarantee** — full-width light background, centered
11. **Testimonials** — card grid (placeholder until real proof collected)
12. **FAQ** — accordion, left-aligned
13. **Final CTA** — full-width Signal Orange section, white text
14. **Footer** — logo, links, legal

---

## CTA Text Variations

- Get Instant Access — $29
- Start Your Offer Sprint Free
- Build Your Offer This Weekend
- Get the Full Workspace — $29
- Upgrade to Pro — $69
- Download Free Starter Kit

---

## Accessibility & Interaction Notes

- Maintain visible keyboard focus states on all interactive elements
- Ensure text/background contrast meets WCAG AA at minimum
- Reserve animation for subtle, purposeful transitions — avoid gimmicks
- Mobile: stack pricing cards, use full-width CTAs, reduce H1 to ~36px, avoid horizontal scroll
