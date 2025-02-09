# Anycubic Kobra Max Cura Config Files

This repository contains custom Cura configuration files for the **Anycubic Kobra Max** 3D printer. The settings are based on the Creality Cr10 profile doing some adjustments and personal experiments using **PLA** and **PETG** filaments, with a primary focus on a **0.8mm nozzle**. These configuration files are optimized to improve print quality and efficiency for the mentioned filaments and nozzle size.

## Printer and Filament Information

- **Printer Model**: Anycubic Kobra Max
- **Filaments Tested**: PLA, PETG from "Das Filament"
- **Nozzle Size**: 0.8mm, 0.4mm

The settings included here are tailored for the specific combination of the Anycubic Kobra Max and the 0.8mm nozzle, with the goal of achieving better layer adhesion, print quality, and speed for these filament types.

## Installation Instructions

To use these configuration files, you need to place them in the correct directory for Cura. Follow the steps below to install:

1. **Download the repository**:
   - You can download the config files by either cloning this repository using Git, or downloading the ZIP file and extracting it.

2. **Find the Cura settings directory**:
   - The configuration files need to be placed in the settings directory for Cura, which is located in the following path:
   
   Linux:

     ```
     $HOME/.local/share/cura/$CURA_VERSION/settings/
     ```
   
   Windows:
   
     ```
     $USER$\AppData\Roaming\cura\$CURA_VERSION$\
     ```
   

   - Replace `$CURA_VERSION` with the version of Cura you are using (e.g., `5.9`).

3. **Copy the files**:
   - Copy all the configuration files from this repository into the `$HOME/.local/share/cura/$CURA_VERSION/settings/` directory. Make sure to backup existing configs.

4. **Restart Cura**:
   - After copying the files, restart Cura. The new printer profiles and settings should now be available under the printer settings.
