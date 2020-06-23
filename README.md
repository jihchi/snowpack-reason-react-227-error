## Reproduce Steps

```sh
git clone https://github.com/jihchi/snowpack-reason-react-227-error.git
cd snowpack-reason-react-227-error
yarn
yarn build
npx serve build
```

Open http://localhost:5000 in your browser.

### The Error

https://reactjs.org/docs/error-decoder.html?invariant=227

> **ReactDOM was loaded before React. Make sure you load the React package before loading ReactDOM.**

## Screenshot

![Screenshot](./screenshot.png?raw=true "Minified React error #227")
