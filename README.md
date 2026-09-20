# DataVista Pro

DataVista Pro is a client-side browser analytics tool for CSV and Excel workbooks. Users select a local file, inspect summary metrics and charts, filter the data, and export a PDF report from a single static page.

## How it runs

Open `index.html` in a modern browser. The page currently loads pinned releases of SheetJS, Chart.js, and jsPDF from public CDNs, so those libraries require network access even though the selected workbook is processed in the browser.

## Privacy boundary

Imported files are read by browser JavaScript and are not intentionally uploaded by this repository. Do not commit user workbooks, generated reports, credentials, or private datasets.

## Validation

There is no build system or automated test suite yet. Before publishing a change, exercise CSV/XLSX import, summary metrics, filtering, chart rendering, error states, and PDF export with synthetic fixtures at narrow and wide browser sizes.

## Repository continuity

Read [AGENTS.md](AGENTS.md) and [docs/PROJECT_STATE.md](docs/PROJECT_STATE.md) before continuing.
