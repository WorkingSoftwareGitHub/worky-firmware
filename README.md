# Worky firmware

Signed firmware releases for Worky, the desk pet. Every Worky checks
`releases/latest/download/manifest.json` every 6 hours and installs newer versions by itself.

Releases are published by `scripts/release.sh` in the (private) source repo. Each Worky only
installs firmware whose manifest is signed with the Worky update key, so a file uploaded here
by hand is ignored.
