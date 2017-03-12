# \<visual-collapse\>

## Polymer Element.
Collapsibles are accordion elements that expand when clicked on. These allow you to hide content that is not immediately relevant to the user. The component call a JSON file,titles ,texts ,imgs and links.

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/vitantonioc/visual-collapse)


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

screenshots:

![alt tag](https://github.com/vitantonioc/visual-collapse/blob/master/visual-collapse.jpg)


## API
## Properties
<pre>action --> string type for action : accordion or expandable</pre>
backgroundtext --> string background text collapse
backgroundtitle --> string background title collapse
collapsibledata --> string collapsable mode, accept only accordion or expandable
colorheader --> string text color header title
colortext --> string text color
idcollapse --> number id for multiple collapse
manager --> Boolean notifies
titleCollapse --> String Default: visual-collapse title for collapse
urljson --> string path file with data
visible --> Array positions into array visible in collapse
width --> number width px row collapsable
## Methods
jsondatanHidden(index) --> function for visibility element in collapse


## License
MIT

