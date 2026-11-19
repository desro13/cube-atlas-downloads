# Cube Atlas downloads

This public repository hosts installable Cube Atlas preview builds and the version feed. Application source remains private.

Download the current [Android 0.9 and Windows 0.8 preview](https://github.com/desro13/cube-atlas-downloads/releases/tag/v0.9.0-preview).

This preview adds free-scramble coaching with checked complete-solve hints, live F2L piece locations, paired Atlas/CFOP practice on the same scramble, and one verified worked example each for Roux, ZZ, and Petrus. These are learning examples, not complete arbitrary-scramble trainers for all methods. The coach uses offline cube-state rules; no language model is bundled.

Android still connects to the Cube Atlas PC Test Cube, not the GAN iCarry 4. Windows GAN integration is unchanged and requires physical testing. The `update.json` feed offers Android updates on app launch. The Windows `.appinstaller` checks for signed MSIX updates. The MSIX uses the existing Cube Atlas test certificate.
