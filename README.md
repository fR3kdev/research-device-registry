# Per-device ownership registry

Every known physical unit with a resolved quantity receives a stable public-safe asset_id and its own devices/<asset-id>/OWNERSHIP.yaml.

- Individual unit records: **98**
- Unresolved-count batches: **5**
- Canonical possession source: ../ASSET-STATE.md
- Sanitized public mirror: fR3kdev/research-device-registry
- Private companion: fR3kdev/research-device-registry-private

## Split-brain prevention

fR3kdev/research remains canonical for possession/condition. The public mirror is generated from this directory. The private companion may add serials, local aliases, purchase records and operational notes, but it must never override public identity/state without updating canonical research first.

## Privacy boundary

Public records never contain serial numbers, MAC addresses, IMEI/ICCID, credentials, private keys, exact home-network endpoints or precise storage/location data. The private companion may hold non-secret sensitive identifiers when operationally useful, but credentials and secret values do not belong in Git at all.

## Unitization

Rows whose source quantity is multiple or 1+ are represented under batches/ until each physical unit is counted. No fake per-unit IDs are invented.
