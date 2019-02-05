# TSLint Config Euclid

[![NPM version](https://img.shields.io/npm/v/tslint-config-euclid.svg?style=flat)](https://www.npmjs.com/package/tslint-config-euclid)
[![Downloads](http://img.shields.io/npm/dm/tslint-config-euclid.svg?style=flat)](https://npmjs.org/package/tslint-config-euclid)

This is a basic TSLint package which contains my personal TSLint preferences.
It may also be useful to anyone else who happens to have similar preferences.

Specifically, it uses the [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)
as much as possible, with some extra settings, such as `no-magic-numbers`, etc.

## Installation

```sh
npm install tslint-config-euclid --save-dev
```

## Usage

In `tslint.json`:

```json
{
  "extends": "tslint-config-euclid"
}
```

## License

MIT