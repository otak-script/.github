
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1a2e,100:16213e&height=200&section=header&text=OTAK%20SCRIPT&fontSize=60&fontColor=fff&animation=fadeIn&fontAlignY=38">
    <img alt="Otak Script" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=OTAK%20SCRIPT&fontSize=60&fontColor=fff&animation=fadeIn&fontAlignY=38">
  </picture>
</p>

<p align="center">
  <b>Enterprise-Grade Digital Solutions · Built with Laravel Ecosystem</b>
</p>

<p align="center">
  <a href="https://laravel.com"><img src="https://img.shields.io/badge/Laravel-13-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel 13"/></a>
  <a href="https://vuejs.org"><img src="https://img.shields.io/badge/Vue.js-3-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue.js 3"/></a>
  <a href="https://react.dev"><img src="https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=white" alt="React 19"/></a>
  <a href="https://inertiajs.com"><img src="https://img.shields.io/badge/Inertia.js-2-9553E9?style=for-the-badge&logo=inertia&logoColor=white" alt="Inertia.js 2"/></a>
  <a href="https://tailwindcss.com"><img src="https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS 4"/></a>
  <a href="https://livewire.laravel.com"><img src="https://img.shields.io/badge/Livewire-3-FB70A9?style=for-the-badge&logo=livewire&logoColor=white" alt="Livewire 3"/></a>
  <a href="https://filamentphp.com"><img src="https://img.shields.io/badge/Filament-3-FD8A4B?style=for-the-badge&logo=filament&logoColor=white" alt="Filament 3"/></a>
</p>

<br/>

---

## 🚀 Overview

**Otak Script** is a collective of Indonesian engineers crafting enterprise-grade digital solutions for transportation, logistics, government administration, HR management, and document governance. Every system is battle-tested in production — powering real businesses and government agencies across Indonesia.

> **Stack DNA:** Laravel · React · Vue.js · Inertia.js · Livewire · Filament · Tailwind CSS · shadcn/ui

---

## 📦 Project Portfolio

<br/>

### 🚗 Transmonang — Transportation Management Backend

> **Stack:** Laravel 13 · REST API · Sanctum

The core API engine for transportation operations. Manages the entire lifecycle of fleet reservations — from booking and dispatch to billing and maintenance.

**Key domains:**
- **Reservations** — Multi-source booking with customer types, routes, schedules, and 3HC (3-hour call) checkpoints
- **Fleet Management** — Vehicles, brands, models, police numbers, TNKB colors, ownership tracking
- **Finance & Accounting** — Chart of Accounts, journals, P&L, balance sheets, expense tracking, automated voucher generation
- **HR & Payroll** — Employee records, salary templates, allowances, deductions, attendance timesheets
- **Operations** — Driver scheduling, vehicle handover (check-in/check-out), workshop maintenance, operational logs
- **Procurement** — Purchase orders, sales orders with item-level tracking
- **Reporting** — PDF exports (profit/loss, balance sheet, vouchers, handover documents)

**Serves:** Operational dispatch, finance, and fleet management teams.

| <a href="https://github.com/otak-script/transmonang"><b>Repository →</b></a> | `otak-script/transmonang` |
|---|---|

<br/>

### 🖥️ Transmonang Client — Admin Dashboard

> **Stack:** Laravel 13 · React 19 · Inertia.js 2 · Tailwind CSS 4 · shadcn/ui

The administrative command center for Transmonang. A single-page dashboard that gives operations teams real-time visibility and control.

**Capabilities:**
- **Dashboard** — Role-aware analytics and KPIs
- **Booking Management** — End-to-end reservation processing with workflow state tracking
- **Car Fleet Overview** — Real-time availability search and booking
- **Management Panel** — User/role/permission CRUD, price configuration (base, origin, addon tiers), customer management
- **Activity Logs** — Full audit trail across all operations

**Serves:** Admin, operations, and finance teams.

| <a href="https://github.com/otak-script/transmonang_client"><b>Repository →</b></a> | `otak-script/transmonang_client` |
|---|---|

<br/>

---

### 🚙 KA Rent Car — Full-Service Car Rental Platform

> **Stack:** Laravel 13 · Vue.js 3 · Inertia.js · Livewire 3 · Tailwind CSS

A complete car rental ecosystem with multi-portal architecture — public website, admin panel, and client portal — all in one codebase.

**Public Portal (`/`):**
- Fleet showcase with price calendar, car details, and availability
- Online booking with confirmation workflow
- About, contact, help center, terms & privacy pages

**Admin Portal (`app.karent.co.id`):**
- **Fleet Management** — Cars, prices, additional add-ons
- **Reservations** — Calendar view, booking management, print documents
- **Client Management** — Client profiles, suspend/activate control
- **Payments & Reports** — Payment tracking, financial reporting
- **Support** — Ticket-based customer support system

**Client Portal (`/client`):**
- Reservation history and details
- Profile management
- Support ticket creation and tracking

**Livewire Pages:**
- Voucher generation, ticket printing
- Central information display
- Vehicle handover check-in/check-out
- PDF exports (P&L, balance sheet, vouchers, handover docs)

| <a href="https://github.com/otak-script/karent_app"><b>Repository →</b></a> | `otak-script/karent_app` |
|---|---|

<br/>

---

### 📋 Absensi Kanim — Immigration Office Queue System

> **Stack:** Laravel 13 · Livewire 3 · Tailwind CSS

