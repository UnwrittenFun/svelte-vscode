# Svelte for VS Code

Provides syntax highlighting and rich intellisense for Svelte components in VS Code, utilising the [svelte language server](https://github.com/UnwrittenFun/svelte-language-server).

## Features

*   Svelte
    *   Diagnostic messages for warnings and errors
    *   Support for svelte preprocessors that provide source maps
*   HTML
    *   Hover info
    *   Autocompletions
    *   [Emmet](https://emmet.io/)
*   CSS / SCSS / LESS
    *   Diagnostic messages for syntax and lint errors
    *   Hover info
    *   Autocompletions
    *   Formatting (via [prettier](https://github.com/prettier/prettier))
    *   [Emmet](https://emmet.io/)
*   TypeScript / JavaScript
    *   Diagnostics messages for syntax and semantic errors
    *   Hover info
    *   Formatting (via [prettier](https://github.com/prettier/prettier))

More features coming soon.

### Settings

#### `svelte.language-server.runtime`

Path to the node executable you would like to use to run the language server.
This is useful when you depend on native modules such as node-sass as without
this they will run in the context of vscode, meaning v8 version mismatch is likely.
