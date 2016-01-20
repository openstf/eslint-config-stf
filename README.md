# STF - ESLint Shareable Config

#### An ESLint [Shareable Config](http://eslint.org/docs/developer-guide/shareable-configs) for STF

## WIP

This module is for advanced users. 

[![js-standard-style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)

## Install

```bash
npm install eslint-config-stf
```

## Usage

Shareable configs are designed to work with the `extends` feature of `.eslintrc` files.
You can learn more about
[Shareable Configs](http://eslint.org/docs/developer-guide/shareable-configs) on the
official ESLint website.

To use the JavaScript Standard Style shareable config, first run this:

```bash
npm install eslint-config-stf eslint-plugin-stf
```

Then, add this to your .eslintrc file:

```
{
  "extends": "stf"
}
```

*Note: We omitted the `eslint-config-` prefix since it is automatically assumed by ESLint.*

You can override settings from the shareable config by adding them directly into your
`.eslintrc` file.
