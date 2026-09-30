# Deepak Gupta — 3D Developer Portfolio

A personal portfolio website showcasing 3D WebGL work, interactive demos, and project highlights. Built with React, TypeScript and Three.js, the site emphasizes performance, accessibility, and a polished 3D experience.

Repository: https://github.com/deepak-lala/My-Portfolio

## Key Features

- Immersive 3D scenes using Three.js and optimized GLB models
- Smooth animations with GSAP
- Responsive design for desktop and mobile
- Easy-to-edit project and social link sections
- Vite-powered dev server for fast iteration

## Quick Start

1. Clone the repository:

```bash
git clone https://github.com/deepak-lala/My-Portfolio.git
cd My-Portfolio
```

2. Install dependencies:

```bash
npm install
```

3. Run the development server:

```bash
npm run dev
```

4. Build for production:

```bash
npm run build
```

5. Preview the production build locally:

```bash
npm run preview
```

## Deployment

- Recommended: Deploy to Vercel or Netlify for automatic builds from `main`.
- This repo includes a `vercel.json` for Vercel-specific configuration.

## Project Structure (important files)

- `public/` — static assets and GLB models
- `src/` — React + TypeScript source code
- `src/components/Character/` — 3D scene and character utilities
- `src/pages/` — site pages (My Works, Play, etc.)
- `vite.config.ts` — Vite config

## How to Customize

- Change the hero text and name in `src/components/Landing.tsx`.
- Update projects/media in `public/` and corresponding entries in `src/pages/MyWorks.tsx`.
- Update social links in `src/components/SocialIcons.tsx`.

## Notes

- The repository no longer contains an attached license file; this codebase is maintained by Deepak Gupta.
- Large binary assets use Git LFS; ensure `git lfs` is installed when cloning.

## Contact

- Deepak Gupta — https://github.com/deepak-lala

---

If you want additional badges (build, preview) or a custom project screenshot/video inserted, tell me what to add and I'll update the README accordingly.
---

Note: The project license file was intentionally removed; this repository is maintained by Deepak Gupta.
