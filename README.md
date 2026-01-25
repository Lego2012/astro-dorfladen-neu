# Dorladen mit Astro (basierend auf Starter Kit: Basics)
Die Dateien wurden alle vom 11ty-Projekt übernommen

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                    | Action                                           |
| :------------------------- | :----------------------------------------------- |
| `pnpm i`                   | Installs dependencies                            |
| `pnpm run dev`             | Starts local dev server at `localhost:4321`      |
| `pnpm run build`           | Build your production site to `./dist/`          |
| `pnpm run preview`         | Preview your build locally, before deploying     |
| `pnpm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `pnpm run astro -- --help` | Get help using the Astro CLI                     |

## [Highlight Nav Link for Current Page in Astro](https://www.cyishere.dev/blog/astro-active-nav-item)

**URL mit Astro Variable**
~~~html
<a href={`https://${data.name}merkel.de`}>Webseite von {data.name}</a>
~~~
