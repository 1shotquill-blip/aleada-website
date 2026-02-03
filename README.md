# Aleada Landing Page

High-converting landing page for Aleada Widget with live demo and pricing.

## Quick Start

### Local Development
```bash
# Simply open index.html in your browser
open index.html
```

### Deploy to Netlify (1 minute)

1. Go to [Netlify](https://netlify.com)
2. Click "Add new site" → "Import an existing project"
3. Select GitHub → Choose `1shotquill-blip/aleada-website`
4. Click "Deploy"

**That's it.** Your site is live.

### Custom Domain
1. In Netlify dashboard, go to "Domain settings"
2. Add your custom domain (e.g., aleada.pro)
3. Update DNS records as instructed

## Files

- `index.html` - Main landing page with embedded widget demo
- `css/style.css` - Styling
- `netlify.toml` - Netlify configuration

## Widget Integration

The widget is embedded in the demo section using:
```html
<script src="https://raw.githubusercontent.com/1shotquill-blip/aleada-widget/main/public/widget.js" data-client="DEMO"></script>
```

Change `data-client` value to track different widget instances.

## Customization

Edit `index.html` to:
- Update pricing
- Change copy/messaging
- Add your logo
- Modify colors in `css/style.css`
