# focusfolio-hq

Chrome extension that tracks reading time per tab

Side project, maintained when I have time.

## Usage

```bash
# click the toolbar icon to see today's reading time
```

## Install

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## Features

- Per-tab time persisted to chrome.storage
- Popup shows today's total focus time
- Manifest V3, service worker based
- No remote calls, everything stays local

## Project structure

```text
├── .github/
│   └── ISSUE_TEMPLATE/
│       └── bug_report.md
├── docs/
│   ├── development.md
│   └── faq.md
├── examples/
│   └── quickstart.md
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
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

## Why

Needed this for myself; figured others might too.
