# biome-vcs-include

REPODUCTION

1. run `npm install` then `npx biome format .`

EXPECTED

src/ignore/index.js should be formatted, but src/main/index.js should be ignored

ACTUAL

Both files are formatted. If you set `useIgnoreFile` to false, it now works as expected.
