# Changelog

## 1.2.2

- Fixed Svelte template tag punctuation (`@`, `#`, `/`, `:` in `{@render}`, `{@html}`, `{#if}`, etc.) appearing white instead of pink by adding `punctuation.definition.keyword` to the keyword color rule

## 1.2.1

- Fixed TypeScript primitive types (`string`, `number`, `boolean`, `void`, etc.) appearing white instead of purple by adding `support.type.primitive.ts` and `.tsx` to the TextMate token rules as a fallback when the TypeScript language server hasn't indexed the file yet

## 1.2.0

- Shifted type-related tokens (types, classes, structs, enums, interfaces, JSON property names, `parameter.label:dart`) to a purple/lavender palette to distinguish them from other syntax groups
- Changed the default `variable` color to a soft mint (`#AEEEE0`) instead of light blue

## 1.1.2

- Added a distinct color (`#78C2B3`) for JSON property names (`support.type.property-name.json`) to separate keys from string values
- Fixed a JSON syntax error in the theme file (stray `//` comments) that prevented VS Code from loading the theme

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
