# Google Maps CSV Exporter

A lightweight, local-first Manifest V3 Chrome extension that exports visible Google Maps business search results into a clean, spreadsheet-ready `.csv` file in one click.

## Features

- **100% Local Processing:** Runs directly in your browser using `activeTab` and `scripting` permissions. No external servers, no tracking, and no account required.
- **11 Structured Columns:** Extracts `Rank`, `Name`, `Category`, `Rating`, `Reviews`, `Phone`, `Website`, `Address`, `Maps URL`, `Search Query`, and `Export Date`.
- **Spreadsheet-Safe Output:** Escapes commas/quotes properly and prevents CSV formula injection for clean imports into Excel, Google Sheets, and Airtable.
- **Automatic Deduplication:** Filters out duplicate place URLs automatically.
- **Timestamped Filenames:** Saves exports using the search query and timestamp so previous files are never overwritten.

## How to Use

1. Open [Google Maps](https://www.google.com/maps) and search for any local business category or location.
2. Scroll down the results panel to load the listings you want to capture.
3. Click the **Google Maps CSV Exporter** icon in your Chrome toolbar and click **Export Visible Results**.

## Privacy

This extension does not collect, store, or transmit any user data. Read the full [Privacy Policy](https://robsoza.github.io/google-maps-csv-exporter/privacy-policy.html).
