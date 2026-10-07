# Analizador de loterías · Demo

**An interactive historical-data exploration interface by Xioleni Salazar.**

The demo presents filters, charts, and statistical views over a small, read-only sample of past `SUPER GANA` results. The interface is built with HTML, CSS, and JavaScript; Chart.js is loaded from jsDelivr.

**Vista previa:** [Abrir el analizador](https://xioleni.com/proyectos/analizador-loterias/)

## Run locally

Serve this folder from a local web server so the browser can load the sample JSON:

```powershell
py -m http.server 8000
```

Open `http://localhost:8000`.

## Demo scope

The repository contains a small historical sample in [`backup/loterias_backup.json`](backup/loterias_backup.json). Live synchronization and administrator actions belong to the hosted site backend and are not part of this static demo.

Historical frequencies and patterns describe past draws only. They do not predict future results or increase the chance of winning.

## Credits

Design and development: **Xioleni Salazar** · [xioleni.com](https://xioleni.com)
