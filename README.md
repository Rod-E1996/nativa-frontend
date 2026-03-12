# NATIVA Landing Page

**Migrated to Nuxt 3** - Modern Vue.js framework with improved performance and developer experience.

## Tech Stack

### Core Framework
- **Nuxt 3** (v3.17.7) - The Intuitive Vue Framework
- **Vue 3** (v3.5.27) - Progressive JavaScript Framework

### Styling
- **Tailwind CSS** (v3.4.17) - Utility-first CSS framework
- **@nuxtjs/tailwindcss** (v6.12.2) - Nuxt module for Tailwind
- **@tailwindcss/forms** (v0.5.9) - Form styles plugin
- **@tailwindcss/aspect-ratio** (v0.4.2) - Aspect ratio utilities
- **Autoprefixer** (v10.4.20) - PostCSS plugin

### Data Visualization
- **Chart.js** (v4.4.7) - Simple yet flexible JavaScript charting
- **vue-chartjs** (v5.3.2) - Vue wrapper for Chart.js

### Animations & UX
- **AOS** (v2.3.4) - Animate On Scroll library

### Development Tools
- **Prettier** (v3.4.2) - Code formatter

## Project Structure

```
.
├── app.vue              # Main app component (Nuxt 3)
├── assets
│   ├── css
│   └── img
├── components
│   ├── base
│   └── landing
├── layouts
├── mixins
├── pages
├── public               # Static assets (images, fonts, etc.)
│   └── img
├── nuxt.config.js
├── package.json
└── tailwind.config.js
```

## Getting Started

```bash
# clone this repository
$ git clone https://github.com/Rod-E1996/nativa-frontend.git

# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

## Migration Notes (Nuxt 2 → Nuxt 3)

### Key Changes:
- ✅ Removed Vue 2 dependencies (`vue-server-renderer`, `vue-template-compiler`, `vue2-smooth-scroll`)
- ✅ Removed deprecated Material Design Icons library (replaced with inline SVG)
- ✅ Updated Chart.js from v2 to v4 with new API
- ✅ Migrated from `require()` to static asset paths in `/public`
- ✅ Updated layout syntax (`<Nuxt />` → `<NuxtPage />`)
- ✅ Removed obsolete ESLint dependencies (incompatible peer dependencies resolved)
- ✅ Added `app.vue` as main entry point

## Other version of NATIVA
