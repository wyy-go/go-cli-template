![GitHub Repo stars](https://img.shields.io/github/stars/wyy-go/go-cli-template?style=social)
![GitHub](https://img.shields.io/github/license/wyy-go/go-cli-template)
![GitHub go.mod Go version](https://img.shields.io/github/go-mod/go-version/wyy-go/go-cli-template)
![GitHub all releases](https://img.shields.io/github/downloads/wyy-go/go-cli-template/total)
![GitHub CI Status](https://img.shields.io/github/workflow/status/wyy-go/go-cli-template/ci?label=CI)
![GitHub Release Status](https://img.shields.io/github/workflow/status/wyy-go/go-cli-template/Release?label=release)

# go-cli-template
This is template that help you to quick implement some CLI using Go.

This repository is contains following.

- minimal CLI implementation using [spf13/cobra](https://github.com/spf13/cobra)
- CI/CD
  - golangci-lint
  - go test
  - goreleaser
  - dependabot for github-actions and Go
  - CodeQL Analysis (Go)

## How to use
1. fork this repository
2. replace `wyy-go` to your user name using `sed`(or others)
3. run `make init`

## Author
wyy-go
