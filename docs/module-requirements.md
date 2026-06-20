# Module Requirements

The beta carries the current 19-module standalone verification slice.

Required module artifacts use artifact family `standalone` and install under `mods/`.

## Required Modules

- `echoadaptercore`
- `echoashfallprotocol`
- `echocommonloot`
- `echocontentcore`
- `echocore`
- `echocreatureroles`
- `echofoundationcore`
- `echohealthcore`
- `echohudcore`
- `echomaterialcore`
- `echoplatformcore`
- `echoschemacore`
- `echoscreencore`
- `echostationcore`
- `echoterminal`
- `echotoolcore`
- `echovalidationcore`
- `echoweathercore`
- `echoworldstarter`

The seven added Phase 5 modules are graph-only Engine imports from ECHO-Modules release graph resources. Their old executable entrypoints are stripped so the standalone engine validates their content graph contracts without loading legacy runtime code.

## Strictness

The manifest preserves:

- `strictArtifacts: true`
- `strictContentGraph: true`
- `requireCrossRuntimeParity: true`

The engine refuses required module files when hash, size, descriptor, dependency, trust, or version checks fail.
