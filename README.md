# sortie

Small Go tool: declutter ~/Downloads in one command

## What it does

- Groups files into folders by extension
- Dry-run prints the plan before moving anything
- Single static binary, no runtime deps
- Skips hidden files and folders by default

## Installation

```bash
go build -o bin/ ./...
```

## How to use

```bash
./bin/sortie ~/Downloads --dry-run
./bin/sortie ~/Downloads
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── faq.md
│   └── roadmap.md
├── examples/
│   └── quickstart.md
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── go.mod
└── main.go
```

## Development

```bash
go build ./...
go vet ./...
```

## 说明

个人练习项目, 谨慎用于生产环境。

## License

MIT. Do whatever you want.
