## Intro

Generates 1D-Barcode in javascript.

## Usage

```js
barcode128('HI34567HI').renderTo(document.querySelector('#demo'));
```

Output will be:

![HI34567HI](demo.png)

## Restrict

Only one supports type is [code128](http://en.wikipedia.org/wiki/Code_128), and **Excludes** FNCx codes.
