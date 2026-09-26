# Famous Sales Factory Outlet — Billing Software

A free, offline billing app built for the shop. It runs from a single file —
no install, no internet needed after the first open (apart from loading the
page's font once).

## File

`famous-sales-factory-outlet-billing.html`

## How to run it

1. Download the file onto the shop computer.
2. Open it in **Chrome** or **Edge** (works best there — printing especially).
3. That's it. Bookmark it or keep a shortcut on the desktop.

To use it on more than one computer, download the same file onto each one.
Each computer keeps its **own** data — see "Where your data lives" below.

## Logging in

- Click **Lock** any time to lock the screen.
- **Owner** — full access (Home, Products, Sales, Settings). Default PIN: `1234`.
  **Change this before real use** — Products tab → Shop settings → New owner PIN.
- **Cashier** — billing screen only, no PIN needed. Safe to leave open at the counter.

## What it does

**Home (owner only)**
Today's sales, bills, items sold, profit, low-stock list, and 30-day best sellers.

**New bill**
- Search or scan a product to add it. Scanning works with most barcode scanners —
  click the search box, scan, done.
- Set quantity, add a serial/IMEI number per item, apply a discount, pick a GST
  rate, add an old-device exchange value, and choose a payment method
  (Cash / UPI / Card / EMI / Split).
- **Print bill** shows the finished invoice on screen with a **Print** button.
  Choose "Save as PDF" if there's no printer connected.

**Products (owner only)**
- Add, edit, delete products — name, price, stock, barcode/code, HSN code,
  cost price, and warranty period (months).
- Low-stock items are flagged in red.
- **Shop settings**: GSTIN, address (printed on bills), owner PIN, low-stock
  threshold, and backup/restore.

**Sales (owner only)**
- Filter by date, see total sales, products sold, and profit.
- Every bill is listed with **Reprint** and **Delete** buttons.
  Deleting a bill puts its stock back and needs two clicks to confirm.
- **Warranty check** — search a serial number, phone number, or customer name
  to see if a product's warranty is still active.

## Backups — please do this regularly

All data (products, bills, settings) is stored **only in that browser, on that
computer**. Clearing browser data, or switching computers/browsers, loses it.

- **Products tab → Shop settings → Download backup** — saves a `.json` file.
- **Restore backup** — loads a backup file back in (replaces current data).

Do this at least once a week, and always before clearing browser data or
updating the file.

## Updating to a newer version

Downloading a new copy of the HTML file does **not** erase your data — data is
kept separately by the browser. But always back up first, just in case.

## Known limits (be upfront about these)

- Data does not sync between computers or phones — each device is separate.
- The owner PIN is a basic lock, not real security.
- No automatic SMS/online bill sharing yet (needs a paid, registered SMS
  service — skipped for now to keep this free).
- No repair job cards, returns/credit notes, or customer list yet.

## Possible next additions

Repair job cards, returns/credit notes, a saved customer list, a narrow
receipt-printer layout (58/80mm rolls), and Excel export of sales.
