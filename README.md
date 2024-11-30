# Snizzle [![npm version](https://img.shields.io/npm/v/snizzle?style=flat-square)](https://www.npmjs.com/package/snizzle)

> A pure-JavaScript fast, CSS selector engine program to be easily select DOM-Elements.

<img src="https://raw.githubusercontent.com/jqrony/content/main/snizzle/thumbnail.png" style="width:100%;">

![license](https://img.shields.io/github/license/jqrony/snizzle?style=flat-square)
[![install size](https://packagephobia.com/badge?p=snizzle)](https://packagephobia.com/result?p=snizzle)
![author](https://img.shields.io/badge/Author-Shahzada%20Modassir-%2344cc11?style=flat-square)
[![jsDelivr Hits](https://img.shields.io/jsdelivr/npm/hy/snizzle?style=flat-square)](https://www.jsdelivr.com/package/npm/snizzle)
[![downloads month](https://img.shields.io/npm/dt/snizzle?style=flat-square)](https://www.npmjs.com/package/snizzle)
[![Github starts](https://img.shields.io/github/stars/jqrony/snizzle?style=flat-square)](https://github.com/jqrony/snizzle)
[![Socket Badge](https://socket.dev/api/badge/npm/package/snizzle)](https://socket.dev/npm/package/snizzle)

- [More information](https://github.com/jqrony/snizzle/wiki)
- [Documentation](https://github.com/jqrony/snizzle/wiki)
- [Browser support](https://github.com/jqrony/snizzle/wiki#browsers)
- [Snizzle releases](https://github.com/jqrony/snizzle/releases)
- [Latest release](https://github.com/jqrony/snizzle/releases/latest)
- [Deployed source](https://jqrony.github.io/snizzle/dist/snizzle-min.js)

## New Features
Snizzle `v1.6.0` in new features included for related advance DOM-Element Selecting Snizzle library in added new features `XPath selenium` now user can be select DOM elements XPath through.

## Contribution Guides
In order to build Snizzle, you should have Node.js/npm latest and git 1.6.0 or later (earlier versions might work OK, but are not tested).

For Windows you have to download and install git and [Node.js](https://nodejs.org/download/).

Mac OS users should install Homebrew. Once Homebrew is installed, run `brew install git` to install git, and `brew install` node to install Node.js.

Linux/BSD users should use their appropriate package managers to install git and Node.js, or build from source if you swing that way. Easy-peasy.

## Downloading Snizzle using npm or Yarn
Snizzle is registered as a <a href="https://www.npmjs.com/package/snizzle">package</a> on <a href="https://www.npmjs.com/">npm</a>. You can install the latest version of Snizzle with the npm CLI command:

```bash
# install locally (recomended)
yarn add snizzle

# install locally (recomended)
npm install snizzle --save
```
As an alternative you can use the Yarn CLI command:

### Snizzle information
For information on how to get started and how to use Snizzle, please see [Snizzle's](https://github.com/jqrony/snizzle) [documentation](https://github.com/jqrony/snizzle/wiki). For source files and issues, please visit the Snizzle repository.

If upgrading, please see the blog post for [release 1.6.0](https://github.com/jqrony/snizzle/releases/tag/1.6.0). This includes notable differences from the previous version and a more readable changelog.

## Including Snizzle
Below are some of the most common ways to include Snizzle

### Browser
#### Script tag
```html
<!--including Snizzle (recomended) HTML document in head section -->
<script src="https://cdn.jsdelivr.net/npm/snizzle@1.8.0/dist/snizzle.min.js"></script>
```

## Usage
#### Webpack / Browserify / Babel
There are several ways to use [Webpack](https://webpack.js.org/), [Browserify](https://browserify.org/) or [Babel](https://babeljs.io/). For more information on using these tools, please refer to the corresponding project's documentation. In the script, including Snizzle will usually look like this:
```js
import Snizzle from "snizzle";
```

If you need to use Snizzle in a file that's not an ECMAScript module, you can use the CommonJS syntax:
```js
const Snizzle = require("snizzle");
```

#### AMD (Asynchronous Module Definition)
AMD is a module format built for the browser. For more information, we recommend
```js
define(["snizzle"], function(snizzle) {

});
```

## Syntax code example
There are simple some usage Snizzle code example syntax and learn more click [Documentation](https://github.com/jqrony/snizzle/wiki).

Code example: `Snizzle("body > div:nth-child(2) + main:eq(2) > :input:disabled)`


## How to build Snizzle
Clone a copy of the main Snizzle git repo by running:
```bash
git clone git://github.com/jqrony/snizzle.git
```
In the `snizzle/dist` folder you will find build version of snizzle along with the minified copy and associated map file.

## Contributing Guide
See [CONTRIBUTING.md](https://github.com/jqrony/snizzle/blob/main/CONTRIBUTING.md)
