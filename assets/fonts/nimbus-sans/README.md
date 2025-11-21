# Nimbus Sans Font Files

This directory should contain the following Nimbus Sans font files:

## Required Files

### Regular Weight (400)
- `nimbus-sans-regular.woff2`
- `nimbus-sans-regular.woff`
- `nimbus-sans-regular-italic.woff2`
- `nimbus-sans-regular-italic.woff`

### Light Weight (300)
- `nimbus-sans-light.woff2`
- `nimbus-sans-light.woff`
- `nimbus-sans-light-italic.woff2` (optional)
- `nimbus-sans-light-italic.woff` (optional)

### Bold Weight (700)
- `nimbus-sans-bold.woff2`
- `nimbus-sans-bold.woff`
- `nimbus-sans-bold-italic.woff2` (optional)
- `nimbus-sans-bold-italic.woff` (optional)

## Font Acquisition Options

### Option 1: Purchase from URW++
Nimbus Sans is a commercial font from URW++. Purchase at:
- https://www.urwpp.de/

### Option 2: Adobe Fonts/Typekit
If you have Adobe Creative Cloud:
1. Create a web project at https://fonts.adobe.com/
2. Add Nimbus Sans to your kit
3. Download the font files from your kit


### Option 4: Use Liberation Sans (Free Alternative)
Liberation Sans is metrically compatible with Nimbus Sans and is open source:
- Download from: https://github.com/liberationfonts/liberation-fonts

## File Naming Convention

Ensure files are named exactly as specified above for the @font-face declarations in `fonts.css` to work correctly.

## Format Priority

- **woff2**: Primary format (best compression, modern browsers)
- **woff**: Fallback format (broader browser support)
