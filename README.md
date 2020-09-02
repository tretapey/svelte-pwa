---

# Svelte PWA

This is a Progressive Web App (PWA) template for [Svelte](https://svelte.dev) apps. It lives at https://github.com/tretapey/svelte-pwa.

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


## PWA Configuration

- The `service-worker.js` and `manifest.json` files are in the `public` folder.
- You should update the icons in `/public/images/icons`
- For an offline experience edit the `/public/offline.html` file.
- This PWA is installable, the `/public/scripts/install.js` file has the install configuration. You should change the app name in the `logAppInstalled` function.
    Note: If you don't want to make the app installable you can remove the script from the `index.html` file in the `public` folder.
    
For more info, this template was made following this [tutorial](https://codelabs.developers.google.com/codelabs/your-first-pwapp)
 
## Building and running in production mode

To create an optimised version of the app:

```bash
npm run build
```
