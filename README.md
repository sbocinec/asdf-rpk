<div align="center">

# asdf-rpk [![Build](https://github.com/sbocinec/asdf-rpk/actions/workflows/build.yml/badge.svg)](https://github.com/sbocinec/asdf-rpk/actions/workflows/build.yml) [![Lint](https://github.com/sbocinec/asdf-rpk/actions/workflows/lint.yml/badge.svg)](https://github.com/sbocinec/asdf-rpk/actions/workflows/lint.yml)


[rpk](https://docs.redpanda.com/docs/reference/rpk-commands/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `unzip`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add rpk
# or
asdf plugin add rpk https://github.com/sbocinec/asdf-rpk.git
```

rpk:

```shell
# Show all installable versions
asdf list-all rpk

# Install specific version
asdf install rpk latest

# Set a version globally (on your ~/.tool-versions file)
asdf global rpk latest

# Now rpk commands are available
rpk --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/sbocinec/asdf-rpk/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Stano Bocinec](https://github.com/sbocinec/)
