## What is new in 1.8.1 (16 Nov 2026)
- **Different home currencies.** When the source company's home currency differs from the Zoho organization's (for example Intuit's US QuickBooks Online sandbox in USD into a UAE Zoho organization in AED), invoices, credit notes and payments now go to Zoho in their own currency and Zoho converts them with the exchange rate set in **Zoho Books → Settings → Currencies** (FTA: the Central Bank of UAE rate; USD 3.6725). Before, the sync was refused.
- If the currency is not set up in Zoho, the sync stops with a message naming it.
- Same home currency on both sides: nothing changes.

Also in 1.8: bill payments made in QuickBooks Desktop / Online or Odoo are recorded in Zoho against the bill.

Install: download PTG-Zoho-Sync-Setup-1.8.1.exe and run it (no administrator rights needed). It updates earlier versions in place; your profiles, keys and history are kept.

Windows SmartScreen may say *"Windows protected your PC"* because the installer isn't code-signed yet: click **More info → Run anyway**.
