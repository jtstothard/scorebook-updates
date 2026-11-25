# Scorebook game versions

This repository holds one thing: the signed list of Football Manager versions that the Scorebook desktop app can read.

- `v1/versions.json` is the list and its signature in one file. The app fetches it, checks the signature against keys built into the app, and only then uses it. A file that fails the check is ignored.
- The file is the same for everyone. Fetching it sends nothing about you, your career or your computer.
- There is no source code here.

If `v1/versions.json` is not here yet, no list has been published.
