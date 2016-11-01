# css-lists 1.0.6

Css module of single purpose classes for lists

#### Stats

411 | 52 | 52
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-lists
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-lists
```

ssh:
```
git clone git@github.com:tachyons-css/css-lists.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-lists";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/css-lists@1.0.6/css/css-lists.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-lists">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*
   LIST STYLE TYPES
*/
.disc { list-style-type: disc; }
.circle { list-style-type: circle; }
.square { list-style-type: square; }
.decimal { list-style-type: decimal; }
.leading-zero { list-style-type: decimal-leading-zero; }
.lower-roman { list-style-type: lower-roman; }
.upper-roman { list-style-type: upper-roman; }
.lower-greek { list-style-type: lower-greek; }
.lower-latin { list-style-type: lower-latin; }
.upper-latin { list-style-type: upper-latin; }
.lower-alpha { list-style-type: lower-alpha; }
.upper-alpha { list-style-type: upper-alpha; }
.list { list-style-type: none; }
@media screen and (min-width: 48em) {
 .disc-ns { list-style-type: disc; }
 .circle-ns { list-style-type: circle; }
 .square-ns { list-style-type: square; }
 .decimal-ns { list-style-type: decimal; }
 .leading-zero-ns { list-style-type: decimal-leading-zero; }
 .lower-roman-ns { list-style-type: lower-roman; }
 .upper-roman-ns { list-style-type: upper-roman; }
 .lower-greek-ns { list-style-type: lower-greek; }
 .lower-latin-ns { list-style-type: lower-latin; }
 .upper-latin-ns { list-style-type: upper-latin; }
 .lower-alpha-ns { list-style-type: lower-alpha; }
 .upper-alpha-ns { list-style-type: upper-alpha; }
 .list-ns { list-style-type: none; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .disc-m { list-style-type: disc; }
 .circle-m { list-style-type: circle; }
 .square-m { list-style-type: square; }
 .decimal-m { list-style-type: decimal; }
 .leading-zero-m { list-style-type: decimal-leading-zero; }
 .lower-roman-m { list-style-type: lower-roman; }
 .upper-roman-m { list-style-type: upper-roman; }
 .lower-greek-m { list-style-type: lower-greek; }
 .lower-latin-m { list-style-type: lower-latin; }
 .upper-latin-m { list-style-type: upper-latin; }
 .lower-alpha-m { list-style-type: lower-alpha; }
 .upper-alpha-m { list-style-type: upper-alpha; }
 .list-m { list-style-type: none; }
}
@media screen and (min-width: 64em) {
 .disc-l { list-style-type: disc; }
 .circle-l { list-style-type: circle; }
 .square-l { list-style-type: square; }
 .decimal-l { list-style-type: decimal; }
 .leading-zero-l { list-style-type: decimal-leading-zero; }
 .lower-roman-l { list-style-type: lower-roman; }
 .upper-roman-l { list-style-type: upper-roman; }
 .lower-greek-l { list-style-type: lower-greek; }
 .lower-latin-l { list-style-type: lower-latin; }
 .upper-latin-l { list-style-type: upper-latin; }
 .lower-alpha-l { list-style-type: lower-alpha; }
 .upper-alpha-l { list-style-type: upper-alpha; }
 .list-l { list-style-type: none; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

ISC

