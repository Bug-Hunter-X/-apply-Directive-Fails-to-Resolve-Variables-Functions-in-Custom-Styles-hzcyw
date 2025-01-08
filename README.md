# Tailwind CSS @apply Directive Variable/Function Resolution Issue

This repository demonstrates a bug where Tailwind CSS's `@apply` directive fails to correctly resolve variables and functions used within custom style definitions.

## Bug Description

When using `@apply` with styles that reference CSS variables or custom functions, the directive may not correctly evaluate these values, resulting in unexpected styling.

## Reproduction Steps

1. Clone this repository.
2. Run a local web server (e.g., `python -m http.server`).
3. Open `index.html` in your browser.

You'll observe that the styles applied using variables and functions are not resolved as expected.

## Solution

The provided solution demonstrates a workaround to use `@apply` correctly using variable and function resolution (if supported) or by directly applying the styles in the main component.  Note: This may depend on your Tailwind CSS version and setup.