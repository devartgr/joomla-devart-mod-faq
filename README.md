# DevArt FAQ for Joomla

![Joomla](https://img.shields.io/badge/Joomla-6.x-blue)
![PHP](https://img.shields.io/badge/PHP-8.2%2B-green)
![License](https://img.shields.io/badge/License-GPLv3-red)
![Version](https://img.shields.io/badge/Version-1.0.2-orange)

Lightweight modern FAQ accordion module for Joomla 6.

Create clean, responsive and SEO-friendly FAQ sections using Joomla articles, custom FAQ items, or mixed FAQ content.

ΙMPORTANT — Product consolidation (August 2026)
DevArt FAQ has been integrated into DevArt Elements as the FAQ element type (Navigation → FAQ), within the Elements component and site module workflow.
This standalone listing is no longer maintained. New features, fixes, and Joomla updates are released only through DevArt Elements (pkg_devartelements).
Existing DevArt FAQ module installations may continue to work on supported Joomla versions, but we recommend planning a move to DevArt Elements for ongoing support and future FAQ, accordion, tabs, and related content blocks in one package.
For new sites, install DevArt Elements instead of this standalone FAQ package.
---

## Latest Release

**Version:** 1.0.2

### Highlights

- Joomla Extensions Directory compliance maintenance release
- Improved XML manifest compatibility
- Improved package consistency for release distribution
- Added missing compliance metadata
- No frontend functionality changes

---

## Overview

DevArt FAQ is a lightweight Joomla 6 module for creating modern FAQ accordion sections.

It is designed for websites that need clean, fast, accessible and SEO-friendly FAQ blocks without heavy frontend dependencies.

The module supports both Joomla Articles and custom FAQ items, allowing administrators to build flexible FAQ sections directly from the module settings.

---

## Features

- Joomla 6 native module
- Mixed FAQ Builder
- Joomla Article integration
- Custom FAQ items
- Native Joomla Article Picker
- Responsive accordion layout
- FAQ Schema JSON-LD support
- Read More support for long article answers
- Color presets and custom color controls
- Mobile-friendly frontend
- Scoped CSS to reduce template conflicts
- Lightweight optimized package
- No jQuery
- No Bootstrap dependency
- Optional module caching support
- GitHub-based Joomla Update Server integration
- GPL Open Source

---

## Core Functionality

### FAQ Builder

Create FAQ sections using:

- Joomla Articles
- Custom Questions and Answers
- Mixed FAQ content in the same module

---

### Accordion Frontend

- Lightweight native JavaScript accordion
- Responsive layout
- Accessible toggle behavior
- Clean modern styling
- Keyboard-friendly interaction

---

### SEO Support

- FAQPage JSON-LD Schema
- Search engine friendly structure
- Optional Read More links
- Article-based FAQ output support

---

### Display Controls

- Default or custom colors
- Accordion styling options
- Open first item option
- Maximum answer length controls
- Optional content stripping controls

---

## Designed For

- News websites
- Editorial portals
- Business websites
- Product FAQs
- Help sections
- Documentation pages
- High-traffic Joomla sites

---

## Installation

1. Download latest release ZIP
2. Go to Joomla Administrator:

`System → Extensions → Install`

3. Upload:

`mod_devartfaq_v1.0.2.zip`

4. Open:

`Content → Site Modules → DevArt FAQ`

or search for:

`DevArt FAQ`

---

## Joomla Native Updates

DevArt FAQ supports Joomla native updates via GitHub.

Update server:

`https://raw.githubusercontent.com/devartgr/joomla-devart-mod-faq/main/update.xml`

After installation, future updates are available from:

`System → Extensions → Update`

---

## Requirements

- Joomla 6.x
- PHP 8.2+

---

## Security

- Joomla entry point protection
- Safe output escaping
- Filtered FAQ rendering
- SQL-safe article loading
- No external JavaScript libraries
- No unsafe script execution
- No remote dependencies
- GPL headers across PHP files
- JED-ready manifest metadata

---

## Performance

- Lightweight frontend output
- No jQuery dependency
- No Bootstrap dependency
- Native JavaScript accordion
- Scoped CSS
- Efficient article loading
- Optional Joomla module caching support

---

## Current Version

**1.0.2**

---

## Changelog 1.0.2

### Fixed

- Fixed Joomla Extensions Directory compliance metadata issues
- Added missing author email metadata
- Added LICENSE.txt manifest reference
- Fixed package structure consistency issues

### Improved

- Improved XML manifest compatibility
- Improved release package consistency
- Retained Joomla native update compatibility

---

## Changelog 1.0.1

- Added `declare(strict_types=1);` across PHP files
- Improved PHP 8.2+ consistency
- Improved long-term maintainability
- Added GPL license headers across PHP files for Joomla Extensions Directory compliance
- Verified XML manifest license metadata
- Cleaned production package metadata
- No frontend behavior changes

---

## Changelog 1.0.0

- Initial public release of DevArt FAQ for Joomla 6
- Added mixed FAQ builder with support for Joomla Articles and Custom FAQ items
- Added native Joomla article picker integration
- Added responsive FAQ accordion frontend layout
- Added FAQ Schema JSON-LD support
- Added optional Read More links for truncated article answers
- Added color presets and custom color controls
- Added module caching support
- Added administrator header banner and DevArt branding footer
- Added Disclaimer / Limitation of Liability section in module settings

---

## License

GNU General Public License v3 or later

---

## Developer

**Stathopoulos Kostas – DevArt**  
https://devart.gr

GitHub Repository:

https://github.com/devartgr/joomla-devart-mod-faq

---

## Roadmap

Possible future improvements:

- Additional accordion styles
- Search and filtering
- Category grouping
- Advanced typography controls
- Optional plugin integration

---

## Disclaimer / Limitation of Liability

This software is provided "as is", without warranty of any kind.

DevArt shall not be held liable for any damages, data loss, downtime, security issues, or other problems resulting from the use or misuse of this software.

Users are responsible for testing the software in their own environment and maintaining proper backups before installation or upgrades.

Always test on a staging environment before using in production.
