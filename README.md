# cbrear70.github.io

The root of the cbrear70.github.io website. The Rugby Team Picker web app itself lives in the `rugby` repository
(https://cbrear70.github.io/rugby/); this repository only holds files that have to sit at the root of the site:

- `.well-known/apple-app-site-association` and `.well-known/assetlinks.json` (added once the app's Apple Team ID
  and Android signing fingerprint exist): they tell iPhones and Android phones that join and share links to
  https://cbrear70.github.io/rugby/ may open the Rugby Team Picker app. Only that page is claimed.
- `.nojekyll`: stops GitHub Pages skipping the `.well-known` folder (it ignores folders starting with a dot).
