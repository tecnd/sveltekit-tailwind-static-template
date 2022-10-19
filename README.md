# sveltekit-tailwind-static-template

Everything you need to start building a static site with SvelteKit and TailwindCSS.
Perfect for deploying to Netlify, Cloudflare Pages, etc.

## Developing

Once you've created a project and installed dependencies with `npm install` (or
`pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

## CSR

By default, client-side rendering is disabled. This essentially turns SvelteKit
into a static site generator, where all of the HTML is generated at build time
and nothing changes afterwards. If you need CSR, you can set

```ts
export const csr = true;
```

in `src/routes/+layout.ts` to enable it.
