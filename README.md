# \<polymer1example\>

Polymer v1 example

## Browser support

- [Browser compatibility with the polyfills](https://www.polymer-project.org/1.0/docs/browsers)
- [Polymer demos are not working in android stock browser](https://github.com/Polymer/polymer/issues/616)
- [Polymer elements not rendering in Android 4.1.2 and 4.2.1. Works on 4.4.2](https://github.com/Polymer/polymer/issues/714)


## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
