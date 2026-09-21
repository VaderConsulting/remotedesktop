# remotedesktop

VB6 desktop-share pair (`PGetDesktop` / `PSendDesktop`): viewer requests a desktop JPEG over Winsock UDP; sender captures via `GetDesktopBitmap.dll` and streams the file back. Open `PGetDesktop.vbp` or `PSendDesktop.vbp` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `PGetDesktop` (`PGetDesktop.vbp`) | VB6 | WinForms exe | Request and display remote desktop JPEG |
| `PSendDesktop` (`PSendDesktop.vbp`) | VB6 | WinForms exe | Capture desktop and send over Winsock |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `PGetDesktop.vbp`
- `PSendDesktop.vbp`

## Requirements

- Visual Basic 6.0 IDE

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Old/remotedesktop`.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
