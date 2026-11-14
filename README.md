# Cursor FX Releases

Public release channel for **Cursor FX by VINT Studio**.

- Private source repository: https://github.com/tkhongcan/CursorFX
- Public update repository: https://github.com/tkhongcan/CursorFX-Releases
- Latest version manifest: [version.json](./version.json)
- Release history: https://github.com/tkhongcan/CursorFX-Releases/releases

## Update manifest

The application checks `version.json` to learn the latest published version. A release is considered installable only after its Windows package has been uploaded and the manifest contains a valid HTTPS download URL and SHA-256 checksum.

## Publishing a release

1. Build and test the Windows application.
2. Create a GitHub Release with a version tag such as `v1.0.0`.
3. Upload the packaged installer/archive as a release asset.
4. Calculate its SHA-256 checksum.
5. Update `version.json` with the version, release page URL, asset URL, checksum, and release notes.
6. Test update detection and installation on a clean Windows 11 machine.

Do not publish source code, private credentials, access tokens, personal data, or user library/configuration backups in this repository.

## Current status

The repository is prepared as the public update channel. No installable application package has been published yet.
