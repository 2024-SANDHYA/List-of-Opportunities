# Hack the Opportunities
Never miss a deadline again!<br><br>
Can't keep track of the opportunities or you get to know about it when it's too late?
I too, had been struggling with constantly learning about new opportunities when someone posted about them on LinkedIn unfortunately way past the deadline :( <br><br>
So I decided to maintain a database of all the opportunities I came across and this repository is the result!
This list is not complete and I alone cannot make it whole. This is where the community efforts come and so I made the list open Source! <br>
## Hack the Hack!
- I made a hackathon calendar that you can subscribe to and never miss an awesome hackathon again! <br>
- Subscribe here: [Hack the Hack Calendar](https://neon.ly/HacktheHackCalendar)
## How to Hack the Opportunities?
Huge shoutout to [Anik Das](https://github.com/sadn1ck/sadn1ck) for his contribution to the website.
Watch this video to get the best out of this:
<a href=""> <img src="" alt="Demo Video" height='500' width='900'/> </a>

### Filter out the opportunities on the basis of 
- 2021 Deadlines
![Uzoma Medium Gif](https://github.com/vibalijoshi/List-of-Opportunities/blob/main/gifs/2021.gif)
- Scholarship
![Uzoma Medium Gif](https://github.com/vibalijoshi/List-of-Opportunities/blob/main/gifs/scholarship.gif)
- Women in Tech Opportunities: Type Women
![Uzoma Medium Gif](https://github.com/vibalijoshi/List-of-Opportunities/blob/main/gifs/women.gif)
- By Month
![Uzoma Medium Gif](https://github.com/vibalijoshi/List-of-Opportunities/blob/main/gifs/august.gif)
- Mentorship
- Internship
- Fellowship
- Hackathons (PIO/PPO)
- Coding Challenges

## Contribution

If you're interested in adding any opportunity to the above list, feel free to make a Pull Request:
> Add the opportunity to [the opportunities file](./src/logic/opportunities.ts) in the given format

PS: Opportunities are classified based on the deadline months from previous years. 

If you have any other ideas, feel free to make an issue!

[Link to the excel sheet](https://docs.google.com/spreadsheets/d/1nGXJTz0dGnj7yaFzTT_q1HcnKny4avz8aRJZW8lm2Ic/edit?usp=sharing) [OUTDATED, please refer website]
#### GitHub Repository Structure

| S.No. | Dir Name | Purpose |
| --------------- | --------------- | --------------- |
| 1. | [data](https://github.com/vibalijoshi/List-of-Opportunities/tree/main/data) | Month-wise opportunities listed|
| 2. | [src/logic/opportunities.ts](https://github.com/vibalijoshi/List-of-Opportunities/blob/main/src/logic/opportunities.ts) | database for website |


---

### Features

- ⚡️ [Vue 3](https://github.com/vuejs/vue-next), [Vite 2](https://github.com/vitejs/vite), [pnpm](https://pnpm.js.org/), [ESBuild](https://github.com/evanw/esbuild) - born with fastness

- 🗂 [File based routing](./src/pages)

- 📦 [Components auto importing](./src/components)

- 📑 [Layout system](./src/layouts)

- 📲 [PWA](https://github.com/antfu/vite-plugin-pwa)

- 🎨 [Windi CSS](https://github.com/windicss/windicss) - next generation utility-first CSS framework

- 😃 [Use icons from any icon sets, with no compromise](./src/components)

- 🗒 [Markdown Support](https://github.com/antfu/vite-plugin-md)

- 🔥 Use the [new `<script setup>` style](https://github.com/vuejs/rfcs/pull/227)

- 🖨 Server-side generation (SSG) via [vite-ssg](https://github.com/antfu/vite-ssg)

- 🦔 Critical CSS via [critters](https://github.com/GoogleChromeLabs/critters)

- 🦾 TypeScript, of course

- ☁️ Deploy on Netlify, zero-config

<br>

### Pre-packed

### UI Frameworks

- [Windi CSS](https://github.com/windicss/windicss) (On-demand [TailwindCSS](https://tailwindcss.com/)) - lighter and faster, with a bunch of additional features!
  - [Windi CSS Typography](https://windicss.org/plugins/official/typography.html)

### Icons

- [Iconify](https://iconify.design) - use icons from any icon sets [🔍Icônes](https://icones.netlify.app/)
- [`vite-plugin-icons`](https://github.com/antfu/vite-plugin-icons) - icons as Vue components

### Plugins

- [Vue Router](https://github.com/vuejs/vue-router)
  - [`vite-plugin-pages`](https://github.com/hannoeru/vite-plugin-pages) - file system based routing
  - [`vite-plugin-vue-layouts`](https://github.com/JohnCampionJr/vite-plugin-vue-layouts) - layouts for pages
- [`vite-plugin-components`](https://github.com/antfu/vite-plugin-components) - components auto import
- [`vite-plugin-pwa`](https://github.com/antfu/vite-plugin-pwa) - PWA
- [`vite-plugin-windicss`](https://github.com/antfu/vite-plugin-windicss) - WindiCSS support
- [`vite-plugin-md`](https://github.com/antfu/vite-plugin-md) - Markdown as components / components in Markdown
  - [`markdown-it-prism`](https://github.com/jGleitz/markdown-it-prism) - [Prism](https://prismjs.com/) for syntax highlighting
  - [`prism-theme-vars`](https://github.com/antfu/prism-theme-vars) - customizable Prism.js theme using CSS variables
- [Vue I18n](https://github.com/intlify/vue-i18n-next) - Internationalization
  - [`vite-plugin-vue-i18n`](https://github.com/intlify/vite-plugin-vue-i18n) - Vite plugin for Vue I18n
- [VueUse](https://github.com/antfu/vueuse) - collection of useful composition APIs
- [`@vueuse/head`](https://github.com/vueuse/head) - manipulate document head reactively
- [`vue-global-api`](https://github.com/antfu/vue-global-api) - Use Vue Composition API globally

### Coding Style

- Use Composition API with [`<script setup>` SFC syntax](https://github.com/vuejs/rfcs/pull/227)
- [ESLint](https://eslint.org/) with [@antfu/eslint-config](https://github.com/antfu/eslint-config), single quotes, no semi.

### Dev tools

- [TypeScript](https://www.typescriptlang.org/)
- [pnpm](https://pnpm.js.org/) - fast, disk space efficient package manager
- [`vite-ssg`](https://github.com/antfu/vite-ssg) - Server-side generation
  - [critters](https://github.com/GoogleChromeLabs/critters) - Critical CSS
- [Netlify](https://www.netlify.com/) - zero-config deployment
- [VS Code Extensions](./.vscode/extensions.json)
  - [Vite](https://marketplace.visualstudio.com/items?itemName=antfu.vite) - Fire up Vite server automatically
  - [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar) - Vue 3 `<script setup>` IDE support
  - [Iconify IntelliSense](https://marketplace.visualstudio.com/items?itemName=antfu.iconify) - Icon inline display and autocomplete
  - [i18n Ally](https://marketplace.visualstudio.com/items?itemName=lokalise.i18n-ally) - All in one i18n support
  - [Windi CSS Intellisense](https://marketplace.visualstudio.com/items?itemName=voorjaar.windicss-intellisense) - IDE support for Windi CSS
  - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

## Usage

### Development

Just run and visit http://localhost:3333

```bash
pnpm dev
```

### Build

To build the App, run

```bash
pnpm build
```

And you will see the generated file in `dist` that ready to be served.
