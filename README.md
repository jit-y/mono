# mono

A command line tool for stripping ANSI escape codes from stdin.

## Install

```sh
go get github.com/jit-y/mono
```

## Usage

```sh
$ printf "\e[31m\e[1mhello\e[0m\n" | mono
hello
```

