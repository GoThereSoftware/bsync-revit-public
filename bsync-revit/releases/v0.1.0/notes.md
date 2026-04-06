# BlenderSync for Revit — Initial Release

This is the first public release of BlenderSync for Revit.

## Highlights

- Install BlenderSync with a dedicated Windows setup application that discovers supported Revit installs and guides you through setup.
- Connect Revit to your BlenderSync server from inside Revit by choosing a sync view and configuring the server host and port.
- Sync changed model content from Revit to Blender, or sync only the elements you currently have selected.
- Capture Blender objects back into Revit as reusable families, making round-trip workflows possible.
- Start and stop LiveSync for faster iteration between Revit and Blender during active work sessions.

## Included in this release

- Support for Revit `2023`, `2024`, and `2025`.
- A `BlenderSync` ribbon tab in Revit with `Setup`, `License`, `Beta`, `About`, and `Report Issue` tools.
- Manual sync commands for `Changes`, `Selected`, and `Capture` workflows.
- Built-in connection checking so you can verify that the BlenderSync server is reachable before syncing.
- Log files for both the installer and the Revit add-in to make troubleshooting easier.

## Important notes

- Sync, capture, and LiveSync workflows depend on a reachable BlenderSync server.
- Some features require an active license.
- The public installer is a single setup executable for Windows.
- During installation, you choose which supported Revit versions should receive the add-in.

## Getting started

- Run the BlenderSync setup application on Windows.
- Open Revit and go to the `BlenderSync` ribbon tab.
- Open `Setup`, choose the sync view for your document, and enter the BlenderSync server host and port.
- Use `Check connection` to confirm the server is responding.
- Start with `Changes` for a document-wide update, `Selected` for targeted updates, or `Capture` when bringing Blender objects back into Revit.

## Support

- Use `Report Issue` in the `BlenderSync` ribbon to send problem details to support.
- Include screenshots, reproduction steps, and relevant log files when reporting issues.
- Revit session logs are stored under `%LOCALAPPDATA%\GoThereSoftware\BsyncRevit\Logs`.
- Installer logs are written to `%TEMP%`.