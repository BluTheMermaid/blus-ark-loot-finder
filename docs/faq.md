# FAQ

## What is Blu's ARK Loot Finder?

It is a desktop/web-backed application for exploring ARK mission loot by item or by mission.

## Does it require an internet connection to browse loot?

Not for normal use after the packaged app is built. The loot dataset is bundled with the application.

## What is the difference between the installer and the ZIP?

- The installer is the normal Windows desktop installation.
- The ZIP is a portable bundle that runs the packaged application jar directly.

## Does the portable ZIP need Java?

Yes. The launch scripts check for Java 21 or newer.

- On Windows, the `.bat` launcher can prompt to install Java 21 via `winget`.
- On Unix-like systems, the `.sh` launcher can attempt `brew` or `apt-get`, depending on what is available.

## Why does the browser open automatically?

The portable launchers open `http://127.0.0.1:8080` in your browser before starting the bundled application jar.

## Where does the loot data come from?

From the ARK Official Community Wiki:

- <https://ark.wiki.gg/>

See `ATTRIBUTIONS.md` for details.

## Is this application official?

No. It is a separate tool built around publicly available ARK wiki data.

## What if Java install is declined or fails in the portable launcher?

Install Java 21 or newer manually, then run the launcher again.

## What if the app does not start?

Check:

- Java 21+ is installed if using the ZIP
- local machine policy allows running the script
- no other process is already occupying `127.0.0.1:8080`
