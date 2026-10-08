# Account Pages site

This repository publishes its root from `main` at `www.maximspur.com`. Keep `CNAME` and the homepage redirect intact. Project Pages sites inherit this domain and publish beneath their repository names.

`visibility-lab.html` is the portable V4 build copied from `MaxSpur/visibility-lab`; `visibility-lab.source.json` records its exact source commit and checksum. Edit and validate in that source repository, then copy the committed build here. Before replacing the existing copy, verify it matches the recorded checksum and preserve any manual changes for review. The source repository's `DEPLOYMENT.md` describes the release steps.

Preview: `python3 -m http.server 8765 --bind 127.0.0.1`. Check `git diff --check`, compare the copied bytes and provenance, commit the intended files and push `main`; this starts the existing Pages deployment. Verify its success and the live HTML checksum before reporting publication.
