# Syncfusion JavaScript Pivot Table – Virtual Scrolling Example

This sample demonstrates **Virtual Scrolling** in the [Syncfusion JavaScript Pivot Table](https://ej2.syncfusion.com/documentation/pivotview/getting-started) component. Virtual scrolling helps you handle **large datasets efficiently** by loading rows and columns on demand as you scroll, instead of rendering all data at once.

## 📖 Overview

The Pivot Table is a powerful tool for summarizing and analyzing data. When working with thousands of records, rendering everything at once can slow down performance. **Virtual Scrolling** solves this by:

- Loading only the visible rows and columns.
- Fetching additional data dynamically as you scroll.
- Keeping the UI responsive even with large datasets.

In this example:

- We use a **large client-side data source** with fields like `ProductID`, `City`, `Year`, `CustomerName`, `Sold`, and `InStock`.
- Virtual scrolling is enabled using the `enableVirtualization` property.
- The layout includes rows, columns, values, and filters similar to a standard Pivot Table.

## 🛠 Prerequisites

- A modern browser (Chrome, Firefox, Edge)
- [Node.js](https://nodejs.org/) (optional, for running a local server)

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Sridhar-Karunakaran/virtual-scrolling-in-pivot-table
   ```

2. **Install dependencies (optional):**
   ```bash
   npm install
   ```

3. **Run the application:**
   ```bash
   npm start
   ```
   This launches the app in your default browser using **browser-sync**.

4. Alternatively, open `Virtual_Scrolling.html` directly in your browser.

## ✅ Key Features

- **High-performance rendering** of large datasets
- **Instant loading** of up to 1 million records
- **Smooth scrolling** using virtual rendering
- **No external dependencies** – runs in the browser

## 📂 Project Structure

- `Virtual_Scrolling.html` – Main sample file with PivotView configuration.
- `styles.css` – Optional custom styles.
- `package.json` – Scripts and dependencies.

## 📚 Learn More

- [Pivot Table Documentation](https://ej2.syncfusion.com/documentation/pivotview/getting-started)
- [Pivot Table Demos](https://ej2.syncfusion.com/demos/#/tailwind3/pivot-table/overview)

## 💬 Support

For questions or feedback, visit the [Syncfusion Support Portal](https://support.syncfusion.com) or [Community Forums](https://www.syncfusion.com/forums).

## 📜 License

This is a commercial product and requires a valid Syncfusion license.  
[View License Terms](https://www.syncfusion.com/license/studio/22.2.5/syncfusion_essential_studio_eula.pdf).
