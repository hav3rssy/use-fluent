# use-fluent

A handful of React hooks I keep copy-pasting between projects

Side project, maintained when I have time.

## Examples

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## Features

- useMediaQuery SSR-safe
- useDebounce with leading/trailing options
- useLocalStorage with JSON serialization
- Tiny: no dependencies besides React

## Install

```bash
npm install
npm test
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
└── package.json
```

## Development

```bash
npm install
```

## License

MIT licensed, see LICENSE.
