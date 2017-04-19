# @mcmath/tslint-config

TSLint configuration for TypeScript projects

## Install

Install as an [npm][npm] development dependency. [TypeScript][typescript] and
[TSLint][tslint] should also be installed.

```sh
npm install --save-dev typescript tslint @mcmath/tslint-config
```

## Usage

Create a `tslint.json` file in the root of your project:

```json
{ "extends": "@mcmath/tslint-config" }
```

New rules may be added or existing ones modified like so:

```json
{
  "extends": "@mcmath/tslint-config",
  "rules": {
    "no-reference": false,
    "quotemark": [true, "single"]
  }
}
```

[npm]: https://www.npmjs.com/package/@mcmath/tslint-config
[typescript]: https://www.typescriptlang.org/
[tslint]: https://palantir.github.io/tslint/
