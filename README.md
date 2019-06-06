# pnpm-dependency-versions

## Repro
1. `pnpm install`
   - Installs `repeat-string@1.6.0` as specfied in `pnpm-lock.yaml`
2. `git clean -xdf`
3. `pnpm install --no-prefer-frozen-shrinkwrap`
   - Installs `repeat-string@1.6.1` (latest on npmjs.com)
