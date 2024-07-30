# @pulsanova/icons

> An icon set, ready to be used in SCSS (entirely based on Phosphor icons)  
> _(See `./package.json` for the exact version of Phosphor on which this project is based)_

## Installation

```bash
# - NPM
npm install @pulsanova/icons

# - Yarn
yarn add @pulsanova/icons
```

## Usage

```scss
@use '@pulsanova/icons' with (
    $duotone-primary-color: #eb4034,
);

.my-rule {
    @include icons.icon('plus', 'fill') {
        font-size: 1.75rem;
    }
}
```
