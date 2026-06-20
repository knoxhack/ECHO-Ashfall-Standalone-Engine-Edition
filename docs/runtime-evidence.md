# Runtime Evidence

The current release payload is generated from `ECHO-Standalone-Engine` version `2.0.0-beta.2`.

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
release-assets/v2.0.0-ashfall-standalone-engine-edition-beta/echo-release.json
release-assets/v2.0.0-ashfall-standalone-engine-edition-beta/release-audit.json
release-assets/v2.0.0-ashfall-standalone-engine-edition-beta/checksums.txt
```

The latest staged release metadata records the engine source revision as `ECHO-Standalone-Engine 50e039a255b62d3ce04acd80bb9b90dd5f0d5742, 2026-06-20`.

The beta.4 payload reports 18 modules, 133 graph nodes, 109 graph edges, 16 features, and zero unresolved references.
