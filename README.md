# Enumuser

VB6 dual-store user admin tool (`EnumUsers.exe`, product UserAdmin) that adds/deletes NT domain users and Access workgroup users in one pass via NetAPI32 and DAO 3.5. Starts on a secure login form, enumerates domain groups/users, and syncs group membership when Access groups match network groups. Company: Direct Communications.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `UserAdd` (`EnumUsers.vbp`) | VB6 | WinForms exe | NT + Access user administration |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `EnumUsers.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Microsoft DAO 3.5 Object Library
- NetAPI32 / domain admin rights on the target PDC or server

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/Enumuser`.
Company names in project files: Direct Communications. NetAPI helpers from Microsoft Knowledge Base; UI/orchestration by Robert May (1998).

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
