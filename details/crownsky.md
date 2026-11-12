[Back to profile](https://github.com/denisans)

<img src="../assets/d-crownsky.svg" alt="Crownsky: A hotel booking website with a guest area and an admin area." width="100%" />

**Repository:** [denisans/Crownsky](https://github.com/denisans/Crownsky) &nbsp;|&nbsp; **Stack:** PHP, MySQL

## Overview

Crownsky is a hotel booking website written in PHP with a MySQL database. Guests can find a room, book it, pay, receive an invoice, and rate their stay. Hotel staff manage rooms, categories, facilities, extra services, bookings, and reports from a separate admin area.

## Guest journey

From searching for a room to rating the stay.

<img src="../assets/d-crownsky-flow-crownsky-guest.svg" alt="Guest journey: Search rooms, Room detail, Book, Check out, Pay, Invoice, Rate" width="100%" />

## Admin workflow

From setting up rooms to printing a report.

<img src="../assets/d-crownsky-flow-crownsky-admin.svg" alt="Admin workflow: Rooms, Facilities, Extra services, Bookings, Report" width="100%" />

## Screens

Simplified sketches of the main screens.

<img src="../assets/d-crownsky-screens.svg" alt="Screen sketches: Room search and results, Checkout and invoice, Admin dashboard and report" width="100%" />

## What is inside

| Area | What it covers | Main files |
|---|---|---|
| **Public site** | Home, room search, room detail, about, contact | `index.php`, `cari_kamar.php`, `kamar_detail.php`, `tentang.php`, `kontak.php` |
| **Guest account** | Register, sign in, orders, payment, invoices, ratings, password | `daftar.php`, `masuk.php`, `customer_pesanan.php`, `customer_pembayaran.php`, `customer_invoice.php`, `customer_rating.php` |
| **Booking** | Booking and checkout with extra services; creates the invoice | `booking.php`, `checkout.php`, `checkout_act.php` |
| **Admin** | Rooms, categories, room facilities, extra services, bookings, ratings, reports | `kamar*.php`, `kategori*.php`, `fasilitas_kamar*.php`, `layanan_tambahan*.php`, `transaksi*.php`, `laporan.php` |

## How it works

- Each admin module follows the same pattern: a list page, add and edit forms, and an action script that writes to the database.
- Delete actions ask for confirmation before removing data.
- Invoices can be viewed and printed by both guests and staff, and reports can be filtered by date range and printed.

## Technology

- PHP with MySQL (mysqli)
- HTML, CSS, and JavaScript
- A dashboard-style layout for the admin area

## Status and next steps

**Status:** A working prototype covering the full booking flow.

- Add a database schema file and a short setup guide so the project can be run from a clean install.
- Add screenshots of the main pages to the repository README.

---

[Back to profile](https://github.com/denisans) &nbsp;|&nbsp; [Open the repository](https://github.com/denisans/Crownsky)
