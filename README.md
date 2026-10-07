# GitHub, explained

A plain-words learning site about Git and GitHub. One file: `public/index.html`. No build step.

## Deploy to Cloudflare (Workers static assets)

`wrangler.jsonc` points Cloudflare at the `public/` folder.

**From your computer**

```
npx wrangler deploy
```

**From GitHub (auto-deploy on every merge to main)**

1. Cloudflare dashboard, Workers & Pages, Create, Import a repository.
2. Pick this repo. Leave the build command empty.
3. Deploy command: `npx wrangler deploy`.

## Preview locally

```
npx wrangler dev
```
