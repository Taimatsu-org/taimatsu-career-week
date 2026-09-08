# TAIMATSU at Le Wagon Japan Career Week

A 45-minute introduction to TAIMATSU, the Samurai Tax refund platform, the
Shopify storefronts and their move to Hydrogen, and the two engineering teams.

**This repository is generated. Do not edit `index.html` here.**

The source lives in `Taimatsu-org/HR-Training-repo` as `career.html`, with its
styles, scripts and images alongside it. To publish a change:

```bash
# in HR-Training-repo, after editing career.html
node tools/check-career.js
python3 tools/build-artifact.py /path/to/this/repo/index.html --standalone
```

Then commit and push here. `index.html` is one self-contained file: the
stylesheets, scripts and images are all inlined, so nothing else is needed to
serve it.

The page carries `noindex` and this repo carries a `robots.txt`, because it
names people's roles and our current hiring position. Anyone with the link
still reads it, which is the intent.
