# Installing macOS High Sierra 10.13.6

## Make Bootable USB drive (from https://www.tonymacx86.com/threads/guide-booting-the-os-x-installer-on-laptops-with-clover.148093/)
(How to write disk image to USB skipped)

I couldn't download the full installer dmg from Apple Store any more but I found a work around by using http://dosdude1.com/highsierra/

### Preparing essential kexts
Multibeast has provided some kexts but we are going to replace them.

Copy essential kexts to the 'Other' directory (FakeSMC, VoodooPS2Controller). You only need the kexts that allow you to boot and operate the installer. Other kexts that you might use in the final installation can wait.

Use RehabMan's own versions of these kexts:
FakeSMC.kext: https://github.com/RehabMan/OS-X-FakeSMC-kozlek
