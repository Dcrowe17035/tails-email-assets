# tails-email-assets

Public hosted images for Tails Pet Resort HTML emails (photos and logos only, no font files).

## Upload these five binaries to repo root (Add file → Upload files)

The GitHub API path used by automation can only commit text, so JPEG/PNG binaries are not on `main` yet. Drop these from `meet-greet-emails/hosted/` (do **not** upload `.ttf` / `.otf` fonts):

- lobby-doodle.jpg
- yard-sniff.jpg
- logo-white.png
- logo-forest.png
- bayshore-tagline-white.png

ASCII base64 copies already live under `b64/`. A decode workflow is at `.github/workflows/decode-assets.yml` — enable Actions if you want future `b64/` pushes to write the binaries automatically.

## Hotlink URLs (after the five files are on main)

- https://raw.githubusercontent.com/Dcrowe17035/tails-email-assets/main/lobby-doodle.jpg
- https://raw.githubusercontent.com/Dcrowe17035/tails-email-assets/main/yard-sniff.jpg
- https://raw.githubusercontent.com/Dcrowe17035/tails-email-assets/main/logo-white.png
- https://raw.githubusercontent.com/Dcrowe17035/tails-email-assets/main/logo-forest.png
- https://raw.githubusercontent.com/Dcrowe17035/tails-email-assets/main/bayshore-tagline-white.png

jsDelivr mirrors: `https://cdn.jsdelivr.net/gh/Dcrowe17035/tails-email-assets@main/<file>`
