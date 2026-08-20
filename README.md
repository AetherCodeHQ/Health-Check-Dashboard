# Health Check Dashboard

![CI](https://github.com/Qyroxen/Health-Check-Dashboard/actions/workflows/ci.yml/badge.svg)
![CodeQL](https://github.com/Qyroxen/Health-Check-Dashboard/actions/workflows/codeql.yml/badge.svg)
![Go](https://img.shields.io/badge/Go-1.23+-00ADD8?style=flat&logo=go)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Stars](https://img.shields.io/github/stars/Qyroxen/Health-Check-Dashboard?style=social)
![Issues](https://img.shields.io/github/issues/Qyroxen/Health-Check-Dashboard)
![PRs](https://img.shields.io/github/issues-pr/Qyroxen/Health-Check-Dashboard)

> A production-ready CLI tool built with Go

[![Star Badge](https://img.shields.io/github/stars/Qyroxen/Health-Check-Dashboard?style=social)](https://github.com/Qyroxen/Health-Check-Dashboard/stargazers)

## What is it?

Health Check Dashboard is a production-ready CLI tool built with Go. It provides powerful functionality with a beautiful terminal interface.

## Features

- Fast and efficient (written in Go)
- Beautiful CLI with colored output
- Comprehensive documentation
- GitHub Actions CI/CD
- CodeQL security analysis
- Dependabot for dependency updates
- MIT Licensed
- Fully offline - zero cloud dependency

## Quick Start

```bash
# Install
git clone https://github.com/Qyroxen/Health-Check-Dashboard.git
cd Health-Check-Dashboard
go build -o healthcheckdashboard .

# Run
./healthcheckdashboard --help
```

## CLI Usage

```bash
# Basic usage
./healthcheckdashboard

# With flags
./healthcheckdashboard --verbose --output json

# Get help
./healthcheckdashboard --help
```

## Examples

```bash
# Example 1
./healthcheckdashboard example1

# Example 2
./healthcheckdashboard example2 --flag value
```

## Development

```bash
# Run tests
go test ./...

# Build
go build -o healthcheckdashboard .

# Lint
golangci-lint run

# Security scan
codeql analyze
```

## Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## Security

For security vulnerabilities, please see [SECURITY.md](SECURITY.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  <a href="https://github.com/Qyroxen/Health-Check-Dashboard/stargazers">
    <img src="https://img.shields.io/github/stars/Qyroxen/Health-Check-Dashboard?style=social" alt="Star this repo">
  </a>
  <a href="https://github.com/Qyroxen/Health-Check-Dashboard/forks">
    <img src="https://img.shields.io/github/forks/Qyroxen/Health-Check-Dashboard?style=social" alt="Fork this repo">
  </a>
  <a href="https://github.com/Qyroxen/Health-Check-Dashboard/issues">
    <img src="https://img.shields.io/github/issues/Qyroxen/Health-Check-Dashboard" alt="Issues">
  </a>
  <a href="https://github.com/Qyroxen/Health-Check-Dashboard/pulls">
    <img src="https://img.shields.io/github/issues-pr/Qyroxen/Health-Check-Dashboard" alt="Pull Requests">
  </a>
</p>
