# Aeria Roadmap

## Core

- [ ] `@aeria-ui/web`
    - [ ] add `v-mask` directive (no longer available since `maska` dependency was dropped)


## Tooling

- [ ] `create-aeria-app`
    - [ ] add standalone backend template
- [ ] `aeria-inspector`: generate reports from an Aeria instance (ideally browser-compatible)
    - [ ] render dot graphs of collections and routes
    - [ ] render reports of the API in a markup language
- [ ] `aeria-language-tools`: integrate Aeria with IDEs and text editors
    - [ ] `aeria-language-server`: provide a rich language server for Aeria Lang
    - [ ] `aeria-grammar-vscode`: VSCode grammar for Aeria
    - [ ] `aeria-grammar-highlightjs`: HighlightJS grammar for Aeria (highlight Aeria on Markdown)
- [ ] `aeria-playground`: try and visualize Aeria projects on the browser
    - [ ] compile `*.aeria` and show js, ts, and errors output (similar to https://typescriptlang.org/play)


## 3rd-party integrations

- [ ] OpenAPI (Swagger)
    - generate a `swagger.json` from data reflected from the backend
- [ ] OpenTelemetry
- [ ] NextJS
    - [ ] create a SSR-compliaint `AeriaForm` component that renders a form from data reflected from the backend, same way as in `aeria-ui`
- [ ] NuxtJS
- [ ] Mailjet
- [ ] Github Actions: generate reports on each push
    - [ ] report security issues
        - endpoints without contracts
        - endpoints without rate limiting
    - [ ] generate a graph with `aeria-inspector`


## Institutional

- [ ] Aeria institutional website

