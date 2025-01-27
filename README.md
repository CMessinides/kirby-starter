# My Kirby Starter

## Features

- Bundling and dev server with [Vite](https://vitejs.dev/) via [kirby-vite](https://github.com/arnoson/kirby-vite) plugin
- Styling with [Tailwind](https://tailwindcss.com/) v4
- Templating in [Twig](https://twig.symfony.com/) via [kirby-twig](https://github.com/wearejust/kirby-twig)

*Based on the [kirby-vite starter kit](https://github.com/arnoson/kirby-vite-basic-kit).*

## Installation

Clone this repository and run:

```
composer install
```

```
npm install
```

## Development

Start vite's dev server and a simple php dev server by running:

```
npm run dev
```

Visit `localhost:8888` in the browser. Vite's dev server (`localhost:5173`) is only used for serving js, css and assets.

## Preview

Get a local production preview by running:

```
npm run preview
```

## Production

Build your optimized frontend assets to `public/dist`:

```
npm run build
```
