# nodelessbuildplugin

This is a plugin for builds.
The nodelessbuildplugin is a framework-agnostic system that is platform-agnostic when converting JavaScript code and works in any environment, including browsers, Worker, Node.js, and JavaScript runtimes.
use [unenv](https://unjs.io/packages/unenv)

How to use:
```ts
import {nodelessbuildplugin} from '@taisan11/nodelessbuildplugin'

// Bun.build or esbuild.build
Bun.build({
    entrypoints:['src/index.ts'],
    outdir: './dist',
    minify: true,
    plugins: [nodelessPlugin],
})
```