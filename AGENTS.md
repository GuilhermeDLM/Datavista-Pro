# DataVista Pro repository instructions

Read `README.md` and `docs/PROJECT_STATE.md` before changing the app.

- DataVista Pro is a single-page browser application in `index.html`.
- Keep imported spreadsheet data in the browser unless the user explicitly requests and approves a backend.
- Never add uploaded workbooks, generated customer reports, credentials, or personal datasets to the repository.
- Preserve CSV/XLSX ingestion, charting, filtering, and PDF export when changing the interface.
- The current app loads pinned third-party libraries from public CDNs. Review and deliberately update those versions rather than floating them.
- Validate changes in a browser with representative synthetic files and check narrow and wide layouts.
- Use focused branches and commits; do not rewrite shared history or force-push.
