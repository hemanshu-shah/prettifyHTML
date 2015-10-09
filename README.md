# prettyHTML

This jQuery plugin generates pretty HTML, which is well indented from source element and appends that to destination element as html encoded text, do dispaly it to the user.

You can use other tools like [prettify.js](http://demo.stanleyhlng.com/prettify-js/) to make it look beautiful.

Plugin prettifyHTML takes following parameters,
* **source**: jQuery selector to find source element in current element, whose HTML content will be beautified and appended to destination element.
* **destination**: jQuery selector to find destination element in current element, to which prettified HTML will be appended.
* **options**: 
  ```defaults = 
{
		tab: '  ', //String to use as character it can be tab character or multiple spaces
		maxCols: 120, //Max number of character used to break the element in multiple lines in case element has only text
		excludeAttributes: ['^ng-'], //attributes matching given patterns will not be included in the output
		excludeElements: ['#comment'], //elements matching given patterns will not be included in the output
}```
