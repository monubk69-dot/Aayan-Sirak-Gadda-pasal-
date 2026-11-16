AAYAN SIRAK GADDA PASAL – MANAGER (OFFLINE V3)

Files:
- index.html
- manifest.webmanifest
- sw.js

HOW TO USE
1. Upload all three files to the root of your GitHub repository (same folder).
2. Enable GitHub Pages: Repository > Settings > Pages > Deploy from branch > main > /(root) > Save.
3. Open the published Pages URL in Chrome on Android.
4. Use Chrome menu > Add to Home screen / Install app.
5. First password: 1234. Change it in Settings.

IMPORTANT OFFLINE NOTES
- The app stores records in the browser on the device using local storage.
- It does NOT sync across phones and does NOT make online backups.
- Download a JSON backup regularly from Settings > Backup & restore.
- A PWA must be opened once online to load/cache its files; after that it can work offline.
- Do not clear Chrome site data or uninstall before making a backup.

FEATURES
- Products with name, variation, category, size, weight, material, cost and suggested price.
- Sales with multiple products, one combined sale price, cash + QR split, optional customer details.
- Purchase cost auto-calculated from product cost, with manual total cost override.
- Expenses split between cash/galla and QR/bank.
- Separate date-based khata with opening cash, galla-for-change, actual counted cash and difference.
- Daily calculation follows the requested formula:
  cash sales + QR + expenses - total sales - galla kept for change.
- Dashboard, date-range reports, gross/net profit and best-selling product quantities.
- CSV export (opens in Excel) and Print > Save as PDF.
- Shared local password and member-name selector.
- JSON backup and restore.

LIMITATIONS / NEXT IMPROVEMENTS
- This is an initial offline build. Entry editing is not yet included for sales and expenses (deletion is available); previous khata fields can be updated.
- The common password is a convenience lock, not strong security. Anyone with access to the device/browser storage may be able to inspect local data.
- CSV is Excel-compatible, not a formatted .xlsx workbook.
- No stock tracking.
