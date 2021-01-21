# SvelteKit Starter

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte);

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

``` sh
# create a new project in the current directory
npm init svelte@next

# create a new project in my-app
npm init svelte@next my-app

# install dependencies
npm i

# start dev server
npm run dev
```

> Note: the `@next` is temporary

## Building

Svelte apps are built with _adapters_, which optimise your project for deployment to different environments, like [Begin](https://begin.com), [Netlify](https://www.netlify.com), [Vercel](https://vercel.com) and so on. (You can also create your own adapter — instructions TODO.)

By default, `npm run build` will generate a Node app that you can run with `node build`. To use a different adapter, install it and update your `svelte.config.js` accordingly. The following official adapters are available:

- [@sveltejs/adapter-node](https://github.com/sveltejs/kit/tree/master/packages/adapter-node)
- [@sveltejs/adapter-static](https://github.com/sveltejs/kit/tree/master/packages/adapter-static)
- [@sveltejs/adapter-netlify](https://github.com/sveltejs/kit/tree/master/packages/adapter-netlify)
- ...more soon
