# asdf-opencode

[opencode](https://github.com/anomalyco/opencode) binary plugin for [asdf](https://github.com/asdf-vm/asdf)

## Install

### Plugin

```sh
asdf plugin add opencode
# or
asdf plugin add opencode https://github.com/egose/asdf-opencode.git
```

### opencode

```sh
# List all versions of a package
asdf list all opencode

# Install a specific version of a package
asdf install opencode <version>

# Install the latest stable version
asdf install opencode latest

# Set the package global version
asdf global opencode <version>

# Check the version
opencode --version
```

Please check [asdf](https://github.com/asdf-vm/asdf) for more details.

# License

See [LICENSE](LICENSE) ©[Junmin Ahn](https://github.com/junminahn/)
