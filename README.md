
# My Font

[![][Fontbakery]](https://SorkinType.github.io/Black-Ops/fontbakery/fontbakery-report.html)
[![][Universal]](https://SorkinType.github.io/Black-Ops/fontbakery/fontbakery-report.html)
[![][GF Profile]](https://SorkinType.github.io/Black-Ops/fontbakery/fontbakery-report.html)
[![][Outline Correctness]](https://SorkinType.github.io/Black-Ops/fontbakery/fontbakery-report.html)
[![][Shaping]](https://SorkinType.github.io/Black-Ops/fontbakery/fontbakery-report.html)

[Fontbakery]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FSorkinType%2FBlack-Ops%2Fgh-pages%2Fbadges%2Foverall.json
[GF Profile]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FSorkinType%2FBlack-Ops%2Fgh-pages%2Fbadges%2FGoogleFonts.json
[Outline Correctness]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FSorkinType%2FBlack-Ops%2Fgh-pages%2Fbadges%2FOutlineCorrectnessChecks.json
[Shaping]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FSorkinType%2FBlack-Ops%2Fgh-pages%2Fbadges%2FShapingChecks.json
[Universal]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FSorkinType%2FBlack-Ops%2Fgh-pages%2Fbadges%2FUniversal.json

Black Ops is a low contrast semi geometric typeface inspired by military stencil lettering. Black Ops is heavy, sturdy, and punchy. Because of the small cuts found in stencils like this one, Black Ops will look best when used at medium to large sizes.

![Sample Image](documentation/image1.png)

## About

James Grieshaber, is a type designer
Eben Sorkin, is a type designer and art director

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions - look at https://SorkinType.github.io/Black-Ops.

## Changelog

When you update your font (new version or new release), please report all notable changes here, with a date.
[Font Versioning](https://github.com/googlefonts/gf-docs/tree/main/Spec#font-versioning) is based on semver. 
Changelog example:

**12 July 2021. Version 1.004**

- SIGNIFICANT Many new langauges are supported.
- SIGNIFICANT Many new Symbols are present.

kerning to be added

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.
