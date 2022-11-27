# @reifiedbeans/semantic-release-config

[![npm version](https://img.shields.io/npm/v/@reifiedbeans/semantic-release-config/latest)](https://www.npmjs.com/package/@reifiedbeans/semantic-release-config)
![semantic-release version](https://img.shields.io/npm/dependency-version/@reifiedbeans/semantic-release-config/peer/semantic-release)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![semantic-release: conventional commits](https://img.shields.io/badge/semantic_release-conventional_commits-e10079?logo=semantic-release)](https://github.com/semantic-release/semantic-release)
[![license: MIT](https://img.shields.io/npm/l/@reifiedbeans/semantic-release-config)](LICENSE)

A (somewhat) sensible [semantic-release] config. The main purpose of this configuration is twofold: use `main` as the tracking branch and use the [Conventional Commits] standard instead of the Angular standard. All other defaults are left untouched.

## Usage

First, install this package as a dev dependency.

```shell
npm install --save-dev @reifiedbeans/semantic-release-config
```

Then, add the following to your `package.json`.

```json
{
  "release": {
    "extends": "@reifiedbeans/semantic-release-config"
  }
}
```

## License

Licensed under the [MIT License](LICENSE).

[semantic-release]: https://github.com/semantic-release/semantic-release
[conventional commits]: https://www.conventionalcommits.org/en/v1.0.0/
