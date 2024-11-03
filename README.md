# Typescript CLI Starter Template

A simple command-line interface (CLI) tool template built with Node.js, TypeScript, and hot-reload functionality using `pnpm` and `nodemon`.

## Features

- **TypeScript** for type safety and modern JavaScript features.
- **Hot Reload** in development for rapid iteration.
- **`pnpm`** as the package manager for fast and efficient dependency management.

## Getting Started

### Prerequisites

- **Node.js** (version 14 or above is recommended)
- **pnpm** (version 6 or above is recommended)

If `pnpm` is not installed, you can install it globally with:

```bash
npm install -g pnpm
```

### Installation

1. Clone this repository and navigate to the project directory.
2. Install dependencies:

   ```bash
   pnpm install
   ```

### Project Structure

```plaintext
├── src
│   └── index.ts         # Entry point of the CLI tool
├── dist                 # Compiled JavaScript files (generated after build)
├── tsconfig.json        # TypeScript configuration
├── nodemon.json         # Nodemon configuration for hot reload
└── package.json         # Project configuration and dependencies
```

### Scripts

- **Development with Hot Reload**: To start the tool in development mode with hot reload, use:

  ```bash
  pnpm run dev
  ```

- **Build**: To compile TypeScript files to JavaScript in the `dist` folder, run:

  ```bash
  pnpm run build
  ```

- **Run**: To run the compiled JavaScript files (after building), use:

  ```bash
  pnpm run start
  ```

## Configuration

- **TypeScript**: Configuration is in `tsconfig.json`. Adjust compiler options as needed.
- **Nodemon**: Configuration is in `nodemon.json`, which allows automatic reload on TypeScript file changes.

## Updating `pnpm`

To update `pnpm` to the latest version, use one of the following:

- If installed globally via `npm`:

  ```bash
  npm install -g pnpm
  ```

- If using `corepack` (for Node.js 16.9+):

  ```bash
  corepack prepare pnpm@latest --activate
  ```

For other installation methods, refer to the [pnpm installation guide](https://pnpm.io/installation).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or fixes.

This `README.md` should provide a comprehensive introduction to the project, including installation, usage, configuration, and contributing information.