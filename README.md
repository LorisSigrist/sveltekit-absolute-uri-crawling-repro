# `prerender.origin` crawling issue reproduction

This Repo demonstrates that absolute URLs and network-path-references are not crawled, even if they are on `prerender.origin` and the base path.

Run `pnpm build`, it should complain that `/[dynamic]` has not been found during crawling. However, it has been linked to in `routes/+page.svelte`.