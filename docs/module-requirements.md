# Module Requirements

The beta carries the current 12-module standalone verification slice.

Required module artifacts use artifact family `standalone` and install under `mods/`.

## Required Modules

- `echoadaptercore`
- `echoashfallprotocol`
- `echocommonloot`
- `echocreatureroles`
- `echofoundationcore`
- `echomaterialcore`
- `echoscreencore`
- `echostationcore`
- `echoterminal`
- `echotoolcore`
- `echoweathercore`
- `echoworldstarter`

## Strictness

The manifest preserves:

- `strictArtifacts: true`
- `strictContentGraph: true`
- `requireCrossRuntimeParity: true`

The engine refuses required module files when hash, size, descriptor, dependency, trust, or version checks fail.
