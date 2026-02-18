<p align="center">
  <img src="https://invoicecrawler.com/invoice_crawler.com.jpg" alt="InvoiceCrawler" width="500">
</p>

<h1 align="center">InvoiceCrawler</h1>

<p align="center">
  <strong>Automatically download invoices & credit notes from your favorite online shops.</strong><br>
  One click. All portals. All invoices. Neatly organized.
</p>

<p align="center">
  <a href="https://invoicecrawler.com">Website</a> &bull;
  <a href="https://scalper-king.com/#pricing">Download</a> &bull;
  <a href="https://invoicecrawler.com/anleitung.html">Guide</a> &bull;
  <a href="https://invoicecrawler.com/blog.html">Blog</a>
</p>

---

## What is InvoiceCrawler?

InvoiceCrawler is a **Windows desktop application** that automatically scans and downloads invoices and credit notes from multiple online portals. No more manually logging into each shop, searching for orders, and saving PDFs one by one.

**2-Phase Workflow:**
1. **Scan** - Connects to your portals and finds all available invoices
2. **Download** - Downloads selected invoices as PDF to a local folder

---

## Supported Portals

| Portal | Method | Features |
|--------|--------|----------|
| **Amazon** DE, FR, IT, ES, UK | Web Scraping | Invoices, Credit Notes, TOTP support |
| **MediaMarkt** | IMAP Email | Invoices from order confirmation emails |
| **Saturn** | IMAP Email | Invoices from order confirmation emails |
| **Otto** | Web Scraping | Invoices |
| **Cardmarket** | Web Scraping | Invoices, TOTP support |
| **Serverprofis** | Web Scraping | Invoices |
| **Webshare** | API | Invoices via API Key |
| **Custom Mail** | IMAP Email | Any invoice from any shop via email - configurable sender, subject & PDF filters |

---

## Features

- **Multi-Portal Support** - Manage credentials for multiple shops in one place
- **Automatic Invoice Detection** - Scans order history or email inboxes to find invoices
- **PDF Download** - Downloads invoices as properly named PDF files
- **Credit Note Detection** - Separately tracks invoices and credit notes (Gutschriften)
- **TOTP / 2FA Support** - Built-in authenticator for Amazon, Cardmarket etc.
- **IMAP Folder Search** - Searches all email folders including nested subfolders
- **Custom Mail Crawler** - Fetch invoices from any shop via IMAP with configurable filters
- **Year Filter** - Filter orders by year to scan specific time periods
- **Dashboard** - Overview of total, downloaded, and pending invoices
- **Monthly Breakdown** - Analytics view with bar charts per month
- **Dark UI** - Modern dark-themed desktop interface
- **Single EXE** - Portable, no installation required
- **AWS WAF Bypass** - Automatic captcha solving via CapSolver

---

## Screenshots

<p align="center">
  <img src="https://invoicecrawler.com/screenshots/documents.png" alt="Documents View" width="800">
</p>

---

## Requirements

- **Windows 10/11** (64-bit)
- **Serial Key** - Available at [scalper-king.com](https://scalper-king.com/#pricing)
- **CapSolver API Key** - Register at [capsolver.com](https://www.capsolver.com) and add credit
- **Portal Credentials** - Login data for the shops you want to scrape

---

## Quick Start

1. **Download** `InvoiceCrawler.exe` from [Releases](https://github.com/Chackyx/InvoiceCrawler/releases)
2. **Run** the EXE - no installation needed
3. **Activate** with your Serial Key and CapSolver API Key
4. **Add Portals** - Enter your shop credentials
5. **Scan & Download** - Click "Start Scraping" and let InvoiceCrawler do the rest

All invoices are saved to the `downloads/` folder next to the EXE.

---

## How It Works

### Web-Based Portals (Amazon, Otto, Cardmarket, ...)
InvoiceCrawler logs into the shop with your credentials, navigates the order history, finds invoice PDFs, and downloads them automatically.

### IMAP-Based Portals (MediaMarkt, Saturn, Custom Mail)
InvoiceCrawler connects to your email account via IMAP, searches all folders (including subfolders) for order confirmation emails, extracts PDF attachments, and saves them locally.

### Custom Mail Crawler
For shops not directly supported, you can configure the **Custom Mail** portal:
- **IMAP Server** - Your email provider's IMAP server
- **Subject Keyword** - Filter emails by subject (e.g. "Rechnung", "Invoice")
- **Sender Email** - Filter by sender address
- **PDF Keyword** - Filter PDF attachments by filename
- **Move Fetched** - Optionally move processed emails to a separate folder

---

## FAQ

**Is this free?**
No, InvoiceCrawler requires a serial key. See [pricing](https://scalper-king.com/#pricing).

**Is my data safe?**
All credentials are stored locally on your machine. InvoiceCrawler never uploads your shop passwords to any server.

**Can I use it on Mac/Linux?**
Currently Windows only.

**Which Amazon marketplaces are supported?**
Amazon DE, FR, IT, ES, and UK.

**My MediaMarkt/Saturn invoices are not found?**
Make sure your IMAP server is correct and that you have email notifications enabled for your orders. InvoiceCrawler searches all folders including subfolders.

---

## Links

- [Website](https://invoicecrawler.com)
- [Buy Serial Key](https://scalper-king.com/#pricing)
- [Setup Guide](https://invoicecrawler.com/anleitung.html)
- [System Requirements](https://invoicecrawler.com/systemanforderungen.html)
- [Blog](https://invoicecrawler.com/blog.html)

---

<p align="center">
  InvoiceCrawler is part of the <a href="https://www.scalper-king.com">Scalper-King</a> software suite.<br>
  Made with :blue_heart: in Germany
</p>
