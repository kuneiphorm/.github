![Java](https://img.shields.io/badge/Java-21-blue)
![License](https://img.shields.io/badge/License-Apache_2.0-blue)

[![kuneiphorm-gradle](https://img.shields.io/github/v/release/kuneiphorm/kuneiphorm-gradle?include_prereleases&label=kuneiphorm-gradle)](https://github.com/kuneiphorm/kuneiphorm-gradle/releases)
[![kuneiphorm-runtime](https://img.shields.io/github/v/release/kuneiphorm/kuneiphorm-runtime?include_prereleases&label=kuneiphorm-runtime)](https://github.com/kuneiphorm/kuneiphorm-runtime/releases)
[![kuneiphorm-daedalus](https://img.shields.io/github/v/release/kuneiphorm/kuneiphorm-daedalus?include_prereleases&label=kuneiphorm-daedalus)](https://github.com/kuneiphorm/kuneiphorm-daedalus/releases)
[![kuneiphorm-regex](https://img.shields.io/github/v/release/kuneiphorm/kuneiphorm-regex?include_prereleases&label=kuneiphorm-regex)](https://github.com/kuneiphorm/kuneiphorm-regex/releases)
[![kuneiphorm-lexer](https://img.shields.io/github/v/release/kuneiphorm/kuneiphorm-lexer?include_prereleases&label=kuneiphorm-lexer)](https://github.com/kuneiphorm/kuneiphorm-lexer/releases)


# Kuneiphorm

<p align="center">
  <img src="https://raw.githubusercontent.com/kuneiphorm/.github/master/assets/logo.svg" alt="Kuneiphorm" width="200">
</p>


A toolkit for generating and executing compiler frontends, lexers and parsers, in Java.

Kuneiphorm takes a grammar definition and produces efficient, readable lexer and parser implementations, as well as runtime interpretable versions.

## Modules

| Module | Description |
|---|---|
| `kuneiphorm-gradle` | Convention plugins: versioning, testing, formatting, publishing |
| `kuneiphorm-runtime` | Runtime primitives: CharFlow, Token, TokenFlow, Parser |
| `kuneiphorm-daedalus` | Expression algebra, finite automata, construction algorithms |
| `kuneiphorm-regex` | Regex parser and tokenizer specification builder |
| `kuneiphorm-lexer` | Runtime regex-based lexer (interprets compiled specs) |

## License

See individual repositories for license information.
