# GAA Performance HQ — standalone copy

Same app as the Claude-hosted HQ, packaged to run anywhere.

## Storage outside Claude
- Data is saved in **this browser only** (localStorage). It does **not** sync between devices.
- Move data in and out with **Data & storage → Full JSON backup / Restore**.
- Cross-device sync outside Claude needs a hosted database (e.g. Supabase/Firebase) and your own account. That adapter is not built yet.

## Host on GitHub Pages (free)
1. Create a repository, upload `index.html`, `manifest.webmanifest`, `icon.svg`.
2. Settings → Pages → Deploy from branch → `main` / root → Save.
3. Open the Pages URL on your iPhone in Safari → Share → **Add to Home Screen**.

## Move your data from the Claude HQ
1. In the Claude HQ: Data & storage → **Full JSON backup**.
2. In the standalone copy: Data & storage → **Restore / merge JSON**.

Keep using one copy as your main record at a time, or you'll have two diverging datasets.
