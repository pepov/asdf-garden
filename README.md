<div align="center">

# asdf-garden [![Build](https://github.com/pepov/asdf-garden/actions/workflows/build.yml/badge.svg)](https://github.com/pepov/asdf-garden/actions/workflows/build.yml) [![Lint](https://github.com/pepov/asdf-garden/actions/workflows/lint.yml/badge.svg)](https://github.com/pepov/asdf-garden/actions/workflows/lint.yml)


[garden](https://docs.garden.io) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add garden
# or
asdf plugin add garden https://github.com/pepov/asdf-garden.git
```

garden:

```shell
# Show all installable versions
asdf list-all garden

# Install specific version
asdf install garden latest

# Set a version globally (on your ~/.tool-versions file)
asdf global garden latest

# Now garden commands are available
garden --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/pepov/asdf-garden/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Peter Wilcsinszky](https://github.com/pepov/)
