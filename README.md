# Phone Zone POS

### Offline-first POS & business management software for mobile phone shops

Phone Zone is a purpose-built desktop POS for mobile phone retailers and repair shops. It brings **billing, inventory, customers, suppliers, expenses, credit, repairs, reporting, backups, and day-to-day shop operations** into one application.

> **Built for real phone shops — not a generic POS with a phone-store label on it.**

---

## Why Phone Zone?

Running a mobile shop means dealing with much more than a cash counter.

You need to know:

- Which phone is in stock — and its exact IMEI
- What you paid for it and what you sold it for
- Which customer bought which device
- How much customers still owe you
- Which suppliers you owe money to
- Which accessories are running low
- How much cash, UPI, and financed sales happened today
- Which repairs are waiting for parts or customer approval
- How profitable the shop actually is

**Phone Zone is designed around those workflows.**

---

## Features built for mobile phone shops

### Point of Sale & Billing

- Fast POS billing designed for phone-shop workflows
- Barcode-scanner friendly input
- Customer search and auto-suggestions
- Cash, UPI, card, finance/credit and other payment workflows
- Partial payments and customer outstanding balances
- Complimentary gifts/freebies with stock validation
- Professional tax invoice generation and printing
- New-phone IMEI association with sales for device-level traceability

### Phone Inventory Management

Manage different types of stock without forcing everything into the same workflow:

- **New Phones** — purchase cost, selling price, GST, HSN, supplier and IMEI tracking
- **Used Phones** — seller details, purchase history, IMEI tracking and margin-scheme support
- **Accessories** — bulk stock, optional serial-number tracking and flexible tax handling
- **Repair Services** — service catalog without treating services as physical inventory

Inventory tools include:

- Individual IMEI / serial tracking
- Supplier-linked purchase history
- Stock valuation at cost
- Retail valuation
- Low-stock and out-of-stock monitoring
- Bulk inventory actions
- Excel export
- Professional A4 inventory printing
- Safe deletion and historical-sales protection

### Repair Shop Management

Phone Zone can also operate as a repair-management system alongside retail sales.

- Customer device intake
- Device model, serial number and IMEI capture
- Problem description and diagnosis
- Device condition and received accessories
- Technician assignment
- Repair job numbers and lifecycle tracking
- Customer approval before repair
- Estimated and final repair costs
- Spare-parts consumption from inventory
- Parts cost vs customer charge tracking
- Labor/service charges
- Repair profitability and gross-margin visibility
- Repair invoice generation
- Customer repair history
- Professional repair ticket printing

Typical workflow:

```text
Customer brings phone
        ↓
Device intake
        ↓
Diagnosis & estimate
        ↓
Customer approval
        ↓
Parts + repair work
        ↓
Quality check
        ↓
Ready for pickup
        ↓
Invoice & payment
```

### Customers & Credit

- Customer profiles
- Purchase history
- Repair history
- Credit/outstanding tracking
- Partial payment history
- Payment-mode audit trail
- Customer ledger

### Suppliers & Payables

- Supplier master records
- Supplier contact information
- Purchase-linked supplier records
- Supplier returns
- Supplier payable tracking
- Loans & liabilities
- Loan/liability editing
- Repayment tracking
- Lender suggestions based on existing records

### Reports & Business Intelligence

Phone Zone is designed to answer the questions a shop owner actually asks at the end of the day.

#### Sales Audit

- Daily revenue
- Buying cost
- Gross profit
- GST collected
- Invoice count
- Items sold
- Sales by category
- Cash / UPI / finance payment breakdown
- Total payment reconciliation
- Inventory stock volume
- Inventory cost valuation
- Retail valuation
- Low-stock item count
- Out-of-stock item count
- Itemized sales audit

#### Inventory Valuation

Understand how much capital is sitting in your shop:

```text
Stock Quantity × Cost Price  →  Stock Worth
Stock Quantity × Retail Price →  Retail Valuation
```

Repair services are kept separate from physical stock valuation.

### Export & Printing

- Complete inventory Excel export
- Multi-category inventory export
- New Phones / Used Phones / Accessories / Repair Services selection
- Multi-select category filtering
- Select All / Clear All
- Dedicated Repair Services export layout
- Professional A4 inventory printouts
- Sales audit printouts
- Repair ticket printouts
- Tax/GST reporting exports
- Business backup export

### Data Safety

Your shop's data is business-critical.

Phone Zone includes safeguards designed around that reality:

- SQLite-based local data storage
- Automated backup support
- JSON backup and restore
- Pre-migration database backups
- Versioned database migrations
- Transactional schema changes
- Schema validation
- Startup protection when a required migration fails
- Historical financial records are not silently rewritten during migrations

### Security & Reliability

- Master password protection
- Machine-bound licensing
- Offline-first operation
- Local database
- Crash-resilient startup
- Automatic application updates
- Stable-release filtering for updates

---

## Designed for the complete phone-shop operation

```text
                         PHONE ZONE
                             │
        ┌────────────────────┼────────────────────┐
        │                    │                    │
       SALES              INVENTORY            REPAIRS
        │                    │                    │
     Billing          New / Used /           Device Intake
     Payments          Accessories             Diagnosis
     Customers         IMEI / Serial           Parts
     Credit            Suppliers               Labor
        │              Valuation               Billing
        └────────────────────┼────────────────────┘
                             │
                         REPORTING
                             │
                 Sales • Profit • Stock
                 Payments • GST • Repairs
```

---

## Built for your shop

Every mobile shop has its own workflow.

If you need a **custom POS / inventory / repair-management application for your mobile shop**, Phone Zone can be adapted around your requirements instead of forcing your business into a generic template.

### Interested in a custom solution?

**Contact the developer to discuss your shop's requirements, workflow and custom features.**

**Developer:** Umair Sheikh  
**GitHub:** [@umair2k1](https://github.com/umair2k1)

Whether you run:

- A mobile phone retail store
- A used-phone business
- An accessories shop
- A phone repair center
- Or a combination of all four

Phone Zone is built to bring those operations into one system.

---

## Latest Release — v1.3.5

The latest release expands Phone Zone from a retail POS into a more complete **phone-shop operations platform**, with major work across repairs, inventory, reporting, liabilities, migrations and printing.

See the full release notes in [`RELEASE_NOTES.md`](./RELEASE_NOTES.md).

---

## Release downloads

Official application releases and installers are published in this repository.

> **Note:** Phone Zone is a commercial shop-management application. Contact the developer for deployment, customization and licensing information.

---

## Project

**Phone Zone — Offline Desktop POS for Mobile Phone Shops**

Built with Electron, Vite, Vanilla CSS and SQLite.

---

*Phone Zone — Run your shop. Track every device. Know your numbers.*
