# Userscripts for Safari

A simple, open-source, userscript editor for Safari.

![Userscripts for Safari](/etc/screenshot-large.png)

## Installation

Once the extension is accepted into the app store, a link will appear here. For now, clone the project and build with Xcode.

## Usage

Using the extension is simple. You can open the editor by clicking on the the toolbar button. Any code you write will be injected into every website you visit.

Here are some usage notes:

- `cmd + s` to save changes to the editor
- hinting is automatic, you can use the shortcut `ctrl + spacebar` to toggle hinting manually
- your code is saved into `~/Library/Containers/com.userscripts.macos.Userscripts-Extension/Data/Documents/data.json`
    - the json object has two properties
        - `code` is the what you have saved fromt he editor
        - `lastEdited` is the time of the last save
- you can click the download icon to save your script file locally, without needing to navigate to this folder

## Why?

With the depreciation of `.safariextz` style extension in Safari 12, I wanted a way to quickly and easily create some "quality of life" userscripts. Since it's no longer possible to create and sign, even personal, `.safariextz` extensions, I needed a new way to dynamically create userscripts.

There are other userscripts editors/managers for other browsers, and even good ones for Safari, but I wanted something very simple and *open-source*.

## License 

[GNU General Public License v3.0](/LICENSE)



