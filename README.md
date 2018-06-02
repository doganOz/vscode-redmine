# `vscode-redmine`

Redmine extension for Visual Studio Code.

## Features

* List of issues assigned to you
* Open issue by id
* Issue actions:
  * Change status of an issue
  * Add time entry to an issue
  * Open issue in browser

_Missing a feature? Open an issue and let me know!_

## Requirements

It's required to enable REST web services in `/settings?tab=api` of your redmine (you have to be administator of redmine server).

## Extension Settings

This extension contributes the following settings:

* `redmine.serverUrl`: URL of redmine server (eg. `redmine.example.com`, `example.com/redmine` _etc._)
* `redmine.serverPort`: Port of redmine server (default: `443`)
* `redmine.serverIsSsl`: Should be connected through SSL or not (default: `true`)
* `redmine.apiKey`: API Key of your redmine account (see `/my/account` page, on right-hand pane)
* `redmine.rejectUnauthorized`: Parameter, which is passed to https request options (true/false) (useful to fix issues with self-signed certificates, see issue #3)

## Contribution

Feel free to contact me, if you want to contribute. ToDo features can be found in `Projects` tab on GitHub.

## Known Issues

No known issues yet. If you found one, feel free to open an issue!

## Release Notes

See `CHANGELOG.md`

**Enjoy!**
