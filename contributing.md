# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test virtctl https://github.com/LF-Certification/asdf-virtctl.git "virtctl version --client"
```

Tests are automatically run in GitHub Actions on push and PR.
