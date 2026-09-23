# qrdestock-extension-releases

Builds **signés par Mozilla** (canal *unlisted*) de l'extension Firefox QRDeStock,
publiés automatiquement par la CI du dépôt privé `qrdestock-extension` à chaque
push sur `main`.

- `updates.json` : manifeste de mise à jour lu par Firefox (`update_url`).
- `xpi/` : les `.xpi` signés.

Ne rien modifier à la main : ce dépôt est écrit par la CI.
