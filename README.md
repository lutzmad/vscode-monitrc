# MONITRC README

This is the README for the extension "MonitRC".

This is a simple Monit configuration syntax highlighting extension.

## Features

The extension does not contain any specific features.

## Requirements

The extension does not have any requirements or dependencies.

## Extension Settings

The extension does not use any VSCode settings.

## Known Issues

There are no known issues in the extension.

The extension does not handle all line breaks correctly.

For example, Monit handle the following lines properly.

```text
set logfile /var/log/monit.log

set
pidfile /var/run/monit.pid
```

But the extension does not highlight the "set pidfile" statement properly.
The noise keywords like "and", "with(in)", "has", "us(ing|e)", "on(ly)", "for", "of" can be used anywhere and should highlighted correctly.

## Release Notes

The extension release notes.

### 0.0.2

Handle the "interval" statement used instead of "daemon" in the future.

### 0.0.1

Initial release.
