# A36 to Flagship

A root module that brings selected Samsung flagship features to the Samsung Galaxy A36 5G running One UI 9.0.

# Features

The following features are currently functional:

- Call Assist
- Writing Assist
- Note Assist
- Transcript Assist
- Browsing Assist
- Photo Assist
- Creative Studio
- Now Brief
- AOD wallpaper and clock transition

**Additional content**

- Samsung Galaxy S26 Ultra live wallpaper

# Known Issues

- Weather Wallpaper: Not functional.
- Health Assist: Available in the system but not yet tested.
- Now Nudge: Available in the system but not yet tested.
- Interpreter: Voice recognition is not working. Text input functions as expected.
- Uninstallation: The uninstall script may not fully restore the functionality of affected system applications. Some applications may remain unusable or continue to crash after removal.
- Bug with lockscreen media player placement.
- SurfaceFlinger may shows SSRM warning, still need investigating. Press on "I got it" will make it go away.
  
# Requirements

- Samsung Galaxy A36 5G
- One UI 9.0
- KernelSU root access
- [Magic Mount](https://github.com/Tools-cx-app/meta-magic_mount-rs/releases)

KernelSU is the recommended root solution. [DFRoot](https://github.com/diabl0w/DFRoot) is provided as a reference for rooting the device.

# Installation

1. Ensure that the device meets all requirements.
2. Install the [Magic Mount module](https://github.com/Tools-cx-app/meta-magic_mount-rs/releases).
3. Perform a soft reboot.
4. Download the latest version from [GitHub Releases](https://github.com/enderbk0/a36toflagship/releases).
5. Install the A36 to Flagship module using KernelSU.
6. Perform another soft reboot to apply the changes.

After rebooting, verify that the installed features and applications function correctly.

# Uninstallation

The uninstall script is currently experimental and may not restore all modified applications to a functional state. Some applications may continue to crash or become unusable after the module is removed.

A factory reset may be required to restore normal system functionality. Back up important data before installation.

# Disclaimer

This module modifies system components and may cause application failures, bootloops, device instability, data loss, or device bricking.

Use this module at your own risk. The developer assumes no responsibility for damage or data loss resulting from its use. Back up your data before installation.

# Credits

Inspired by [ducthoe/A56-To-Flagship](https://github.com/ducthoe/A56-To-Flagship).
