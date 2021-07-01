# Codepoint's tsx/jsx Prettier config

[![npm Release Version](https://img.shields.io/github/v/release/codepointtku/jsx-prettier?logo=npm&style=for-the-badge&labelColor=333333)](https://www.npmjs.com/package/@codepointtku/jsx-prettier)
[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/codepointtku/jsx-prettier/npm%20Publish?logo=githubactions&logoColor=cyan&style=for-the-badge&labelColor=333333)](https://github.com/codepointtku/jsx-prettier/actions/workflows/npm-publish.yml)

*Codepoint's Prettier config file for formatting jsx code.*

* **What is this for?:** This Prettier config is meant to be used for Codepoint's web development projects.
* **Can anyone use it?:** Yes, you can use this config however you like, but keep in mind that these settings might change over time.

[Contact for questions, information and to contribute](mailto:juuso.laakso@turku.fi)

## Installation
**Run** this command in your repository
```bash
$ npm install @codepointtku/jsx-prettier --save-dev
```

## Usage
**Add** it to your `.prettierrc.js` *which will allow you to override settings in case you need to*
```js
module.exports = {
  ...require("@codepointtku/jsx-prettier"),
}
```
**Or** to your `package.json`
```jsonc
{
  "prettier": "@codepointtku/jsx-prettier"
}
```
**Or...** add it to your `.prettierrc`/`.prettierrc.json`
```jsonc
{
  "@codepointtku/jsx-prettier"
}
```
