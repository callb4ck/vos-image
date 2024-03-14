# What's this?
This is a custom Vib image to be used by ABRoot on VanillaOS

## Features
This image differs from stock in the following ways:
- Onedriver is preinstalled

# Usage
## Install

Execute the following command in the `vso-pico` shell:
```bash
host-shell pkexec sed -i.old 's/vanilla-os\/desktop/dumbmahreeo\/custom/g' /etc/abroot/abroot.json
```

## Uninstall (back to stock image)

Execute this other command:
```bash
host-shell pkexec mv /etc/abroot/abroot.json.old /etc/abroot/abroot.json
```
