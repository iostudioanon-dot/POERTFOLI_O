# PORTFOL I/O

Luke Hillhouse portfolio website for the PORTFOL I/O project.

The site is a lightweight Next.js multimedia portfolio designed as a cinematic archive, classified research interface, architectural operating system, and analogue-digital transmission environment.

## Current Status

The local site is running as a modular archive operating system with:

- cinematic landing transmission interface
- instructions page with archive chart, guide video, and QR transmission node
- layered environmental hub
- IO project routes
- Timeline I/O route
- structured content and asset registries
- lightweight CSS motion, scanlines, subtle glitch hover states, and reduced-motion support

## Local Development

```bash
npm install
npm run dev
```

Open:

```text
http://127.0.0.1:3000
```

Current local workspace:

```text
C:\Users\MHill\Documents\FOL IO
```

## Build Check

```bash
npm run lint
npm run build
```

## Main Routes

- `/`
- `/instructions`
- `/hub`
- `/io1`
- `/io2`
- `/io3`
- `/io4`
- `/xfm`

## Content Structure

Project metadata:

```text
data/projects.ts
```

Global site copy and system labels:

```text
src/data/siteContent.ts
```

Navigation map:

```text
src/data/siteMap.ts
```

Archive assets and external transmissions:

```text
src/data/archiveRegistry.ts
```

Reusable portfolio links:

```text
src/data/portfolioLinks.ts
```

Static assets:

```text
public/assets
```

## Hosting Space

GitHub repository:

```text
https://github.com/iostudioanon-dot/POERTFOLI_O
```

Recommended first deployment path: connect this repository to Vercel and use the default Next.js build settings after the full local source has been pushed into the repo.
