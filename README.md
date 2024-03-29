# Next.js App Router + React Server Components

Try the demo live here: [**theduke-nextjs-my-test-123.wasmer.app**](https://theduke-nextjs-my-test-123.wasmer.app).

> Note: This app is a clone of [Next.js Server Components demo](https://github.com/vercel/next-react-server-components/), [minimally adapted](https://github.com/theduke/nextjs-my-test-123/commit/0b2afd3a6e633caf7e43a89f4a89cd349365b482) to run in [WinterJS](https://github.com/wasmerio/winterjs).

## Introduction

This is a demo app of the Hacker News website clone, which shows Next.js App Router with support for React Server Components.

[Learn more](https://nextjs.org/docs/getting-started/react-essentials#server-components).

### Running Locally

1. `pnpm install`
2. `pnpm dev`

Go to `localhost:3000`.

If you want to run it with Wasmer locally, you can do `pnpm run edge:build` and then `pnpm run edge:preview`.

## Deploy on Wasmer Edge

The easiest way to deploy this Next.js Server Side components app is to use the [Wasmer Edge](https://wasmer.io/products/edge).

Live example: https://theduke-nextjs-my-test-123.wasmer.app/

First, you'll need to run `npm run edge:build`, and then, to deploy to Wasmer Edge:

```bash
wasmer deploy
```

> [!NOTE]
> You will need to have Wasmer installed (check out [the docs to install the Wasmer CLI](https://docs.wasmer.io/install)!). 
> You will also need to change the namespace in `wasmer.toml` to your own namespace and app name in `app.yaml` to your own app name.
