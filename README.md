# Biscuit datalog language server

## Introduction

This repo provides a (minimal) language server for biscuit datalog.

It is based on [tower-lsp](https://github.com/ebkalderon/tower-lsp) and [tower-lsp-boilerplate](https://github.com/IWANABETHATGUY/tower-lsp-boilerplate).

## Features

Some of these features, like _code completion_, require support for fault-tolerant parsing, which is not done yet. Other features, like _go to definition_ or _inlay hints_ might be hard to map to datalog semantics.

- [x] syntactic error diagnostic
- [ ] code completion
- [ ] find reference
- [ ] rename
- [ ] semantic token
- [ ] go to definition
- [ ] inlay hints

## Installation / usage

This language server has not been released yet and is not part of the [biscuit-auth VSCode extension](https://marketplace.visualstudio.com/items?itemName=biscuit-auth.vscode-biscuit).

It can be used fairly easily from nvim or helix.