# Update Flow

The Engine Edition follows the standard Launcher ZIP install and repair path.

## Install

1. Resolve `ashfall-standalone-engine-edition`.
2. Download the pack manifest.
3. Download `ashfall-standalone-engine-edition-2.0.0-beta.2.zip`.
4. Extract into `Ashfall Standalone Engine Edition`.
5. Write `.echo/installed-manifest.json`.
6. Verify required files, hashes, sizes, Java 21, engine jar, and content graph evidence.

## Repair

Repair uses the manifest file list as authority. Missing or corrupt required files are restored from the pack ZIP. Module JARs remain under `mods/`.

## Compatibility

This lane uses runtime mode `standalone-engine`. Legacy `native-runtime` and `standalone-runtime` profile values remain compatibility paths for old standalone packs.
