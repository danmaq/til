# javascript/react-native

## Setup

* Require npm 4.6.x when create and first launch project in aug.2017 version.
* package.json avail version, GitHub repos, and branches.

## Styles

* flexbox e.g.: `flex`
* aspectRatio

## UI

* ReactNative support Liquid-layout. But __unsupported Responsive layout__.

## Trouble-shoot

### Fail on npm start plobrem.

```
child_process.js:614
    throw err;
    ^

Error: spawnSync /Users/danmaq/src/Repos/netch-native/node_modules/react-native/local-cli/setup_env.sh EACCES
    at _errnoException (util.js:1041:11)
```

-> `find node_modules/react-native -name '*.sh' | xargs chmod a+x`

## modules

* react-native-router-flux
* Redux

## React JSX

* embedding HTML in JavaScript, like E4X.
* Element vars __must be PascalCase__.
* If use js-beautify, use `"e4x": true` in .jsbeautifyrc file.

## misc.

* Initial Screen resolution
    * Same to browser view?
    * width: 414
    * height: 736
