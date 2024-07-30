<div align="center">
  <img src="https://github.com/diiaz2910/assets-repo/blob/master/Untitled-removebg-preview.png?raw=true" width="180">
  <h1>Mantine Template</h1>
  <p>
    # Mantine Template - Pre-configured

A template designed for rapid development with Mantine UI. This template comes pre-configured with:

- **Mantine UI Components**: Styled and ready-to-use components to kickstart your UI development.
- **Apollo**: Easily manage GraphQL data with Apollo Client.
- **Vite**: A fast and modern build tool for an enhanced development experience.
- **PostCSS Configuration**: Pre-configured for advanced CSS processing.
- **Tabler Icons**: Beautiful and customizable icons included out-of-the-box.
- **TypeScript**: Leverage the power of static typing to write more robust and maintainable code.
- **ESLint and Plugins**: Enforced code quality and consistency with pre-configured ESLint and essential plugins.

Get started quickly and efficiently with this comprehensive setup, perfect for building modern, scalable web applications.

  </p>
</div>


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
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json', './tsconfig.app.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
