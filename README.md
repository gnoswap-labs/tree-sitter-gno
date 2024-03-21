# tree-sitter-gno

gno grammar for tree-sitter

## Description

Gno is essentially identical to Go's syntax, but some syntax such as `generic`, `channel` and `go` are not supported. Therefore, the grammar rules have been written and generated to fit these characteristics.

However, we believe that these syntax elements will be [fully implemented eventually](<https://github.com/gnolang/gno/blob/master/PLAN.md#gnolang>), so they have been commented out for now. Once they start being supported, you can simply remove the comments from thos parts and _**regenerate**_ the grammar with the following command

```bash
tree-sitter generate
```

## Project Setup

For project setup, please refer to the setup section of tree-sitter's official [documentation](<https://tree-sitter.github.io/tree-sitter/creating-parsers#project-setup>).
