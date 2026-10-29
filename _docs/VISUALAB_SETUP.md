# Visualab Studio setup

## Branding

The source uses a provisional V mark and wordmark. Replace `visualab-icon.svg`, the `visualab-logo-*` SVGs and the desktop icons with official Visualab artwork when available. The Tauri bundle uses `com.visualabstudios.studio`; the native app uses a separate `.native` suffix. Local data is stored under `VisualabStudio` rather than importing upstream credentials.

## External services

The upstream desktop application contacts ArtCraft / Storyteller services for login, generation, credits and billing. Provider labels intentionally retain the provider names. Do not replace those hosts with the Visualab marketing domain: it does not implement their APIs. Accounts or API keys for chosen providers still need configuration. The backend services are in the separate `storytold/artcraft-services` repository.

## Before distribution

1. Remove or replace all resources explicitly excluded by NOTICE and audit other demo assets.
2. Configure your own providers or deploy and adapt a compatible backend.
3. Build on the target OS with the dependencies documented in dev_setup.md.
4. Verify login, uploads, generation, downloads, light/dark themes and window menus.
5. Configure your own signing certificates, updater endpoints and release workflow. Upstream CI relies on organization-specific shared workflows / secrets.

No credentials, paid generations, signed installers or independent backend were provisioned as part of the branding change.
