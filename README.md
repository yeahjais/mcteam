# MCBot Website

The official website for MCBot - Your all-in-one Discord bot for Minecraft communities.

## 🚀 Project Structure

This is an Astro project with the following structure:

```
/
├── public/
│   └── assets/         # Static assets (fonts, images, CSS, JS)
├── src/
│   ├── components/     # Astro components
│   │   ├── Navigation.astro
│   │   └── Footer.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro # Main page
└── package.json
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |

## 📝 Features

- ✅ Converted to Astro static site generator
- ✅ Componentized Navigation and Footer
- ✅ Fixed navigation vertical centering
- ✅ Optimized for performance with static site generation
- ✅ Easy to maintain and extend

## 🔧 Navigation Component

The navigation component (`src/components/Navigation.astro`) now properly centers all items vertically using flexbox with `align-items: center` applied to:
- The navbar brand
- The navbar navigation list
- Individual nav items

This ensures consistent vertical alignment across all screen sizes.

## 📦 Deployment

The site is built as a static site and can be deployed to any static hosting service:

```bash
npm run build
```

The built files will be in the `dist/` directory.
