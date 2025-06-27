<div align="center">

# asdf-oama [![Build](https://github.com/asdf-communitiy/asdf-oama/actions/workflows/build.yml/badge.svg)](https://github.com/asdf-communitiy/asdf-oama/actions/workflows/build.yml) [![Lint](https://github.com/asdf-community/asdf-oama/actions/workflows/lint.yml/badge.svg)](https://github.com/asdf-communitiy/asdf-oama/actions/workflows/lint.yml)

[oama](https://github.com/pdobsan/oama) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [asdf-oama  ](#asdf-oama--)
- [Contents](#contents)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add oama
# or
asdf plugin add oama https://github.com/asdf-communitiy/asdf-oama.git
```

oama:

```shell
# Show all installable versions
asdf list-all oama

# Install specific version
asdf install oama latest

# Set a version globally (on your ~/.tool-versions file)
asdf global oama latest

# Now oama commands are available
oama --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/asdf-community/asdf-oama/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [ChangZhuo Chen (陳昌倬) <czchen@czchen.org>](https://github.com/czchen/)
