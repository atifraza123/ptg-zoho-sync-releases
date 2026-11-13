## What is new in 1.8.0 (13 Nov 2026)
- **Bill payments to Zoho.** Pay a supplier bill in QuickBooks Desktop (Pay Bills), QuickBooks Online or Odoo, and on the next sync the app records the same payment in Zoho Books as a vendor payment against the bill, so the Zoho bill shows *Paid* or *Partially paid*.
  - Turn it on under **Supplier bills → Bill payments: source ERP → Zoho**, click *Load Zoho accounts*, and map your bank / card accounts (`ERP account = Zoho account`).
  - Each payment is copied once; a payment larger than the Zoho balance is reported, not copied; vendor credits are not copied.
  - Record bill payments only in the source ERP.

Install: download PTG-Zoho-Sync-Setup-1.8.0.exe and run it (no administrator rights needed). It updates earlier versions in place; your profiles, keys and history are kept.

Windows SmartScreen may say *"Windows protected your PC"* because the installer isn't code-signed yet: click **More info → Run anyway**.
