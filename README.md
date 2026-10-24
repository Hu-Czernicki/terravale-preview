# Terravale — Live Preview

This public repository contains the **compiled preview**, not the private Terravale source code.

- The preview is built from Terravale Living Codex v0.11.0.
- The interface runs in **local demonstration mode** until Supabase + Discord OAuth is configured.
- The full source and database migrations remain in the separate private development repository.
- To publish, enable **Settings → Pages → Source: GitHub Actions**.
- This preview is publicly accessible and is intended for interface testing.

Deployment is managed by [the Pages workflow](.github/workflows/deploy.yml). It verifies the SHA-256 of the compiled site bundle and extracts the 577 static files without rebuilding or publishing the private code.
