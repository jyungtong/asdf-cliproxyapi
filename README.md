<div align="center">

# asdf-cliproxyapi [![Build](https://github.com/jyungtong/asdf-cliproxyapi/actions/workflows/build.yml/badge.svg)](https://github.com/jyungtong/asdf-cliproxyapi/actions/workflows/build.yml) [![Lint](https://github.com/jyungtong/asdf-cliproxyapi/actions/workflows/lint.yml/badge.svg)](https://github.com/jyungtong/asdf-cliproxyapi/actions/workflows/lint.yml)

[cliproxyapi](https://github.com/router-for-me/CLIProxyAPI) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add cliproxyapi
# or
asdf plugin add cliproxyapi https://github.com/jyungtong/asdf-cliproxyapi.git
```

cliproxyapi:

```shell
# Show all installable versions
asdf list-all cliproxyapi

# Install specific version
asdf install cliproxyapi latest

# Set a version globally (on your ~/.tool-versions file)
asdf global cliproxyapi latest

# Now cliproxyapi commands are available
cli-proxy-api --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jyungtong/asdf-cliproxyapi/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [jyung](https://github.com/jyungtong/)
