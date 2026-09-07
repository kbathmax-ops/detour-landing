# detour — landing page

The one-page site for [detour](https://github.com/kbathmax-ops/detour-extension),
a Chrome extension that hides flight results routing through the US.

Live: https://detour-landing-roan.vercel.app

## Editing

`index.html` is the whole site — no build step, no dependencies, no framework.
Open it in a browser to preview. Pushing to `main` deploys to production
automatically; pushing any other branch gets a preview URL.

## Before the store listing goes live

The install button points at the extension repo. Swap the `href` marked in
`index.html` for the Chrome Web Store URL once the listing clears review.

## Note on the URL

Production is **detour-landing-roan.vercel.app**. `detour-landing.vercel.app`
without the suffix is a different project belonging to someone else — don't
share that one.
