# helix-config

Please see [config.toml](config.toml) for my very basic Helix configuration.

## Prerequisites

I use [Chocolatey](https://chocolatey.org/) package manager to install Helix:

    choco install helix

I use Fira Code [Nerd Font](https://www.nerdfonts.com/) in my terminal windows.

## Language Specifics

### Go

    go install golang.org/x/tools/gopls@latest
    go install github.com/go-delve/delve/cmd/dlv@latest
    go install honnef.co/go/tools/cmd/staticcheck@latest

### R

Install the [languageserver](https://cran.r-project.org/package=languageserver) package from CRAN.
