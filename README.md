<div align="center">

# asdf-hledger-flow [![Build](https://github.com/airtonix/asdf-hledger-flow/actions/workflows/build.yml/badge.svg)](https://github.com/airtonix/asdf-hledger-flow/actions/workflows/build.yml) [![Lint](https://github.com/airtonix/asdf-hledger-flow/actions/workflows/lint.yml/badge.svg)](https://github.com/airtonix/asdf-hledger-flow/actions/workflows/lint.yml)

[hledger-flow](https://github.com/apauley/hledger-flow) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [asdf-hledger-flow](#asdf-hledger-flow)
- [Contents](#contents)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar` and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add hledger-flow
# or
asdf plugin add hledger-flow https://github.com/airtonix/asdf-hledger-flow.git
```

hledger:

```shell
# Show all installable versions
asdf list-all hledger-flow

# Install specific version
asdf install hledger-flow latest

# Set a version globally (on your ~/.tool-versions file)
asdf global hledger-flow latest

# Now hledger commands are available
hledger-flow --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/airtonix/asdf-hledger/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Zeno Jiricek](https://github.com/airtonix/)
