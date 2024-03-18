# What's this?
This is a custom Vib image to be used by ABRoot on VanillaOS

## Features
This image differs from stock in the following ways:
- Onedriver is preinstalled
- New apx stack `void-glibc` based on void linux
- Console not closing upon shell exit, fixed

# Usage
## Install

Execute the following command in the `vso-pico` shell:
```bash
host-shell pkexec sh -c "sed -i.old 's/vanilla-os\/desktop/dumbmahreeo\/vos-image/g' /etc/abroot/abroot.json && abroot upgrade"
```

## Uninstall (back to stock image)

Execute this other command:
```bash
host-shell pkexec sh -c "mv /etc/abroot/abroot.json.old /etc/abroot/abroot.json && abroot upgrade"
```
 
