# ab-svgutil

JavaScript SVG utils.

At the moment this module has 1 util:

- Convert SVG URLs in 'img' elements to inline SVG code

## Install

With [npm](http://npmjs.org) do:

```bash
$ npm install ab-svgutil --save-dev
```

## Usage
	
	// all img elements using SVG URLs should have a ".svg" class

	// Given the following Jade markup:
	// img.svg(src= 'svg_file.svg');

	// get the util
	var svgutil = require('ab-svgutil');

	// convert all img SVG to inline code
	svgutil.convertAllToInline()

## Dependencies

- jQuery

## License

MIT
