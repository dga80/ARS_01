# ARS Advocats - Website

Modern, high-performance website for ARS Advocats built with Astro, Tailwind CSS, and TypeScript.

## 🚀 Quick Start

### Development

```bash
# Install dependencies
npm install

# Start development server
npm run dev
```

Visit `http://localhost:4321` to see the site.

### Build for Production

```bash
# Build the site
npm run build

# Preview the build
npm run preview
```

## 📁 Project Structure

```
/
├── public/
│   ├── images/          # Static images (logo, team photos)
│   └── robots.txt       # SEO robots file
├── src/
│   ├── components/      # Reusable components
│   ├── layouts/         # Page layouts
│   ├── pages/           # Site pages (routes)
│   └── styles/          # Global styles
├── astro.config.mjs     # Astro configuration
├── tailwind.config.mjs  # Tailwind configuration
└── netlify.toml         # Netlify deployment config
```

## 🌐 Pages

- `/` - Homepage (splash page)
- `/presentacio` - Firm presentation
- `/equip` - Team members
- `/especialitats` - Legal services
- `/contacte` - Contact form

## 🎨 Tech Stack

- **Framework:** Astro 5.x
- **Styling:** Tailwind CSS 4.0
- **Deployment:** Netlify
- **Forms:** Netlify Forms
- **SEO:** Built-in meta tags, JSON-LD, sitemap

## 📝 To-Do Before Deployment

- [ ] Replace `/public/images/logo.png` with actual ARS logo
- [ ] Replace team photos in `/public/images/team/`
- [ ] Update social media URLs in components if needed
- [ ] Test contact form after Netlify deployment

## 🚀 Deployment to Netlify

1. Build the site: `npm run build`
2. Connect your Git repository to Netlify
3. Configure build settings:
   - Build command: `npm run build`
   - Publish directory: `dist`
4. Deploy!

The `netlify.toml` file contains all necessary configuration.

## 📧 Contact Form

The contact form uses Netlify Forms. After deployment:
1. Go to Netlify dashboard → Forms
2. Configure email notifications
3. Test form submissions

## 📄 License

© 2026 ARS Advocats. All rights reserved.
