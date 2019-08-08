# `Promise` for Sketch

A [`Promise`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise) polyfill for Sketch that uses `setImmediate` and makes `process` emit `multipleResolves`, `unhandledRejection` and `uncaughtException` when it should.
