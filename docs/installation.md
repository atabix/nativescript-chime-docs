---
layout: default
title: Installation
nav_order: 1
description: "Just the Docs is a responsive Jekyll theme with built-in search that is easily customizable and hosted on GitHub Pages."
---

## Installation

<div class="note">
<b class="label">Note</b> This package is only avaialble <abbr title="Node Package Manager">NPM</abbr>. So make sure it's installed. Here is a quick <a href="https://docs.npmjs.com/downloading-and-installing-node-js-and-npm">installation guide</a> on how to install npm.
</div>

To install this package you simply need go to your project directory and run the following command in the terminal.

`npm install "@atabix/nativescript-amazon-chime`

if using [typescript](https://www.typescriptlang.org/ "typescript") you can also install types by adding the following to `references.d.ts`:

```js
/// <reference path="../node_modules/@atabix/nativescript-amazon-chime/platforms/ios/objc!AmazonChimeSDK.d.ts" />
/// <reference path="../node_modules/@atabix/nativescript-amazon-chime/platforms/android/android-amazon-chime-sdk.d.ts" />
```

That's it! You are ready to [get started](/).

---

## About the project

NativeScript Chime is &copy; 2020-{{ "now" | date: "%Y" }} by [Atabix Solutions](https://atabix.nl).

### License

NativeScript Chime is distributed by an [MIT license](https://github.com/atabix/nativescript-chime/tree/master/LICENSE).

### Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change. Read more about becoming a contributor in [our GitHub repo](https://github.com/atabix/nativescript-chime#contributing).

### Code of Conduct

Just the Docs is committed to fostering a welcoming community.

[View our Code of Conduct](https://github.com/atabix/nativescript-chime/tree/master/CODE_OF_CONDUCT.md) on our GitHub repository.
