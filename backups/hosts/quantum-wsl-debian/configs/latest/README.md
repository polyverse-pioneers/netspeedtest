# Config Snapshot Notes (latest)

These snapshots are captured from `quantum-wsl-debian` after migration toward k3s-first runtime.

## Runtime Notes

- `secrets` and `proxy` deployment source is k3s manifests.
- Rootless Podman bootstrap on this node is deprecated.
- Keep environment variable names aligned with current repos (`SITE_URL`, `DB_CONNECTION_URI`, `REDIS_URL`, `INFISICAL_*`).
