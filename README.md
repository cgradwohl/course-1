# Course-1

## remix.run

- This app was created with `npx create-remix@latest` and bootstrapped with Typescript and fly.io support.

## tailwindcss.com

- Run `build:css` to pull all generated css from the inline styles and output a minified css file. Note this file is consumed in the root.ts file.

- Run `npm run generate:css` to pull all generated css from the inline styles and output a css file. Note this file is consumed in the root.ts file.

## prisma.io

- Run `npx prisma init --datasource-provider sqlite` to add sqlite db provider.
- Run `npx prisma db push` to update schema and create any new tables or keys.

## fly.io

1. [Install `flyctl`](https://fly.io/docs/getting-started/installing-flyctl/)

2. Sign up and log in to Fly

```sh
flyctl auth signup
```

3. Setup Fly. It might ask if you want to deploy, say no since you haven't built the app yet.

```sh
flyctl launch
```

## github actions

## docker image

## Development

From your terminal:

```sh
npm run dev
```

This starts your app in development mode, rebuilding assets on file changes.

## Deployment

If you've followed the setup instructions already, all you need to do is run this:

```sh
npm run deploy
```

You can run `flyctl info` to get the url and ip address of your server.

Check out the [fly docs](https://fly.io/docs/getting-started/node/) for more information.
