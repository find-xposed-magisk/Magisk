## f0986075-delta

- [Manager] Update UI

Canary and Debug are built from the same source code.  Debug builds have more detailed logs and are suitable for debugging. Canary builds have less logs, are more stable than Debug, and are suitable for most common uses

If you like my work, you can donate me at [PayPal/HuskyDG](http://paypal.me/huskydg)

### Diffs to 25.2-delta-6

- [MagiskHide] Switch to Ptrace-based MagiskHide
- [MagiskHide] Allow SuList apps to load magisk module mounts.
- [General] Fix MagiskHide and Zygisk become non-functional after enable Core-only mode
- [General] Trim mountinfo before mounting mirrors
- [MagiskHide] No longer reset sensitive properties after boot completed
- [SuList] No longer automatically grant root access for SuList apps
- [SuList] Only unmounts after system server start, so module like systemize apps and debloat should work (you also need to add apps that are systemized by Magisk module to SuList)
- [SuList] Fix Magisk app cannot get root access after Hide Magisk app
- [Zygisk] Introduce new way to load Zygisk
- [Zygisk] Hide magisk modules from maps
- [SuList] Introduce Zygisk-SuList
- [Manager] Add Disable Magisk button in reboot option
- [SuList] Add `magisk --hide sulist enable/disable` CLI to enable/disable SuList (need reboot to take effect)
- [Manager] Flashing `disabler.zip` to install Magisk and enable Core-only mode

### Diffs to official Magisk

- [General] MagiskHide is back
- [Manager] Support installing into system partition
- [General] Copy required files to `/system` for `addon.d`
- [Manager] Show all supported languages in Language settings for Chinese ROM
- [Module] Support systemless deleting files or folders for modules
- [General] Built-in Bootloop Protection to protect system from bootloop by magisk module
- [General] Tune F2FS driver
- [MagiskInit] Support Pre-Init mount, replace system files before `init` starts
- [MagiskInit] Support loading custom rc script from pre-init directory
- [Modules] Support magic mount more partitions (`my_*`, `odm`, `optics`, `prism`)
- [MagiskHide] Introduce SuList feature
- [Zygisk]: Switch to use native bridge by 5ec1cff
- [Zygisk]: Replace xhook with lsplt hook api
- [MagicMount]: Recreate all mounts under mirrors
- [General] Support Bluestacks, needs [app_process wrapper](https://github.com/HuskyDG/app_process_wrapper/releases) to run Zygisk, overwise it will be bootloop
- [Module] Live patch `sepolicy.rule` if it is not found in `sepolicy.rules` directory

### Magisk upstream

- Sync upstream source code to 71b7f526

## Magisk (831a398b) (25206)

- Fix support on Linux < 3.6
- Several minor under-the-hood improvements

## Diffs to v25.2

- [General] Fix minor bug in module files mounting implementation
- [MagiskPolicy] Fix minor bug in command line argument parsing
- [Zygisk] Prevent crashing daemon in error
- [Zygisk] Rewrite zygote code injection with new loader library approach
- [App] Make stub patching 100% offline
