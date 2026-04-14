# REGISTRY

A minimalist, serverless activity tracker.

## Overview
**Single-File Architecture:** Built entirely within a single HTML file for maximum portability and speed.

**Local Storage:** No external database or server. All data is stored directly in your browser's local cache.

**Dynamic Schema:** Create and edit custom activity types with specific metrics.

**Data Lifecycle:** Built-in tools for exporting backups and a mapping tool for importing external CSV data.

## Setup & Installation
The app is designed as a **Progressive Web App (PWA)**:
1. **Mobile Install:** Access the URL on your mobile browser.
1. **Add to Home Screen:** Use your browser's "Add to Home Screen" feature to install the app as a standalone utility.

## Functionality
**Logging** 

Select an activity type and input required metrics to commit a new entry.

**System Analytics** 

Visualize data via a 14-day rolling SVG graph. Filter by activity type or specific metrics to track performance trends.

**Customization** 

Use the configuration panel to manage the registry's internal structure:
* **Schema Engine:** Define new protocols, edit existing attributes, or delete types.
* **System Purge:** Wipe all local records and schemas.

**History** 

View entries in the scrollable log feed. Filter the feed by activity type to isolate specific records.

**Import/Export** 

Ensure data continuity by exporting your history as a `.csv` file. The import tool includes a configuration step to map date/type fields and select specific columns to preserve.

## Maintenance
**Backups** 

Because data is stored locally in the browser, it is recommended to export your data regularly.

**Clearing Cache** 

Clearing your browser's site data will remove your history. Always ensure you have a recent export before performing system maintenance.
