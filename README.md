## URL: my-portfolio--site.pages.dev

## Tech Stack

- [Astro](https://astro.build)
- [tailwindcss](https://tailwindcss.com/)

## Project Structure

```php
├── src/
│   ├── components/
│   │   ├── cv/
│   │   │   ├── TimeLine
│   │   ├── BaseHead.astro
│   │   ├── Footer.astro
│   │   ├── Header.astro
│   │   └── SideBar.astro
│   │   └── SideBarMenu.astro
│   │   └── SideBarFooter.astro
│   │
│   ├── layouts/
│   │   └── BaseLayout.astro
│   │   └── PostLayout.astro
│   └── pages/
│   │   |
|   |   |── projects/
|   |   |   └── fukulog.astro
|   |   |   └── myFirstProject.astro
|   |   |
|   |   └──404.astro
|   |   └──blog.astro
│   │   └── index.astro
│   │   └── projects.astro
│   │   └── rss.xml.js
│   ├── styles/
│   │   └── global.css
│   └── config.ts
├── public/
│
├── astro.config.mjs
├── tailwind.config.cjs
├── package.json
└── tsconfig.json
```
