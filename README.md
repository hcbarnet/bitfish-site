# Bitfish site

Public site for **Bitfish: Hollow County**: privacy policy, support and a short
landing page. Published with GitHub Pages from the `main` branch.

Kept separate from the game repo, which is private. These are public documents
by definition, and GitHub Pages needs a public repo on a free plan.

## app-ads.txt

`app-ads.txt` is present but **not yet effective**. Crawlers look for it at the
root of the developer domain in the App Store listing — so it has to resolve at
`<domain>/app-ads.txt`. On a project-page URL it sits under
`/bitfish-site/app-ads.txt`, where nothing will look for it.

Point a custom domain at this repo (a `CNAME` file, as `malachi-speaks-privacy`
does) and it starts working with no other change. It is optional for launch: it
unlocks programmatic ad demand, it does not gate serving.
