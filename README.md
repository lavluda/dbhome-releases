# DBHome — Releases

Public distribution channel for [DBHome](https://github.com/lavluda/dbhome)
(the source repository is private).

This repo holds **only build artifacts**: signed installers for macOS, Linux,
and Windows, plus the `latest.json` manifest that the in-app updater reads.

- Updater endpoint: `releases/latest/download/latest.json`
- Every artifact is Minisign-signed; the app verifies signatures against an
  embedded public key before applying any update.

Releases here are produced automatically by CI in the private source repo.
Do not commit source or secrets to this repository.