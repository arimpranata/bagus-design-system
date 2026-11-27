# bagus-design-system
Standarisasi style dan layout Bagus Discovery website

WordPress plugin for bagusjati.com, bagusagropelaga.com, puribaguscandidasa.com, puribaguslovina.com and puribagusmanggis.com.

This repository is the update server: the installed plugin (3.6.0+) reads `update.json` every 6 hours and installs `bagus-design-system.zip` when `version` is newer.

## Releasing a new version
1. Replace `bagus-design-system.zip` with the new build (folder `bagus-design-system/` inside).
2. Set `version` (and `changelog`) in `update.json` to the version in the plugin header.
3. Commit to `main`. Sites update within 6 hours (or WordPress → Settings → Bagus Design System → Check for updates now).
