# Cube Atlas downloads

This public repository hosts installable Cube Atlas preview builds and the version feed. The application source is kept in a private repository.

Download the current [Android 0.6 and Windows 0.5 preview](https://github.com/desro13/cube-atlas-downloads/releases/tag/v0.6.0-preview).

Android 0.6 and Windows 0.5 include a saved six-checkpoint beginner practice path with random cases, alongside notation, OLL, PLL, and full-solve drills. Both builds clear guided hints when a free scramble or reset starts. Android's Bluetooth client supports the Cube Atlas PC Test Cube only; it does **not** yet discover a GAN iCarry 4. Windows GAN integration still needs connection and move-synchronization testing. A compact offline cubing coach is planned, not yet included.

The `update.json` file is the public version feed. Android checks it on launch and offers newer APKs, with Android installation approval. The Windows `.appinstaller` file sets up update checks for the signed MSIX package. The portable Windows ZIP does not update itself. The MSIX uses a test certificate and requires that certificate to be trusted on the PC.
