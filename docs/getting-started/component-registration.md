---
layout: default
title: Registering a component
parent: Getting Started
nav_order: 1
---

## Registering the component

Locate your entry file where your Vue instance is defined. (usually call index.js or main.js)

```js
new Vue()
```

and at the top of that file add

```js
import { VueAmazonChimePlugin } from '@atabix/nativescript-amazon-chime';
```

somewhere bellow the import and above the creation of the Vue instance, add the following to register the plugin.

```js
Vue.use(VueAmazonChimePlugin);
```

You can now use the component registed under the name `AmazonChimeVideo`

Nativescript example
```html
<AmazonChimeVideo
  ref="chimeVideoConference"
  @loaded="onLoaded"
  class="myClass"
/>
```