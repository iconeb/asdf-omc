<div align="center">

# asdf-omc [![Build](https://github.com/iconeb/asdf-omc/actions/workflows/build.yml/badge.svg)](https://github.com/iconeb/asdf-omc/actions/workflows/build.yml) [![Lint](https://github.com/iconeb/asdf-omc/actions/workflows/lint.yml/badge.svg)](https://github.com/iconeb/asdf-omc/actions/workflows/lint.yml)

[omc](https://github.com/gmeghnag/omc) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Install

Plugin:

```shell
asdf plugin add omc
# or
asdf plugin add omc https://github.com/iconeb/asdf-omc.git
```

omc:

```shell
# Show all installable versions
asdf list-all omc

# Install specific version
asdf install omc latest

# Set a version globally (on your ~/.tool-versions file)
asdf global omc latest

# Now omc commands are available
omc --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/iconeb/asdf-omc/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Federico Nebiolo](https://github.com/iconeb/)
