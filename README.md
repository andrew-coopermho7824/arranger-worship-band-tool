# Arranger v3.4 - Worship Band Arrangement Tool 2026

> **Arranger is a web-based planning tool for worship bands that helps map songs, build setlists, and produce readable arrangement references with version 3.4.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v3.4-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/andrew-coopermho7824/arranger-worship-band-tool?style=flat-square)](https://github.com/andrew-coopermho7824/arranger-worship-band-tool)

---

<p align="center">
  <a href="https://andrew-coopermho7824.github.io/arranger-worship-band-tool/">
    <img src="https://img.shields.io/badge/Download-Arranger%20Latest-brightgreen?style=for-the-badge" alt="Download Arranger">
  </a>
</p>

> **[Download Arranger v3.4](https://andrew-coopermho7824.github.io/arranger-worship-band-tool/)**

---

[Download Latest Build](https://andrew-coopermho7824.github.io/arranger-worship-band-tool/)

---

## What Arranger Does

Arranger turns worship song concepts into usable visual arrangement plans. Define the sections of a song, specify what each instrument does, and examine the finished layout in a format suited to rehearsals, preparation, or live performance reference.

A plan can include as many as eight instruments. The same arrangement is available through diagram, flowchart, icon score, and text-list views. Arranger is distributed as one HTML file, so it can run offline without a separate installation.

---

## Highlights

- Create visual maps of song sections and arrangement layers.
- Choose instruments and playing styles for individual song parts.
- Build arrangements containing up to eight instruments.
- Move sections into a new order or duplicate them while shaping the song.
- Switch between diagram, flowchart, icon score, and text-list presentations.
- Keep arrangements in browser `localStorage`.
- Exchange arrangement data through JSON import and export.
- Produce CSV or PNG exports from an arrangement.
- Print A4 icon scores or save those scores as PDF.
- Use the single-file application offline in a modern web browser.

---

## Getting Started

Arranger works without a package manager and does not need an application installer.

### Download and open

1. Visit the [latest build](https://andrew-coopermho7824.github.io/arranger-worship-band-tool/).
2. Save the HTML file locally for offline access.
3. Open the saved file in a modern web browser.

### Get the source with Git

```bash
git clone https://github.com/andrew-coopermho7824/arranger-worship-band-tool.git
cd REPO
```

After cloning, open the Arranger HTML file directly in your browser. Its single-file design supports offline operation.

---

## Working with Arrangements

A common workflow looks like this:

1. Launch Arranger in a web browser.
2. Start a new arrangement or load an existing one.
3. Add the sections needed for the song.
4. Duplicate and reorder sections until the full structure is in place.
5. Define the instruments and playing styles for every section.
6. Inspect the result in diagram, flowchart, icon score, or text-list mode.
7. Save the work in the browser or export it for sharing and reference.

### Import and export

JSON is the appropriate format for keeping an arrangement editable and moving it between sessions:

- Export the active arrangement as JSON.
- Import a JSON file into another Arranger session.
- Choose CSV for a table-oriented version of the arrangement.
- Create a PNG or print an icon score for visual reference.

---

## Storage and Configuration

Saved arrangements are held in the browser's `localStorage`. Arranger has no separate configuration file and does not require server setup.

For backups that can be carried between sessions, use JSON export. JSON imports can restore arrangements in another browser session. CSV, PNG, and PDF files are available for sharing, review, and printed reference use.

---

## Requirements

- A modern web browser.
- Permission to open the HTML file locally for offline use.
- No additional runtime or installation package.
- Enabled browser storage for saved arrangements.
- Optional disk space for JSON, CSV, PNG, and PDF exports.

---

## Frequently Asked Questions

### Must Arranger be installed?

No. The application is a single HTML file and can be opened directly in a web browser.

### Is offline use supported?

Yes. Once the HTML file has been obtained, Arranger is intended to work without an internet connection.

### What is the instrument limit?

An arrangement can contain up to eight instruments.

### Where does Arranger save my arrangements?

The application stores saved arrangements in the browser's `localStorage`.

### How do I transfer an arrangement to another browser?

Export it as a JSON file, then import that file into the Arranger session running in the other browser.

### What files can Arranger create?

The available exports are JSON, CSV, and PNG. Icon scores may also be printed on A4 paper or saved as PDF.

### What if my saved arrangement is missing?

Confirm that browser storage is enabled and that you are using the original browser profile. Export important arrangements as JSON to keep portable backups.

### Where can I find the newest version?

Open the [latest build](https://andrew-coopermho7824.github.io/arranger-worship-band-tool/) to use the currently published version.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
