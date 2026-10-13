# MAGNA UMROH — GitHub Source v1.1

Prototype frontend for **MAGNA UMROH**, an Umrah Travel Management Platform. This version updates the public landing page, login demo, admin dashboard, and Core / Travel Partner / POS-Cashier / AI modules using the visual direction from the supplied **Palmeera Lounge v2.0** PDF.

## Branding
- Product name remains **MAGNA UMROH**.
- Uses the supplied MAGNA TOURS logo at `assets/magna-tours-logo.jpeg`.
- Visual direction: forest green, warm gold accents, white/light-gray operational workspace, dark-green sidebar, card-based dashboard and data tables.

## Modules included
- Overview dashboard
- Core Platform
- Partner Management
- Travel Partner
- Data Jamaah
- Reservasi & Invoice
- POS / Cashier
- MAGNA AI Assistant (local demo responses)
- Reports

## Run locally
No build step or package installation is required.

### Option 1: Open directly
Open `index.html` in a modern browser.

### Option 2: Local server
From this directory run:

```bash
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## Upload to GitHub
1. Create a repository, e.g. `magna-umroh-platform`.
2. Upload the contents of this folder to the repository root.
3. To publish the static frontend, enable GitHub Pages in repository Settings → Pages and select the deployment source appropriate for your repository.

## Important limitations
This is a **frontend prototype**, not a production application.
- Login is a UI demonstration only. It does not authenticate users or secure pages.
- Data is in-memory sample data; refresh resets demo changes.
- AI responses are local scripted scenarios, not a live LLM integration.
- No backend, database, tenant isolation, real payment processing, live QR validation, document storage, or production authorization is included.
- Do not enter real pilgrim, passport, payment, or other sensitive data.
- Production use requires backend APIs, authentication, role/permission enforcement, tenant isolation, audit logging, backup, and security testing.

## Design reference
Adapted from the supplied `Palmeera mockup v2.0` PDF:
- Landing / sign-in concepts: pages 5–7
- Core dashboard and reservation / billing patterns: pages 8–14
- Agent dashboard, reporting and reservation flow: pages 25–32
- Receptionist / cashier, QR and confirmation flow: pages 37–43

The implementation is a visual adaptation for MAGNA UMROH, not a pixel-identical reproduction of the original lounge UI.

## Version
`v1.1` — UI alignment and logo update.
