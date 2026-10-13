# Cool hotspot my bro

this is a project made to port linux to Hotspot MiFi devices.

## Whats being used?

- [LK2ND](https://github.com/msm8916-mainline/lk2nd)
- ADB and Fastboot
- a lot of testing and probably more pain than needed.

## Current status

so far i managed to boot LK2ND on my MiFi device, which is running Android 4.4.4 with a Qualcomm MSM8916 chipset.

but now comes the fun part...

**getting linux to actually boot.**

right now linux has NOT been confirmed to boot on the device. im still trying to figure out the boot process and what is needed to get this thing running linux.

## What now?

- figure out how to boot a linux kernel
- investigate kernel and device tree support
- test things and see what works

the project is still in progress, and theres no guarantee this will work yet.

## License

This project's original code and documentation are licensed under the **GNU General Public License v3.0 (GPL-3.0)**. See [LICENSE](LICENSE).

Third-party components remain under their respective licenses.
