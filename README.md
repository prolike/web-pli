# Web Production-like Environment

Include in your Jekyll site as a submodule.

```
cd `git rev-parse --show-toplevel`
git submodule add \
  -b master \
  --depth 1 \
  --name "Web Production-like Environment" \
  https://github.com/prolike/web-pli.git .pli
git submodule init
cp .pli/_dev_config.yml .
git add .
git commit -m "Added the Web Production-like Environment submodule"
```
