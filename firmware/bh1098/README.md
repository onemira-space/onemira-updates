# BH1098 production firmware feed

This directory is the stable update feed for supplier-built BH1098/BH1199
production firmware used by Mira Context.

The first approved firmware release will publish:

- `stable.json` — signed release metadata and BLE/USB asset URLs
- `stable.json.sig` — Ed25519 signature over the exact `stable.json` bytes

Firmware binaries are stored as immutable-version GitHub Release assets, not in
this branch. Until `stable.json` exists, clients must report that no production
firmware release is available and must not fall back to development firmware.

Schema: <https://updates.onemira.com/firmware/schema-v1.json>

