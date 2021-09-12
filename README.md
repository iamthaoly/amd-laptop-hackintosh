# Opencore EFI for AMD Laptops (updated to Big Sur 11.5.2)

**Opencore version: 0.6.3**

**macOS: Big Sur 11.5.2**

![alt text](http://url/to/img.png)

My laptop is **ASUS Vivobook A412D**
- CPU: AMD Ryzen 5 3500U
- Display: AMD Radeon Vega 8
- Network: Intel wireless 8265
- Audio: AMD K17.1

## What's in the box?
```
└── EFI
    ├── BOOT
    └── OC
        ├── ACPI
        ├── Bootstrap
        ├── Drivers
        ├── Kexts
        │   ├── AirportItlwm.kext
        │   ├── AMDRyzenCPUPowerManagement.kext
        │   ├── AppleALC.kext
        │   ├── AppleMCEReporterDisabler.kext
        │   ├── Lilu.kext
        │   ├── NVMeFix.kext
        │   ├── SMCAMDProcessor.kext
        │   ├── VirtualSMC.kext
        │   ├── VoodooPS2Controller.kext
        │   │       ├── MacOS
        │   │       └── PlugIns
        │   │           ├── VoodooInput.kext
        │   │           ├── VoodooPS2Keyboard.kext
        │   │           ├── VoodooPS2Mouse.kext
        │   │           └── VoodooPS2Trackpad.kext
        │   └── WhateverGreen.kext
        └── Resources
            ├── Font
            ├── Image
            └── Label

```