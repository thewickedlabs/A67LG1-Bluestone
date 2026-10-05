# A67LG1 Bluestone

Removes the preinstalled Rsota update service.

A KernelSU Next module for the **Foxxd A67L Gen 1**. Gen 2 version: [A67LG2-Bluestone](https://github.com/thewickedlabs/A67LG2-Bluestone).

Built from the Gen 1 stock firmware; not yet tested on Gen 1 hardware. Reports welcome.

Rsota (`com.revoview.update`) is the factory over-the-air update app. It reports the device to its
own servers and can install software silently. This module hides it systemlessly, so it isn't loaded
at boot.

## Requirements

- Foxxd A67L Gen 1
- Rooted with KernelSU Next

The installer stops without changing anything if either is missing.

## Install

1. Download `A67LG1-Bluestone.zip` from Releases.
2. KernelSU Next → Modules → Install from storage → select the zip.
3. Reboot.

## Uninstall

Disable or remove the module and reboot. Rsota comes back untouched.

## License

[WTFPL](LICENSE).

---

Wicked Labs · https://www.cyberspace7.org
