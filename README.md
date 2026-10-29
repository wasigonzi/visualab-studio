# Visualab Studio

Creative desktop application customized for **Visualab Studios**. Based on [ArtCraft](https://github.com/storytold/artcraft).

- Black / turquoise identity for the React/Tauri app and the experimental native Rust app.
- Visualab application name, isolated application identifiers and data directory.
- Provisional vector wordmark and V icon; these are not a reproduction of an official Visualab logo.
- Upstream Google Analytics and Clarity tags removed. PostHog requires your own environment key.

## Development

See [_docs/dev_setup.md](_docs/dev_setup.md) for the original platform dependencies and commands. Internal crate names and Nx targets remain `artcraft` to preserve build compatibility.

## Services and release status

This is a branding fork, not an independent hosted AI service. AI providers, billing, authentication and remote model catalogs retain their original endpoints and require the corresponding accounts / credentials. Visualab website links are informational, not replacement API endpoints.

No Visualab installer has been built or signed yet. A desktop build and interactive verification are required before distribution. Resources excluded by the upstream NOTICE (sounds, memes, some skyboxes, motion files and animation previews) remain in the source and require removal or replacement before a commercial release. See [VISUALAB_SETUP.md](_docs/VISUALAB_SETUP.md).

## License and attribution

Copyright (c) 2026 ArtCraft Team and the ArtCraft contributors. Code is available under [MIT](LICENSE-MIT) or [Apache-2.0](LICENSE-APACHE). Preserve [NOTICE](NOTICE), including third-party licenses and exclusions. Visualab is an independent customization, not an official ArtCraft release.
