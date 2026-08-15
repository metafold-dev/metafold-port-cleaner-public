# Changelog

## v1.0.8

- Added a Task Manager Pro button powered by bundled Microsoft Sysinternals Process Explorer
- Bundled Process Explorer x86, x64, ARM64 executables and EULA under tools\ProcessExplorer
- Launches the matching Process Explorer executable as administrator based on Windows architecture

## v1.0.7

- Improved startup update checks so the app checks silently on each launch when startup update checks are enabled
- Shows the update prompt automatically when a newer OTA release is available
- Keeps "no update available" messages silent during startup checks

## v1.0.6

- Added safer scheduled cleanup prompts with current scan counts before removal
- Added ready-made list sorting presets such as date, port, COM/ADB/USB priority, manufacturer, class, and Device ID
- Improved large screen and DPI layout behavior for command buttons and the main window
- Improved driver signature failure messaging for Secure Boot/admin-policy cases
- Centered the About dialog text layout
- Replaced harsh warning prompts with a softer MetaFold warning sound

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
