# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test kubectl-cnpg https://github.com/surskitt/asdf-kubectl-cnpg.git "kubectl-cnpg --help"
```

Tests are automatically run in GitHub Actions on push and PR.
