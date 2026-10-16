# Faber

Faber is a programming language designed to be written by language models and
read by people. It is built on a small number of uniform, mechanical rules, so
that a model can predict what a program means without importing the habits of
whichever language it saw most in training. It compiles to many targets, from a
reference interpreter and readable C to Rust, Go, TypeScript and GPU kernels.

> **Experimental through version 1.** The language changes constantly, and
> breaking changes ship in minor releases. Pin an exact version and read the
> release notes before you upgrade.

- **Source:** [faberlang/faber](https://github.com/faberlang/faber) holds the
  compiler front end, the reference runner, the standard library (Norma), the
  grammar and locale packs, and the corpus. It is open source under
  `MIT OR Apache-2.0` and does not accept pull requests.
- **Releases:** [faberlang/releases](https://github.com/faberlang/releases)
  publishes the official `faber` binaries for macOS (Apple silicon) and Linux
  (x86_64). They include every code generator, not only the ones in the public
  source. The current release is 1.14.0.
- **Website and documentation:** [faberlang.dev](https://faberlang.dev).

## Around the language

| Repository | What it is |
| --- | --- |
| [triga](https://github.com/faberlang/triga) | Graphics and geometry library |
| [gradus](https://github.com/faberlang/gradus) | Autograd and machine-learning library |
| [tela](https://github.com/faberlang/tela) | UI and view library |
| [tree-sitter-faber](https://github.com/faberlang/tree-sitter-faber) | Syntax highlighting for editors |

Each repository's README states its own status.

## History

- [faber-1.x](https://github.com/faberlang/faber-1.x) is the repository that
  held Faber 1.0 to 1.12. It is archived, and its version tags were carried
  into `faber`, so a project pinned to a 1.x tag keeps resolving.
- [norma](https://github.com/faberlang/norma) and
  [hosts](https://github.com/faberlang/hosts) are archived and superseded. The
  standard library now lives in `faber` (`lib/norma`).
