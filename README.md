# React WinJS

![Teclib' Banner](https://user-images.githubusercontent.com/29282308/31669540-abed67a8-b355-11e7-98e2-0ad190f37088.png)

[![License MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE.md)
[![Follow twitter](https://img.shields.io/badge/Twitter-Teclib%27-940CA5.svg)](https://twitter.com/teclib)
[![Greenkeeper badge](https://badges.greenkeeper.io/flyve-mdm/react-winjs.svg)](https://greenkeeper.io/)
[![Project Status: Active](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg)](https://conventionalcommits.org)

Teclib’ is an open source software editor that offers a vast range of fully integrated open source technology packages, to better respond to business needs.

Visit our Website [Teclib'](http://www.teclib-edition.com/en/).

## Table of Contents

* [Synopsis](#synopsis)
* [Build Status](#build-status)
* [Installation](#installation)
* [Code examples](#code-examples)
* [Documentation](#documentation)
* [Versioning](#versioning)
* [Contact](#contact)
* [Contribute](#contribute)
* [Copying](#copying)

## Synopsis

A React wrapper around WinJS's controls. Implemented using the technique described on [this WinJS wiki page](https://github.com/winjs/winjs/wiki/Using-WinJS-with-React).

## Build Status

|**Release channel**|Beta Channel|
|:---:|:---:|
|[![Travis CI build](https://api.travis-ci.org/TECLIB/react-winjs.svg?branch=master)](https://travis-ci.org/TECLIB/react-winjs)|[![Travis CI build](https://api.travis-ci.org/TECLIB/react-winjs.svg?branch=develop)](https://travis-ci.org/TECLIB/react-winjs)|

## Installation

```shell
npm install react-winjs --save
```

## Code examples

Include [WinJS 4.4](http://try.buildwinjs.com/#get) on your page. For example:

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/winjs/4.4.0/css/ui-dark.css" />
<script src="https://cdnjs.cloudflare.com/ajax/libs/winjs/4.4.0/js/base.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/winjs/4.4.0/js/ui.js"></script>
```

Then require `react-winjs` and use it:

```jsx
var React = require('react');
var ReactDOM = require('react-dom');
var ReactWinJS = require('react-winjs');

var App = React.createClass({
  render: function () {
    return <ReactWinJS.Rating maxRating={3} />;
  }
});

ReactDOM.render(<App />, document.getElementById("app"));
```

## Documentation

We maintain a detailed documentation of the project on the Website, check the [Development](https://teclib.github.io/react-winjs/) and [How-tos](https://teclib.github.io/react-winjs/howtos) sections.

You can also check the [live examples](https://teclib.github.io/react-winjs/examples/).

## Versioning

In order to provide transparency on our release cycle and to maintain backward compatibility, Teclib' is maintained under [the Semantic Versioning guidelines](http://semver.org/). We are committed to following and complying with the rules, the best we can.

See [the tags section of our GitHub project](https://github.com/TECLIB/react-winjs/tags) for changelogs for each release version. Release announcement posts on [the official Teclib' blog](http://www.teclib-edition.com/en/communities/blog-posts/) contain summaries of the most noteworthy changes made in each release.

## Contact

You can contact us through any of our channels, check our [Contact section](http://www.teclib-edition.com/en/contact-us/).

## Contribute

Want to file a bug, contribute some code, or improve documentation? Excellent! Read up on our
guidelines for [contributing](./CONTRIBUTING.md) and then check out one of our issues in the [Issues Dashboard](https://github.com/TECLIB/react-winjs/issues).

## Copying

* **Code**: you can redistribute it and/or modify
    it under the terms of the License MIT ([MIT](https://opensource.org/licenses/MIT)).
* **Documentation**: released under Attribution 4.0 International ([CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)).