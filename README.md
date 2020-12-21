# Arch Linux ARM (aarch64) with wine and mono (x86_64)

 - Includes Arch Linux ARM (aarch64) for a Raspberry Pi 4.
 - Includes binaries and binfmt_misc entries for emulating x86 and x86_64 binaries.
 - Includes an Arch Linux (x86_64) filesystem with binaries for emulating x86 and x86_64 binaries, preconfigured `pacman.conf` and preinstalled `mono` and `wine-mono`.

## Installation:

Follow the instructions here:
https://archlinuxarm.org/platforms/armv8/broadcom/raspberry-pi-4

Replace step 5 with:
```
cat aarch64_custom_partaa aarch64_custom_partab aarch64_custom_partac > aarch64_custom.tar.gz
bsdtar -xpf aarch64_custom.tar.gz -C root
sync
```

