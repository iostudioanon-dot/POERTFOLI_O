# PORTFOL I/O Hosting Plan

## Recommended Host

Use Vercel for the first live version because the site is a Next.js application and currently builds cleanly with `npm run build`.

## GitHub Role

GitHub should act as:

- source-code archive
- version history
- deployment source for Vercel
- future collaboration/review space

## Current Readiness

The local project already has:

- `package.json` with `dev`, `build`, `start`, and `lint` scripts
- Next.js App Router routes
- reusable components
- structured project metadata
- public asset folders
- responsive styling
- successful local production build

## Next Steps

1. Push all local project files into this repository.
2. Import `iostudioanon-dot/POERTFOLI_O` into Vercel.
3. Use default Vercel build settings:
   - Framework: Next.js
   - Install command: `npm install`
   - Build command: `npm run build`
   - Output: Vercel default
4. Add a custom domain later if needed.

## GitHub Pages Alternative

GitHub Pages can be used later, but it will need a static export configuration and careful route/image handling. Keep Vercel as the safer first host for this Next.js build.
