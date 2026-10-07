# GitHub, explained

A plain-words learning site about Git and GitHub. One file: `public/index.html`. No build step.

## Deploy to Cloudflare Pages

`wrangler.jsonc` tells Pages to publish the `public/` folder.

**From GitHub (auto-deploy on every push to main)**

1. Cloudflare dashboard, Workers & Pages, Create, Pages, Connect to Git.
2. Pick this repo. Leave the build command empty.
3. Build output directory: `public`.

**From your computer**

```
npx wrangler pages deploy
```

## Preview locally

```
npx wrangler pages dev
```
