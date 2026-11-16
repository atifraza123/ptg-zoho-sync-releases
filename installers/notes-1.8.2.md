## What is new in 1.8.2 (16 Nov 2026)
- **QuickBooks Online:** a customer without a country takes the company's own country, so customers of a US company become *non-GCC* in Zoho (not UAE "VAT not registered"). Billable time / expense lines are sent with their amount and tax code. Zero-amount invoices are skipped instead of being reported as errors.
- **Zoho MCP links:** when a link's address briefly fails to resolve ("address not found"), the app retries for about half a minute before reporting it.
- **Clearer messages:** a missing *List Currencies* tool on the Zoho connector links is named; the source name is no longer doubled in the log.

Install: download PTG-Zoho-Sync-Setup-1.8.2.exe and run it (no administrator rights needed). It updates earlier versions in place; your profiles, keys and history are kept.

Windows SmartScreen may say *"Windows protected your PC"* because the installer isn't code-signed yet: click **More info → Run anyway**.
