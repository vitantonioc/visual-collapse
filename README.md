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

![alt tag](https://github.com/vitantonioc/visual-collapse/blob/master/visual-collapse1.jpg)


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

<!---
```
<custom-element-demo>
  <template>
    <link rel="import" href="../iron-component-page/iron-component-page.html">
       <link rel="import" href="../iron-demo-helpers/demo-pages-shared-styles.html">
        <link rel="import" href="../iron-demo-helpers/demo-snippet.html">
        <link rel="import" href="../iron-ajax/iron-ajax.html">
        <iron-component-page src="visual-collapse.html"></iron-component-page>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<visual-collapse>...</visual-collapse>
```
## Use

Import element :
```html
<link rel="import" href="../visual-collapse.html">
```

Change properties:
```html
  <visual-collapse 
      idcollapse="one"
      ajaxclass="ajaxclass"
      collapsibledata="accordion"
      action="popout"
      width="350" 
      visible="[0,1,3,4]"
      colorheader="white" 
      backgroundtitle="blue"
      backgroundtext="white"
      colortext="green"
      urljson="data.json" 
      manager>
   </visual-collapse>
```
Json data1:
```html
[
    {"icon": "repeat_one", "title": "First" , "text": "Lorem ipsum dolor sit amet <a href='#' title='link1' target='_blank'>link1 </a>"},
    {"icon": "live_help", "title": "Second" , "text": "Lorem ipsum dolor sit amet2 <a href='#' title='Polymer img'><img src='polymer.png' style='width:60px' /></a>"},
    {"icon": "spellcheck", "title": "Third" , "text": "Lorem ipsum dolor sit amet3 <a href='#'  title='link2' target='_blank'>link2 </a>"},
    {"icon": "error_outline", "title": "Four" , "text": "Lorem ipsum dolor sit amet4"},
    {"icon": "whatshot", "title": "Five" , "text": "Lorem ipsum dolor sit amet5"}              
]
```
Json data2:
```html
[
    {"icon": "repeat_one", "title": "Six" , "text": "Lorem ipsum dolor sit amet <a href='#' title='link1' target='_blank'>link1 </a>"},
    {"icon": "live_help", "title": "Seven" , "text": "Lorem ipsum dolor sit amet2 <a href='#' title='Polymer img'><img src='polymer.png' style='width:60px' /></a>"},
    {"icon": "spellcheck", "title": "Eight" , "text": "Lorem ipsum dolor sit amet3 <a href='#'  title='link2' target='_blank'>link2 </a>"},
    {"icon": "error_outline", "title": "Nine" , "text": "Lorem ipsum dolor sit amet4"},
    {"icon": "whatshot", "title": "Ten" , "text": "Lorem ipsum dolor sit amet5"}              
]

```


## License
MIT

