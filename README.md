# atunko JBang catalog

[JBang](https://www.jbang.dev/) catalog for [atunko](https://github.com/atunko-dev/atunko) —
a TUI + CLI for OpenRewrite: browse, search, configure and run recipes.

## Usage

```bash
jbang atunko@atunko-dev tui
jbang atunko@atunko-dev search "spring"
jbang atunko@atunko-dev run -r org.openrewrite.java.RemoveUnusedImports
```

The alias resolves the rolling [snapshot pre-release](https://github.com/atunko-dev/atunko/releases/tag/snapshot)
(stable releases will take over once published);
JBang provisions a matching Java runtime automatically.

The canonical copy of this catalog lives in the main repository
([`jbang-catalog.json`](https://github.com/atunko-dev/atunko/blob/main/jbang-catalog.json)),
which also works directly: `jbang atunko@atunko-dev/atunko tui`.

## License

Apache 2.0, same as atunko.
