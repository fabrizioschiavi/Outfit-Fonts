----
# Outfit Fonts

[![][Fontbakery]](https://Outfitio.github.io/Outfit-Fonts/fontbakery-report.html)
[![][Universal]](https://Outfitio.github.io/Outfit-Fonts/fontbakery-report.html)
[![][GF Profile]](https://Outfitio.github.io/Outfit-Fonts/fontbakery-report.html)
[![][Outline Correctness]](https://Outfitio.github.io/Outfit-Fonts/fontbakery-report.html)
[![][Shaping]](https://Outfitio.github.io/Outfit-Fonts/fontbakery-report.html)

[Fontbakery]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FOutfitio%2FOutfit-Fonts%2Fgh-pages%2Fbadges%2Foverall.json
[GF Profile]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FOutfitio%2FOutfit-Fonts%2Fgh-pages%2Fbadges%2FGoogleFonts.json
[Outline Correctness]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FOutfitio%2FOutfit-Fonts%2Fgh-pages%2Fbadges%2FOutlineCorrectnessChecks.json
[Shaping]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FOutfitio%2FOutfit-Fonts%2Fgh-pages%2Fbadges%2FShapingChecks.json
[Universal]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FOutfitio%2FOutfit-Fonts%2Fgh-pages%2Fbadges%2FUniversal.json


![FSD Outfit as Reddit font sample](https://github.com/fabrizioschiavi/Outfit-Fonts/blob/main/documentation/fsd_outfit_reddit.png)
![FSD Outfit changes](https://github.com/fabrizioschiavi/Outfit-Fonts/blob/main/documentation/fsd_outfit_changes.png)

Original Outfit specimen repo:
![Outfit original sample](documentation/image1.png)

## About

A beautiful geometric sans: The official typeface for brand automation company outfit.io

> “typefaces are the clothes words wear.” -Beatrice Warde

Inspired by the ligature-rich outfit wordmark, Outfit.io is delighted to release it's own type family.
The Outfit typeface links the Outfit written voice to Outfit product marks; on brand by default. 


The proof files and QA tests are also available [automatically via GitHub Actions](https://outfitio.github.io/Outfit-Fonts/)


## Building

Fonts are built automatically by GitHub Actions

If you want to build fonts manually on your own computer:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

## Changelog

**8 May 2025. Version 1.104**
- [Fabrizio Schiavi](https://fsd.it) changes `e r f ff` and regenerate the Variable Fonts and all the Static Fonts

**30 April 2025. Version 1.102**
- [Fabrizio Schiavi](https://fsd.it) changes `r ff fj rt rf` create `ffi ffl` ligatures and regenerate the Variable Fonts 

**28 April 2025. Version 1.101**
- [Fabrizio Schiavi](https://fsd.it) changes `t fi fl` and regenerate the Variable Fonts 

**29 August 2021. Version 1.0**
- Hello World - Initial Public Release.

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is copied below, and is also available with a FAQ at
https://scripts.sil.org/OFL

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.
