# Changelog

## 1.1.1

- Brightened the default `variable` color to a light blue (`#bdf0ffe1`) for better readability in JS/TS/React
- Added `meta.property-name.css` as a fallback so newer/unrecognized CSS properties (e.g. `border-inline`, logical properties) get colored even when the CSS grammar doesn't yet whitelist them

## 1.1.0

- Added distinct color for React/JSX custom components (`support.class.component`) so they no longer match plain HTML tags
- Added color for JS/TS object literal keys for easier scanning of objects/props
- Added support for modern CSS (2021+): at-rules (`@layer`, `@container`, `@supports`, etc.), custom properties (`var()`/`--foo`), and CSS functions (`calc()`, `clamp()`, gradients, transforms)
- Removed a redundant duplicate token color rule for `support.function`

## 1.0.0

- Renamed theme to Neon Void
- Reworked accent colors to a neon yellow-green / cyan / pink palette
- Added custom bracket pair colorization
- First Marketplace release
