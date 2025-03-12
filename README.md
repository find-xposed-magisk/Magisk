# Kitsune Magisk

**This is not an officially supported [topjohnwu](https://github.com/topjohnwu) project**. 

> This is not Official Magisk, please [go to this page and download Official Magisk](https://github.com/topjohnwu/Magisk)

# Download

## Stable / Beta

- [Kitsune Mask v26.4 Stable](https://github.com/HuskyDG/download/raw/main/magisk/26.4-kitsune.zip)

## Canary / Debug

> We only accept bug reports from the **LATEST DEBUG** build. Invalid bug reports will be closed instantly.

### Kitsune Mask

> Kitsune Mask has MagiskHide, SuList, and a new Zygisk loading mechanism

- [Canary (kitsune-release.exe)](https://huskydg.github.io/magisk-files/kitsune-release.zip)
- [Debug (kitsune-debug.exe)](https://huskydg.github.io/magisk-files/kitsune-debug.zip)
- [Changelog](https://github.com/HuskyDG/magisk-files/blob/main/note.md)

## Other Versions

- [Releases page](https://github.com/HuskyDG/magisk-files/releases)

## Source Code

- [https://github.com/KitsuneMagisk/magisk](https://github.com/KitsuneMagisk/magisk)

# How to Install

## Installing Kitsune Mask via PC

### Step-by-Step Guide

1. Download the latest version of `26.4-kitsune.exe` from the [Stable/Beta section](#stable--beta).
2. Run `26.4-kitsune.exe` on your PC.
3. Connect your Android device to the PC via USB.
4. Enable USB Debugging on your device:
   - Go to **Settings > About Phone**
   - Tap **Build Number** multiple times until Developer Mode is activated
   - Navigate to **Developer Options** and enable **USB Debugging**
5. Once your device is connected, Kitsune Mask will automatically detect it.
6. Follow on-screen instructions to proceed with the installation.
7. Your device will reboot automatically upon successful installation.
8. Open the Kitsune Mask app on your Android device and grant root access.

## Switching from Magisk to Kitsune Mask and Vice Versa

Simply install Kitsune Mask using the steps above. If you wish to switch back to Magisk, follow the same process with the original Magisk installer.

## Installing Magisk via PC (Alternative Method)

1. Download `26.4-kitsune.exe`.
2. Boot your device into **Fastboot Mode** (Power + Volume Down for most devices).
3. Run `26.4-kitsune.exe` and select **Install via Fastboot**.
4. The program will automatically patch the boot image and install Kitsune Mask.
5. Reboot your device normally.
6. Open Kitsune Mask to verify installation.

## Installing Kitsune Mask on an Android Emulator

1. Ensure that the emulator has root access enabled in its settings.
2. Download and run `26.4-kitsune.exe` on your PC.
3. Select your emulator from the list of detected devices.
4. Click **Install** and wait for the process to complete.
5. Restart the emulator and verify installation inside Kitsune Mask.

> **Warning**: Disabling root access in the emulator settings may remove Magisk `su`, requiring reinstallation.

# Kitsune Module

- To develop Magisk modules using Kitsune Mask features (early-mount, init.rc injector, etc.), download the [module template](https://huskydg.github.io/magisk-files/module-template.zip).

# Donate

- PayPal: [paypal.me/huskydg](http://paypal.me/huskydg)
- Thank you for your support!

# Credits

- Magisk author: [topjohnwu](https://github.com/topjohnwu/magisk)
- Magisk contributors: [vvb2060](https://github.com/vvb2060), [yujincheng08](https://github.com/yujincheng08), [RikkaW](https://github.com/RikkaW), [canyie](https://github.com/canyie)
- Magisk Hide in whitelist mode: [MagiskLite](https://t.me/magisklite)
- Zygisk implementation by ptrace: [ZygiskNext](https://github.com/Dr-TSNG/ZygiskNext), [Dr-TSNG](https://github.com/Dr-TSNG/ZygiskNext), and [5ec1cff](https://github.com/5ec1cff)

# License

Our license follows the same terms as [Magisk's license](https://github.com/topjohnwu/Magisk#License):

```
Magisk, including all git submodules, is free software:
you can redistribute it and/or modify it under the terms of the
GNU General Public License as published by the Free Software Foundation,
either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. If not, see <http://www.gnu.org/licenses/>.
```

