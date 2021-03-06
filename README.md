# Silence

## What is this?

An interactive [design language](https://link.medium.com/rJ3wBmDFIT) editor and app creator. Includes [Custom Elements v1](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_custom_elements), a [component library](https://www.webcomponents.org/libraries) and [coding sandbox](https://en.wikipedia.org/wiki/Sandbox_(software_development)).

### Other Features

* [ES6/7](https://codeburst.io/javascript-wtf-is-es6-es8-es-2017-ecmascript-dca859e4821c)
* [async/await](https://link.medium.com/G2t27I3dM)
* (optional) Watches and bundles source code with <a href="https://rollupjs.org/guide/en#overview"><img src=https://rollupjs.org/logo.svg width=25 /> rollup.js</a>
* (optional) [Transpiles](https://github.com/loraxx753/design-doc-concept/blob/master/package.json#L7) with <a href="https://babeljs.io/docs/en/"><img src="https://d33wubrfki0l68.cloudfront.net/7a197cfe44548cc1a3f581152af70a3051e11671/78df8/img/babel.svg" alt="babel" width="50" /></a> & [polyfills](https://developer.mozilla.org/en-US/docs/Glossary/Polyfill) served to [legacy browsers](https://stackoverflow.com/questions/45943494/what-s-the-purpose-of-the-html-nomodule-attribute-for-script-elements-if-the-d).
* (optional) Deploy to production/staging/QA with <a href="https://surge.sh/" target="_blank"><img src="https://surge.sh/images/logos/svg/surge-logo.svg" width="25" />surge.sh</a>
* All dependencies are solely used in [package.json](https://github.com/antiPhaseDomain/Silence/blob/master/package.json#L7-L12).
* [Custom](https://github.comt/antiPhaseDomain/Silence/blob/master/_assets/styles/lib/base.css), [fully reset](https://github.com/antiPhaseDomain/Silence/blob/master/_assets/styles/lib/reset.css), cross-browser CSS. 
* Hopefully🤞, easy to understand.
* _**STILL A WORK IN PROGRESS**_


## What do I do?

[See this code running live](http://silence.surge.sh/).

## Use As A Boilerplate
1. Clone the respository and change into the directory
  * `git clone https://github.com/antiPhaseDomain/Silence.git && cd Silence`
2. Install the dependencies used for transpiling and working on legacy browsers
  * `npm i `
3. Run `npm start` and visit [127.0.0.1:8080/](http://127.0.0.1:8080/)

## Deploy Your Project

* Install [surge.sh](https://surge.sh) globally `npm i -g surge` or as a dev-dependency `npm i --save-dev surge`.
* Change the [CNAME](https://github.com/loraxx753/hybrid-design/blob/master/public/CNAME) file to `whatever-name-you-want.surge.sh`.
* Type `npm run deploy` and press enter.
* Visit your project url: https://whatever-name-you-want.surge.sh

### What About A Custom Domain?

_[Adding a custom domain](https://surge.sh/help/adding-a-custom-domain)_ by [Surge](https://surge.sh/help/chat)!

### Who Has Password Protection?

[Surge does](https://surge.sh/help/adding-password-protection-to-a-project)!

### Custom 404 page?
[Boom](https://surge.sh/help/adding-a-custom-404-not-found-page).

### Can My Friends Play?
[Only if they bring their own XBOX](https://surge.sh/help/adding-collaborators).

### Javascript Redirects Are Bad!
[I know, right](https://surge.sh/help/adding-redirects)?

* [You get a cool feature!](https://surge.sh/help/ignoring-files-and-directories)
* [You get a cool feature!](https://surge.sh/help/using-gzip-automatically)
* _[Everybody gets a cool feature!](https://surge.sh/help/using-lucid-caching-automatically)_

_[Bees](https://surge.sh/help/enabling-cross-origin-resource-sharing), [Bees](https://surge.sh/help/adding-a-200-page-for-client-side-routing), [Bees](https://surge.sh/help/using-incremental-publishing)!_

