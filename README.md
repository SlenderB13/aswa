# ASWA - Slide Presentation With Astro
Yes, there is a typo.

## How to start
```sh
npm install
```
```sh
npm run dev
```

## Objective
I just needed to do a presentation and wanted to use Markdown.
So i built this to make it easier.

## How to use it
Each Markdown file in `/pages/` folder is a slide page and has its onw route, like `localhost/slide-1`.

1. Add every MD file in `src/pages/` folder.
2. Every file should be named as `slide-<index>.md`.
3. Every file should have `title`, `layout` and `index` properties.
4. The `layout` prop should point to the `BaseLayout.astro` layout file, or you can create your own.

**Folder structure example:**
```bash
- src
    - pages
        - slide-1.md
        - slide-2.md
        - slide-3.md
```
> As said in steps 1 and 2.

**File properties example:**
```markdown
---
title: first-slide
layout: "../layouts/BaseLayout.astro"
index: 1
---
## Objective
Make presentations easier with markdown files.

```
> As said in steps 3 and 4.

___

## If you don't know Astro
[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/basics)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/basics)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/basics/devcontainer.json)

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

![just-the-basics](https://github.com/withastro/astro/assets/2244813/a0a5533c-a856-4198-8470-2d67b1d7c554)

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

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

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
