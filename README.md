## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```sh
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```sh
npm run build
```

The production build output directory is `dist` (configured for Vercel). If you're deploying to Vercel, set the **Output Directory** option to `dist` in the project settings or keep the included `vercel.json` which tells Vercel to use `dist`.

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://svelte.dev/docs/kit/adapters) for your target environment.
---

## Migration note

This repository was migrated from a static HTML site into a SvelteKit app. The original `index.html` has been moved to `index.html.bak` for reference. To run locally:

```sh
npm install
npm run dev -- --open
```

Build for production with:

```sh
npm run build
```