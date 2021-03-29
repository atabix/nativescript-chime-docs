---
layout: default
title: Getting Started
has_children: false
nav_order: 2
permalink: /

---
# Introduction

## What is NativeScript Chime?

Amazon Chime allows you to easily build video calling, audio calling, and screen sharing applications with Amazon Chime in NativeScript.
It is currenty design to work in conjunction with [Vue.js](https://vuejs.org "Vue.js"), a progressive framework for building user interfaces or [Nativescript Vue](https://nativescript-vue.org/ "Nativescript Vue"), an open source framework for building truly native mobile applications using JavaScript.


<!-- [Get started now](#getting-started){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [View it on GitHub](https://github.com/atabix/nativescript-chime){: .btn .fs-5 .mb-4 .mb-md-0 } -->

---
## Getting Started
<br>
[Installation](docs/installation){: .btn .btn-green }



### First Steps
Locate your entry file where your Vue instance is defined. (usually call index.js or main.js)

```js
new Vue()
```

and at the top of that file add

```js
import { VueAmazonChimePlugin } from '@atabix/nativescript-amazon-chime';
```

now you can access to all the available methods and vue component.

--

