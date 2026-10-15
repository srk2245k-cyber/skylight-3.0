# SKYLIGHT ENGINEERING & ENERGY SOLUTIONS PRIVATE LIMITED
### Corporate Web Portal V2 — Industrial Automation, Electrical Systems & Renewable Energy

[![Next.js](https://img.shields.io/badge/Next.js-16.4.1-black?logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.3.0-blue?logo=react)](https://react.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v4.0-38bdf8?logo=tailwind-css)](https://tailwindcss.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-blue?logo=typescript)](https://www.typescriptlang.org/)
[![State](https://img.shields.io/badge/Jurisdiction-Maharashtra%2C%20India-emerald)](#)

---

## 🏢 Executive Overview

This repository hosts the official enterprise web portal for **SKYLIGHT ENGINEERING & ENERGY SOLUTIONS PRIVATE LIMITED**, an engineering firm based in **Maharashtra, India**. 

The portal communicates technical rigor, reliability, innovation, industrial capability, and sustainable energy development in strict alignment with the company's **Memorandum of Association (MOA)**:
1. **Industrial Automation** (PLC, SCADA, DCS, Robotics, Motion Control)
2. **Electrical and Control Systems** (PCC, MCC, APFC, Substation Switchgear)
3. **Renewable & Solar Energy** (Commercial & Industrial Rooftop Solar, BESS, Microgrids)
4. **Industrial Machinery & Equipment** (IE4 Motors, Heavy VFDs, Process Pumps)
5. **Engineering Consultancy** (Feasibility Studies, Power Quality, Energy Audits)
6. **Maintenance & Modernisation** (Legacy System Retrofitting, AMC, Predictive Diagnostics)

---

## 🚀 Key Architectural Features

- **Full Enterprise Multi-Page Experience**:
  - `/` — Homepage featuring Hero (*"Powering Industry. Engineering Tomorrow."*), Company Introduction, 6 MOA Capability Cards, 6 Value Propositions, Featured Demonstration Solutions, Target Sectors, and Interactive FAQ Accordion.
  - `/about` — Corporate Governance, Mission, Vision, R&D Focus, and Registered Office Information.
  - `/services` — Detailed engineering service catalog with category filtering, MOA objectives, scopes of work, deliverables, and technology stacks.
  - `/projects` — Image-led project benchmark portfolio with category filtering (Automation, Electrical, Renewable Energy, Equipment, Maintenance) and detailed specification modal.
  - `/products` — Real-time searchable industrial equipment catalogue with technical parameters and instant quotation request workflows.
  - `/tenders` — Verified tender announcements, downloadable specification dossiers, vendor empanelment application, and administrator RFP publication.
  - `/enquiry` — Dedicated technical proposal form with file attachment simulation, urgency selection, NDA checkbox, validation, and local persistence.
  - `/contact` — Registered office address in Maharashtra, direct phone/email channels, WhatsApp quick messaging, and Maharashtra industrial grid map.
  - `/admin` — Authorised administrator dashboard with demo authentication, metrics, inquiry management, and CSV data exports.
  - `/privacy` & `/terms` — Corporate legal compliance, data protection, and arbitration frameworks under Indian law.

- **Interactive Global Components**:
  - **Sticky Corporate Navigation Bar** with mobile drawer, contact strip, and quick consultation trigger.
  - **Interactive Consultation & Quotation Modal** prefillable from any product or service card.
  - **Downloadable / Printable Corporate Profile Dossier** (`window.print()` / PDF export view).
  - **Smooth Back-to-Top Navigation**.
  - **Zero External Database Dependency for Demo Mode** — Stores enquiries and tenders in client-side `localStorage`.

---

## 🛠️ Technology Stack

| Component | Technology |
| :--- | :--- |
| **Framework** | Next.js 16.4.1 (App Router + Turbopack) |
| **Language** | TypeScript 5 |
| **Styling** | Tailwind CSS v4 |
| **Icons** | Lucide React |
| **Fonts** | Google Inter font |
| **State & Persistence** | LocalStorage with typed schemas |

---

## 💻 Local Setup & Development

### 1. Prerequisites
Ensure you have **Node.js 20+** and **npm** installed on your system.

```bash
node -v   # Recommended: v20.x or later
npm -v
```

### 2. Installation
Clone the repository or navigate to the project directory:

```bash
cd c:/skylight
npm install
```

### 3. Running the Development Server
Launch the Next.js development server with Turbopack:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### 4. Production Build Verification
To compile the production bundle and verify all static routes:

```bash
npm run build
```

To run the built production bundle:
```bash
npm run start
```

---

## 🔐 Administrative Portal Credentials (Demo Mode)

The administrative desk is accessible at [`/admin`](http://localhost:3000/admin):

- **Username / Email:** `admin@skylightengineering.in`
- **Password:** `skylight2026`
- *Or click "Auto-fill Demo Credentials" directly on the login screen.*

### Admin Capabilities:
- View all client inquiries submitted through the website.
- Update technical review statuses (`New`, `Under Technical Review`, `Quote Dispatched`, `Archived`).
- Export registered inquiries to CSV format.
- Publish new tender notices to the live portal.

---

## ☁️ Deployment Guide (Vercel)

The application is built for seamless deployment on **Vercel** with zero configuration required.

### Method A: Deploy via Vercel CLI
1. Install Vercel CLI globally:
   ```bash
   npm i -g vercel
   ```
2. In the `c:/skylight` directory, execute:
   ```bash
   vercel
   ```
3. Follow the CLI prompts:
   - Set up and deploy `c:\skylight`? **Yes**
   - Which scope? Select your personal or organization account.
   - Link to existing project? **No**
   - What's your project's name? **skylight-engineering**
   - In which directory is your code located? `./`
4. For production release:
   ```bash
   vercel --prod
   ```

### Method B: Deploy via GitHub / GitLab Repository
1. Push the repository to GitHub:
   ```bash
   git init
   git add .
   git commit -m "feat: Skylight Engineering corporate portal V2"
   git branch -M main
   git remote add origin https://github.com/<your-username>/skylight-portal.git
   git push -u origin main
   ```
2. Log into the [Vercel Dashboard](https://vercel.com).
3. Click **"Add New Project"** and import the `skylight-portal` repository.
4. Framework Preset will be automatically detected as **Next.js**.
5. Click **"Deploy"**. Your site will be live at `https://skylight-portal.vercel.app` in under 2 minutes.

---

## 📜 Compliance & Transparency Note

All case studies, project metrics, and technical layouts marked with the **"Demonstration Case Study"** badge illustrate engineering methodologies and MOA capabilities. Verified client installation references and confidential single-line schematics are shared under formal Non-Disclosure Agreements (NDAs).

---

## 📬 Registered Office & Contact

- **Entity**: SKYLIGHT ENGINEERING & ENERGY SOLUTIONS PRIVATE LIMITED
- **Registered Office**: Plot No. 42/B, Industrial Area, MIDC, Pune - 411018, Maharashtra, India
- **Official Email**: `info@skylightengineering.in`
- **Projects Desk**: `projects@skylightengineering.in`
- **Tenders Cell**: `tenders@skylightengineering.in`
- **Phone**: +91 20 2747 8900
