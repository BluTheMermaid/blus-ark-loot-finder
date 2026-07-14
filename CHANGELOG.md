# Changelog

## v1.0.1
This update focuses on smoothing out a few early issues, especially around the portable run scripts and launcher behavior.

> The Windows `.exe` installer should update an existing installation normally.
> If it does not, uninstall the older version manually from **Settings > Apps**, then run the installer again.

### Added:
- Home page now shows a notice when a newer release is available.
- Added an in-app changelog page accessible from the version info in the navigation drawer.
- Improved search fields with clear buttons, a search icon, and small UI polish.

### Changed:
- The portable ZIP now includes a versioned `.jar` filename.

### Fixed:
- Improved portable launcher behavior on Windows and Linux/macOS.
- Browser now opens only after the app is ready.
- Launcher now exits the running app process correctly.
- Portable launchers can handle an existing process already using port `8080`.
- External links now open correctly from the desktop app.

## v1.0.0

Initial public release of Blu's ARK Loot Finder.

### Added:
- Search for loot items to discover which loot sources can drop them.
- View drop chances and quality ranges for each loot source.
- Browse Genesis: Part 1 mission loot tables.
- Search missions directly by name.
- View Hexagon rewards for Gamma, Beta, and Alpha mission difficulties.
- Display item and mission information with links to the corresponding ARK Wiki pages.
- Desktop application for Windows, including installer and portable version.
