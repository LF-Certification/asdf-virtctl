<div align="center">

# asdf-virtctl [![Build](https://github.com/LF-Certification/asdf-virtctl/actions/workflows/build.yml/badge.svg)](https://github.com/LF-Certification/asdf-virtctl/actions/workflows/build.yml) [![Lint](https://github.com/LF-Certification/asdf-virtctl/actions/workflows/lint.yml/badge.svg)](https://github.com/LF-Certification/asdf-virtctl/actions/workflows/lint.yml)

[virtctl](https://kubevirt.io/user-guide/operations/virtctl_client_tool/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add virtctl
# or
asdf plugin add virtctl https://github.com/LF-Certification/asdf-virtctl.git
```

virtctl:

```shell
# Show all installable versions
asdf list-all virtctl

# Install specific version
asdf install virtctl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global virtctl latest

# Now virtctl commands are available
virtctl version --client
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/LF-Certification/asdf-virtctl/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jonathan Kinred](https://github.com/LF-Certification/)
