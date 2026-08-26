# focusfolio

MV3 extension playground: page reading-time estimator

## Usage

```bash
# click the toolbar icon to see today's reading time
```

## What it does

- Popup shows today's total focus time
- Manifest V3, service worker based
- Per-tab time persisted to chrome.storage
- No remote calls, everything stays local

## Install

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## Project structure

```text
├── .github/
│   └── ISSUE_TEMPLATE/
│       └── bug_report.md
├── docs/
│   ├── configuration.md
│   ├── development.md
│   └── faq.md
├── scripts/
│   └── dev.sh
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```

## Development

```bash
npm install
npm test
```

## License

MIT. Do whatever you want.
