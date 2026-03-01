# MedStocksy Landing Page

A modern, high-performance landing page for MedStocksy - Pharmacy Management Software for Indian retail chemists.

##🚀 Features

- **Lightweight & Fast**: Optimized for performance with minimal dependencies
- **SEO Optimized**: Complete SEO setup with sitemap, robots.txt, and structured data
- **Mobile Responsive**: Fully responsive design using Tailwind CSS
- **Dark Mode**: Built-in dark/light theme toggle
- **PWA Ready**: Web App Manifest for installable experience
- **Vercel Optimized**: Ready for one-click deployment

##📁 Project Structure

```
MedStocksy-Page/
├── index.html          # Main landing page
├── manifest.json       # PWA manifest
├── robots.txt         # Search engine crawler rules
├── sitemap.xml        # XML sitemap for SEO
├── vercel.json        # Vercel deployment configuration
├── package.json       # Project metadata and scripts
├── assets/            # Static assets
│   ├── logo/         # Logo files
│  └── testimonial/  # Testimonial images
└── README.md         # This file
```

##🛠️ Development

### Local Development

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build
```

### Vercel Deployment

This project is optimized for Vercel deployment:

1. Push to GitHub
2. Connect repository to Vercel
3. Deploy with zero configuration

The `vercel.json` file includes:
- Static file serving configuration
- Cache optimization headers
- Security headers
- Route handling

##🔧 Files

### vercel.json
- Static file serving configuration
- Cache control headers
- Security headers (X-Content-Type-Options)
- GitHub integration

### manifest.json
- PWA configuration
- App icons and theme colors
- Installable web app support

### robots.txt
- Search engine crawler directives
- Sitemap location reference
- File exclusion rules

### sitemap.xml
- Complete site structure for SEO
- Page priorities and update frequencies
- All content pages indexed

## 📈 Performance

- **Core Web Vitals**: Optimized for LCP, FID, CLS
- **SEO**: Complete metadata and structured data
- **Accessibility**: WCAG compliant
- **Mobile**: Responsive design for all devices

##🌐 Live Demo

[https://www.medstocksy.in](https://www.medstocksy.in)

##📝 License

MIT License - See [LICENSE](LICENSE) file for details

##🤝 Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a pull request