# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test idris2 https://github.com/asdf-community/asdf-idris2.git "scheme --version"
```

Tests are automatically run in GitHub Actions on push and PR.
