# Dubai Font Face

Dubai is a sans-serif typeface commissioned by the Government of Dubai.

![Dubai Font Weights](/demo.png)

## Font Weights

Only 4 weights of the font are available:

- 300 Light
- 400 Regular
- 500 Medium
- 700 Bold

## Installation

Install via npm

```sh
npm install @ahmedhamdan/dubai-font --save
```

## Usage

To import all included weights in JavaScript

```js
import "@ahmedhamdan/dubai-font";
```

You can also import weights individually

```js
import "@ahmedhamdan/dubai-font/css/300.css";
import "@ahmedhamdan/dubai-font/css/400.css";
import "@ahmedhamdan/dubai-font/css/500.css";
import "@ahmedhamdan/dubai-font/css/700.css";
```

Apply the font to css

```css
body {
  font-family: "Dubai", Helvetica, sans-serif;
}
```
