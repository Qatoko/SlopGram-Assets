# SlopGram Assets

Public downloadable resources for the SlopGram plugin.

## Layout

- `assets/mascot/gipti.webp` — Gipti, the update-restart mascot.

To update a picture, replace the file **at the same path and with the same filename**. SlopGram checks GitHub on startup, compares the Git blob hash and downloads only new or changed files. It keeps the last successful download in the app's persistent private storage and uses it offline.

If a download fails, the previous version is kept. After successful synchronization, obsolete files that were deleted or renamed in this repository are cleaned up.

You can add additional image assets under `assets/` without embedding their data into DEX. New UI features still need a code reference to the asset's path.
