# Component library with styled-components

This setup demonstrates a React app using a typescript component library.

The trick is to use Babel to compile typescript (rather than [rollup-plugin-typescript](https://www.npmjs.com/package/rollup-plugin-typescript2) and rely on typescript for type checking and generation of declaration files. You'll receive faster builds and can still use the Babel plugins you're used to.

## Getting started

Clone this repository:

```shell
npx degit https://github.com/ben-rogerson/twin.examples/twin-component-library-monorepo folder-name
```

## Tech

### Components (packages/components)

- [React](https://reactjs.org/)
- [styled-components](https://styled-components.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Twin](https://github.com/ben-rogerson/twin.macro)
- [Parcel](https://parceljs.org/)

### App (packages/app)

- [Typescript](https://www.typescriptlang.org/)
- [React](https://reactjs.org/)
- [styled-components](https://styled-components.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Twin](https://github.com/ben-rogerson/twin.macro)
- [Rollup.js](https://rollupjs.org/guide/en/)
