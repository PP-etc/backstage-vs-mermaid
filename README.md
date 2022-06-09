# backstage-vs-mermaid
This is a demo of a `mermaid` diagram generation failure. Potentially, specific part of the markdown shall be rendered in to the diagram. And this happens on the page load. However, when you navigate to the other page — the markdown stays unchanged. On the page reload — it is again rendered.

Depending on the `techdocs.generator.runIn` configuration:
* `docker` — works ✅
* `local` — does not work 🚫

# [Backstage](https://backstage.io)

This is your newly scaffolded Backstage App, Good Luck!

To start the app, run:

```sh
yarn install
yarn dev
```
