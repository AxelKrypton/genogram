# Changelog

All notable changes to the `genogram` package will be documented in this file.

This project does not adhere to [Semantic Versioning](http://semver.org/spec/v2.0.0.html), but it follows some aspects inspired from it.
In particular (even though this is not a strict, always respected rule), given a version number `X.Y`,
 - `Y` is incremented for minor changes (e.g. bug fixes) and 
 - `X` for major ones (e.g. new features).

### Legend

 * :heavy_plus_sign: New feature
 * :heavy_check_mark: Enhancement
 * :sos: Bug fix
 * :heavy_minus_sign: Removed feature

---

## [Unreleased]

* :heavy_plus_sign: Add keys to customize outer space of people with respect to their parents.
* :heavy_plus_sign: Add `\addTikzGlobalOptions` command.
* :heavy_minus_sign: Genogram without frame by default.
* :heavy_check_mark: Adjust `TikZ` coordinates such that they are always at crossing points of connections.
* :heavy_plus_sign: Add `\son` and `\daughter` commands.
* :heavy_minus_sign: Remove `\child` command.
* :heavy_plus_sign: Add `\nephew` and `\niece` commands and placement keys.
* :heavy_plus_sign: Allow moving children vertically with new key.
* :heavy_plus_sign: Add key to customize vertical generation distance of siblings.
* :heavy_plus_sign: Add `\brotherInLaw` and `\sisterInLaw` commands.
* :heavy_check_mark: Change approach to draw genogram in order to respect the order of user commands.

---

## [Version 1.0] &nbsp;&nbsp; <sub><sup>22 March 2019</sub></sup>

This has been the first release of the repository.


[Unreleased]: https://github.com/AxelKrypton/genogram/compare/v1.0...HEAD
[Version 1.0]: https://github.com/AxelKrypton/genogram/releases/tag/v1.0
