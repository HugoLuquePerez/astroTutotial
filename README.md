# ✔ Project Status

[![Netlify Status](https://api.netlify.com/api/v1/badges/371375e5-0cf4-4b0f-9435-7555d093f570/deploy-status)](https://app.netlify.com/sites/astrotutorial19/deploys)

[Visitar Web](https://astrotutorial19.netlify.app)

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
├── src/
│   └── pages/
│   │     ├── about.astro
│   │     ├── blog.astro
│   │     ├── index.astro
│   │     └── post/    
│   │           ├──post-1.md
│   │           ├──post-2.md
│   │           └──post-3.md
│   └── styles/
│         └── global.css
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |


