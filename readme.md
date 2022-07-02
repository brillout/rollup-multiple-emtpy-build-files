# Reproduction

Showcase that Rollup can generated multiple empty build files.

```bash
git clone git@github.com:brillout/rollup-multiple-emtpy-build-files
cd rollup-multiple-emtpy-build-files/
pnpm install
pnpm run build
```

Same as single line (copy-paste me):

```bash
git clone git@github.com:brillout/rollup-multiple-emtpy-build-files && cd rollup-multiple-emtpy-build-files/ && pnpm install && pnpm run build
```

Now observe:

```bash
# Empty file
cat dist/client/assets/chunk-87797ab9.js
# Another empty file
cat dist/client/assets/chunk-87797ab92.js
```

This is a small demo; in a realistic app there are a lot more of these empty files.
