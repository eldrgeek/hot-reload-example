## Demo of hot reloading

[This is](https://codesandbox.io/s/hot-reload-example-whqu0) a code sandbox that demonstrates hot reloading using `react-app-rewire` and `react-hot-loader`

On reloading the client, I get this error message:

```
React-Hot-Loader: react-🔥-dom patch is not detected. React 16.6+ features may not work.

```

I've tried creating an alias in `config-overrides.js` and even replaced

```js
import ReactDOM from "react-dom";
```

with

```js
import ReactDOM from "@hot-loader/react-dom";
```

but I get the error in every case.
