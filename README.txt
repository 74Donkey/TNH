# The Naked Hop Soaperie — Inventory & POS (Version 1)

This is a first working prototype for Windows/HP laptop + iPhone 15.

## What it does
- Product database with name, scent, ingredients, price, cost, stock and low-stock level
- Automatic SKU numbers such as NHS-0001
- Code 128 barcode generation
- QR code generation
- Printable barcode/QR sheets one product at a time
- Inventory adjustments
- iPhone camera scanning through the Scan & Sell screen
- Checkout/cart
- Automatic inventory deduction after a sale
- Sales history and dashboard
- Data is stored in the browser on the device

## Important for iPhone camera scanning
Apple Safari requires camera access to be served from a secure HTTPS website (or a suitable local development environment). Opening the HTML file directly on the iPhone will not reliably provide camera scanning.

The easiest next step is to publish this folder on a free HTTPS host such as GitHub Pages or another static web host. Then open the HTTPS address on the iPhone and choose Safari > Share > Add to Home Screen.

## Data warning
Version 1 stores data in browser storage. Do not rely on it as your only business record yet. The next version should add cloud synchronization and backups so the HP and iPhone always share the same inventory.

## Suggested next upgrades
1. Cloud database/synchronization
2. Product photos
3. Batch numbers and cure dates
4. Customer receipts
5. Tax settings for Canada/Ontario
6. CSV import/export
7. Profit reporting
8. Multi-device login
9. Label sheet printing with multiple labels per page
10. Optional Bluetooth/USB barcode scanner support
