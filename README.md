karma-luxon
============

A Karma plugin - adapter for luxon.js.

Installation
------------

Install the plugin from npm:

```sh
$ npm install karma-luxon --save-dev
```

Add `luxon` to the `plugins` property in your Karma configuration:

```js
module.exports = function(config) {
  config.set({

    plugins: ['karma-luxon']

   //...
```

---

Add `luxon` of the version you need to the `frameworks` property in your Karma configuration:
```js
module.exports = function(config) {
  config.set({

    frameworks: ['luxon-1.23.0']
    
    //...
```
 