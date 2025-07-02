# LambdaTest SmartUI Reporter

> Instantly visualize your SmartUI test results—just drop in your JSON file to explore interactive before-and-after snapshots in a clean, filterable dashboard.
>
> Built for Developers, Designers, Managers, and QA teams to easily spot visual regressions, assess their impact, and collaborate on fixes with ease.
>
> Try it now and streamline your entire visual testing workflow!

## 📚 Table of Contents

- [✨ Features](#✨-features)
- [🔧 Prerequisites](#🔧-prerequisites)
- [🚀 Installation](#🚀-installation)
- [🌐 Online Demo](#🌐-online-demo)
- [💡 Usage Examples](#💡-usage-examples)
- [⚙️ Configuration](#⚙️-configuration)
- [🗂️ File Structure](#🗂️-file-structure)
- [🤝 Contributing](#🤝-contributing)
- [📬 Questions and Support](#questions-and-support)
- [📈 Roadmap](#📈-roadmap)
- [📝 Changelog](#📝-changelog)
- [🔑 Licence](#🔑-licence)

---

## ✨ Features

- **Dashboard View**: Overview table showing pages, browsers, viewports, and mismatch rates.
- **Filtering**: Quickly narrow results by page, browser, or resolution.
- **Interactive Diff**: Compare baseline vs. capture with a draggable slider.
- **Export**: Download CSV for data analysis or PDF for reports.
- **Theme Toggle**: Light/dark modes with preference saved in `localStorage`.

[Back to top](#📚-table-of-contents)

## 🔧 Prerequisites

- A JSON results file from LambdaTest SmartUI:
  ```bash
  smartui capture urls.json --config smartui-web.json --fetch-results results.json
  ```
- Modern browser (Chrome, Firefox, Edge, Safari)

[Back to top](#📚-table-of-contents)

## 🚀 Installation

Clone and open locally:

```bash
git clone https://github.com/vijopv83/LambdaTestSmartUIReporter.git
cd LambdaTestSmartUIReporter
open index.html
```

[Back to top](#📚-table-of-contents)

## 🌐 Online Demo

No setup, view live on GitHub Pages:

[https://vijopv83.github.io/LambdaTestSmartUIReporter/](https://vijopv83.github.io/LambdaTestSmartUIReporter/)

[Back to top](#📚-table-of-contents)

## 💡 Usage Examples

Load your JSON and run through the UI:

```bash
# Upload your results file
# Explore dashboard filters
# Click Export CSV or Export All Views (PDF)
```

[Back to top](#📚-table-of-contents)

## ⚙️ Configuration

- Toggle dark/light mode via the 🌙 button.
- Load sample files (`LTResults.json` / `LTSmartIgnoreResults.json`) from the dropdown.

[Back to top](#📚-table-of-contents)

## 🗂️ File Structure

```
├── LTSmartUIReporter.html    # Main UI
├── LTResults.json            # Sample results
├── LTSmartIgnoreResults.json # Ignore results sample
├── screenshot.gif            # Demo animation
└── favicon.ico               # Icon
```

[Back to top](#📚-table-of-contents)

## 🤝 Contributing

We welcome your contributions!

- ⭐ Star the repo to show your support
- 🔎 Check existing [issues](https://github.com/vijopv83/LambdaTestSmartUIReporter/issues)
- ➕ Submit new issues using our [issue templates](https://github.com/vijopv83/LambdaTestSmartUIReporter/tree/main/.github/ISSUE_TEMPLATE)
- 📦 Fork the project, make your changes, and open a Pull Request

[Back to top](#📚-table-of-contents)

## 📈 Roadmap

Planned enhancements:

- 🌐 Multi-language support for localization
- 📊 Advanced analytics dashboard

[Back to top](#📚-table-of-contents)

## 📝 Changelog

See [CHANGELOG.md](https://github.com/vijopv83/LambdaTestSmartUIReporter/blob/main/CHANGELOG.md) for release notes and version history.

[Back to top](#📚-table-of-contents)

## **Questions and Support**

Got feedback, ideas, or need help?

Feel free to reach out on [LinkedIn](https://www.linkedin.com/in/vijopv83/), happy to connect!

[Back to top](#📚-table-of-contents)

## 🔑 Licence

MIT © [Vijo Varghese](https://github.com/vijopv83)