A digital queue management system deployed at **Kantor Imigrasi** (Immigration Office). Replaces paper-based queuing with a real-time electronic system.

**Features:**
- **Kiosk Display** — Real-time counter queue display with live updates, bell ring integration, text-to-speech call in Indonesian & English
- **Queue Management** — Queue code generation, status tracking (active/skipped/completed)
- **Print Queue** — Automatic print dispatch for queue tickets

**Impact:** Eliminates physical queue cards, reduces wait-time confusion, and modernizes the immigration service experience.

| <a href="https://github.com/otak-script/absensi_kanim"><b>Repository →</b></a> | `otak-script/absensi_kanim` |
|---|---|

<br/>

---

### 🐔 PO Ayam — Poultry Purchase Order System

> **Stack:** Laravel 13 · Livewire 3 · Tailwind CSS

A specialized purchase order and invoicing system built for the poultry supply chain.

**Features:**
- **Purchase Orders** — Create and manage PO with item-level details
- **Invoicing** — Invoice generation with customer, vendor, and payment tracking
- **Invoice Printing** — Formatted print layout with organization branding, logo, and payment information
- **Vendor & Customer Management** — Complete directory of supply chain partners
- **Payment Tracking** — Record and reconcile payments against invoices

**Serves:** Poultry distributors, suppliers, and finance teams managing B2B transactions.

| <a href="https://github.com/otak-script/po_ayam"><b>Repository →</b></a> | `otak-script/po_ayam` |
|---|---|

<br/>

---

### 🏢 Absensi Givaudan — Enterprise HR & Attendance

> **Stack:** Laravel 13 · Filament 3 · Livewire 3 · Tailwind CSS

A full-featured HR management system deployed for **Givaudan**, built on Filament's admin panel framework.

**Features:**
- **Employee Database** — Integrated with existing `tmp_t_usr` table, employee relations and details
- **Organization Structure** — Site locations, business units, departments, cost centers
- **Shift Management** — Configurable shift settings with scheduling
- **Attendance Tracking** — Employee attendance with import/export support
- **Notifications & Logging** — Telescope integration, notification system
- **Filament Panels** — Admin resources, widgets, pages for data management and visualization

| <a href="https://github.com/otak-script/absensi_givaudan"><b>Repository →</b></a> | `otak-script/absensi_givaudan` |
|---|---|

<br/>

---

### 📁 Document Archiving — Government Document Registry

> **Stack:** Laravel 13 · React 19 · Inertia.js 2 · Tailwind CSS 4 · shadcn/ui

A comprehensive electronic document archiving system (**Sistem Kearsipan Elektronik**) deployed at **Kantor Imigrasi Kelas I Khusus Non TPI Tangerang** — the Immigration Office.

**Complete document lifecycle management:**
- **Document Registration** — Register incoming documents with applicant data and metadata
- **Archive Management** — Organize documents in virtual filing cabinets with location tracking
- **Document Search** — Full-text and filtered search across the entire archive
- **Document Loans** — Track borrowed documents with borrower identity and return dates
- **Document Returns** — Process and record document returns
- **Document Retention** — Automated retention scheduling, bulk disposal for expired documents
- **Label Printing** — Print document labels for physical filing identification
- **Role & Permission Management** — Granular access control with RBAC
- **User Management** — Full admin panel for system users
- **Activity Logging** — Complete audit trail for every document action

| <a href="https://github.com/otak-script/document_archiving"><b>Repository →</b></a> | `otak-script/document_archiving` |
|---|---|

---

## 🧰 Technology Stack

| Layer | Technology |
|---|---|
| **Backend** | Laravel 13 · PHP 8.4 |
| **Frontend (SPA)** | React 19 · Vue.js 3 · Inertia.js 2 |
| **Frontend (Classic)** | Livewire 3 · Filament 3 |
| **Styling** | Tailwind CSS 4 · shadcn/ui |
| **Database** | SQLite · MySQL · PostgreSQL |
| **Auth** | Laravel Sanctum · Fortify · Laravel Jetstream |
| **Queue** | Laravel Horizon · Telescope |
| **Tooling** | Bun · Vite · TypeScript · Prettier |

---

## 🎯 Impact

| Metric | Scope |
|---|---|
| **Government Agencies** | Immigration office document & queue systems |
| **Enterprise Deployments** | Givaudan HR & attendance |
| **Transportation Ops** | Fleet management, reservations, logistics |
| **Supply Chain** | Poultry PO & invoicing |
| **All Systems** | Built with Laravel 13, modern reactive UIs, production-hardened |

---

<p align="center">
  <i>Built with precision by the Otak Script team.</i>
  <br/>
  <b>Laravel · React · Vue · Livewire · Filament · Tailwind</b>
  <br/><br/>
  <img src="https://img.shields.io/badge/Made%20in-Indonesia-E61B23?style=flat-square&logo=java&logoColor=white" alt="Made in Indonesia"/>
  <img src="https://img.shields.io/badge/Production-Ready-00C853?style=flat-square" alt="Production Ready"/>
  <img src="https://img.shields.io/badge/Open%20Source-Welcome-1F8ACB?style=flat-square" alt="Open Source Welcome"/>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,50:1a1a2e,100:0d1117&height=150&section=footer&fontSize=20">
    <img alt="Footer" src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=150&section=footer&fontSize=20">
  </picture>
</p>
