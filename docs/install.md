# Installation

## Windows installer

1. Download `BlusArkLootFinder_<version>_setup.exe` from the release.
2. Run the installer.
3. Start the app from the installed shortcut.

## Portable ZIP

1. Download `BlusArkLootFinder_<version>.zip` from the release.
2. Extract it to a folder of your choice.
3. Run one of the launchers:

### Windows

- `run-BlusArkLootFinder.bat`

### macOS / Linux

- `run-BlusArkLootFinder.sh`

## Java requirement for ZIP mode

The portable ZIP launchers require Java 21 or newer.

### Windows

If Java is missing, the batch launcher prompts whether it should install Microsoft OpenJDK 21 using `winget`.

### macOS / Linux

If Java is missing, the shell launcher prompts whether it should try an installation using:

- `brew install openjdk@21`
- or `apt-get install openjdk-21-jre`

If automatic install is declined or unavailable, install Java 21 manually and rerun the launcher.
