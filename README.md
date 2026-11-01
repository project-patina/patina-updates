# Patina updates

Release packages and the update manifest for the Patina launcher.

`latest.json` describes the current version and `latest.json.sig` is its signature. The launcher accepts a manifest only if it verifies against the public key built into the launcher, and accepts a package only if its SHA-256 matches the signed manifest. A manifest marked `critical` installs without asking.

Source code: [project-patina/patina](https://github.com/project-patina/patina).
