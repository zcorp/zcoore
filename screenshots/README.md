# Portfolio Screenshots

Place your project screenshots here. Recommended format: JPEG, 800×500px, < 150KB.

## Files expected

| Filename | Project |
|----------|---------|
| `boutique-aminata.jpg` | Site e-commerce Aminata |
| `gestion-interne-marc.jpg` | App gestion BTP Marc |
| `coaching-sophie.jpg` | Site coach Sophie |

## Generate automatically

```bash
# Install Puppeteer first
npm install --save-dev puppeteer

# Generate all screenshots
node scripts/screenshots.js

# Generate one screenshot
node scripts/screenshots.js --url https://example.com --name my-project
```

## Manual

1. Open the site in Chrome
2. DevTools → Device Toolbar → 1440×900
3. Screenshot (Cmd+Shift+P → "Capture screenshot")
4. Resize to 800×500 with any image editor
5. Save as JPEG quality ~85%
