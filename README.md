# Bulma.styl

[![npm](https://img.shields.io/npm/v/bulma.styl.svg)](https://www.npmjs.com/package/bulma.styl)
[![npm](https://img.shields.io/npm/dm/bulma.styl.svg)](https://www.npmjs.com/package/bulma.styl)

This is a 1:1 Stylus translation of the [Bulma](http://bulma.io) CSS framework.

Bulma.styl aims at 1:1 functional parity with the latest dev-master branch of [the original Sass-based Bulma](https://github.com/jgthms/bulma).

## Installation

If you simply need a compiled version of Bulma, please refer to the official [Bulma repository](https://github.com/jgthms/bulma/blob/master/css/bulma.css).

However, if you want the Stylus files in order to customize variables and include only certain components, please install Bulma.styl using npm or Yarn:

### Install from npm

```sh
npm install bulma.styl
```

### Install from Yarn 

```sh
yarn add bulma.styl 
```

## Documentation

Since Bulma.styl is functionally identical to the original Bulma, you can refer to the original [Bulma documentation](http://bulma.io/documentation/overview/start/) for instructions, examples, syntax and browser support.

All variable and mixin names are the same. The only caveat is that if you wish to customize the `$colors` variable, you must adhere to the Stylus hash format. Refer to the default value in [`/stylus/utilities/variables.styl:148`](https://github.com/Log1x/bulma.styl/blob/master/stylus/utilities/variables.styl#L148) for an example.

## Bugs & support

Any bugs or support requests can be posted into [the GitHub issue tracker](https://github.com/Log1x/bulma.styl/issues).

**Please note:** Bulma.styl is simply a translation of Bulma from Sass to Stylus, with no corrections or deviations made. Therefore, before submitting a bug, please make sure the issue is actually related specifically to the translation, and the Sass edition of Bulma does not exhibit the same bug. If it does, please submit your issue to [Bulma's issue tracker](https://github.com/jgthms/bulma/issues) instead.

Similarly, any pull requests should only relate directly to the translation (translate a newer version into Stylus, fix syntax errors). Any pull requests for new features or behavior fixes should go [directly to Bulma](https://github.com/jgthms/bulma/pulls).

## License

Released under the MIT license.
