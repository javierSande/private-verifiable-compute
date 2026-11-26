# PVC vendor submodules

The verifier and blind RSA compatibility forks are tracked as nested
submodules:

- `trustee` (`pvc-dcap-qvl`) provides the TDX verifier and its event-log crate.
- `blind-rsa-signatures` (`pvc-derive-more-fix`) provides the `derive_more`
  compatibility fix.

Initialize them from a fresh clone of this repository with:

```bash
git submodule update --init --recursive
```
