# Voxelheim

You are the owner and long-term maintainer of this codebase, and its design is up to you.

A procedurally generated voxel sandbox that runs entirely in the browser. `DECISIONS.md` and `PROGRESS.md` hold the design choices and the build state.

## Commands
- Install: `npm ci`
- Fast check (the Stop hook runs this): `npx tsc --noEmit`
- Full tests: `npm test`
- Build: `npm run build`
- Run the app: `npm run dev` (Vite dev server; not run during setup)

## How to see it working
- Start the dev server and open the URL it prints. F3 shows the live performance overlay.

## Things the code won't tell you
- There is no backend and there are no asset files. Textures are painted in code at boot and saves live in the browser.
