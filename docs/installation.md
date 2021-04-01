---
layout: default
title: Installation
nav_order: 1
description: "Just the Docs is a responsive Jekyll theme with built-in search that is easily customizable and hosted on GitHub Pages."
---

## Installation

<div class="note">
<b class="label">Note</b>This package is only avaialble <abbr title="Node Package Manager">NPM</abbr>. So make sure it's installed. Here is a quick <a href="https://docs.npmjs.com/downloading-and-installing-node-js-and-npm" target="_blank">installation guide</a> on how to install npm.
</div>

To install this package you simply need go to your project directory and run the following command in the terminal.

`npm install "@atabix/nativescript-amazon-chime`

if using [typescript](https://www.typescriptlang.org/ "typescript") you can also install types by adding the following to `references.d.ts`:

```js
/// <reference path="../node_modules/@atabix/nativescript-amazon-chime/platforms/ios/objc!AmazonChimeSDK.d.ts" />
/// <reference path="../node_modules/@atabix/nativescript-amazon-chime/platforms/android/android-amazon-chime-sdk.d.ts" />
```

That's it! You are ready to [register a component](/docs/getting-started/component-registration/).


