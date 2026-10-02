# qiven-toolchain-win Agent Contract

qiven-toolchain-win is the pinned Windows build tools repository; see
`README.md`.

- Content under `cmake/`, `third_party/` and `toolchain.json` is
  version-pinned; consult `qiven-devkit` CMake usage law before changing
  pinning or layout.
- Engineering conventions (naming, layout, scripts) are canonical in the
  Devkit: `docs/conventions/README.md` there, and apply to THIS
  repository. Read that index before creating files, folders, branches or
  targets.
- Operator discovery surface (B6): canonical usage for operator
  subcommands (`surface`, `records`), workspace mechanisms (lock-update,
  resolver, bootstrap) and devkit tool surfaces (schema-check, deploy
  bundle) is qiven-devkit `docs/conventions/operator-usage.md`.
