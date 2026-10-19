# CareLink companion updates

Signed release files for the CareLink companion app's in-app updates (OTA).

- `manifest.json` lists the current phone and watch builds with their SHA-256, size, package and signer.
- `manifest.json.sig` is an ECDSA P-256 signature over the exact bytes of `manifest.json`.
- The app installs a file only after the manifest signature, the file's size and SHA-256, and Android's own package signature all match.

This repository holds no source code, keys or user data.
