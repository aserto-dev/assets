# aserto-cli

Aserto CLI


# Setup

To install the `aserto` CLI

## MacOS (x64)

Using [brew](https://github.com/aserto-dev/homebrew-tap#readme)

## Linux (x64)

Using [brew](https://github.com/aserto-dev/homebrew-tap#readme)

## Windows 10 (x64)

win-get install coming soon

## Manual installation

* Download the [release] (https://github.com/aserto-dev/aserto-cli/releases) for you platform
* Unzip the binary
* Place it in the PATH

Done!

# Known issues

* The CLI relies on Docker to be present, but does not current verify this prerequisite
* The CLI interacts with the resident OS credential manager for storing secrets, this prevents using the CLI inside a Docker container if there is no credential manager (libsecret, which relies on D-Bus) present.