# Ryvo for Fire TV

Install with Downloader:

    raw.githubusercontent.com/Dannyflo300543/ryvo-releases/main/ryvo.apk

This lane is **release-signed** (`518fa4be…`) — the same certificate as
https://www.ryvo.uk/r, which is what Downloader code **5072045** serves.
Never put a debug-signed APK here: Android refuses to install across a
signature change, so it would break updates for everyone installed from it.

Published by `ship-ryvo.js` in the Luxe repo, which fetches every install
path back afterwards and reads the version and certificate out of what
actually arrives.
