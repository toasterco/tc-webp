# \<tc-webp\>

A simple Polymer component to display webp images, with optional fallback to other formats. Also allows optional loading of retina assets.

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
Running `polymer test` will run tests. By default, selenium tests will be run against all browsers on your OS. On OSX this requires the
[SafariDriver extension](https://github.com/SeleniumHQ/selenium/wiki/SafariDriver#getting-started) to be installed.

If you want to run tests against individual browsers, run `polymer test -l chrome`

** NOTE: Firefox 47.0.0 breaks FirefoxDriver working with Selenium. To fix, either downgrade to 46 or upgrade to 47.0.1
