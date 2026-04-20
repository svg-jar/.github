<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/svg-jar/plugin/main/logo-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/svg-jar/plugin/main/logo-light.svg">
  <img alt="SvgJar" src="https://raw.githubusercontent.com/svg-jar/plugin/main/logo-light.svg" width="300" height="201">
</picture>

# SVG Jar

</div>

SVG Jar is a collection of tools for working with SVG files on the web. It provides a modern approach to SVG management -- import SVGs directly as components in your framework of choice, with build-time optimisation and a visual browser for your icon library.

## Packages

### [@svg-jar/plugin](https://github.com/svg-jar/plugin)

**Status: In development**

An [unplugin](https://github.com/unjs/unplugin) for importing SVGs as components with sprite sheet support. Works with Vite and Rollup.

See the [plugin README](https://github.com/svg-jar/plugin/blob/main/plugin/README.md) for full documentation.

---

### [@svg-jar/codemod](https://github.com/svg-jar/codemod)

**Status: In development**

A CLI codemod that migrates Ember projects from [`ember-svg-jar`](https://github.com/evoactivity/ember-svg-jar) to direct SVG component imports.

```sh
pnpm dlx @svg-jar/codemod
```

See the [codemod README](https://github.com/svg-jar/codemod/blob/main/README.md) for full documentation.

---

### [@svg-jar/browser](https://github.com/svg-jar/browser)

**Status: Planned**

A UI for browsing and searching your application's SVG files. Provides a visual catalogue of all available icons, making it easy to find the right icon and copy its import path.
