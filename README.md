# Circle

A responsive React + Vite student community demo for Thapar. Authentication checks only for an `@thapar.edu` email format; it does not verify enrollment or send a code. Posts and chat are local to this browser and are not real-time.

## Run locally

```bash
npm install
npm run dev
```

## Build and deploy

```bash
npm run build
```

Deploy the repository to Vercel with the Vite preset. The included `vercel.json` rewrites application routes to `index.html`; Vercel uses `npm run build` and `dist` as the output directory.

Circle saves the demo account, community membership, community content, and appearance preference in LocalStorage. Clearing browser storage resets the demo.
