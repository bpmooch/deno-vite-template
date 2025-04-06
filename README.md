# Vite + Deno + React + TypeScript

- installed tailwind using https://tailwindcss.com/docs/installation/using-vite

## tailwind install notes

```
# --allow-scripts is required for swc usage
deno install --allow-scripts npm:tailwindcss npm:@tailwindcss/vite
```

## Running

You need to have Deno v2.0.0 or later installed to run this repo.

Start a dev server:

```
$ deno task dev
```

## Deploy

Build production assets:

```
$ deno task build
```
