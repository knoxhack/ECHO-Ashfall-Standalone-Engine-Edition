# Install

Ashfall Standalone Engine Edition installs as a ZIP-backed standalone pack.

## Requirements

- Java 21 or newer
- ECHO Launcher with `standalone-engine` runtime mode support
- Pack manifest: `ashfall-standalone-engine-edition-beta-2.0.0-beta.5.pack.json`
- Pack artifact: `ashfall-standalone-engine-edition-2.0.0-beta.5.zip`

## Expected Install Layout

```text
Ashfall Standalone Engine Edition/
  echo-standalone-engine-2.0.0-beta.5.jar
  pack.json
  content-graph-evidence.json
  checksums.sha256
  run.ps1
  run.sh
  mods/
```

The Launcher verifies required files from the manifest, then starts the engine with:

```text
java -Dfile.encoding=UTF-8 -jar echo-standalone-engine-2.0.0-beta.5.jar --pack-root <installRoot> --manifest pack.json --save-root <installRoot>/saves
```

## Warning Gate

The pack is installable for verification but remains warning-gated until public install, repair, first-launch, and gameplay evidence exist.
