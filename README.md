## Mission

ROM-builders organization is created to support and help collaborate developers working on custom Android ROMs that 
don't have access to powerful enough computers to build [AOSP](https://source.android.com/) locally in a timely manner.

This organization provides powerful servers (sponsored by [Cirrus Labs](https://github.com/cirruslabs/cirrus-ci-docs))
configured and optimized for building AOSP fast.

## How to add your ROM?

In order to add your ROM to this organization to have access to compute power please read the following requirements/standards
for projects:

1. Repository name should be formatted as `device_code_name-RomName-Builder's_Name` (like `mido-AospExtended-Apon77`).
2. Repository should have ReadMe.md that describes the ROM for both developers and users:
    * Please add description of the ROM with the main differences/features.
    * Provide screenshots and/or instruction on how to install the ROM on a device.
    * Try to make the ReadMe pretty and easily understandable by people with little background in ROM development.
3. Repository should have `build_rom.sh` script that builds and uploads your ROM.
4. Once you prepared your repository please [create an issue in this repository](https://github.com/ROM-builders/how-to-add-your-rom/issues/new)
   with a link to the repository, please describe how you distribute the ROM (via forum, Telegram channel or something else).
   Ideally, if you have that information, tell us how many people install your ROM.
