# textX-jinja changelog

All _notable_ changes to this project will be documented in this file.

The format is based on _[Keep a Changelog][keepachangelog]_, and this project
adheres to _[Semantic Versioning][semver]_.

Everything that is documented in the [official docs][textXDocs] is considered
the part of the public API.

Backward incompatible changes are marked with **(BIC)**. These changes are the
reason for the major version increase so when upgrading between major versions
please take a look at related PRs and issues and see if the change affects you.

## [Unreleased]

### Added
  - Support for model iterables in filenames [#1]. Thanks balsa-sarenac@GitHub.

### Fixed

### Changed


[#1]: https://github.com/textX/textX-jinja/pull/1

## [0.2.1] (Released: 2020-11-01)

### Fixed
  - Added `click` dependency.

### Changed

  - Make warning about not overwriting generated file more visible
    ([7a06fd7543f98](https://github.com/textx/textX-jinja/commit/7a06fd7))


## [0.2.0] (Released: 2020-10-05)

### Added
- Support for single template file and output filename instead of path
  ([824618c6c](https://github.com/textX/textX-jinja/commit/824618c),
  [2bbdf05a](https://github.com/igordejanovic/textX-jinja/commit/2bbdf05))
- Support for jinja filters
  ([350df6b1f](https://github.com/igordejanovic/textX-jinja/commit/350df6b))

### Fixed
- Removed `project_name` from config dict
  ([2f82d94c7](https://github.com/igordejanovic/textX-jinja/commit/2f82d94))


## [0.1.0]

- Initial release


[Unreleased]: https://github.com/textX/textX-jinja/compare/0.2.1...HEAD
[0.2.1]: https://github.com/textX/textX-jinja/compare/0.2.0...0.2.1
[0.2.0]: https://github.com/textX/textX-jinja/compare/0.1.0...0.2.0
[0.1.0]: https://github.com/textX/textX-jinja/tree/0.1.0


[keepachangelog]: https://keepachangelog.com/
[semver]: https://semver.org/spec/v2.0.0.html
[textXDocs]: http://textx.github.io/textX/latest/
