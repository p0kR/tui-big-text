# Changelog

All notable changes to this project will be documented in this file.

## [0.4.0](https://github.com/joshka/tui-big-text/releases/tag/0.4.0) - 2024-02-08

### Bug Fixes

- [8e17a8e](https://github.com/joshka/tui-big-text/commit/8e17a8e703d5953299a6fa2083a81150483f374c)
  Typos

### Features

- [9233b06](https://github.com/joshka/tui-big-text/commit/9233b0665d29d5cb0006ce057d63ce7f11537322)
  Add sextant-based fonts ([#26](https://github.com/joshka/tui-big-text/pull/26))

  ````text
  Adds two new sizes of pixels `ThirdHeight` and `Sextant`
  which use the sextant characters to render big text 1/3 the normal
  big text height and 1/2 wide * 1/3 height respectively.

  ---------
  ````

### Miscellaneous Tasks

- [64d5921](https://github.com/joshka/tui-big-text/commit/64d59216acd0fded2dbcc2d1ae9a024843847fbf)
  Bump codecov/codecov-action from 3 to 4 ([#34](https://github.com/joshka/tui-big-text/pull/34))

  ````text
  Bumps [codecov/codecov-action](https://github.com/codecov/codecov-action) from 3 to 4.
  - [Release notes](https://github.com/codecov/codecov-action/releases)
  - [Changelog](https://github.com/codecov/codecov-action/blob/main/CHANGELOG.md)
  - [Commits](https://github.com/codecov/codecov-action/compare/v3...v4)

  ---
  updated-dependencies:
  - dependency-name: codecov/codecov-action
    dependency-type: direct:production
    update-type: version-update:semver-major
  ...
  ````

### Refactor

- [a7db511](https://github.com/joshka/tui-big-text/commit/a7db5113cdde257fb1c30eef52cd2b166bcd29c4)
  Split big_text and pixel_size into modules for readability

<!-- generated by git-cliff -->

## [0.3.6](https://github.com/joshka/tui-big-text/releases/tag/0.3.6) - 2024-02-04

### Miscellaneous Tasks

- [b49f69b](https://github.com/joshka/tui-big-text/commit/b49f69ba9c0def1c6d9c8886f46542b914a5b9c7)
  Update ratatui to 0.26 ([#32](https://github.com/joshka/tui-big-text/pull/32))

<!-- generated by git-cliff -->
<!-- generated by git-cliff -->

## [0.3.4](https://github.com/joshka/tui-big-text/releases/tag/0.3.4) - 2024-01-29

### Miscellaneous Tasks

- [0fe1dd5](https://github.com/joshka/tui-big-text/commit/0fe1dd5bb2e2d150c2f8874527c3ce3816be8fab)
  Update derive_builder requirement from 0.12.0 to 0.13.0 ([#29](https://github.com/joshka/tui-big-text/pull/29))

  ````text
  Updates the requirements on [derive_builder](https://github.com/colin-kiegel/rust-derive-builder) to permit the latest version.
  - [Release notes](https://github.com/colin-kiegel/rust-derive-builder/releases)
  - [Commits](https://github.com/colin-kiegel/rust-derive-builder/compare/v0.12.0...v0.13.0)

  ---
  updated-dependencies:
  - dependency-name: derive_builder
    dependency-type: direct:production
  ...
  ````

<!-- generated by git-cliff -->

## [0.3.3](https://github.com/joshka/tui-big-text/releases/tag/0.3.3) - 2024-01-24

### Bug Fixes

- [faaa42c](https://github.com/joshka/tui-big-text/commit/faaa42c07e335684922d68c5ec198d5edfd5b80d)
  Builder initialization of BigTextBuilder in docs ([#27](https://github.com/joshka/tui-big-text/pull/27))

### Miscellaneous Tasks

- [5b2a0d7](https://github.com/joshka/tui-big-text/commit/5b2a0d71e956518cb77df7aebcf5691894a36f6a)
  Fix missing changelog entry for PixelSize change

  ````text
  git-cliff missed the change due to case sensitivity
  ````
- [c505b82](https://github.com/joshka/tui-big-text/commit/c505b824c0a1f89c4df4361c6cc70b5b3b2a1d04)
  Create dependabot.yml

<!-- generated by git-cliff -->

## [0.3.2](https://github.com/joshka/tui-big-text/releases/tag/0.3.2) - 2024-01-12

### Features

- [9ffb3bf](https://github.com/joshka/tui-big-text/commit/9ffb3bf11e5405ecb339752b52eeedf3897ed347)
  Add PixelSize option

  Add a new `TuiBigText::pixel_size()` option that indicates the size of a pixel in the font
  - Full: a full character cell (`'█'`)
  - HalfHeight: a half (upper/lower) character cell (`'▀', '▄'`)
  - HalfWidth: a half (left/right) character cell (`'▌', '▐'`)
  - Quadrant: a quadrant of a character cell (`'▘', '▝', '▖', '▗'`)

  The Half height option leads to the most square looking pixels as terminals usually render
  cells around twice as high as they are wide.

### Documentation

- [f127fde](https://github.com/joshka/tui-big-text/commit/f127fde7e945310d77aed010fb2198eecd555dc5)
  Improve examples

### Miscellaneous Tasks

- [70490cd](https://github.com/joshka/tui-big-text/commit/70490cd39380dd06b175e37bf9be2555a1cb1872)
  Clean up links
- [9fcf4ff](https://github.com/joshka/tui-big-text/commit/9fcf4ffbb5ea9e44dad2724ee51f33b22bff6361)
  More cleanup

<!-- generated by git-cliff -->

## [0.3.1](https://github.com/joshka/tui-big-text/releases/tag/0.3.1) - 2023-12-23

### Documentation

- [bc3cd46](https://github.com/joshka/tui-big-text/commit/bc3cd46a8f2e34ae65054b6191e9475d477612c1)
  Update example image ([#20](https://github.com/joshka/tui-big-text/pull/20))

<!-- generated by git-cliff -->

## [0.3.0](https://github.com/joshka/tui-big-text/releases/tag/0.3.0) - 2023-12-23

### Documentation

- [541ac21](https://github.com/joshka/tui-big-text/commit/541ac21d1af72ff7c20425ca96048a369a7f57d2)
  Hello world raw mode and screenshot ([#19](https://github.com/joshka/tui-big-text/pull/19))

### Miscellaneous Tasks

- [5b030f6](https://github.com/joshka/tui-big-text/commit/5b030f6f3c5587e25a38d8e6317d89e58b93050e)
  Add check for cargo-rdme to ensure readme is updated when lib.rs docs are ([#16](https://github.com/joshka/tui-big-text/pull/16))

  ````text
  * ci: add check for cargo-rdme to ensure readme is updated when lib.rs docs are
  * docs: update readme with recent change for Frame no longer being generic
  ````

- [3042382](https://github.com/joshka/tui-big-text/commit/3042382c09177574ca72563c5c99db43af26a815)
  Update dependencies to ratatui 0.25.0 and itertools 0.12.0 ([#18](https://github.com/joshka/tui-big-text/pull/18))

<!-- generated by git-cliff -->

## [0.1.5](https://github.com/joshka/tui-big-text/releases/tag/0.1.5) - 2023-10-27

### Bug Fixes

- [9501e45](https://github.com/joshka/tui-big-text/commit/9501e45ff7835f7f4f17f40f306dd03ec6bbfd0e)
  Update examples to build with ratatui 0.24.0

<!-- generated by git-cliff -->

## [0.1.4](https://github.com/joshka/tui-big-text/releases/tag/0.1.4) - 2023-09-05

### Miscellaneous Tasks

- [id](https://github.com/joshka/tui-big-text/commit/id)
  Undo release-plz fetch-depth change
- [id](https://github.com/joshka/tui-big-text/commit/id)
  Update changelog

<!-- generated by git-cliff -->

## [0.1.3](https://github.com/joshka/tui-big-text/releases/tag/v0.1.3) - 2023-09-05

### Bug Fixes

- [b2be1bb](https://github.com/joshka/tui-big-text/commit/b2be1bb3bd6dbf5b26b0f104f9f26f30b438f813)
  Add doc test imports (#8)

### Documentation

- [22d8822](https://github.com/joshka/tui-big-text/commit/22d88226498d0c4478598931e217773c1b17f0c1)
  Tweak readme, licenses, contributing (#10)

### Miscellaneous Tasks

- [22f3b19](https://github.com/joshka/tui-big-text/commit/22f3b19f5669ab2a779461d426e9f3ab3f9fd6a2)
  Add ci.yml (#6)
- [10f854e](https://github.com/joshka/tui-big-text/commit/10f854ed05cbfefa90cebb57a958e26b7a59d2fd)
  Add bacon config
- [8bbaed3](https://github.com/joshka/tui-big-text/commit/8bbaed356041220d1d48a1a0eb05cfb85c6ead02)
  Configure git-cliff (#11)
- [4721f0d](https://github.com/joshka/tui-big-text/commit/4721f0d2daaa91281ebcf7f82a25e58fcd5aa9da)
  Configure release-plz fetch depth

  ````text
  Ensures that the release-plz action fetches the full commit history
  for the repository so that it can use the ids in the changelog.
  ````

### Refactor

- [48e635a](https://github.com/joshka/tui-big-text/commit/48e635a883bd8dae7f7d942e864361c9f596bd1f)
  Render fn

### Testing

- [c13cd63](https://github.com/joshka/tui-big-text/commit/c13cd636eb3399c7ef26a444cd4277c273911fc7)
  Fix coverage for expected buffers in codecov

  ````text
  I'm unsure why the code coverage doesn't see these lines as covered,
  but extracting a variable fixes it.
  ````

## [0.1.2](https://github.com/joshka/tui-big-text/releases/tag/v0.1.2) - 2023-09-05

### Documentation

- [3a1b8c6](https://github.com/joshka/tui-big-text/commit/3a1b8c60aa424b14b94b47d75c15cc625e800f71)
  Use cargo-rdme to sync lib.rs to README.md (#4)

## [0.1.1](https://github.com/joshka/tui-big-text/releases/tag/v0.1.1) - 2023-09-05

### Bug Fixes

- [686a58f](https://github.com/joshka/tui-big-text/commit/686a58f81fb489f8c30b8f549939a1729dbc72af)
  Render correctly when not at the origin

### Documentation

- [030981a](https://github.com/joshka/tui-big-text/commit/030981ad9398569af082110c740d0cd44b80c2d5)
  Add stopwatch example

### Features

- [ba75f24](https://github.com/joshka/tui-big-text/commit/ba75f24b154ddab7cacd84f4b03d0b1ae65f32c9)
  Initial implementation

### Miscellaneous Tasks

- [1378e62](https://github.com/joshka/tui-big-text/commit/1378e624680f4968f02a0e3a70b36f175a4a0425)
  Fix repository link (#1)

### Styling

- [0915802](https://github.com/joshka/tui-big-text/commit/09158028143300ed07aff10968fcc3dcd122271a)
  Readme wrapping

<!-- generated by git-cliff -->
