# Elm Version Manager

A very simple version manager that uses your installed elm versions.

Example: `elm use 0.18`

### Instructions

For a version to be available you must install it with the pkg installer available for download on the official site: https://guide.elm-lang.org/install.html.

Whenever you invoke `evm use x.x `, it will save the current version to `~/.evm/versions/y.y` and restore `~/.evm/versions/x.x`, unless:

- the two are the same
- the desired version does not exist

in which cases `evm` will do nothing, possibly printing an error.

LICENSE

MIT
