# Flarum Composer Installer

[![Build Status](https://travis-ci.org/flarum/composer-installer.svg)](https://travis-ci.org/flarum/composer-installer)

A [Custom Installer](https://getcomposer.org/doc/articles/custom-installers.md) for Composer that places Flarum extensions in the `extensions` directory in the format of `{vendor}-{name}`. If present, a `flarum-` prefix will be removed from the extension name.

## Usage

Add the following lines to your extension's composer.json:

```json
    "type": "flarum-extension",
    "require": {
        "flarum/composer-installer": "~1.0"
    }
```
