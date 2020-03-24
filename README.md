# Firefox Epiphany Theme [WIP]
A custom userChrome file to make Firefox look like epiphany, and blend in with the elementary desktop.

This is still a work in progress, so bugs are expected.

## Screenshots
![screenshot](https://github.com/Angalexik/firefox-epiphany-theme/raw/master/screenshots/screenshot.png)

## Prerequisites
[OS Style Close Button](https://addons.mozilla.org/cs/firefox/addon/os-style-close-window-button/?src=search)

[OS Style Maximize Button](https://addons.mozilla.org/cs/firefox/addon/os-style-maxmize-window-button/)

## Instalation
Install the required prerequisites
Position the close and maximize buttons like this:
![toolbar](https://github.com/Angalexik/firefox-epiphany-theme/raw/master/screenshots/toolbar.png)

Two icons on the left and right with an overflow menu.

In firefox navigate to [about:config](about:config)
Search for `toolkit.legacyUserProfileCustomizations.stylesheets`
Change it to true by double-clicking on it.

Copy the contents of this repo to `~/.mozilla/firefox/<profile_folder>/chrome`