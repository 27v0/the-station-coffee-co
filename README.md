# The Station Coffee Co. — Official Website

Modern, lightweight, ultra-fast corporate coming soon & future web platform for **The Station Coffee Co.**

## 🚀 Tech Stack

- **Framework:** [Astro](https://astro.build/) (Static Site Generation / Zero-JS by default)
- **SEO & Metadata:**
  - Automated XML Sitemaps (`@astrojs/sitemap`)
  - `robots.txt` configuration
  - OpenGraph & Twitter Card tags
  - Schema.org (`CafeOrCoffeeShop` JSON-LD Structured Data) for Google Local Search
- **Hosting & Deployment:** [Vercel](https://vercel.com/) (Edge CDN, Automated SSL, Zero-config Astro integration)

## 🛠️ Local Development

```bash
# Install dependencies
npm install

# Start local development server
npm run dev

# Build for production
npm run build

# Preview production build locally
npm run preview
```

## 🌐 Deploy to Vercel

1. Push this repository to GitHub:
   ```bash
   git remote add origin https://github.com/<your-username>/<your-repo-name>.git
   git branch -M main
   git push -u origin main
   ```
2. Go to [Vercel Dashboard](https://vercel.com/new).
3. Import this repository. Vercel automatically detects **Astro** with:
   - **Framework Preset:** Astro
   - **Build Command:** `npm run build`
   - **Output Directory:** `dist`
4. Click **Deploy**.
5. Add your custom domain under **Project Settings > Domains**.
