# Base Astro + Tailwind

Projet minimal Astro 5 avec Tailwind CSS 4 déjà câblé via le plugin Vite.

## Installation

```sh
npm install
```

## Scripts

- `npm run dev` : démarre le serveur de dev sur `localhost:4321`
- `npm run build` : build statique dans `dist/`
- `npm run preview` : prévisualise le build

## Structure

- `src/pages/index.astro` : page d'accueil avec Tailwind importé.
- `src/styles/global.css` : point d'entrée Tailwind (`@import "tailwindcss";`).
- `public/` : assets statiques.

## Ressources

- Docs Astro : https://docs.astro.build
- Docs Tailwind : https://tailwindcss.com/docs
