# Cube Atlas downloads

This public repository hosts installable Cube Atlas preview builds and the version feed. The application source is kept in a private repository.

Download the current [preview release](https://github.com/desro13/cube-atlas-downloads/releases/tag/v0.2.0-preview).

The Android preview supports the Cube Atlas PC Test Cube over Bluetooth. It does **not** yet discover a GAN iCarry 4. The Windows preview contains the existing GAN integration, which is still undergoing connection and move-synchronization testing.

The `update.json` file is the public version feed. Android 0.2 checks it on launch and offers newer APKs, with Android installation approval. The Windows `.appinstaller` file sets up update checks for the signed MSIX package. The portable Windows ZIP does not update itself. The MSIX uses a test certificate and requires that certificate to be trusted on the PC.
