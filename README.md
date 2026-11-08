# escape releases

Public builds of escape (desktop app and `escape-server`) and the update manifest the app reads.

- Update manifest: `https://github.com/MakFly/escape-releases/releases/latest/download/latest.json`
- Every update artifact is signed with escape's updater key (Ed25519, minisign); the app refuses an artifact whose
  signature does not verify against the public key it embeds.

The source code lives in a private repository; this one only hosts release artifacts.
