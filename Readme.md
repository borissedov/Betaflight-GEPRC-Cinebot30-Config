# Cinebot30 Betaflight Configurations

This repository provides Betaflight configuration files and presets for the GEPRC Cinebot30 drone, aiming to help enthusiasts quickly set up their quad with known-good settings. The files here are intended to be used with the Betaflight Configurator and can be uploaded directly via the **Presets** tab.

## Branches

- **main:**  
  Contains the latest updated configuration for Betaflight 4.5.1 (or newer), incorporating all current tweaks and improvements.

- **4.3.1:**  
  Holds the original Cinebot30 configuration files as provided for Betaflight 4.3.1. Use this branch if you need to reference or revert to the older firmware setup.

- **4.5.1:**  
  Contains an intermediate set of configuration changes adapted from the original 4.3.1 setup and merged into what’s now on `main`. This branch captures the migration and compatibility adjustments made when upgrading from Betaflight 4.3.1 to 4.5.1.

## Files

- **cinebot30 official.txt:**  
  The official Cinebot30 configuration file sourced from the GEPRC website. This file represents the manufacturer’s recommended settings out of the box for a given firmware version.

- **BTFL_cli_backup_CINEBOT30_GEPRC_F722_AIO.txt:**  
  The actual CLI backup file used for restoring or migrating configurations in Betaflight. This file is tailored to the Cinebot30’s GEPRC F722 AIO flight controller. You can upload this via the **Presets** tab in the Betaflight Configurator to quickly apply the configuration.

## Usage

1. **Choosing the Right Branch:**  
   - If you’re running Betaflight 4.3.1, switch to the `4.3.1` branch and use the provided files there.
   - For Betaflight 4.5.1 or newer, use the `main` branch to get the most up-to-date configuration.

2. **Uploading a Preset:**  
   - Open the Betaflight Configurator.
   - Navigate to the **Presets** tab.
   - Click the **Local File** button and select `BTFL_cli_backup_CINEBOT30_GEPRC_F722_AIO.txt` (or `cinebot30 official.txt` if you need to rollback to original configuration) from your local clone of this repository.
   - Apply the preset and then save/reboot your flight controller as prompted.

3. **Verifying Settings:**  
   After applying a preset, review your configuration in the Configurator’s tabs (Ports, Configuration, Receiver, etc.) to ensure everything matches your hardware setup (e.g., UART for DJI O3, GPS connections, LED strip configuration).

## Contributing

If you make improvements or discover better settings, feel free to create a pull request or open an issue. Contributions help the community maintain an up-to-date and well-tuned configuration for the Cinebot30.