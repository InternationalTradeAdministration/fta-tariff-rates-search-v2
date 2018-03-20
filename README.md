Tariff Rates Search
=====================

A search client for international tariff rates data.

### Setup

```
npm install
npm start
open http://localhost:3001
```

### Linting

This boilerplate project includes React-friendly ESLint configuration.

```
npm run lint
```

### Build & Deploy to GitHub Page

```
npm run clean && npm run build && npm run deploy
```

### Use as a plugin.

Include the build output (e.g. `bundle.js` and `explorer.css`) within the `head` tag.
```html
<html>
  <head>
    ...
    <script src="bundle.js"></script> <!-- Tariff Rates Search js -->
    <link href="explorer.css"></script> <!-- Tariff Rates Search styles -->
    ...
  </head>
  <body>
  ...
    <div id="main"></div>
    <script>
      // Explorer is provided by bundle.js.
      // Explorer.render(<elementId>) must be called after the DOM element.
      Explorer.render('main')
    </script>
  </body>
</html>
```

### Dependencies

* React
* Webpack
* [webpack-dev-server](https://github.com/webpack/webpack-dev-server)
* [babel-loader](https://github.com/babel/babel-loader)
* [react-hot-loader](https://github.com/gaearon/react-hot-loader)
