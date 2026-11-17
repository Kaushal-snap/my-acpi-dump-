<div align="center">

# K513EA · ACPI & Hardware Research Archive

**Reference material for ASUS VivoBook K15 OLED · Intel Core i5-1135G7**

![Hardware](https://img.shields.io/badge/Platform-ASUS%20K513EA-0071C5?style=for-the-badge)
![Purpose](https://img.shields.io/badge/Content-ACPI%20Research-7B61FF?style=for-the-badge)
![Privacy](https://img.shields.io/badge/Privacy-Sanitization%20in%20progress-orange?style=for-the-badge)

</div>

This repository stores hardware and ACPI reference material used during Hackintosh development for the ASUS VivoBook K15 OLED K513EA.

## Intended contents

- ACPI dump archives for table inspection
- Hardware report exports used to identify devices
- OLED panel EDID reference data
- Brightness-related patch experiments
- Diagnostic logs used during display investigation

## Hardware context

The associated laptop configuration is reported as:

- ASUS VivoBook K15 OLED K513EA
- Intel Core i5-1135G7 (Tiger Lake-U)
- Intel Iris Xe integrated graphics
- OLED internal display

Exact subsystem IDs and hardware revisions should be confirmed from the individual machine before reusing any patch.

## Privacy and safe sharing

Raw hardware reports can contain computer names, device identifiers, storage details, timestamps, serial numbers, usernames, and other machine-specific information.

- Do not upload unredacted HWiNFO/System Information reports.
- Do not publish SMBIOS Serial Number, MLB, SystemUUID, ROM, Wi-Fi credentials, or personal file paths.
- Share only the minimum ACPI tables or sanitized excerpts needed for a technical issue.
- Review archives before publishing; deleting a file from the current branch does not erase it from Git history.

A raw HWiNFO export containing the Windows computer name was removed from the current branch as a privacy cleanup. Historical copies may remain in previous Git commits.

## Usage

Treat these files as diagnostic references, not ready-to-install EFI components. Compare ACPI paths, device IDs and panel details against your own hardware. Never replace a working EFI without a complete backup and a separate USB test.

## Disclaimer

Research archive for a specific laptop configuration. Files are provided as-is and may contain machine-specific assumptions. Validate all changes locally before use.
