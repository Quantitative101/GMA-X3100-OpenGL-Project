# GMA-X3100-OpenGL-Project
**Unlocking FULL OpenGL 2.1 (And partial 3.0) for the GMA X3100 (GM965)**

> [!WARNING!]
> **NOT COMPATIBLE WITH WINDOWS AERO.** Using this driver with Aero enabled will result in extreme gamma glitches and visual artifacts. You **NEED** to use the Basic or Classic theme.

## The "Frankenstein" Mod
This project is a "Frankenstein" of drivers. It works by mixing parts from the 2012 HD Graphics drivers (Arrandale) with the legacy GMA X3100 drivers.
* **My Work:** INF remapping and flag tweaking.

## Installation Instructions

1. **Download the Base:** Get the `15.22.54.64.2622` drivers from the [Official Site](https://www.intel.com/content/www/us/en/download/16652/intel-hd-graphics-driver-for-windows-vista-64-exe.html).
2. **Extract:** Use [7-Zip](https://www.7-zip.org/) to extract the `.exe` file contents.
3. **Locate:** Open the `Graphics` folder.
4. **Swap:** Replace the original `igdlh64.inf` with the modded version provided here.
5. **Driver Signature:** Disable **Driver Signature Enforcement** (Settings > Recovery > Advanced Startup). *Usually not required for Windows 7.*
6. **Install:** Run `Setup.exe`. If Windows warns about an unsigned driver, click **"Install this driver software anyway."**
7. **Reboot:** Needed for changes to take effect.

## Common Issues & Fixes

* **Issue:** Gamma is insanely high or the screen looks artifact-y
  * **Fix:** Disable **Windows Aero**!!!
* **Issue:** The Graphics Command Panel is bugged/wont open.
  * **Fix:** This is expected behavior. You must change settings via `regedit` if you need to. The UI will not render correctly on GM965 chips.

---
**Tested on:** GMA X3100 (GM965) | Windows 7 x64 SP1

*Theoretically works on Windows 10/11, but you'd need to do it via devmgmt and it has NOT been tested!.*



<img width="1090" height="816" alt="image" src="https://github.com/user-attachments/assets/d48e84c7-9187-4567-a7b3-33384d7dddbd" />
