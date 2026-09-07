# QueryTool

Rio Tinto Policy Query Tool (`QueryTool.exe`) that looks up a domain username via ADSI/ADO, shows policy attributes (pipe-delimited policy name/status), and can write an extension-attribute style value back. Open `QueryTool.vbp` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `QueryTool` (`QueryTool.vbp`) | VB6 | WinForms exe | QueryTool |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `QueryTool.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `TABCTL32.OCX`

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/QueryTool`.
Company names in `.vbp` files: Rio Tinto.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
