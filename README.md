# Vue Designer îles Tailwind CSS - Quick start template

This is a starter template that pre-includes the [Pinegrow îles Module](https://www.npmjs.com/package/@pinegrow/iles-module), [Pinegrow Tailwind CSS Plugin](https://www.npmjs.com/package/@pinegrow/tailwindcss-plugin) and other goodies for Vue Designer.

## Vue Designer

A desktop drag-and-drop editor for Vue apps supporting Mac, Windows and Linux by [Pinegrow](https://pinegrow.com/).

It let's you visually design 🎨 your Vue single file components and boosts your productivity and your creativity while building your component-based Vue apps.

It smartly integrates with your ⚡️ [Vite](https://vitejs.dev/) based CLI, and provides an amazing deverloper experience with it's powerful visual controls and features.

Clean code 😃, No lock-in - Pinegrow Vue Designer is an open-tool ❤️

## Try it now!

### 1. Clone to local

[Create a repo from this template on GitHub](https://github.com/pinegrow/pg-iles-tailwindcss/generate).

(or)

If you prefer to do it manually with the cleaner git history

```bash
npx giget@latest gh:pinegrow/pg-iles-tailwindcss my-iles-tailwindcss-app #project-name
cd my-iles-tailwindcss-app
npm install #or use pnpm
```

## 2. Open in Vue Designer

Open your project in Vue Designer, and follow the instructions displayed in the Config Panel (that should pop-out automatically). Config Panel ⚙️ displays the key packages and the various links to their individual ecosystem and community.

## Usage

### Start your development server

```bash
npm run dev # SPA during development
```

### Preview

```bash
npm run now # build & preview
```

### Build

```bash
npm run build # MPA SSG (islands architecture)
```

And you will see the generated file in `dist` that's ready to be served.

### Deploy on Netlify

Go to [Netlify](https://app.netlify.com/start) and select your clone, `OK` along the way, and your App will be live in a minute.

Check out the [deployment documentation](https://iles.pages.dev/guide/deployment) for more information.

## Pre-packed

### Meta Framework (Vue-based)

- [îles](https://iles.pages.dev/) - A Joyful Site Generator.
  - 🏝 **[Partial Hydration]** - zero JS by default, hydrates the interactive bits
  - 🔌 **[Batteries Included]** - layouts, components, site-wide data
  - 🧱 **[Multi-Framework]** - vue, preact, svelte, solid
  - 📖 **[Markdown]** - use components in markdown and viceversa
  - 🛣 **[Routing]** - automatically configured from files
  - 🛠 **[Devtools][devtools]** - debug panel and [hydration timeline]
  - ⚡️ **[Fast][vite]** - instant reloading powered by [Vite]

### UI Frameworks

- [Tailwind CSS](https://tailwindcss.com/docs/guides/vite#vue) - The amazing utility-first CSS framework.

### Filed-based CMS (markdown)

- [@islands/mdx](https://github.com/ElMassimo/iles/tree/main/packages/mdx) - file-based CMS for powered by Markdown & Vue components. This module is shipped inside îles. Note: This page is a markdown file 🗒.
- [@islands/prism](https://github.com/ElMassimo/iles/tree/main/packages/prism) - an îles module that injects a remark plugin to provide syntax highlighting for MDX documents.

### Icons

- [UnoCSS Preset Icons](https://github.com/unocss/unocss/tree/main/packages/preset-icons/) - use over 100,000 open-source [Iconify](https://iconify.design/) icons. Uses the **unocss** format for icon names, for eg, `i-mdi-home`.

### Modules/Plugins

- [VueUse](https://vueuse.org/) - collection of essential Vue composition utilities.
- [Pinegrow îles Module](https://www.npmjs.com/package/@pinegrow/iles-module) - enables you to live-design your Vue single-file-components visually in Vue Designer.
- [Pinegrow Tailwind CSS Plugin](https://www.npmjs.com/package/@pinegrow/tailwindcss-plugin) - via Design Panel, enables visual controls customization (automatic) and theme customization (optional).

### Devtools

- [îles Devtools](https://iles.pages.dev/guide/development#devtools) - Page information is available in the in-app debug panel (similar to Vitepress). Also access the "Islands" inspector in Vue devtools.
- [Vue Devtools](https://devtools.vuejs.org/guide/installation.html#standalone) - Official devtools that can be used as a standalone app alongside Vue Designer. It's conditionally configured in `app.ts` (only during development).
  - **ACTION REQUIRED**: Currently deactivated. In `app.ts`, uncomment the top devtools related snippet to activate.

### VS Code Extensions

- [VS Code Extensions](./.vscode/extensions.json & ./.vscode/settings.json)
  - [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) - Vue 3 `<script setup>` IDE support
  - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
  - [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

### Coding Style

- Use Composition API with [`<script setup>` SFC syntax](https://vuejs.org/guide/scaling-up/sfc.html)
- [ESLint](https://eslint.org) with [@nuxt/eslint-config](https://github.com/nuxt/eslint-config) - opinionated not-so-strict set of linting rules. Nuxt & îles share a similar directory structure, so are their linting rules.
- [Prettier](https://prettier.io) with [eslint-config-prettier](https://github.com/prettier/eslint-config-prettier) - format without conflicting with eslint rules.

### Typescript

Allows JS & strict mode is turned off. Update `tsconfig.ts` as required.

```json
{
  "compilerOptions": {
    // ...
    "strict": false,
    "allowJs": true
  }
}
```

## Community

- [Pinegrow Vue Designer](https://forum.pinegrow.com/vue-designer)
