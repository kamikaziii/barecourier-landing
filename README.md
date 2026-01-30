# bareCourier Landing Page

Marketing landing page for bareCourier - a PWA for courier delivery management.

## Tech Stack

- Pure HTML/CSS/JS (no build step)
- Space Grotesk + JetBrains Mono fonts
- Phosphor Icons
- WebP images for performance

## Development

Simply open `index.html` in a browser or serve with any static server:

```bash
# Using Python
python -m http.server 8000

# Using Node
npx serve .
```

## Structure

```
├── index.html              # Main landing page
├── logo-v1.svg            # Logo (SVG)
├── og-image.webp          # Open Graph image
├── favicon.ico            # Favicon
├── favicon-*.png          # Favicon sizes
├── apple-touch-icon.png   # iOS icon
├── courier-*.webp         # App screenshots (courier view)
├── client-*.webp          # App screenshots (client view)
└── _unused/               # Archive of unused assets (gitignored)
```

## Design

- **Colors**: Dark theme with orange accent (#ff6b35)
- **Typography**: Space Grotesk (headings), JetBrains Mono (code/tags)
- **Animations**: Scroll reveal, parallax phones, pulsing gradients

## Sections

1. **Hero** - Headline with CTA
2. **Problem** - Pain points cards
3. **Showcase** - 3D phone mockups
4. **Features** - Bento grid layout
5. **Workflow** - Timeline steps
6. **Stats** - Key numbers
7. **All Features** - Accordion list
8. **CTA** - Final call to action

## Image Optimization

Images are WebP format for ~60-70% size reduction. Run optimization script if adding new images:

```bash
node ../scripts/optimize-landing.mjs
```
