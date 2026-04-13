# REGISTRY

A minimalist, serverless activity tracker.

## Overview
**Single-File Architecture:** Built entirely within a single HTML file for maximum portability and speed.

**Local Storage:** No external database or server. All data is stored directly in your browser's local cache.

**Dynamic Schema:** Create custom activity types with specific metrics.

**Data Lifecycle:** Built-in tools for importing CSV data and exporting backups for long-term storage.

## Setup & Installation
The app is designed as a **Progressive Web App (PWA)**:
1. **Mobile Install:** Access the URL on your mobile browser.
1. **Add to Home Screen:** Use your browser's "Add to Home Screen" feature to install the app as a standalone utility.

## Functionality
**Logging** 

Select an activity type and input required metrics to commit a new entry.

**Customization** 

Use the "Define New Activity" section to add new categories (e.g., `Yoga` with metrics `Minutes, Intensity`).

**History** 

View your most recent entries in the scrollable log feed.

**Import/Export** 

Ensure data continuity by exporting your history as a `.csv` file. To sync across devices, export from one and import to the other.

## Maintenance
**Backups** 

Because data is stored locally in the browser, it is recommended to export your data regularly.

**Clearing Cache** 

Clearing your browser's site data will remove your history. Always ensure you have a recent export before performing system maintenance.
