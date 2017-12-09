# Awesome Mithril [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://mithril.js.org/logo.svg" align="right" width="100">](https://mithril.js.org)

> A curated list of Mithril awesome

Mithril is a modern client-side Javascript framework for building Single Page Applications.

## Contents

- [Official Resources](#official-resources)
- [Community](#community)
- [Learn](#learn)
  * [Tutorials](#tutorials)
  * [Screencasts](#screencasts)
- [Examples](#examples)
  * [Apps](#apps)
  * [Snippets](#snippets)
  * [Starter kits](#starter-kits)
- [Testing](#testing)
- [Libraries & Plugins](#libraries--plugins)
- [Tools](#tools)
- [pre 1.0 Release](#pre-10-release)
- [License](#license)

### Official Resources

- [Website](https://mithril.js.org/)
- [Simple Application Tutorial](https://mithril.js.org/simple-application.html)
- [API Reference](https://mithril.js.org/api.html)
- [GitHub Repo](https://github.com/MithrilJS/mithril.js)
- [Framework Comparison](https://mithril.js.org/framework-comparison.html)
- [Change Log](https://mithril.js.org/change-log.html)
- [Contribution Guide](https://mithril.js.org/contributing.html)
- [Job listing](https://github.com/MithrilJS/mithril.js/wiki/JOBS)
- [Who uses Mithril?](https://github.com/MithrilJS/mithril.js/wiki/Who-Uses-Mithril)


### Community

- [Gitter Chat Room](https://gitter.im/mithriljs/mithril.js)
- Use `#mithriljs` on Twitter and other social media.

### Learn

#### Tutorials

- [Isomorphic web application with Mithril](https://isomorphic-mithril.mvlabs.it/en/) - How to write isomorphic web applications, ie. serverside rendering and clientside code with one codebase.
- [Example Mithril Components](https://mithril-examples.firebaseapp.com/) - Concise examples with both ES5 and ES6 versions.

### Examples

#### Apps

- [Isomorphic web application with Mithril](https://github.com/mvlabs/isomorphic-mithril) - Serverside rendering example using [mithril-node-render](https://github.com/MithrilJS/mithril-node-render).
- [Mithril tutorial app](https://github.com/spacejack/mithril-tutorial-ts) - The tutorial app from mithril.js.org adapted to Typescript.
- [Freddy](https://github.com/spacejack/freddy) - Mobile Reddit Reader.
- [Flems](https://github.com/porsager/flems) - Web playground & sandbox as an embeddable module.
- [mithril-slides](https://github.com/wulab/mithril-slides) - Keynote-inspired presentation app.

#### Snippets

- [Basic drag and drop example](https://codepen.io/grilchgristle/pen/rmaZag)
- [Somewhat opinionated typeahead](https://codepen.io/grilchgristle/pen/pPvGRg)
- [Simple carousel](https://github.com/spacejack/m-carousel)
- [Mithril-Datepicker](https://github.com/CreaturesInUnitards/mithril-datepicker)
- [Filter using CSS](https://flems.io/#0=N4IgzgpgNhDGAuEAmIBcIB0ArMIA0IAZgJYy6oDaoAdgIYC2EamAFvPVPiLAPbWL9mIAL54aDJumy4CvfhEHo5YeAAI6jMKoC8qgOQAZWgFcATtFUBRWqfgtaqgFLGoxJz1NI+qgCq0A7tQAng4A4hAeAObEtNTUqgBi5kgQpsSwANYOAIJxxFmqANIKQRDw8A4AsjbE1BCq2QBGpgy+PG7hURCxdFZI-rUOAGq0MGkOAOq11MSEyaoAQhAAbr4QYGAOAEqxKfXZngqJtPDE9LQsqgDKxptxDgCSaVrVpssOV7EO1qZ1KrX1BbmaheeIGMrpGLuSDleoATVoYHoANUr0iCnqlR49nojCQRQUSFGqi2xkaR0csTKiESyVS6Q+xKGZQcAHkZhVVEZlnwoZYkEE7EUar1CsQAF7ioKqIbEHhQHKuSANahYaAMtqNGJaQonel1VHEcbxV5BBUgvQYMAAB1c8AAFHp9ABKAA61HdMDUAEdjKlpbo9Hp3apQ6p3fQMPQeMZ+PavLBjIx+BhGjwBXhVMAQ6plsQIP5UKp7c6dAA+VQUHOh+iO2rW4zwPSZ7PxMOh95QP1F33+vDVsO86gN+BF+raCu90wB1QQDAVUzo+AYTt++c8Aw8fypADCiIgJYHwmd-bbNcdKjNEGbqin0oAZPfVAADAehjB31SuVDUHgOiinPAMCqAAVLorogAAJMAd7CBBAC6patu27ZIMQNoKkERa-nUb6qHBZ4vieA61noaHLB+frTs2eEaOsUa0Na9rxBOeHnnorg3shKHtoBMDYeum7bqYe6QIehHtqI6huhJqgye28mqPB7rHiIYggHRzAYLAGxcHIAjwEIwjwQQrjUBk5BUCAZicOgbDwNaYCoAA9M5sbWhkkTaTw9DOcidhpJwBDwEE1qSCAOAiPBwhAA)
- [Get a string representation of a vnode using fragments](https://flems.io/#0=N4IgZglgNgpgziAXAbVAOwIYFsZJAOgAsAXLKEAGhAGMB7NYmBvEAXwvW10QICsEqdBk2J4AbhgBOAAjCSMAcxwNpAXmkATWtQCuy4vmqSYGRgBFtekQDF5SkQAoAlAB00WfMbQaYkh3MV9CmksBwByQgBGMOCImCgoWjCnVzQAB387fXxISThiAGFCaA0nNg4QTBw8QzgBGnpGZh42AF0qKAg0AGsEFE5qniwIYkJJaEoQHUlyHhJiNLhEAHplnXTuhUNaLGXh0fGoAAFI-FOAVj2Rseh8fkniAE807hB71lbWIA)

#### Starter kits

- [Mithril/SASS/Webpack2](https://github.com/CreaturesInUnitards/mithril-sass-webpack-starter)
- [Mithril/Typescript/SASS/PostCSS/Webpack2](https://github.com/spacejack/mithril-webpack-ts)
- [Mithril/Typescript/PostCSS/Browserify/HMR/Budō](https://github.com/spacejack/mithril-browserify-ts-budo)

### Testing

Mithril does not require specialized tools for testing, however the following have been developed as side projects to the main framework or by the community.

- [Ospec](https://github.com/MithrilJS/mithril.js/tree/rewrite/ospec) - Mithril's own fast test runner.
- [Mithril Query](https://github.com/MithrilJS/mithril-query) - Query Mithril virtual dom for testing purposes.


### Libraries & Plugins

- [Polythene](https://github.com/ArthurClemens/Polythene) - Material Design for Mithril and React.
- [mopt](https://github.com/MithrilJS/mopt) - Optimize `m()` calls to javascript objects.
- [mithril-range](https://www.npmjs.com/package/mithril-range) - Customizable range component.
- [mithril-select](https://www.npmjs.com/package/mithril-select) - Customizable select component.
- [TypeScript types](https://www.npmjs.com/package/@types/mithril) - Typescript type definitions for Mithril.
- [mithril-helpers](https://github.com/isiahmeadows/mithril-helpers) - Collection of Mithril helpers and utilities.
- [mithril-transition-group](https://github.com/vasilrimar/mithril-transition-group) - Components for creating state/class based transitions.

### Tools

- [Mithril Template Converter](http://arthurclemens.github.io/mithril-template-converter/) - Convert HTML to `m()` hyperscript.
- [Mithril Emmet VSCode Extension](https://marketplace.visualstudio.com/items?itemName=FallenMax.mithril-emmet) - Add Emmet (zen-coding) support for Mithril inside of VSCode.

### pre 1.0 Release

- [Leo's Blog](http://lhorie.github.io/mithril-blog/) - Leo, the main Mithril author, writes about virtual dom and tips and tricks.
- [Github Wiki](https://github.com/MithrilJS/mithril.js/wiki) - Wiki content is mostly about the 0.2 version, some material may be more up to date with the current API.

### Mithril in the Wild

- [flems.io](https://flems.io) - Web Playground & Sandbox with easily shareable urls and other neat features.
- [lichobile](https://lichess.org/mobile) - Mobile version for lichess.org using Mithril inside Cordova.

### License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
