# Face Glowva — legal pages

Public hosting for the Face Glowva mobile app's legal documents, served by GitHub Pages
from the root of `main` — the same shape as `SuMo-Productivity/ShieldX-Privacy`.

| Page | URL |
| :-- | :-- |
| Privacy Policy | https://faceglowva.sumosols.com/privacy_policy.html |
| Terms of Use | https://faceglowva.sumosols.com/terms_of_use.html |

The Privacy Policy URL is the one required by the Google Play Console store listing.

## Custom domain

`CNAME` pins the site to `faceglowva.sumosols.com`, which needs a matching DNS record:

    faceglowva   CNAME   sumo-productivity.github.io.

Until that record resolves and Pages is enabled, the site will not serve.

## Notes

Source of truth for these files is `docs/legal/` in the app repository — edit there, then
copy here. `.nojekyll` keeps GitHub Pages from running the files through Jekyll.

No `app-ads.txt` (Face Glowva shows no ads) and no `delete-account.html` (the app has no
accounts — everything is on-device, so there is no server-side data to delete).
