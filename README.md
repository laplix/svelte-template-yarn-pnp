# Basic Svelte template with Yarn Plug'n'Play feature

This is a template for scaffolding [Svelte](https://svelte.dev) apps. This template is basically a copy of the [sveltejs/template](https://github.com/sveltejs/template) to which I added the Yarn [Plug'n'Play](https://yarnpkg.com/lang/en/docs/pnp/) feature.

This means **no more `node_modules`** with hundred of megabytes in each of your projects and it is so much faster. Pure Awesomeness!

## Getting started

To create a new project based on this template, you can use [degit](https://github.com/Rich-Harris/degit), a _straightforward project scaffolding_ tool writtent by Rich Harris, the Svelte author. Go check it out, You'll be impressed.

*Note that you will need to have [Node.js v8+](https://nodejs.org) installed to use `degit`.*

Create your project:

```bash
npx degit laplix/svelte-template-yarn-pnp your-svelte-app
```

Alternatively, you can install `degit` on your machine and use it like such:

```bash
npm install -g degit
degit laplix/svelte-template-yarn-pnp your-svelte-app
```

Install the dependencies...

```bash
cd your-svelte-app
yarn
```

...then start the development server using [Rollup](https://rollupjs.org) (a module bundler also written by Ricj Harris):

```bash
yarn dev
```

Navigate to [localhost:5000](http://localhost:5000). You should see your app running.

Start coding:

Edit the `main.js` file in `src`, replace the `name` property with your app name, save it, and you should see your change reflected immediately in your browser.

Now, edit `src/app.svelte` and add the following under the `<h1>` header:

```html
<h2>Welcome to my new app</h2>
```

Save it. Again, you should see the change in the brpwser.

Happy coding...

## Resources

For more information about Svelte templates, please see the original [template](https://github.com/sveltejs/template) README.

If your new to Svelte, I strongly suggest the [Svelte tutorial](https://svelte.dev/tutorial/basics) which will get you up to speed rapidly. Alos, a visit to [svelte examples](https://svelte.dev/examples#hello-world) and the [Svelte API](https://svelte.dev/docs) will also help you a lot.
