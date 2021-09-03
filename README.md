# eslint-config-typescript

[shareable](https://eslint.org/docs/developer-guide/shareable-configs#shareable-configs)
[ESLint](https://eslint.org) config for
[TypeScript](https://www.typescriptlang.org/) projects

<!--status-badges start -->

[![Node CI Workflow Status][github-actions-ci-badge]][github-actions-ci-link]

<!--status-badges end -->

## Table of Contents

* [Usage](#usage)
  * [Installation](#installation)
  * [Add to the project config](#add-to-the-project-config)
* [Contributing](#contributing)
  * [Dependencies](#dependencies)
  * [Verification](#verification)

## Usage

<!--consumer-badges start -->

[![MIT license][license-badge]][license-link]
[![npm][npm-badge]][npm-link]

<!--consumer-badges end -->

### Installation

```sh
$ npm install @form8ion/eslint-config-typescript --save-dev
```

### Add to the project config

Such as in an `.eslintrc.js`

```js
module.exports = {
  extends: ['@form8ion', '@form8ion/typescript']
};
```

## Contributing

<!--contribution-badges start -->

[![PRs Welcome][PRs-badge]][PRs-link]
[![Commitizen friendly][commitizen-badge]][commitizen-link]
[![Conventional Commits][commit-convention-badge]][commit-convention-link]
[![semantic-release][semantic-release-badge]][semantic-release-link]
[![Renovate][renovate-badge]][renovate-link]

<!--contribution-badges end -->

### Dependencies

```sh
$ nvm install
$ npm install
```

### Verification

```sh
$ npm test
```

[PRs-link]: http://makeapullrequest.com

[PRs-badge]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg

[commitizen-link]: http://commitizen.github.io/cz-cli/

[commitizen-badge]: https://img.shields.io/badge/commitizen-friendly-brightgreen.svg

[commit-convention-link]: https://conventionalcommits.org

[commit-convention-badge]: https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg

[semantic-release-link]: https://github.com/semantic-release/semantic-release

[semantic-release-badge]: https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg

[renovate-link]: https://renovatebot.com

[renovate-badge]: https://img.shields.io/badge/renovate-enabled-brightgreen.svg?logo=renovatebot

[github-actions-ci-link]: https://github.com/form8ion/eslint-config-typescript/actions?query=workflow%3A%22Node.js+CI%22+branch%3Amaster

[github-actions-ci-badge]: https://github.com/form8ion/eslint-config-typescript/workflows/Node.js%20CI/badge.svg

[license-link]: LICENSE

[license-badge]: https://img.shields.io/github/license/form8ion/eslint-config-typescript.svg

[npm-link]: https://www.npmjs.com/package/@form8ion/eslint-config-typescript

[npm-badge]: https://img.shields.io/npm/v/@form8ion/eslint-config-typescript.svg
