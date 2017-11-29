# CLI for the Serial Robotics docker environment

## Installation

1. From the `cli/` folder run: `sudo ./cli install sr-cli`  
This will:

    * allow you to call the CLI from any location in your filesystem (adds a
    * symlink to the `cli` script in `/usr/bin`).
    * setup the auto-completion (adds a script in `/etc/bash_completion.d/`).

1. Source your `.bashrc` or restart your terminal.

## Use

By simply running `sr-cli` you can visualize all available commands with a short
description.

## Unistall

From the `cli/` folder run: `sudo ./cli uninstall sr-cli`
This will remove the two files created during the installation step.

## Screencasts

* Install and first run

[![asciicast](https://asciinema.org/a/uziQIiamjbRZQwK9msiP5JUKo.png)](https://asciinema.org/a/uziQIiamjbRZQwK9msiP5JUKo)

* Use a custom image instead of the default `cyrillg/sr-dev`

Coming soon...

## Credits

This tool is based on the very helpful _Bash CLI_ framework by SierraSoftworks,
available at https://github.com/SierraSoftworks/bash-cli.
