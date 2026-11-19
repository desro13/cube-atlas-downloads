# Cube Atlas downloads

This public repository hosts installable Cube Atlas preview builds and the version feed. The application source is kept in a private repository.

Download the current [Android 0.4 and Windows 0.3 preview](https://github.com/desro13/cube-atlas-downloads/releases/tag/v0.4.0-preview).

Android 0.4 includes guided virtual-cube practice for notation, beginner layers, OLL, PLL, and full solves, plus the Cube Atlas launcher icon. Its Bluetooth client supports the Cube Atlas PC Test Cube only; it does **not** yet discover a GAN iCarry 4. Windows 0.3 has the same icon and the existing GAN integration, which still needs connection and move-synchronization testing.

The `update.json` file is the public version feed. Android checks it on launch and offers newer APKs, with Android installation approval. The Windows `.appinstaller` file sets up update checks for the signed MSIX package. The portable Windows ZIP does not update itself. The MSIX uses a test certificate and requires that certificate to be trusted on the PC.
