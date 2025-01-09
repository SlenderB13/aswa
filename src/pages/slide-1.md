---
title: first-slide
layout: "../layouts/BaseLayout.astro"
index: 1
---
## Objective
I just needed to do a presentation and wanted to use Markdown.
So i built this to make it easier.

## How
Each Markdown file in `/pages/` folder is a slide page.

1. Add every MD file in `src/pages/` folder.
2. Every file should be named as `slide-<index>.md`.
3. Every file should have `title`, `layout` and `index` properties.
4. The `layout` prop should point to the `BaseLayout.astro` layout file, or you can create your own.

Folder structure example:
```bash
- src
    - pages
        - slide-1.md
        - slide-2.md
        - slide-3.md
```

File properties example:
```markdown
---
title: first-slide
layout: "../layouts/BaseLayout.astro"
index: 1
---
## Objective
Make presentations easier with markdown files.

```
You can also see the [README file](https://github.com/slenderb13/aswa/blob/main/README.md)
