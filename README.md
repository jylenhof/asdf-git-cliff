<div align="center">

# asdf-git-cliff [![Build](https://github.com/jylenhof/asdf-git-cliff/actions/workflows/build.yml/badge.svg)](https://github.com/jylenhof/asdf-git-cliff/actions/workflows/build.yml) [![Lint](https://github.com/jylenhof/asdf-git-cliff/actions/workflows/lint.yml/badge.svg)](https://github.com/jylenhof/asdf-git-cliff/actions/workflows/lint.yml)

[git-cliff](https://git-cliff.org/docs/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add git-cliff
# or
asdf plugin add git-cliff https://github.com/jylenhof/asdf-git-cliff.git
```

git-cliff:

```shell
# Show all installable versions
asdf list-all git-cliff

# Install specific version
asdf install git-cliff latest

# Set a version globally (on your ~/.tool-versions file)
asdf global git-cliff latest

# Now git-cliff commands are available
git-cliff --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jylenhof/asdf-git-cliff/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jean-Yves LENHOF](https://github.com/jylenhof/)
