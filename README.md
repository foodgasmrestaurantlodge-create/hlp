# Grok Scanner

AI-powered document scanning, OCR, PDF management, and intelligent document assistant platform.

## Features Implemented (Web MVP)

### Core UI
- **Dashboard** — Recent documents, folders, storage overview, quick tools
- **Smart Scanner** — 16+ scan modes (Document, ID, Passport, Receipt, Invoice, Business Card, Book, Whiteboard, QR, etc.)
- **Documents Library** — Grid/list view, full-text search, folder filters, tags
- **AI Document Assistant** — Chat interface grounded in selected documents (summarize, extract, translate, compare)
- **PDF Tools** — Merge, split, compress, convert, annotate, sign, protect
- **Settings** — Account, security, cloud, notifications, storage

### Design
- Dark modern UI with indigo/cyan accent
- Collapsible sidebar
- Responsive layout
- Mock data for documents, folders, storage

## Tech Stack
- Next.js 16 (App Router)
- TypeScript
- Tailwind CSS v4
- Lucide React icons
- clsx + tailwind-merge

## Run Locally

```bash
cd grok-scanner
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000)

## Product Vision Coverage

This MVP implements the **frontend shell and navigation** for the full Grok Scanner specification:

1. Smart Document Scanner (UI + modes)
2. Scan Modes (full list)
3. OCR (UI entry points)
4. AI Document Assistant (interactive chat mock)
5. AI Auto Organization (folder classification shown)
6–9. Receipt / Invoice / Business Card / ID scanners (modes)
10–14. PDF Creator / Tools / Editor / Signature / Security (tools UI)
15–25. Sharing, Cloud, Search, Folders, Tags, Offline concepts (settings & UI)
26–44. Comparison, Translation, Bulk, Import/Export (AI + tools)
45–47. Security architecture & Account system (settings)

Backend OCR engines, camera capture, real cloud storage, and production AI would be integrated in subsequent phases.
