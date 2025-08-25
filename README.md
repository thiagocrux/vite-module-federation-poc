# Vite Module Federation POC (Web)

A proof of concept demonstrating module federation using React.js and TypeScript.

## Technologies

These are some of the tecnologies used in this project:

- `jotai`: A lightweight, flexible state management library for React, offering a simple API similar to React's built-in `useState` but with scalable atomic state and efficient re-renders.
- `react`: A JavaScript library for building user interfaces or UI components.
- `typescript`: A superset of JavaScript that introduces optional static typing, interfaces, enums, and other language features.
- `vite`:  A blazing-fast frontend build tool with instant server start, ES modules support, and built-in Module Federation support (via plugins) for micro-frontends and dynamic code sharing across apps.

_For more information about other dependencies, see the `package.json` file._

## Installation

1. Clone the repository:

```bash
git clone https://github.com/thiagocrux/vite-module-federation-poc.git
```

2. Browse to the `host` folder and install the dependencies:

```bash
cd vite-module-federation-poc/host && pnpm install
```

3. Browse to the `remote` folder and install the dependencies:

```bash
cd ../remote && pnpm install
```

## Available scripts

This section describes the available scripts in the `package.json` file and their functionalities.

### Development

- #### `dev`

  Starts the server in development mode, enabling faster builds and live-reloading.

  ```bash
  pnpm dev
  ```

### Production

- #### `build`

  Compiles the application for production.

  ```bash
  pnpm build
  ```

- #### `preview`

  Start the server for a local preview of the production build.

  ```bash
  pnpm preview
  ```

### Code quality

- #### `lint`

  Analyzes your codebase for potential errors and style violations using `next lint`.

  ```bash
  pnpm lint
  ```

## License

[MIT](https://choosealicense.com/licenses/mit/)
