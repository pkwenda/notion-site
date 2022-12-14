# Contributing

By participating to this project, you agree to abide our [code of conduct](/CODEOFCONDUCT.md).

## Setup your machine

`zpan` is written in [Go](https://golang.org/).

Prerequisites:

- `make`
- [Go 1.17+](https://golang.org/doc/install)

Clone `notion-site` anywhere:

```sh
$ git clone git@github.com:pkwenda/notion-site.git
```

Install the build and lint dependencies:

```sh
$ make mod
```

A good way of making sure everything is all right is running the test suite:

```sh
$ make test
```

## Test your change

You can create a branch for your changes and try to build from the source as you go:

```sh
$ make build
```

Which runs all the linters and tests.

## Create a commit

Commit messages should be well formatted, and to make that "standardized", we
are using Conventional Commits.

You can follow the documentation on
[their website](https://www.conventionalcommits.org).

## Submit a pull request

Push your branch to your `notion-site` fork and open a pull request against the
master branch.
