# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: "latest",
    sourceType: "module",
    project: ["./tsconfig.json", "./tsconfig.node.json"],
    tsconfigRootDir: __dirname,
  },
};
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list

# Arrays time complexity

## inserting

    ### insert
        O(1) => constant time
    ### ordered inesertion
        O(n) => linear time

## deleting

    O(n) => linear time

## searching

    ### linear search
        O(n) => linear time
    ### binary search
        O(log(n)) => logarithmic time

## sorting

    ### bubble sort
        O(n^2) => quadratic time
    ### selection sort
        O(n^2) => quadratic time but less swaping than the bubble sort .
        So selection sort is faster that the bubble sort.
    ### insertion sort
        O(n^2) => quadratic time but it’s about twice as fast as the bubble sort
        and somewhat faster than the selection sort in normal situations.

    ### merge sort
