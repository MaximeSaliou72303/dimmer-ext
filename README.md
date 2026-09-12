# dimmer-ext

MV3 extension playground: page reading-time estimator

Built for my own use; public in case it helps someone.

## Getting started

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## Highlights

- Popup shows today's total focus time
- Per-tab time persisted to chrome.storage
- No remote calls, everything stays local
- Manifest V3, service worker based

## Usage

```bash
# click the toolbar icon to see today's reading time
```

## Project structure

```text
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```

## Development

```bash
npm install
```

## License

MIT. Do whatever you want.
