# OpenRock-Events

A pub/sub layer over Bedrock's own world.beforeEvents/afterEvents - OpenRock makes the one real .subscribe() call per native event and fans out to every registered handler, each isolated by its own try/catch.

Part of the [OpenRock](https://github.com/codex-alchemist-dev/OpenRock) Minecraft Bedrock mod-packaging ecosystem - a Codex Alchemist project, under Fireball Everything. Consumed as a real git submodule at `libs/events` in the main OpenRock repo, and directly `npm require`/`import`-able (real top-level CommonJS exports, esbuild-CJS/ESM-interop-compatible) by any mod's own build-time kernel registration or real in-game script.

## License

MPL-2.0. See [LICENSE](LICENSE).
