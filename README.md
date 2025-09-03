# tsdown-dual-publish-esm-cjs 

If you want to migrate from `tsup` this is a repo to follow.

```
pnpm i
pnpm test
```
What the ouput of `test` looks like.
```
> tsdown

ℹ tsdown v0.14.2 powered by rolldown v1.0.0-beta.34
ℹ Using tsdown config: /Users/hacksore/code/tsdown-dual-publish-esm-cjs/tsdown.config.ts
ℹ entry: src/index.ts
ℹ tsconfig: tsconfig.json
ℹ Build start
ℹ Cleaning 4 files
ℹ [CJS] dist/index.cjs  0.10 kB │ gzip: 0.11 kB
ℹ [CJS] 1 files, total: 0.10 kB
ℹ [CJS] dist/index.d.cts  0.09 kB │ gzip: 0.10 kB
ℹ [CJS] 1 files, total: 0.09 kB
ℹ [ESM] dist/index.js    0.10 kB │ gzip: 0.11 kB
ℹ [ESM] dist/index.d.ts  0.09 kB │ gzip: 0.10 kB
ℹ [ESM] 2 files, total: 0.19 kB
✔ Build complete in 575ms

tsdown-dual-publish-esm-cjs v0.0.0

Build tools:
- typescript@~5.8.3
- tsdown@^0.14.2

 No problems found 🌟


┌───────────────────┬───────────────────────────────┐
│                   │ "tsdown-dual-publish-esm-cjs" │
├───────────────────┼───────────────────────────────┤
│ node10            │ 🟢                            │
├───────────────────┼───────────────────────────────┤
│ node16 (from CJS) │ 🟢 (CJS)                      │
├───────────────────┼───────────────────────────────┤
│ node16 (from ESM) │ 🟢 (ESM)                      │
├───────────────────┼───────────────────────────────┤
│ bundler           │ 🟢                            │
└───────────────────┴───────────────────────────────┘
```

It works 😊!
