<div align="center">

<!-- Header with left text and right logo -->
<div style="display: flex; align-items: center; justify-content: space-between; width: 100%;">
  <div style="text-align: left;">
    <strong style="font-size: 1.2em;">The Universal Container</strong><br>
    <strong style="font-size: 1em;">Mantra:</strong> Bind folders & files to tables & records.<br>
    <strong style="font-size: 1em;">Tagline:</strong> Files close to data.
  </div>
  <div>
    <img src="https://www.protee.org/images/wob_Boxes/wob_Boxes.png" alt="wob_Boxes Logo" width="120" style="border-radius: 12px;">
  </div>
</div>

<!-- Title and badges -->
# wob_Boxes

[![4D Component](https://img.shields.io/badge/4D-Component-blue)](#)
[![4D Pop](https://img.shields.io/badge/4D-Pop-blue)](#)
[![License: Commercial](https://img.shields.io/badge/License-Commercial-red.svg)](#license)
[![Platform: macOS & Windows](https://img.shields.io/badge/Platform-macOS%20%7C%20Windows-lightgrey)](#)
[![4D v21+](https://img.shields.io/badge/4D-v21%2B-brightgreen)](#)

</div>

## Overview

wob_Boxes provides a managed, Dropbox-like repository for files, without storing them in the database as BLOBs. It offers a structured hierarchy for file storage at the global, table, and individual record levels, keeping your database lean and efficient while providing a familiar file management interface for users.[reference:0][reference:1]

## Key Features

- **Structured File Repository**: A root folder on the server is designated for all file storage. `wob_Boxes` then creates a structured hierarchy for global files, table-specific files, and individual record-specific files.[reference:2]
- **Client-Server Interface**: Generic widgets are provided for easy placement on any form. These widgets open a Finder-like interface, allowing users to drag & drop files, view, organize, and recover files stored in their dedicated boxes.[reference:3]
- **Programmatic Access**: Low-level methods enable server-side automation. You can programmatically retrieve files (`Get file from Box`), save files (`Save file to Box`), and use them for automated tasks like attaching files to outgoing emails.[reference:4]
- **Technical Foundation**: The entire system is built on robust, standard POSIX paths and utilizes 4D's built-in `File` and `Folder` classes for reliable cross-platform operation.[reference:5]
- **Widget Integration**: The resizable widget displays the file count of the related folder. On click, it opens a form in a separate process, providing a bounded view of this folder. The widget's file count is automatically updated when the contents of the opened `ogBox` are modified.[reference:6]
- **Key Benefits**:
  - **Database Efficiency**: Keeps user files out of the database, maintaining optimal performance and size.[reference:7]
  - **Ease of Use**: Provides a familiar, intuitive file browser experience anywhere in your application.[reference:8]
  - **Flexibility**: Offers structured storage at the global, table, and individual record levels.[reference:9]
  - **Powerful Automation**: Supports both user interaction and fully programmed file management.[reference:10]
- **Multi-Language Support**: Fully localized in **English (EN)**, **French (FR)**, **Spanish (ES)**, and **German (DE)**.[reference:11]

---

## Installation & Dependencies

### Prerequisites
- **4D v21** or higher (Project mode recommended).
- [**wok_Krolific**](https://github.com/protee/wok_Krolific) – Licensing component (mandatory dependency).
- [**wox_Xlibrary**](https://github.com/protee/wox_Xlibrary) – Core utilities (mandatory dependency).
- [**woc_Colours**](https://github.com/protee/woc_Colours) – Color management engine (mandatory dependency).
- The [**SVG with Classes**](https://github.com/vdelachaux/SVG-with-Classes) must be available in your project.

### Installation via Dependencies Manager (GitHub)

Starting with 4D v21, the recommended way to install wob_Boxes (and any ogTools component) is through the **Dependencies Manager** using the **GitHub repository**:

1. In your 4D project, open the **Dependencies Manager** (`Project > Dependencies`).
2. Click the `+` button and select **Add a dependency from a Git URL**.
3. Enter the following Git URL:  
   `protee/wob_Boxes`
4. Choose the desired version (e.g., `main`, `latest`, or a specific release tag).
5. Confirm the installation – the component will be automatically fetched from GitHub, placed in the `Components` folder, and linked to your project.

> **Note**: For team development, commit the dependency configuration file (`dependencies.json`) to your source control so all team members automatically fetch the same version from GitHub.

---

## ogTools Suite – Dependencies

wob_Boxes is the file repository pillar of the comprehensive **ogTools suite** – an integrated development ecosystem for 4D. Other key components include:

| Icon | Component | Description |
|------|-----------|-------------|
| <img src="https://www.protee.org/images/wok_Krolific/wok_Krolific.png" alt="wok_Krolific Logo" width="60" style="border-radius: 12px;"> | **wok_Krolific** | License manager. |
| <img src="https://www.protee.org/images/wox_Xlibrary/wox_Xlibrary.png" alt="wox_Xlibrary Logo" width="60" style="border-radius: 12px;"> | **wox_Xlibrary** | Core utilities for everyday development tasks. |
| <img src="https://www.protee.org/images/woc_Colours/woc_Colours.png" alt="woc_Colours Logo" width="60" style="border-radius: 12px;"> | **woc_Colours** | Advanced, indexed color management engine. |

## License

wob_Boxes is a **commercial component** and is part of the paid ogTools suite. A valid license is required for use. For licensing options and trial requests, please contact the sales team directly.

---

## Localization

wob_Boxes supports the following languages out‑of‑the‑box:

- 🇺🇸 English (EN), 🇫🇷 French (FR), 🇪🇸 Spanish (ES), 🇩🇪 German (DE)
- More on demand

Localization affects error messages, UI prompts, and built‑in pane texts.

---

## Support & Resources

- **Official Website**: [https://www.protee.org](https://www.protee.org)
- **Documentation**: Full documentation and HDI (Host Database Interface) demos are included with your purchase.

For direct inquiries:
- **Email**: [og@protee.org](mailto:og@protee.org)
- **Phone**: +33 6 3718 5941

---

## About the Creator

wob_Boxes and the ogToolsSuite are developed by **Protée sarl**, a company with over 30 years of expertise in 4D development. Led by Olivier Grimbert, the team focuses on delivering high‑quality, production‑grade tools that enhance developer productivity and application reliability.

---

<div align="center">
  <sub>Built with ❤️ for the 4D community by Protée sarl. © 2016 - Present</sub>
</div>