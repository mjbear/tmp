# tmp

This is essentially my testing and proving ground for GitHub Actions.

Maybe it's temporary or maybe it's not. :laughing:

## Dockerfile Linting

Is this super useful? Maybe, maybe not so much.

* https://github.com/replicatedhq/dockerfilelint
   * GH Action - https://github.com/marketplace/actions/docker-lint
* https://github.com/hadolint/hadolint
   * GH Action - https://github.com/marketplace/actions/hadolint-action

## Markdown Linting

* https://github.com/markdownlint/markdownlint
    * Ruby
    * GH Action: https://github.com/marketplace/actions/run-markdownlint-mdl
* https://github.com/DavidAnson/markdownlint
    * Node.js (Javascript)
    * inspired by the Ruby one at the top
    * Two CLIs, second of which from the same author
      https://github.com/DavidAnson/markdownlint-cli2
    * GH Action: https://github.com/marketplace/actions/markdownlint-cli2-action
* https://github.com/igorshubovych/markdownlint-cli
    * Node.js (Javascript)
    * this cli uses DavidAnson's project as the base
    * GH Action: https://github.com/marketplace/actions/markdown-linting-action
* https://github.com/btford/write-good
   * Node.js (Javascript)
   * not exactly a MD linter?
   * GH Action: https://github.com/marketplace/actions/lint-markdown
* https://github.com/jackdewinter/pymarkdown/tree/main
    * Python
    * pypi - https://pypi.org/project/pymarkdownlnt/
    * GH Action: _None?_

## Python Linting and Formatting

(At the moment) This is not an exhaustive list as there are other Python
linters and formatters. (ex: flake8, pylint, pydocstyle, black)

* https://github.com/astral-sh/ruff
    * Rust
    * extremely fast
    * can _lint and format_ based on the arguments passed to `ruff`
    * GH Action: https://github.com/marketplace/actions/ruff-action

## YAML Linting

* https://github.com/adrienverge/yamllint
   * Python
   * GH Action: https://github.com/marketplace/actions/yaml-lint

<!---
https://github.com/mattcone/markdown-guide/blob/master/_basic-syntax/horizontal-rules.md

Horizontal rule
```markdown
***
---
___
```
--->

---

# Testing

testing GH actions

* 1
* 2
* 3
* 4
* 5

1. foo
1. bar
