# CSS LISTS

  Mobile-first classes for css-lists.
  Set the desired css-lists on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-lists
```
View on [npm](https://www.npmjs.org/package/css-lists)


## File Size

2.7K lists.css
2.1K lists.min.css
352B minified and gzipped

## The Code
```
.disc {         list-style-type: disc; }
.circle {       list-style-type: circle; }
.square {       list-style-type: square; }
.decimal {      list-style-type: decimal; }
.leading-zero { list-style-type: decimal-leading-zero; }
.lower-roman {  list-style-type: lower-roman; }
.upper-roman {  list-style-type: upper-roman; }
.lower-greek {  list-style-type: lower-greek; }
.lower-latin {  list-style-type: lower-latin; }
.upper-latin {  list-style-type: upper-latin; }
.lower-alpha {  list-style-type: lower-alpha; }
.upper-alpha {  list-style-type: upper-alpha; }
.list {         list-style-type: none; }

@media screen and (min-width: 48em) {
  .disc-ns {         list-style-type: disc; }
  .circle-ns {       list-style-type: circle; }
  .square-ns {       list-style-type: square; }
  .decimal-ns {      list-style-type: decimal; }
  .leading-zero-ns { list-style-type: decimal-leading-zero; }
  .lower-roman-ns {  list-style-type: lower-roman; }
  .upper-roman-ns {  list-style-type: upper-roman; }
  .lower-greek-ns {  list-style-type: lower-greek; }
  .lower-latin-ns {  list-style-type: lower-latin; }
  .upper-latin-ns {  list-style-type: upper-latin; }
  .lower-alpha-ns {  list-style-type: lower-alpha; }
  .upper-alpha-ns {  list-style-type: upper-alpha; }
  .list-ns {         list-style-type: none; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .disc-m {         list-style-type: disc; }
  .circle-m {       list-style-type: circle; }
  .square-m {       list-style-type: square; }
  .decimal-m {      list-style-type: decimal; }
  .leading-zero-m { list-style-type: decimal-leading-zero; }
  .lower-roman-m {  list-style-type: lower-roman; }
  .upper-roman-m {  list-style-type: upper-roman; }
  .lower-greek-m {  list-style-type: lower-greek; }
  .lower-latin-m {  list-style-type: lower-latin; }
  .upper-latin-m {  list-style-type: upper-latin; }
  .lower-alpha-m {  list-style-type: lower-alpha; }
  .upper-alpha-m {  list-style-type: upper-alpha; }
  .list-m {         list-style-type: none; }
}

@media screen and (min-width: 64em)  {
  .disc-l {         list-style-type: disc; }
  .circle-l {       list-style-type: circle; }
  .square-l {       list-style-type: square; }
  .decimal-l {      list-style-type: decimal; }
  .leading-zero-l { list-style-type: decimal-leading-zero; }
  .lower-roman-l {  list-style-type: lower-roman; }
  .upper-roman-l {  list-style-type: upper-roman; }
  .lower-greek-l {  list-style-type: lower-greek; }
  .lower-latin-l {  list-style-type: lower-latin; }
  .upper-latin-l {  list-style-type: upper-latin; }
  .lower-alpha-l {  list-style-type: lower-alpha; }
  .upper-alpha-l {  list-style-type: upper-alpha; }
  .list-l {         list-style-type: none; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2015 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

