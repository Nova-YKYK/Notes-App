# Notes

A simple, fast, and lightweight notes app for Windows. Keep your notes organised in a clean sidebar, find what you need with built-in search, and let automatic saving take care of the rest.

Notes stores your notes as plain `.txt` files, making them easy to access, manage, and use outside the application.

## Features

- **Organised Sidebar** – Browse your saved notes in a sidebar, sorted newest first, with last-modified dates.
- **Search** – Quickly search across note titles and contents.
- **Create & Delete Notes** – Create new notes or delete existing ones. Deleted notes are moved to the Windows Recycle Bin.
- **Automatic Saving** – Notes are automatically saved approximately 1.5 seconds after you stop typing. Auto-save can be disabled in Settings.
- **Three Themes** – Choose between Light, Dark, and System Default. System Default follows your Windows theme and updates automatically when it changes.
- **Customisable Editor** – Adjust the editor font, font size, and word wrapping.
- **Settings Page** – Manage your theme, editor preferences, auto-save behaviour, and confirmation options.
- **Plain Text Storage** – Notes are saved as standard `.txt` files, so your data remains accessible without the app.

## Screenshots

<!-- Add application screenshots here -->

| Main Window | Settings |
|:---:|:---:|
| <!-- Add main window screenshot --> | <!-- Add settings screenshot --> |

## System Requirements

| Requirement | Details |
|---|---|
| Operating System | Windows 10 or Windows 11 |
| Architecture | 64-bit (x64) |
| Framework | .NET 8 |
| Installation | Windows installer |

## Installation

1. Download the latest installer from the [Releases](../../releases) page.
2. Run the downloaded installer.
3. Follow the installation instructions.
4. Launch **Notes** from the Start Menu or desktop shortcut, if created.

> **Note:** The application is designed for 64-bit versions of Windows 10 and Windows 11.

## Building from Source

### Prerequisites

- Windows 10 or Windows 11 (64-bit)
- [Visual Studio](https://visualstudio.microsoft.com/)
- .NET 8 SDK
- [Inno Setup](https://jrsoftware.org/isinfo.php) (for building the installer)

### Build Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/USERNAME/Notes.git
