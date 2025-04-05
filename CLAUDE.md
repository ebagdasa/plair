# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Build/Test Commands
- Open HTML: `open index.html` (View in browser)
- Validate HTML: `npx html-validate index.html`
- CSS Lint: `npx stylelint "*.css"`
- Check Links: `npx link-checker index.html`

## Code Style Guidelines
- HTML: Use semantic tags, maintain proper indentation (2 spaces), keep attributes in alphabetical order
- CSS: Follow BEM naming convention when appropriate, group related properties
- Fonts: Use Montserrat for headings, Open Sans for body text
- Colors: Use UMass brand colors (--umass-red: #881c1c, --umass-dark-red: #5e0f0f)
- Responsive: Ensure mobile-friendly design with appropriate breakpoints
- Icons: Use Font Awesome for icons, maintain consistent styling
- Images: Optimize all images before committing
- Error Handling: Use graceful degradation for CSS features
- Performance: Minimize HTTP requests, optimize asset loading