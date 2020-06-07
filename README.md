<div align="center">

# asdf-idris2 ![Build](https://github.com/asdf-community/asdf-idris2/workflows/Build/badge.svg) ![Lint](https://github.com/asdf-community/asdf-idris2/workflows/Lint/badge.svg)

[idris2](https://github.com/idris-lang/Idris2) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- A working `scheme` compiler. See [asdf-chezscheme](https://github.com/asdf-community/asdf-chezscheme)
- set env `ASDF_IDRIS2_BOOTSTRAP_OPTS` if you need a custom bootstrap process (eg, `bootstrap-rkt`)
- `bash`, `curl`, `tar`, generic POSIX build utilities.

# Install

Plugin:

```shell
asdf plugin add idris2
# or
asdf plugin add https://github.com/asdf-community/asdf-idris2.git
```

idris2:

```shell
# Show all installable versions
asdf list-all idris2

# Install specific version
asdf install idris2 latest

# Set a version globally (on your ~/.tool-versions file)
asdf global idris2 latest

# Now idris2 commands are available
idris2 --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/asdf-community/asdf-idris2/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Victor Hugo Borja](https://github.com/asdf-community/)
