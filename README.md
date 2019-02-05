# TSLint Config Alexandria

[![NPM version](https://img.shields.io/npm/v/tslint-config-alexandria.svg?style=flat)](https://www.npmjs.com/package/tslint-config-alexandria)
[![Downloads](http://img.shields.io/npm/dm/tslint-config-alexandria.svg?style=flat)](https://npmjs.org/package/tslint-config-alexandria)

This is a basic TSLint package which contains my personal TSLint preferences.
It may also be useful to anyone else who happens to have similar preferences.

Specifically, it uses the [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)
as much as possible, with some extra settings, such as `no-magic-numbers`, etc.

## Installation

```sh
npm install tslint-config-alexandria --save-dev
```

## Usage

In `tslint.json`:

```json
{
  "extends": "tslint-config-alexandria"
}
```

## License

MIT