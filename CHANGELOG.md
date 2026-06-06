# Changelog

## v1.0.5

- Updated the application logo to the new round Meta-USB design
- Updated installer, shortcut, and public product logo assets

## v1.0.4

- Added Huawei USB Driver package
- Added bundled x86 and x64 Huawei driver files
- Improved architecture filtering so x86/x64 driver folders are handled according to the current Windows architecture

## v1.0.3

- Skipped legacy Samsung Win9x INF files during driver installation
- Skipped wrong-architecture Samsung INF files on 64-bit Windows
- Prevented incompatible INF files from appearing as failed driver install results

## v1.0.2

- Added Samsung USB Driver support
- Extracted Samsung driver installer into direct INF/CAT/SYS driver package files
- Samsung driver package now installs through the Driver Store flow

## v1.0.1

- Added OTA update support with public manifest checks
- Added manual update check from the Help menu
- Added startup update check preference
- Added SHA256 verification for downloaded installers

## v1.0.0

- Initial MetaFold Port Cleaner public release
- Non-present device listing and cleanup
- COM port visibility
- Driver manager for bundled service drivers
- Turkish and English interface
- Light and dark theme support
- Scheduled cleanup option
