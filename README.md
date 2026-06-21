# Ashfall Standalone Engine Edition

Ashfall Standalone Engine Edition is the beta pack lane for the new `echo-standalone-engine` runtime.

This repo stages release assets and public docs for a side-by-side verification lane. It does not replace Ashfall Native Edition, Ashfall NeoForge Edition, or the legacy Ashfall Standalone Edition.

## Current Release

```text
2.0.0-beta.5
```

Staged assets:

```text
release-assets/v2.0.0-ashfall-standalone-engine-edition-beta.5/
```

Primary assets:

- `ashfall-standalone-engine-edition-2.0.0-beta.5.zip`
- `ashfall-standalone-engine-edition-beta-2.0.0-beta.5.pack.json`
- `checksums.txt`
- `echo-release.json`
- `release-audit.json`

## Runtime Contract

- Pack id: `ashfall-standalone-engine-edition`
- Display name: `Ashfall Standalone Engine Edition`
- Channel: `beta`
- Validation: `warning`
- Loader id: `echo-standalone-engine`
- Runtime product id: `echo-standalone-engine`
- Runtime target: `echo_runtime_standalone`
- Required Java: `21+`

## Scope

This beta is a graph-first playable vertical slice for runtime, install, repair, launch, and content graph evidence. It includes the current 19-module standalone verification slice and preserves strict artifact and content graph behavior.

Full Ashfall gameplay parity is not claimed yet.

## Docs

- [Install](docs/install.md)
- [Update Flow](docs/update-flow.md)
- [Module Requirements](docs/module-requirements.md)
- [Runtime Evidence](docs/runtime-evidence.md)
- [Gameplay Evidence](docs/gameplay-evidence.md)
