# Cube Atlas downloads

This public repository hosts installable Cube Atlas preview builds and the version feed. The application source is kept in a private repository.

Download the current [Android 0.3 preview](https://github.com/desro13/cube-atlas-downloads/releases/tag/v0.3.0-preview). The Windows 0.2 preview remains available [here](https://github.com/desro13/cube-atlas-downloads/releases/tag/v0.2.0-preview).

Android 0.3 adds guided virtual-cube practice for notation, beginner layers, OLL, PLL, and full solves. Its Bluetooth client supports the Cube Atlas PC Test Cube only; it does **not** yet discover a GAN iCarry 4. The Windows preview contains the existing GAN integration, which is still undergoing connection and move-synchronization testing.

The `update.json` file is the public version feed. Android checks it on launch and offers newer APKs, with Android installation approval. The Windows `.appinstaller` file sets up update checks for the signed MSIX package. The portable Windows ZIP does not update itself. The MSIX uses a test certificate and requires that certificate to be trusted on the PC.
