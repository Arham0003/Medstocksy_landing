# MedStocksy Landing Page

A modern, responsive landing page for MedStocksy - a Pharmacy CRM & Inventory Management platform.

## Deployment to Vercel

This site is ready for deployment to Vercel. Simply:

1. Push this repository to GitHub
2. Connect the repository to Vercel
3. Deploy!

The `vercel.json` configuration file handles routing:
- `/` routes to `/dashboard/main.html`
- All other paths route to corresponding files in `/dashboard/`

## Local Development

To run locally:

```bash
npm install
npm run dev
```

Or simply open `dashboard/main.html` directly in your browser.

## File Structure

```
├── dashboard/
│   ├── assets/
│   │   └── medstocky.png
│   └── main.html
├── index.html          # Redirects to dashboard/main.html
├── vercel.json         # Vercel configuration
└── package.json        # Project metadata
```

## Features

- Responsive design with Tailwind CSS
- Dark/light theme toggle
- Smooth animations and transitions
- Mobile-friendly navigation
- Modal dialogs for legal information
- Pricing section with toggle
- Modern glass-morphism UI elements

## Customization

To customize the content:
- Edit `dashboard/main.html` for the main landing page content
- Update images in `dashboard/assets/`
- Modify styles in the `<style>` section of the HTML file