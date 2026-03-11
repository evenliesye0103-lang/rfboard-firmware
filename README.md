# RF-BOARD Firmware Bank

Static firmware hosting for RF-BOARD OTA updates.

## URLs

- latest metadata: `https://evenliesye0103-lang.github.io/rfboard-firmware/latest.json`
- firmware files: `https://evenliesye0103-lang.github.io/rfboard-firmware/firmware/...`

## Update flow

1. Build firmware from RF-BOARD project
2. Copy generated `.bin` and `latest.json` from local `out/`
3. Commit to this repository
4. GitHub Pages serves the files
