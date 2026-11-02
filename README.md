# Kingdom Defense by KRUPOY — Vercel Edition

## Deploy
1. Create a new GitHub repository, for example `kingdom-defense`.
2. Upload `index.html` to the repository root.
3. Import the repository in Vercel.
4. Framework preset: Other. Build command: leave blank. Output directory: `.`.
5. Deploy.

## Technical notes
- Static HTML/CSS/JavaScript. No Google Apps Script runtime.
- The original question bank and tower-defense rules are retained from the supplied `Index.html`.
- Player name, per-kingdom results and best stars are stored in browser LocalStorage.
- Result card can be exported as JPG.
- No remote database is connected in this first Vercel port. The saved data is local to the browser/device. A database adapter can be added later.
- `Code.gs` is intentionally not included because it only served the Apps Script HTML and Google Sheets reporting endpoint.
