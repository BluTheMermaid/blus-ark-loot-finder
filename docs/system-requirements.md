# System Requirements

## Installer build target

The packaged installer currently targets Windows x64.

## Portable ZIP

The portable ZIP requires:

- Java 21 or newer

## Runtime behavior

The portable launcher starts the application locally and opens:

- `http://127.0.0.1:8080`

## Notes

- The application uses a local in-memory H2 database at runtime.
- Loot data is bundled into the application build.
- The application currently focuses on `Genesis: Part 1` mission loot.
