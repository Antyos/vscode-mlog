# Changelog

## [0.0.2] - (2020-12-25)

### Added

- Global constants: `@maph` and `@mapw`
- No operation: `noop`

### Fixed

- Highlighting global constants for blocks now (correctly) use dash-case instead of camelCase. I.e. `@copper-wall-large` instead of `@copperWallLarge`
- Fixed distinction between logical **AND** operator and bitwise **AND**. Logical **AND** (`land`) is now highlighted
    |                 | In game|  mlog |
    |-----------------|--------|-------|
    | Logical **AND** |   `and`| `land`|
    | Bitwise **AND** | `b-and`|  `and`|

## [0.0.1] - (2020-12-23)

### Initial release

- Syntax highlighting for Mindustry Logic (`mlog`) files
