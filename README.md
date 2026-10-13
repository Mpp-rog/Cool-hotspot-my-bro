# Cool Hotspot My Bro

This is a project made to port Linux to hotspot MiFi devices.

## What's Being Used?

- [LK2ND](https://github.com/msm8916-mainline/lk2nd)
- ADB and Fastboot
- A lot of testing and probably more pain than needed.

## Current Status

So far, I've managed to boot LK2ND on my MiFi device, which is running Android 4.4.4 with a Qualcomm MSM8916 chipset.

But now comes the fun part...

**Getting Linux to actually boot.**

Right now, Linux has NOT been confirmed to boot on the device. I'm still trying to figure out the boot process and what's needed to get this thing running Linux.

## Project Roadmap

### Phase 1 — Research

- [x] Boot LK2ND on the MiFi device.
- [x] Get ADB and Fastboot working.
- [ ] Figure out how the device currently boots Android.
- [ ] Investigate how LK2ND loads kernels and boot configurations.

### Phase 2 — Kernel Research

- [ ] Find a suitable Linux kernel for the Qualcomm MSM8916.
- [ ] Investigate the device tree and hardware support.
- [ ] Figure out which drivers are needed for the MiFi's hardware.
- [ ] Work out how to pass the correct boot arguments to the kernel.

### Phase 3 — First Linux Boot

- [ ] Find a way to load a Linux kernel without breaking the existing Android installation.
- [ ] Get the kernel to start and collect boot logs.
- [ ] Troubleshoot any boot errors.
- [ ] Confirm whether Linux can actually boot on the device.

### Phase 4 — Getting Linux Working

- [ ] Get basic hardware working, such as storage and networking.
- [ ] Find or build a suitable Linux root filesystem.
- [ ] Get a usable shell running.
- [ ] Test which device features work and which need more development.

### Phase 5 — Documentation and Community

- [ ] Document confirmed working methods.
- [ ] Write guides for other people with compatible MiFi devices.
- [ ] Collect device information and testing results from the community.
- [ ] Update the project as more progress is made.

**Note:** These phases are goals, not promises. Some steps may change depending on what the hardware and bootloader support.

## What Now?

The next step is to investigate the boot process, kernel compatibility, and device tree support before attempting a proper Linux boot.

The project is still in progress, and there's no guarantee this will work yet.

## When Will You Be Done?

Soon, VERY SOON.

## License

This project's original code and documentation are licensed under the **GNU General Public License v3.0 (GPL-3.0)**. See [LICENSE](LICENSE).

Third-party components remain under their respective licenses.
