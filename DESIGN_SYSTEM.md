# APInexGate redesign system

## Product intent
A restrained, trustworthy AI API gateway console for developers and platform operators. The redesign changes presentation and information hierarchy, not gateway, authentication, billing, or provider behavior.

## Foundations
- Typeface: Work Sans, system sans-serif fallback.
- Base text: 12.8px with 1.5 line height; compact, readable developer-console density.
- Palette: near-black primary text (#202020), white surfaces, #fbfbfb canvas, #f2f2f2 raised surfaces, neutral #e9e9e9 borders, near-black primary action.
- Spacing rhythm: 3.2px, 6.4px, 9.6px increments.
- Corners: 6px controls, 8px cards and panels.
- Shadows: subtle elevation only; avoid glow, gradients, glass effects and neon accents.
- Motion: 150–200ms, restrained, never required to understand state.

## Components and states
Buttons, links, inputs, selects, navigation, cards, tables, dialogs, badges and charts must define default, hover, focus-visible, active, disabled, loading and error states where applicable. Keep focus visible. Do not communicate state through color alone.

## Layout
- Customer workspace: compact persistent left navigation, clear page title and action area, content-first canvas.
- Admin console: distinct operator navigation and top bar, consistent neutral surface system.
- Dashboard: concise balance and usage summary, clear onboarding progress, recent activity and direct API setup actions.
- Tables: aligned numeric columns, readable empty/loading/error states, horizontal overflow handling on narrow screens.
- Responsive behavior: collapse navigation on small screens; preserve touch targets and avoid horizontal page overflow.

## Accessibility and acceptance
- Target WCAG 2.2 AA contrast.
- All interactive elements keyboard reachable and visibly focused.
- Semantic headings, labels, button names and table headers.
- Test keyboard, pointer and touch; long labels, empty data, loading, errors, disabled controls, small screens and zoom.
- Preserve all existing route names, API calls, authentication, billing and gateway behavior.

## Content and tone
Use concise, specific labels. Prefer operational language over marketing superlatives. Clearly distinguish unavailable functionality from working functionality.

## Anti-patterns
No decorative gradients, neon provider colors, oversized rounded cards, excessive shadows, ambiguous icon-only actions, hidden focus rings, or invented payment availability.
