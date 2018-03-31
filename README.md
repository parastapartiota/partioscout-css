# partioscout-css

The Guides and Scouts of Finland (Suomen Partiolaiset – Finlands Scouter ry) style guide in CSS

## Installation

```sh
yarn add partioscout-css
```

## Get Started

### Static page

```sh
yarn add parcel-bundler # Install parcel to build the static page
yarn add serve # Serve the static site locally
yarn add typeface-pt-sans typeface-source-sans-pro # Install the fonts
```

```html
<!-- index.html -->
<!doctype html>
<html>
  <head>
    <title>PartioScout Site Example</title>
    <link rel="preload" href="../node_modules/typeface-pt-sans/files/pt-sans-latin-400.woff2" as="font" type="font/woff2" crossorigin/>
    <link rel="preload" href="../node_modules/typeface-source-sans-pro/files/source-sans-pro-latin-900.woff2" as="font" type="font/woff2" crossorigin/>
    <link rel="stylesheet" href="./styles.css" type="text/css"/>
  </head>

  <body>
    <h1>PartioScout Site Example</h1>
    <p>Foobar</p>
  </body>

</html>
```

```css
/* styles.css */
@import 'typeface-pt-sans/index.css';
@import 'typeface-source-sans-pro/index.css';
@import 'partioscout-css/dist/partioscout-site.css';
```

```sh
yarn parcel build index.html # Bundle with Parcel
yarn serve dist/ --open # Serve the built page and open it in browser
```

### CSS Modules

TODO...

## License

MIT
