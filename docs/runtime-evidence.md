# Runtime Evidence

The current release payload is generated from `ECHO-Standalone-Engine` version `2.0.0-beta.5`.

## Build Evidence

- Engine build: PASS
- API build: PASS
- Java target: 21
- Compiler flags: `--release 21 -Xlint:all -Werror`
- Headless smoke: PASS
- Content graph evidence: PASS
- AdapterCore canonical bridge audit: PASS

## Staged Evidence Files

```text
release-assets/v2.0.0-ashfall-standalone-engine-edition-beta.5/echo-release.json
release-assets/v2.0.0-ashfall-standalone-engine-edition-beta.5/release-audit.json
release-assets/v2.0.0-ashfall-standalone-engine-edition-beta.5/checksums.txt
```

The latest staged release metadata records the engine source revision as `ECHO-Standalone-Engine ca323c5889533b44ff04d9b6480118cbff12e8eb, 2026-06-21`.

The beta.5 payload reports 19 modules, 140 graph nodes, 110 graph edges, 16 features, and zero unresolved references.
