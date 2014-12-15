todomvc-moreartyjs
==================

**Extended with [Couchbase Lite for JavaScript](https://github.com/couchbaselabs/couchbase-lite-js) via [Immutable CBLJS](https://github.com/couchbaselabs/immutable-cbljs) to enable persistence and sync.**

TodoMVC implementation using Morearty.js with webpack and [react-hot-loader](https://github.com/gaearon/react-hot-loader).

`npm install`, then run with `npm run start`. Build standalone app with `npm run build`. Or just [open](https://rawgit.com/moreartyjs/todomvc-moreartyjs/master/index.html) in browser.

To make hot loader work properly with Morearty state put app entry point `React.createClass` call into the same module as state.
