# VM - Go Version Manager Plugin for [ZMicro](https://github.com/zcorky/zmicro)

[![Release](https://img.shields.io/github/tag/zmicro-design/plugin-vm.svg?label=Release)](https://github.com/zmicro-design/plugin-vm/tags)
[![Build Status](https://github.com/zmicro-design/plugin-vm/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/zmicro-design/plugin-vm/actions/workflows/test.yml)
[![GitHub issues](https://img.shields.io/github/issues/zmicro-design/plugin-vm.svg)](https://github.com/zmicro-design/plugin-vm/issues)

## Installation

To install the package, run:

```bash
zmicro plugin install vm
```

### If you donot install [ZMicro](https://github.com/zcorky/zmicro):

```bash
# CURL
curl -o- https://raw.githubusercontent.com/zmicro-design/plugin-vm/master/install | bash

# WGET
wget -qO- https://raw.githubusercontent.com/zmicro-design/plugin-vm/master/install | bash
```

## Usage

```markdown
Go Version Manager (v1.0.6)

Go Version Manager is a tool for managing multiple Go versions.

Usage:
  vm install <version>   - Install Go version
  vm use <version>       - Use Go version
  vm remove <version>    - Remove Go version
  vm ls                  - List all Go versions
  vm ls-remote           - Show current Go version
  vm current             - Show current Go version
  vm help                - Show help

Example:
  vm install v1.18
  vm use v1.18
  vm remove v1.18
  vm ls
  vm ls-remote
  vm current
```

## License

ZMicro Design is released under the [MIT License](./LICENSE).
