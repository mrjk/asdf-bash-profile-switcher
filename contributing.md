# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test bash-profile-switcher https://github.com/mrjk/asdf-bash-profile-switcher.git "bash_profile_switcher.sh --help"
```

Tests are automatically run in GitHub Actions on push and PR.
