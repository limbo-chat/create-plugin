# limbo plugin template

This template is a starting point for creating a [limbo](https://github.com/limbo-llm) plugin with:

-   TypeScript
-   [Rollup](https://github.com/rollup/rollup)
-   [Rollup plugin limbo](https://github.com/rollup-plugin)

## Useful resources

-   todo include link to limbo developer docs

## Prerequisites

-   [pnpm](https://pnpm.io/settings) v10+

## Get started

1. Copy .env.example -> .env

## Development

Running the `dev` script allows Rollup to rebuild your plugin on change. To start development, run one of the following command depending on your package manager.

```sh
npm run dev

# or

pnpm dev

# or

yarn dev
```

### Hot reloading

The limbo desktop app can watch your plugins directory for changes. To copy your built plugin to the limbo plugins directory after a build automatically, enable the `copyToPluginsDir` option with the rollup limbo plugin.

## Production

Running the `build` script builds your plugin for production and the output will be ready to be published.

```sh
npm run build

# or

pnpm build

# or

yarn build
```
