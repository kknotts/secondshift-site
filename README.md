# toolbelt-site

Static marketing site. Everything under /site deploys to GitHub Pages on
merge to main. Landing page, start-here, demo, and /blog articles.
Merging to main IS the deploy; there is no other publish step.

Setup once: repo Settings > Pages > Source: GitHub Actions. Point the
custom domain here and enable HTTPS.

Content rule: articles arrive as pull requests from the content job in
the kit repo, or are written by hand. Nothing publishes unmerged.
