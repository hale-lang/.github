<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/hale-lang/hale/raw/main/assets/readme/banner-dark.png">
    <img src="https://github.com/hale-lang/hale/raw/main/assets/readme/banner-light.png" alt="Hale" width="100%">
  </picture>
</p>

<h3 align="center">Less language. More compiler.</h3>

<p align="center">
  One language from a five-line script to a dynamic distributed system.
</p>

<p align="center">
  <a href="https://hale-lang.org"><b>hale-lang.org</b></a> ·
  <a href="https://hale-lang.org/docs">Guide</a> ·
  <a href="https://hale-lang.org/playground">Playground</a> ·
  <a href="https://hale-lang.org/packages">Packages</a> ·
  <a href="https://hale-lang.org/features">Features</a> ·
  <a href="https://hale-lang.org/glossary">Glossary</a>
</p>

Hale is a compiled, general-purpose language. Every piece of state has one
owner, and the parts of a program talk only over declared, typed message
channels. That shape lets the compiler check a program's architecture the
way it checks its types. It runs natively with no garbage collector and no
borrow checker, and its concurrency has no locks and no data races.

## Start here

- **Try it in the browser** in the [playground](https://hale-lang.org/playground).
- **Install it** with one line: `curl -fsSL https://hale-lang.org/install.sh | sh`
- **Read the guide** at [hale-lang.org/docs](https://hale-lang.org/docs).
- **Read the compiler**, runtime and spec in [hale](https://github.com/hale-lang/hale).

## Repositories

| Repository | What it holds |
|---|---|
| [hale](https://github.com/hale-lang/hale) | The language: compiler, runtime, standard library, spec and guide |
| [hale-lang.org](https://github.com/hale-lang/hale-lang.org) | The website, with the guide, examples and playground |
| [pond](https://github.com/hale-lang/pond) | Contributed libraries: HTTP, SQLite, WebSocket, routing, LLM agents, metrics and terminal UI |
| [tree-sitter-hale](https://github.com/hale-lang/tree-sitter-hale) | The Tree-sitter grammar, for editors and highlighting |
| [hlhub](https://github.com/hale-lang/hlhub) | Hale highlighting on github.com, a browser extension whose core is written in Hale |
| [iris](https://github.com/hale-lang/iris) | A live observer for running Hale systems: structure, message flow and transport behavior |
| [bench](https://github.com/hale-lang/bench) | Benchmarks, with a cross-language comparison and instructions to reproduce it |
| [papers](https://github.com/hale-lang/papers) | Two papers on capacity-allocation bounds in coordinated systems |

## Status

Hale is in prerelease. Syntax and artifact formats still change between
releases, so pin a version if you depend on anything.

## License

Apache 2.0 across the organization unless a repository says otherwise.

---

Also building [brained.dev](https://brained.dev).
