# Much Kennel

Static mirror of Much Kennel, deployed to GitHub Pages: https://0xzahra.github.io/much-kennel/

The built `assets/` folder (JS, CSS, PNG) is stored as a base64 tar.gz split into `bundle/assets.tgz.b64.part*` and unpacked by the Pages workflow (`.github/workflows/pages.yml`). To get it locally: `cat bundle/assets.tgz.b64.part* | base64 -d | tar xzf -`
