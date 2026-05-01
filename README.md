# BPL4DWP — BPL Files for the Delphi Welcome Page Plugin

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE)
[![Delphi](https://img.shields.io/badge/Delphi-11%20%7C%2012%20%7C%2013-red.svg)](https://www.embarcadero.com/products/delphi)
[![Maintainer](https://img.shields.io/badge/Maintainer-gkobler-informational.svg)](https://github.com/gkobler)

---

This repository provides the compiled **BPL files** (Borland Package Library) for the **Delphi Welcome Page Plugin** by [dwp.gksoft.ch](https://dwp.gksoft.ch). The BPL files are synchronized and versioned here so they can be downloaded and installed into Delphi / RAD Studio in a straightforward and traceable way.

> The plugin itself is developed and maintained at [dwp.gksoft.ch](https://dwp.gksoft.ch).  
> This repository contains **only the compiled BPL files** — no plugin source code.

---

## Table of Contents

- [Versionshistorie](#Versionhistory)
- [About the Plugin](#about-the-plugin)
- [Supported Delphi Versions](#supported-delphi-versions)
- [Installation](#installation)
- [Updating to a New Version](#updating-to-a-new-version)
- [Known Limitations](#known-limitations)
- [License](#license)

---

## Versionhistory
[Versionshistorie](Versionhistory.md)


## About the Plugin

The **Delphi Welcome Page Plugin** by gksoft extends the Welcome Page of Delphi 11 Alexandria and later. It allows you to customize the layout of the Welcome Page and provides a convenient starting point for your projects directly when the IDE launches.

- 🔧 Customizable Welcome Page layout via the built-in layout editor
- 💾 Settings are stored in the **Windows Registry**
- 🔄 Backup and restore supported via the standard Delphi **migration tool**
- 📦 Distributed as a single BPL file — no complex installation required

---

## Supported Delphi Versions

BPL files are provided separately for each Delphi version. The version number in the filename corresponds to the Delphi internal version:

| Filename                     | Delphi Version               |
|------------------------------|------------------------------|
| `WP.gksoftPlugin280.bpl`     | Delphi 11 Alexandria         |
| `WP.gksoftPlugin290.bpl`     | Delphi 12 Athens             |
| `WP.gksoftPlugin370.bpl`     | Delphi 13 / RAD Studio 13    |

---

## Installation

> ⚠️ **RAD Studio / Delphi must be closed during installation.**

1. Download the BPL file matching your Delphi version from this repository.
2. Copy the BPL file to the directory (e.g. `C:\Users\Public\Documents\Embarcadero\Studio\37.0\Bpl\`).
3. Open Delphi and go to **Component → Install Packages**.
4. Click **Add** and select the downloaded `.bpl` file.
5. The plugin will appear in the component list and is now active.
6. You can start customizing the Welcome Page layout right away.

---

## Updating to a New Version

Updating is straightforward:

1. **Close Delphi.**
2. **Overwrite** the existing BPL file with the new version from this repository (same path, same filename).
3. Start Delphi — the plugin will load the new version automatically.

> It is **not** necessary to uninstall the plugin or re-add it to the component list.

---

## Known Limitations

- Editing the Welcome Page with the layout editor may trigger a known issue → **RSP-38956** (Embarcadero bug tracker).
- When upgrading to a new major Delphi version, the matching BPL file for the new IDE version must be installed.

---

## Further Links

- 🌐 **Plugin website:** [dwp.gksoft.ch](https://dwp.gksoft.ch)
- 🏢 **Developer:** [G. Kobler Automatisierung & Industriesoftware](https://www.gksoft.ch)
- 💬 **Community discussion:** [Delphi-PRAXiS – Welcome Page Plugin](https://en.delphipraxis.net/forum/42-delphi-welcome-page-plugin/)

---

## License

This repository is licensed under the [Apache License 2.0](LICENSE).  
The plugin itself is subject to the terms of use of [dwp.gksoft.ch](https://dwp.gksoft.ch).
