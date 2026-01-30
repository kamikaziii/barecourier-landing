# bareCourier Landing Page

Marketing landing page for bareCourier courier management app.

## Tech Stack

- **Pure HTML/CSS/JS** - No build step, no framework
- **Fonts**: Space Grotesk, JetBrains Mono (Google Fonts)
- **Icons**: Phosphor Icons (CDN)
- **Images**: WebP format for performance

## Development

```bash
# Serve locally
python -m http.server 8000
# or
npx serve .
```

Open http://localhost:8000

## File Structure

```
index.html           # Single-page landing
logo-v1.svg          # Brand logo
og-image.webp        # Social sharing image
*.webp               # App screenshots
favicon.*            # Favicons
_unused/             # Archived assets (gitignored)
```

## Design Tokens

```css
--black: #0a0a0a      /* Background */
--white: #fafafa      /* Text */
--gray: #888          /* Muted text */
--accent: #ff6b35     /* Orange CTA */
--green: #22c55e      /* Success */
--blue: #3b82f6       /* Info */
```

## Editing Guidelines

- Keep it a single HTML file (no build complexity)
- Use semantic HTML sections
- Images must be WebP format
- Test on mobile (375px) and desktop (1440px)
- Animations respect `prefers-reduced-motion`

## Related

- Main app: [bareCourier](https://github.com/kamikaziii/bareCourier)
