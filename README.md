# Cube Atlas downloads

This public repository hosts installable Cube Atlas preview builds and the version feed. The application source is kept in a private repository.

Download the current [preview release](https://github.com/desro13/cube-atlas-downloads/releases/tag/v0.1.0-preview).

The Android preview supports the Cube Atlas PC Test Cube over Bluetooth. It does **not** yet discover a GAN iCarry 4. The Windows preview contains the existing GAN integration, which is still undergoing connection and move-synchronization testing.

The `update.json` file is the public version feed. The current preview apps do not yet check this feed automatically. Future signed builds will use it to announce updates; Android will still ask for installation approval, and Windows update delivery will require an installer or updater.
