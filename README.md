---

# Svelte PWA

This is a Svelte PWA project template for [Svelte](https://svelte.dev) apps. It lives at https://github.com/tretapey/svelte-pwa.

To create a new project based on this template using [degit](https://github.com/Rich-Harris/degit):

```bash
npx degit tretapey/svelte-pwa my-svelte-pwa
cd my-svelte-pwa
```

*Note that you will need to have [Node.js](https://nodejs.org) installed.*


## Get started

Install the dependencies...

```bash
cd my-svelte-pwa
npm install
```

...then start [Rollup](https://rollupjs.org):

```bash
npm run dev
```

Navigate to [localhost:5000](http://localhost:5000). You should see your app running. Edit a component file in `src`, save it, and reload the page to see your changes.

By default, the server will only respond to requests from localhost. To allow connections from other computers, edit the `sirv` commands in package.json to include the option `--host 0.0.0.0`.


## Building and running in production mode

To create an optimised version of the app:

```bash
npm run build
```
