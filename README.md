# Myra Landing Page

Professional landing page for Myra - Unified Customer Messaging Platform by Myrateq.

## Purpose

This landing page is designed for:
- Meta business verification process
- Showcasing Myra's features and capabilities
- Establishing brand legitimacy (with Clustersub reference)
- Providing information about the product during development phase

## Features

- ✅ Development notice banner (indicates app is in active development)
- ✅ Myra logo in header (from myra-icon.svg)
- ✅ Professional hero section with clear value proposition
- ✅ **Waitlist modal** with form (collects user interest)
  - Name, email, company, phone, team size, use case
  - Client-side only (no backend, no data storage)
  - Success page after submission
  - Smooth animations and transitions
- ✅ Feature showcase (6 key features)
- ✅ How it works (3-step process)
- ✅ Integration highlights
- ✅ About Myrateq section with Clustersub reference
- ✅ Fully responsive design (mobile, tablet, desktop)
- ✅ Modern UI with smooth animations
- ✅ SEO optimized meta tags

## Tech Stack

- **Pure HTML, CSS & Vanilla JavaScript** - No frameworks, no build process
- **Tailwind-inspired custom CSS** - Clean, modern design
- **Responsive Grid Layout** - Works on all devices
- **Zero Dependencies** - Fast loading, easy deployment
- **Client-side only** - Waitlist form doesn't submit data anywhere (by design)

## Files

```
myra-landing/
├── index.html           # Main landing page
├── styles.css           # All styles
├── favicon.ico          # Website icon
├── images/
│   └── myra-icon.svg   # Myra logo
└── README.md            # This file
```

## Deployment

### Option 1: Static Hosting (Vercel - Recommended)

1. Install Vercel CLI:
```bash
npm install -g vercel
```

2. Deploy:
```bash
cd /Users/preciousagoma/Sites/myra-landing
vercel
```

3. Follow prompts to link to your Vercel account

4. Set custom domain: `myra.usemyra.io` or `www.usemyra.io`

### Option 2: Netlify

1. Drag and drop the entire folder to [Netlify Drop](https://app.netlify.com/drop)
2. Configure custom domain in settings

### Option 3: GitHub Pages

1. Create a new repository: `myra-landing`
2. Push code:
```bash
git remote add origin git@github.com:myrateq/myra-landing.git
git push -u origin main
```
3. Enable GitHub Pages in repository settings
4. Configure custom domain

### Option 4: Traditional Web Server

Simply upload all files to your web server root directory via FTP/SFTP.

## Custom Domain Setup

Point your domain to the hosting provider:

**For Vercel:**
- Add CNAME record: `www` → `cname.vercel-dns.com`
- Add A records for root domain (see Vercel dashboard)

**For Netlify:**
- Add CNAME record: `www` → `your-site.netlify.app`
- Add A record for root domain: `75.2.60.5`

## Meta Business Verification

When submitting for Meta verification, provide:
- **Website URL:** https://www.usemyra.io (or wherever deployed)
- **Privacy Policy:** Create and link from footer
- **Terms of Service:** Create and link from footer

## Customization

### Update Links
All links to `https://app.usemyra.io` can be changed by searching and replacing in `index.html`.

### Change Colors
Edit CSS variables in `styles.css`:
```css
:root {
    --primary-color: #4F46E5;
    --secondary-color: #10B981;
    /* etc */
}
```

### Remove Development Notice
Delete the `dev-notice` div from `index.html` and its CSS from `styles.css` when ready for production.

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- **Page Size:** ~15KB (HTML + CSS)
- **Load Time:** <1 second
- **No JavaScript:** Faster initial load
- **No External Dependencies:** No CDN delays

## License

© 2024 Myrateq. All rights reserved.
