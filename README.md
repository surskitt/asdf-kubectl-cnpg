<div align="center">

# asdf-kubectl-cnpg [![Build](https://github.com/surskitt/asdf-kubectl-cnpg/actions/workflows/build.yml/badge.svg)](https://github.com/surskitt/asdf-kubectl-cnpg/actions/workflows/build.yml) [![Lint](https://github.com/surskitt/asdf-kubectl-cnpg/actions/workflows/lint.yml/badge.svg)](https://github.com/surskitt/asdf-kubectl-cnpg/actions/workflows/lint.yml)

[kubectl-cnpg](https://cloudnative-pg.io/documentation/current/kubectl-plugin/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add kubectl-cnpg
# or
asdf plugin add kubectl-cnpg https://github.com/surskitt/asdf-kubectl-cnpg.git
```

kubectl-cnpg:

```shell
# Show all installable versions
asdf list-all kubectl-cnpg

# Install specific version
asdf install kubectl-cnpg latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kubectl-cnpg latest

# Now kubectl-cnpg commands are available
kubectl-cnpg --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/surskitt/asdf-kubectl-cnpg/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [surskitt](https://github.com/surskitt/)
