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

How to run it:

1. Extract the ZIP fully before starting the app.
2. Open the extracted folder.
3. Double-click `run-BlusArkLootFinder.bat`.

If Windows shows a security warning, allow the file to continue.

If the app starts but your browser does not open automatically, open:

- `http://127.0.0.1:8080`

### macOS / Linux

- `run-BlusArkLootFinder.sh`

How to run it:

1. Extract the ZIP fully before starting the app.
2. Open a terminal in the extracted folder.
3. Run:

```bash
chmod +x run-BlusArkLootFinder.sh
./run-BlusArkLootFinder.sh
```

If double-clicking the file does nothing in your file manager, use the terminal command above instead.

If the app starts but your browser does not open automatically, open:

- `http://127.0.0.1:8080`

## Java requirement for ZIP mode

The portable ZIP launchers require Java 21 or newer.

### Windows

If Java is missing, the batch launcher prompts whether it should install Microsoft OpenJDK 21 using `winget`.

### macOS / Linux

If Java is missing, the shell launcher prompts whether it should try an installation using:

- `brew install openjdk@21`
- or `apt-get install openjdk-21-jre`

If automatic install is declined or unavailable, install Java 21 manually and rerun the launcher.
