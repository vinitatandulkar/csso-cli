## next

- Stop support Node.js before `6.14`
- Updated dependencies and fixed known security issues
- Fixed `--usage` option that didn't actually work

## 2.0.2 (December 28, 2018)

- Fixed one more issue with paths in source maps on Windows platform

## 2.0.1 (December 26, 2018)

- Fixed source map paths when perform on Windows platform (path should be in unix format)

## 2.0.0 (December 11, 2018)

- Use relative paths to files in generated source map (#7)
- Removed setting output file with no option label, i.e. `--output` is required
- Renamed options
    - `--restructure-off` → `--no-restructure`
    - `--map` → `--source-map`
    - `--input-map` → `--input-source-map`

## 1.1.0 (September 10, 2017)

- Bumped `CSSO` to `3.2.0`
- Added `--watch` option to run CLI in watch mode (@rijkvanzanten, #4)
- Added `--declaration-list` option to take input as a declaration list (@amarcu5, #8)
- Added `--force-media-merge` option to force `@media` rules merge (see [forceMediaMerge](https://github.com/css/csso#compressast-options) option for details) (@lahmatiy)

## 1.0.0 (March 13, 2017)

- Initial release as standalone package
