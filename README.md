# OATLinks 🚀

OATLinks is a premium, high-performance link tree application built with **Astro**. It features a modern dark-mode aesthetic, immersive background animations, and industry-standard image optimization.

## ✨ Features

- 🖼️ **Astro Asset Optimization**: Uses `astro:assets` (`<Image />` and `<Picture />`) for automated WebP/AVIF generation and image resizing.
- 🌌 **Premium Particle Background**: A "Pure CSS" particle system driven by Astro's dynamic templating, featuring floating particles and a masked sky background.
- ✨ **Fluid Animations**: Staggered entrance animations for link cards utilizing GPU-accelerated CSS transforms.
- 🔍 **SEO & Social Ready**: Fully configured with Open Graph meta tags and Twitter card support for professional social sharing.
- 📱 **Responsive Design**: Mobile-first architecture that scales perfectly from smartphones to desktops.

## 🚀 Project Structure

```text
/
├── public/          # Static assets (favicons, etc.)
├── src/
│   ├── img/         # Optimized source images and icons
│   ├── pages/       # Astro pages (index.astro)
│   └── style.css    # Modern CSS design system
└── package.json
```

## 🧞 Commands

All commands are run from the root of the project:

| Command | Action |
| :--- | :--- |
| `pnpm install` | Installs dependencies |
| `pnpm dev` | Starts local dev server at `localhost:4321` |
| `pnpm build` | Builds the production site to `./dist/` |
| `pnpm preview` | Previews the build locally |
| `pnpm astro ...` | Runs Astro CLI commands |

## 🛠️ Built With

- **Framework**: [Astro](https://astro.build/)
- **Styling**: Vanilla CSS (Custom Design System)
- **Icons**: Icons8
- **Deployment**: Configured for Netlify

---
*Created by [Otheman El Farji](https://oatman.netlify.app/)*
