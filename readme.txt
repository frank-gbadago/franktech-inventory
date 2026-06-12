# FrankTech — Business Manager

A sleek, modern, and high-performance client-side application tailored for managing inventory, logging customer sales, tracking outstanding credit balances, and preparing automated customer messages. 

Built using HTML5, modern vanilla JavaScript, Tailwind CSS, and optimized with custom modern typefaces (*Syne*, *DM Sans*, *DM Mono*), this business portal operates fully within the browser—ensuring lightning-fast response times and absolute data privacy.

---

## 🚀 Key Features

* **Dynamic Inventory Control Dashboard**
    * Track product metrics live: *Total Products*, *Total Stock*, *Stock Value (Cost Price)*, and *Low Stock items*.
    * Pre-categorized workflows designed specifically for phone accessories (Cases, Screens, Chargers, Cables, Earphones, Power Banks, etc.).
    * Real-time stock indicators alongside configurable visual low-stock alert thresholds.
* **Sales Processing Terminal**
    * Instantly record retail transactions against existing stock levels.
    * Dynamically calculates transaction entries on-the-fly.
* **Credit & Debtor Management Ledger**
    * Track balances due, client records, and transaction histories easily.
    * Keep an accurate financial overview of outstanding liabilities.
* **Automated Messaging Desk**
    * Instantly compose context-aware notifications, receipts, or outstanding balance notices.
    * Direct links to bridge customer profiles and text payloads smoothly.
* **Zero-Server Offline Portability & Backups**
    * **Export:** Safely package your full business dataset into a standard lightweight `.json` backup file with a single click.
    * **Restore:** Instantly overwrite or restore historical logs by uploading your locally saved `.json` database file.

---

## 🛠️ Architecture & Tech Stack

This portal is intentionally designed as a standalone **Single Page Application (SPA)**, meaning it does not require complex database servers, background dependencies, or runtimes. 

* **Frontend Interface:** Semantic HTML5 structured layout wrapped in responsive components.
* **Utility Styling Engine:** Tailwind CSS framework served cleanly over a Content Delivery Network (CDN).
* **Custom Interface Variables:** Extended CSS customized palette explicitly featuring a high-contrast theme (`--navy`, `--orange`, `--blue`).
* **State Management:** Reactive Client-side Vanilla JavaScript.

---

## 📦 How to Deploy to GitHub Pages

Since this system runs entirely in the browser, it can be hosted globally for free using GitHub Pages. Follow these steps:

1.  **Rename your file:** Ensure your main script file is named precisely **`index.html`**. *(GitHub looks specifically for an `index.html` file at the root level to serve as the homepage).*
2.  **Initialize a Repository:** Push this file directly up to a new, **Public** repository on your GitHub profile.
3.  **Activate Pages:**
    * Navigate into your online repository's **Settings** tab.
    * Select **Pages** from the sidebar menu layout.
    * Under the "Build and deployment" configuration section, switch the source branch from *None* to **`main`** (or `master`), and hit **Save**.
4.  **Access on Mobile:** Within a couple of minutes, GitHub will supply a live production link (`https://<username>.github.io/<repository-name>/`). Copy this link onto your mobile browser and select **"Add to Home Screen"** to utilize it exactly like a native smartphone application.

---

## 🔒 Data Privacy Statement

Because this application relies exclusively on browser-centric memory models and manual database file exports (`.json`), **none of your financial data, product records, or client contacts are ever uploaded to a remote cloud or external server**. Your records remain completely private, secure, and under your absolute control on your physical hardware.