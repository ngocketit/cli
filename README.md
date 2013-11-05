# Go CLI Library

cli is a library for implementing powerful command-line interfaces in Go.
cli is the library that powers the CLI for
[Packer](https://github.com/mitchellh/packer) and
[Serf](https://github.com/hashicorp/serf).

## Features

* Easy sub-command based CLIs: `cli foo`, `cli bar`, etc.

* Automatic help generation for listing subcommands

* Automatic help flag recognition of `-h`, `--help`, etc.

* Use of Go interfaces/types makes augmenting various parts of the library a
  piece of cake.
