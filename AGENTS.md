# AGENTS.md — iot-esphome

ESPHome configurations for the household's devices, one `*.yaml` per device, compiled in CI by
`.github/workflows/build.yaml`.

## Design history

Which app a device talks to, the MQTT topics and REST endpoints it uses, and why the configs look the
way they do live in a private knowledge base, not in this repo. Use the global `knowledge-base` skill
before changing how a device integrates with the rest of the homelab.
