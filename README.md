# cliparse

Small TypeScript CLI: CSV to JSON converter

Started as a weekend hack, grew on me.

## Installation

```bash
npm install
npm run build
```

## Usage

```bash
npx . convert data.csv -d ';'
# or after npm link: cliparse convert data.csv
```

## Features

- Ships as an ESM binary
- commander-based subcommands
- Strict tsconfig, no any
- npm link friendly

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   └── development.md
├── examples/
│   └── quickstart.md
├── src/
│   └── index.ts
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── package.json
└── tsconfig.json
```

## Development

```bash
npm install
```

## 说明

个人练习项目, 谨慎用于生产环境。

## License

MIT - see [LICENSE](LICENSE).
