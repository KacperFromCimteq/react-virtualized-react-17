# React virtualized for React v17

React components for efficiently rendering large lists and tabular data.
Check out [the demo](https://bvaughn.github.io/react-virtualized/) for some examples.

## Important note
This is just the fork of the react-virtualized repo from [andreieftimie](https://github.com/andreieftimie)

## Getting started

Install `react-virtualized` using npm.

```shell
npm install KacperFromCimteq/react-virtualized-react-17 --save
```

ES6, CommonJS, and UMD builds are available with each distribution.
For example:

```js
// Most of react-virtualized's styles are functional (eg position, size).
// Functional styles are applied directly to DOM elements.
// The Table component ships with a few presentational styles as well.
// They are optional, but if you want them you will need to also import the CSS file.
// This only needs to be done once; probably during your application's bootstrapping process.
import 'react-virtualized/styles.css';

// You can import any component you want as a named export from 'react-virtualized', eg
import {Column, Table} from 'react-virtualized';

// But if you only use a few react-virtualized components,
// And you're concerned about increasing your application's bundle size,
// You can directly import only the components you need, like so:
import AutoSizer from 'react-virtualized/dist/commonjs/AutoSizer';
import List from 'react-virtualized/dist/commonjs/List';
```
Now you're ready to start using the components.
You can learn more about which components react-virtualized has to offer [below](#documentation).

## Documentation

API documentation with examples are available at main branch [here](https://github.com/bvaughn/react-virtualized).

## License

_react-virtualized_ is available under the MIT License.
