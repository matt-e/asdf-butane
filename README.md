<div align="center">

# asdf-butane [![Build](https://github.com/matt-e/asdf-butane/actions/workflows/build.yml/badge.svg)](https://github.com/matt-e/asdf-butane/actions/workflows/build.yml) [![Lint](https://github.com/matt-e/asdf-butane/actions/workflows/lint.yml/badge.svg)](https://github.com/matt-e/asdf-butane/actions/workflows/lint.yml)


[butane](https://github.com/coreos/butane) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add butane
# or
asdf plugin add butane https://github.com/matt-e/asdf-butane.git
```

butane:

```shell
# Show all installable versions
asdf list-all butane

# Install specific version
asdf install butane latest

# Set a version globally (on your ~/.tool-versions file)
asdf global butane latest

# Now butane commands are available
butane --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/matt-e/asdf-butane/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Matthew Eddey](https://github.com/matt-e/)
