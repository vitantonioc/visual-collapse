# \<visual-collapse\>

## Polymer Element.
Collapsibles are accordion elements that expand when clicked on. These allow you to hide content that is not immediately relevant to the user. The component call a JSON file,titles ,texts ,imgs and links.

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/vitantonioc/visual-collapse)


## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Install bower components

```
$ bower install
```

## Viewing Application

```
$ polymer serve
```

## Building Application

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
<pre><b>action</b> --> String &#x1F539; type for action : accordion or expandable</pre>
<pre><b>backgroundtext</b> --> String &#x1F539;background text collapse</pre>
<pre><b>backgroundtitle</b> --> String &#x1F539;background title collapse</pre>
<pre><b>collapsibledata</b> --> String &#x1F539;collapsable mode, accept only accordion or expandable</pre>
<pre><b>colorheader</b> --> String &#x1F539;text color header title</pre>
<pre><b>colortext</b> --> String &#x1F539;text color</pre>
<pre><b>idcollapse</b> --> Number &#x1F539;id for multiple collapse</pre>
<pre><b>manager</b> --> Boolean &#x1F539;notifies</pre>
<pre><b>titleCollapse</b> --> String &#x1F539;Default: visual-collapse title for collapse</pre>
<pre><b>urljson</b> --> String &#x1F539;path file with data</pre>
<pre><b>visible</b> --> Array &#x1F539;positions into array visible in collapse</pre>
<pre><b>width</b> --> Number &#x1F539;width px row collapsable</pre>
## Methods
<pre><b>jsondatanHidden(index)</b> --> function for visibility element in collapse</pre>


## License
MIT

