# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html),
with a [Calendar Versioning](https://calver.org/) for 0.x releases.

## [Unreleased]

### Changed

 - Minor updates to documentation.

## [0.20180728.0]

### Added
 - New command line utilities: `sro2syllabics` and `syllabics2sro`!
 - Added `sro2syllabics` `--sandhi`/`--no-sandhi` options.
 - Added `syllabics2sro` `--macrons`/`--circumflexes` options.

### Fixed
 - Fix a bug in `sro2syllabics()` that crashes when transcribing a word
   with one or more hyphens.

### Changed

 - **Breaking change**: hyphens are no longer produced when calling
   `sro2syllabics(..., sandhi=False)`.

## [0.20180724.0]

### Changed

 - **Breaking change**: `sro2syllabics()` gains the `sandhi=True`
   keyword argument that applies the [sandhi][] orthographic convention
   by default on transcriptions from SRO to syllabics.
 - Enhanced comments.
 - Proofread and enhanced glossary.

[sandhi]: https://crk-orthography.readthedocs.io/en/stable/glossary.html#term-sandhi