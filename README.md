<div align="center">

# asdf-bash-profile-switcher [![Build](https://github.com/mrjk/asdf-bash-profile-switcher/actions/workflows/build.yml/badge.svg)](https://github.com/mrjk/asdf-bash-profile-switcher/actions/workflows/build.yml) [![Lint](https://github.com/mrjk/asdf-bash-profile-switcher/actions/workflows/lint.yml/badge.svg)](https://github.com/mrjk/asdf-bash-profile-switcher/actions/workflows/lint.yml)

[bash-profile-switcher](https://github.com/mrjk/bash-profile-switcher) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add bash-profile-switcher
# or
asdf plugin add bash-profile-switcher https://github.com/mrjk/asdf-bash-profile-switcher.git
```

Via mise:
```
mise plugins install bash-profile-switcher https://github.com/mrjk/asdf-bash-profile-switcher.git
```

bash-profile-switcher:

```shell
# Show all installable versions
asdf list all bash-profile-switcher

# Install specific version
asdf install bash-profile-switcher latest
asdf uninstall bash-profile-switcher latest

# Set a version globally (on your ~/.tool-versions file)
asdf global bash-profile-switcher latest

# Now bash-profile-switcher commands are available
bash_profile_switcher.sh --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mrjk/asdf-bash-profile-switcher/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [mrjk](https://github.com/mrjk/)
