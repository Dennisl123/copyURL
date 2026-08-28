# Copy URL

Copy URL is an NVDA add-on that copies the current web page URL or a link's destination URL to the clipboard and announces the result.

## Commands

- Press `Alt+Control+Windows+C` in a browse-mode document to copy the current page URL.
- Move the browse-mode cursor or navigator object to a link and press `Alt+Control+Windows+L` to copy its destination without opening it.

Both commands appear in NVDA's **Input Gestures** dialog under the **Copy URL** category, where their shortcuts can be changed or removed.

## Settings

Open **NVDA menu > Preferences > Settings > Copy URL** to:

- Turn the "URL copied" prefix for page URLs on or off.
- Enable or disable the Copy Link URL command.
- Turn the "Link URL copied" prefix for link URLs on or off.

## Compatibility

- Minimum NVDA version: 2019.3.0
- Last tested NVDA version: 2026.1.1
- Designed for browse-mode content in browsers such as Firefox, Chrome, and Edge.

## Privacy and security

Copy URL does not connect to the internet, write files, or collect information. It reads a URL exposed by NVDA and places that URL on the clipboard only when the user invokes one of its commands.

## Author and contact

Dennis Long <dennisl@fastmail.com>

## Source and license

Source: https://github.com/Dennisl123/copyURL

Copyright (C) 2026 Dennis Long. Licensed under the [GNU General Public License version 2 or later](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html).

## Changes in 1.9.1

- Updated the author, compatibility, licensing, and documentation metadata for NVDA Add-on Store submission.
- Made settings-panel registration and cleanup safe during add-on reloads.
