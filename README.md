# Saib Bakery Management & Speed POS (Adama, Ethiopia)

A mobile-first, offline-capable Progressive Web Application (PWA) built for **Saib Bakery in Adama, Ethiopia**.

## Key Features
- **Trilingual Interface**: Instant 1-tap switching between **English** (default), **Amharic (አማርኛ)**, and **Afaan Oromo**.
- **Ethiopian Birr (ETB) Speed POS**:
  - Designed for peak morning (6:00–9:30 AM) and evening (4:00–8:00 PM) bread rushes.
  - One-handed multiplier steps (`+1`, `+5`, `+10`, `+25`, `+50`) and 1-tap Rush Combos (`5× Frenj Dabo`, `10× Frenj Dabo`, `50× Kiosk Crate`).
  - Supports **Cash (ጥሬ ገንዘብ)**, **Telebirr (ቴሌብር)**, **CBE Birr (ሲቢኢ ብር)**, and **Adama Wholesale Kiosk Credit (የሱቅ ብድር)** with an automatic ETB note change calculator (`50`, `100`, `200`, `500 ETB`).
- **Oven Batch & Production Tracker**:
  - Automatically calculates and deducts **First-Grade Wheat Flour (in kg & 100kg Quintals)**, **Dry Yeast**, **Sugar**, **Cooking Oil**, **Bread Improver**, and **Salt** from store inventory when a batch is baked, while adding the finished loaves directly to counter stock.
- **Raw Material Inventory & Low-Stock Alerts**:
  - Tracks flour in both **kg** and **Quintals (ኩንታል / Kuntaala)** with burn-rate days remaining and supplier delivery logging.
- **Owner Reports & Adama Kiosk Wholesale Ledger**:
  - Real-time revenue, COGS, net margin, hourly peak sales chart, product revenue mix, CSV export, and credit settlement tracking for local Adama kiosks.

## Deploying to Vercel
1. Unzip this folder and push it to a GitHub repository (or use the Vercel CLI).
2. In Vercel, click **Add New Project** → Import your repository → Click **Deploy** (zero build configuration required; `vercel.json` is pre-configured).
3. Or from your terminal inside this folder, run:
   ```bash
   npx vercel --prod
   ```

## Installing on Android & iPhone (PWA)
- **Android (Chrome)**: Open your deployed Vercel URL → Tap the menu (`⋮`) → Tap **Install App** or **Add to Home Screen**.
- **iPhone (Safari)**: Open your deployed Vercel URL → Tap **Share** → Tap **Add to Home Screen**.
