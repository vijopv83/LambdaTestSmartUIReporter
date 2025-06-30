# 📊 LambdaTest SmartUI Report Viewer

An interactive, client-side HTML report viewer for [LambdaTest Smart UI](https://www.lambdatest.com/visual-regression-testing) visual regression test results.

Check out the [LambdaTest Smart UI] https://vijopv83.github.io/LambdaTestSmartUIReporter/LTSmartUIReporter.html GitHub Pages to explore it in action."

---

## 🚀 Quick Start

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/LTSmartUIReporter.git
   cd LTSmartUIReporter
   ```

2. **Run your Smart UI test command**  
   ```bash
   smartui capture urls.json --config smartui-web.json --fetch-results
   ```

3. **Launch the report viewer**  
   - Open `LTSmartUIReporter.html` in your favorite browser.

4. **Upload JSON results**  
   - Click **Upload JSON** and select the Smart UI JSON response.  
   - Your visual test report is generated dynamically!

---

## ✨ Key Features

- **Dynamic Filtering**: Instantly filter results by **Page**, **Browser**, and **Resolution**.  
- **Multiple Diff Types**: Choose between **Compared Image**, **Captured Diff**, or **Baseline Diff** (auto-detected).  
- **Dark Mode**: Toggle between light and dark themes for day/night testing.  
- **PDF Export**: Export all browser-resolution comparisons at once for offline review.  
- **Offline-First**: Pure HTML/JS—no server or backend required.  
- **Sticky Header**: Always have controls accessible while scrolling.  
- **Responsive Layout**: Automatically adapts to different viewport sizes.

---

## ⚙️ Functionality Details

1. **Dashboard View**  
   - **Page Selector**: Lists all tested page names.  
   - **Browser Selector**: Shows browsers with test data for the selected page.  
   - **Resolution Selector**: Displays available viewport sizes for the chosen page/browser.  
   - **Summary Table**: Clickable rows open the detailed comparison view.

2. **Detail View**  
   - **Three-Panel Layout**: Side-by-side **Baseline**, **Captured**, and **Diff** images.  
   - **Diff Dropdown**: Dynamically lists available diff image types from JSON.  
   - **Back Button**: Returns to the Dashboard without reloading.

3. **Export to PDF**  
   - Collects all combinations (`browser × resolution`) for the current page.  
   - Preloads images to ensure a complete PDF snapshot.  
   - Opens the print dialog, ready-to-export all comparisons.

4. **Customization**  
   - **Configuration**: Easily tweak colors, fonts, and layout via CSS variables in the `<style>` block.  
   - **Extensibility**: Single-page JS code—add new filters or export formats with minimal effort.

---

## 🛠️ Development

- **HTML/CSS/JS**: Vanilla, no frameworks—straightforward to understand and extend.  
- **Modular Functions**:  
  - `renderSummaryTable()`  
  - `filterSummaryTable()`  
  - `populateDropdowns()`  
  - `renderImages()`  
  - `exportAllPDF()`  
  - `toggleDarkMode()`  

- **Use Cases**:  
  - Integrate into CI pipelines to visualize Smart UI results.  
  - Share interactive test reports with non-technical stakeholders.  
  - Quickly identify visual regressions across browsers and viewports.

---

## 🪪 License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.
