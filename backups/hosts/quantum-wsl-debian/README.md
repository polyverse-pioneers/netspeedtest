# Backup Root: quantum-wsl-debian

This backup root tracks snapshots for `quantum-wsl-debian`.

## Migration Snapshot Notes

- Node runtime baseline is k3s on `quantum-wsl-trixie`.
- `secrets` and `proxy` runtime moved to k3s manifests.
- Legacy rootless Podman artifacts are candidates for cleanup only after k3s health checks pass.

## Paths

- Config snapshots: `./configs/latest/`
- Historical snapshots: `./snapshots/`
- Windows root cert export target: `/mnt/c/Users/Public/spinrikolab/certs/secrets-root-ca.crt`
