# Hackintosh-Gigabyte-z390-Gaming-X
Custom Hackintosh EFI Build for Gigabyte z390 Gaming X Motherboard

*This configuration is currently compatible with macOS Catalina.*

## Clover

Download the latest Clover package and copy the contents of  `Clover` folder of this repository to your `EFI` partition.

## OpenCore

Copy the `EFI` folder inside `OpenCore` folder to your `EFI` partition. Download the latest OpenCore package and extract the following to the said partition as follows:

- `EFI/BOOT/BOOTx64.efi`
- `EFI/OC/OpenCore.efi`
- `EFI/OC/Bootstrap/Bootstrap.efi`
- `EFI/OC/Drivers/OpenCanopy.efi`
- `EFI/OC/Drivers/OpenRuntime.efi`
- `EFI/OC/Tools/OpenShell.efi`

*Note: USE AT YOUR OWN RISK. Backup your current EFI bootloader before using this one.*
