# Vite + Deno + React + TypeScript

Created using `deno run -RWE npm:create-vite-extra@latest`, choosing
`deno-react` and `Typescript + SWC`.

- installed tailwind using https://tailwindcss.com/docs/installation/using-vite

## tailwind install notes

swc complained about "nodeModulesDir" not being set to "auto" and
`--allow-scripts` not being used to install the dependencies

```
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
