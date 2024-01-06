# How this monorepo was setup via NX:

arvil@Mac-mini  ~/Repos  npx create-nx-workspace --pm pnpm

> NX Let's create a new workspace [https://nx.dev/getting-started/intro]

✔ Where would you like to create your workspace? · astro-fails-to-serve-dev-overlay
✔ Which stack do you want to use? · node
✔ What framework should be used? · none
✔ Integrated monorepo, or standalone project? · integrated
✔ Application name · backend
✔ Would you like to generate a Dockerfile? [https://docs.docker.com/] · No
✔ Enable distributed caching to make your CI faster · No

> NX Creating your v17.2.8 workspace.

To make sure the command works reliably in all environments, and that the preset is applied correctly,
Nx will run "pnpm install" several times. Please wait.

✔ Installing dependencies with pnpm
✔ Successfully created the workspace: astro-fails-to-serve-dev-overlay.
arvil@Mac-mini  ~/Repos  cd astro-fails-to-serve-dev-overlay

# Start Dev:

`pnpm exec nx run frontend-astro:dev`
