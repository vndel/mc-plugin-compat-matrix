# mc-plugin-compat-matrix

Compatibility tracking and release test plan for Minecraft plugin fleets. The matrix records tested combinations; it does not infer compatibility from dependency metadata alone.

## Upgrade gate
Test the exact Paper/Velocity build, Java runtime, plugin set, config migration, startup/shutdown, and representative gameplay on a disposable copy. Upgrade one environment at a time and retain a rollback artifact.

Report failures with sanitized logs and reproducible steps. MIT licensed.
