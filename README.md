# aur-obscura-browser-bin

GitHub Actions wrapper for publishing `obscura-browser-bin` to the AUR.

The AUR package repository is tracked as a submodule at `aur/obscura-browser-bin`.
The `Publish AUR package` workflow publishes the submodule's `PKGBUILD` to
`ssh://aur@aur.archlinux.org/obscura-browser-bin.git` using the
`AUR_SSH_PRIVATE_KEY` repository secret.
