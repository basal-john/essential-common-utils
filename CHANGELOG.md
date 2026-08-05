# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [1.15.0](https://github.com/basal-john/essential-common-utils/compare/essential-common-utils-v1.14.1...essential-common-utils-v1.15.0) (2026-08-05)


### Features

* add capitalizeFirstWord ([e9ee69f](https://github.com/basal-john/essential-common-utils/commit/e9ee69fed3b882a518ee9116ed2212147a212879))
* Add capitalizeFirstWord and getPascalCaseText functions ([8c30e9e](https://github.com/basal-john/essential-common-utils/commit/8c30e9e697cad2e36eb82c64231da0d294d2d16b))
* add function normalizePriceString to normalize price string ([90c4d28](https://github.com/basal-john/essential-common-utils/commit/90c4d28c4973294926a82de5b1c8854ce5cd96e7))
* add function normalizePriceString to normalize price string ([771d818](https://github.com/basal-john/essential-common-utils/commit/771d818a814af4b603824e40dc29f201bddff585))
* add getMultipleUniqueIndexes function ([98ea50c](https://github.com/basal-john/essential-common-utils/commit/98ea50c8a6ed96781b2618382e2187c9d40cb4d4))
* add getMultipleUniqueIndexes function ([066de22](https://github.com/basal-john/essential-common-utils/commit/066de22c54aa1a3a044ff13d8201b22675f79edc))
* add getPascalCaseText ([18d9c57](https://github.com/basal-john/essential-common-utils/commit/18d9c570ec4655a4cb33aac95ca2243d9e4587ad))
* add getRandomString function and update README with usage example ([40200b5](https://github.com/basal-john/essential-common-utils/commit/40200b555d9d892da99ae04b526410cf864ff727))
* add money utility functions for price normalization and formatting ([0562ceb](https://github.com/basal-john/essential-common-utils/commit/0562cebdc9e11ed5951966a5f360c833d676030f))
* add parsePricesWithLocaleFormatting function to handle various price formats ([88b61c9](https://github.com/basal-john/essential-common-utils/commit/88b61c9db7ad82d21eca1575f96a6abc8181fe09))
* add textHelper utility functions for HTML entity decoding and text normalization ([22c725d](https://github.com/basal-john/essential-common-utils/commit/22c725dfec5cb5994ea86d3689d17958b697a529))
* Add trimToTwoDecimalPlaces and capitalizeFirstWord functions ([1a64766](https://github.com/basal-john/essential-common-utils/commit/1a64766c28431adc121e6c1dc6fcfe09a235bbe0))
* enhance getRandomString function to handle empty array case ([02547d2](https://github.com/basal-john/essential-common-utils/commit/02547d2c4cc9e385aa0d820029fdbe79c33d4d91))
* function to format us price ([5222f99](https://github.com/basal-john/essential-common-utils/commit/5222f99e4b8e5c2a22c0c1df67c1a72be12c3500))
* function to format us price ([fa5585b](https://github.com/basal-john/essential-common-utils/commit/fa5585b4950b61667317ec8ca61c1d42b9a48944))
* modify function ([9c75c5e](https://github.com/basal-john/essential-common-utils/commit/9c75c5e152e837ab98fa5761adb3995d6fe7ded9))
* Refactor getCamelCaseText function for improved readability and performance ([fb64e88](https://github.com/basal-john/essential-common-utils/commit/fb64e88a6956ac010c593b5841a2b766fb3c8edf))
* **utils:** add capitalizeFirstWord ([71a6d2e](https://github.com/basal-john/essential-common-utils/commit/71a6d2e97643ccfdd27cdad0a22855817a976acd))
* **utils:** add getPascalCaseText and getCamelCaseText ([5d86882](https://github.com/basal-john/essential-common-utils/commit/5d86882259e5eb77fdd27067a2984a5964347630))
* **utils:** unroll changes ([ba79d57](https://github.com/basal-john/essential-common-utils/commit/ba79d57f5d6a5e8856f270fc5cfe30ed78af2729))
* **utils:** update function getCamelCaseText ([e800bb6](https://github.com/basal-john/essential-common-utils/commit/e800bb67e1f30f9f0d38dbf04e710a608f25a93f))


### Bug Fixes

* **getCamelCase:** Update method to accept other special characters ([a1b68fd](https://github.com/basal-john/essential-common-utils/commit/a1b68fd5f339c45c747848cf7f9362dbfd70f259))
* **getCamelCase:** Update method to accept other special characters ([1532749](https://github.com/basal-john/essential-common-utils/commit/153274988b8d898db029677eb9e1c71f0c84aa41))

### [1.14.1](https://github.com/basal-john/essential-common-utils/compare/v1.14.0...v1.14.1) (2026-07-10)

## [1.14.0](https://github.com/basal-john/essential-common-utils/compare/v1.13.1...v1.14.0) (2026-02-25)


### Features

* add money utility functions for price normalization and formatting ([0562ceb](https://github.com/basal-john/essential-common-utils/commit/0562cebdc9e11ed5951966a5f360c833d676030f))

### [1.13.1](https://github.com/basal-john/essential-common-utils/compare/v1.12.3...v1.13.1) (2026-02-24)

### [1.12.3](https://github.com/basal-john/essential-common-utils/compare/v1.12.2...v1.12.3) (2026-02-12)

### [1.12.2](https://github.com/basal-john/essential-common-utils/compare/v1.12.1...v1.12.2) (2026-02-12)

### [1.12.1](https://github.com/basal-john/essential-common-utils/compare/v1.11.0...v1.12.1) (2026-02-12)

## [1.12.0](https://github.com/basal-john/essential-common-utils/compare/v1.11.0...v1.12.0) (2026-02-12)

### Features

- improve package metadata with explicit `exports`, `sideEffects`, and safer publish checks
- modernize CI matrix and workflows (Node 20/22, GitHub Actions v4, separate format check)
- refresh dependencies and lockfile to current compatible versions

### Bug Fixes

- make `extractUrlsFromText` return an empty array when no links are found
- fix `normalizePriceString` for US thousands+decimal formats (for example `2,500.00`)
- support Unicode letters in `getPascalCaseText`
- collapse repeated spaces consistently in `trimAndRemoveDoubleSpaces`
- remove noisy console side effects from `textHelper.compareTexts`

## [1.11.0](https://github.com/basal-john/essential-common-utils/compare/v1.10.0...v1.11.0) (2025-11-24)

### Features

- add function normalizePriceString to normalize price string ([771d818](https://github.com/basal-john/essential-common-utils/commit/771d818a814af4b603824e40dc29f201bddff585))

## [1.10.0](https://github.com/basal-john/essential-common-utils/compare/v1.9.3...v1.10.0) (2025-09-05)

### Features

- function to format us price ([fa5585b](https://github.com/basal-john/essential-common-utils/commit/fa5585b4950b61667317ec8ca61c1d42b9a48944))

### [1.9.3](https://github.com/basal-john/essential-common-utils/compare/v1.9.2...v1.9.3) (2025-07-01)

### [1.9.2](https://github.com/basal-john/essential-common-utils/compare/v1.9.0...v1.9.2) (2025-04-08)

### Bug Fixes

- **getCamelCase:** Update method to accept other special characters ([1532749](https://github.com/basal-john/essential-common-utils/commit/153274988b8d898db029677eb9e1c71f0c84aa41))

### [1.9.1](https://github.com/basal-john/essential-common-utils/compare/v1.9.0...v1.9.1) (2025-04-02)

## [1.9.0](https://github.com/basal-john/essential-common-utils/compare/v1.8.4...v1.9.0) (2025-03-27)

### Features

- add textHelper utility functions for HTML entity decoding and text normalization ([22c725d](https://github.com/basal-john/essential-common-utils/commit/22c725dfec5cb5994ea86d3689d17958b697a529))

### [1.8.4](https://github.com/basal-john/essential-common-utils/compare/v1.8.3...v1.8.4) (2025-03-18)

### [1.8.3](https://github.com/basal-john/essential-common-utils/compare/v1.8.2...v1.8.3) (2025-03-13)

### [1.8.2](https://github.com/basal-john/essential-common-utils/compare/v1.8.1...v1.8.2) (2025-03-13)

### [1.8.1](https://github.com/basal-john/essential-common-utils/compare/v1.8.0...v1.8.1) (2025-03-13)

## [1.8.0](https://github.com/basal-john/essential-common-utils/compare/v1.7.0...v1.8.0) (2025-03-13)

### Features

- add parsePricesWithLocaleFormatting function to handle various price formats ([88b61c9](https://github.com/basal-john/essential-common-utils/commit/88b61c9db7ad82d21eca1575f96a6abc8181fe09))

## [1.7.0](https://github.com/basal-john/essential-common-utils/compare/v1.6.0...v1.7.0) (2025-02-17)

### Features

- enhance getRandomString function to handle empty array case ([02547d2](https://github.com/basal-john/essential-common-utils/commit/02547d2c4cc9e385aa0d820029fdbe79c33d4d91))

## [1.6.0](https://github.com/basal-john/essential-common-utils/compare/v1.5.0...v1.6.0) (2025-01-03)

### Features

- add getRandomString function and update README with usage example ([40200b5](https://github.com/basal-john/essential-common-utils/commit/40200b555d9d892da99ae04b526410cf864ff727))

## [1.5.0](https://github.com/basal-john/essential-common-utils/compare/v1.4.4...v1.5.0) (2025-01-03)

### Features

- add getMultipleUniqueIndexes function ([066de22](https://github.com/basal-john/essential-common-utils/commit/066de22c54aa1a3a044ff13d8201b22675f79edc))

### [1.4.4](https://github.com/basal-john/essential-common-utils/compare/v1.4.3...v1.4.4) (2024-12-05)

### [1.4.3](https://github.com/basal-john/essential-common-utils/compare/v1.4.2...v1.4.3) (2024-12-05)

### [1.4.2](https://github.com/basal-john/essential-common-utils/compare/v1.4.1...v1.4.2) (2024-11-11)

### [1.4.1](https://github.com/basal-john/essential-common-utils/compare/v1.4.0...v1.4.1) (2024-10-09)

## [1.4.0](https://github.com/basal-john/essential-common-utils/compare/v1.3.1...v1.4.0) (2024-10-04)

### Features

- Add capitalizeFirstWord and getPascalCaseText functions ([8c30e9e](https://github.com/basal-john/essential-common-utils/commit/8c30e9e697cad2e36eb82c64231da0d294d2d16b))

### [1.3.1](https://github.com/basal-john/essential-common-utils/compare/v1.3.0...v1.3.1) (2024-09-24)

## [1.3.0](https://github.com/basal-john/essential-common-utils/compare/v1.0.4...v1.3.0) (2024-09-18)

### Features

- add capitalizeFirstWord ([e9ee69f](https://github.com/basal-john/essential-common-utils/commit/e9ee69fed3b882a518ee9116ed2212147a212879))
- add getPascalCaseText ([18d9c57](https://github.com/basal-john/essential-common-utils/commit/18d9c570ec4655a4cb33aac95ca2243d9e4587ad))
- Add trimToTwoDecimalPlaces and capitalizeFirstWord functions ([1a64766](https://github.com/basal-john/essential-common-utils/commit/1a64766c28431adc121e6c1dc6fcfe09a235bbe0))
- modify function ([9c75c5e](https://github.com/basal-john/essential-common-utils/commit/9c75c5e152e837ab98fa5761adb3995d6fe7ded9))
- Refactor getCamelCaseText function for improved readability and performance ([fb64e88](https://github.com/basal-john/essential-common-utils/commit/fb64e88a6956ac010c593b5841a2b766fb3c8edf))
