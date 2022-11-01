# Renovate Config

[![version][npm-image]][npm-url] [![Build Status][circle-image]][circle-url]

> vernaillen preset configs for [Renovate][].
> forked from [@telus](https://github.com/telus/renovate-config)

Renovate helps us to keep our dependencies up to date. It will periodically create Pull Requests every week to install new versions of any dependencies with updates. Renovate is fully configurable and developers can control its behaviour in their repositories using the PRs it makes. Close a PR to have it ignore updates for that dependency, or leave it open if you want upgrade it later and Renovate will rebase the branch to keep it from getting stale.

## Usage

Create a `.renovate.json` file in your repository, with the following content:

###### `.renovate.json`

```json
{
  "extends": [
    "@vernaillen"
  ]
}
```

You can find the configuration in [`package.json`](./package.json).

Review [Full configuration docs](https://renovatebot.com/docs/configuration-options/)

---

> Github: [@telus](https://github.com/telus) &bull;
> Twitter: [@telusdigital](https://twitter.com/telusdigital)

[circle-url]: https://circleci.com/gh/vernaillen/renovate-config
[circle-image]: https://img.shields.io/circleci/project/github/vernaillen/renovate-config/master.svg?style=for-the-badge&logo=circleci

[npm-url]: https://www.npmjs.com/package/@vernaillen/renovate-config
[npm-image]: https://img.shields.io/npm/v/@vernaillen/renovate-config.svg?style=for-the-badge&logo=npm
