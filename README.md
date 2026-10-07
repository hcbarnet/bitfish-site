# Bitfish site

Public site for **Bitfish: Hollow County**: privacy policy, support and a short
landing page. Published with GitHub Pages from the `main` branch.

Kept separate from the game repo, which is private. These are public documents
by definition, and GitHub Pages needs a public repo on a free plan.

## Custom domain

The site is served at **https://bitfish.app** via the `CNAME` file. GitHub Pages
needs the DNS at the registrar to point here:

| Type  | Host  | Value                 |
|-------|-------|-----------------------|
| A     | `@`   | `185.199.108.153`     |
| A     | `@`   | `185.199.109.153`     |
| A     | `@`   | `185.199.110.153`     |
| A     | `@`   | `185.199.111.153`     |
| CNAME | `www` | `hcbarnet.github.io`  |

Then in the repo's Settings → Pages, confirm the custom domain shows
`bitfish.app` and tick **Enforce HTTPS** once the certificate is issued.

## app-ads.txt

`app-ads.txt` authorises Google AdMob to sell inventory for the app. Crawlers
look for it at the root of the developer domain in the App Store listing, so it
resolves at `https://bitfish.app/app-ads.txt` once the DNS above is live. The
store listing's developer website must be `https://bitfish.app` for AdMob to
find it.
