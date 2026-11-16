# LAMP PRO - online update files

The LAMP PRO page (System -> Firmware -> Check online) reads `version.json` from this repo. If `latest` is newer
than the lamp, the phone downloads `file` and sends it to the lamp; the lamp checks the sha256 inside the file.

- `version.json` - latest version, file, size, sha256, notes (English / Hindi)
- `firmware/LAMP_PRO_FW_vNN_UPDATE.bin` - OTA files (not the whole-flash files)

Only compiled update files are here - no source code.
