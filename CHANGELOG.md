# Changes to jscc-brunch

## \[2.8.10] - 2018-12-10

### Added

- @jsbits/deep-clone.
- Simple test with mocha and expect.js
- Brunch 2.10.0 in peerDependencies.
- TypeScript typings.

### Changed

- Update metada and eslint.
- Update Changelog format.
- Update dependencies.
- Update Readme.

## \[2.8.2] - 2016-10-18

### Changed

- Update jscc to v0.3.3
- Brunch plugins (compilers) are not prepared to merge sourceMaps, so now sourceMap is disabled by default.

## \[2.8.1] - 2016-10-18

### Fixed

- Fix to the plugin generating wrong file types.
  Now the file extension is limited to 'js' by default, you can define extensions with the `pattern` option.
