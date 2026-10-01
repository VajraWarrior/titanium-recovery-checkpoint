# titanium-recovery-checkpoint

Signed recovery checkpoints only. No recovery pack, no canon, no secrets.

- `current.json` is the latest signed checkpoint.
- `checkpoints/` keeps every published checkpoint, append-only.
- A consumer trusts nothing here until the checkpoint signature verifies against its own pinned trust root.
