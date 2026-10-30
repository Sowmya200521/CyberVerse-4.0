# CyberVerse 4.0 — Advanced Labs & Learning Dashboard

An updated frontend-only Vite project based on CyberVerse 3.0.

## Run locally

1. Open the **CyberVerse-4.0** folder containing `package.json` in VS Code.
2. Run `npm install`.
3. Run `npm run dev` and open the URL shown.
4. Run `npm run build` to create the `dist` folder for static deployment.
5. Run `npm run preview` to check the production build.

## What's new

- Enhanced procedural Three.js laptop scene with rotating clickable 3D security objects.
- 108 curated quiz questions across 6 topics, with three difficulty levels, randomized options, practice and assessment modes, and explanations.
- Topic-wise best scores, recent assessment history, 10 unlockable achievement badges.
- Downloadable educational completion certificate as HTML; open it and Print > Save as PDF.
- Portfolio/About panels and a GitHub link configurable with `GITHUB_REPOSITORY_URL` in `src/main.js`.
- Existing password, phishing, network, encryption, and challenge exercises preserved.

## Important

- Educational simulations only. URL heuristics cannot certify a site as safe.
- Progress is saved only in the current browser via localStorage; do not store sensitive data there.
- The certificate is not an accredited qualification.
- GitHub link remains disabled until you add your real repository URL.
- To update your existing Vercel site, build and deploy the **contents of `dist`** to the existing project. Don't create a new project unless you want a new URL.
