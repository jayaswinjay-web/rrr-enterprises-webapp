# RRR Enterprises — Financial & Legal Services Web Application

A lightweight, low-resource web application for **RRR Enterprises**, a multi-service
financial and legal services provider.

---

## Overview

RRR Enterprises serves customers across loans, insurance, legal and property services
through a single responsive portal with a built-in referral and rewards program.

## Features

- Landing page presenting all service categories (loans, insurance, legal, property)
- User registration and login
- Unique referral code issued to every registered user
- Full referral funnel: Share → Lead → In Progress → Closed → Coupon
- Coupon/reward system with major retail brands
- Referrer dashboard for managing leads and coupons
- Admin dashboard for leads, referrers, coupons and service management
- CSV export for leads, referrers and coupons
- Mobile-responsive, banking-style interface
- Gzip compression, static caching and prepared statements throughout

## Tech Stack

- **Backend:** Vanilla PHP 8.1+ (no heavy frameworks)
- **Database:** PostgreSQL (Supabase) via PDO with prepared statements
- **Auth:** Supabase Auth (REST API + JWT session management)
- **Frontend:** Server-rendered PHP with minimal vanilla JS/CSS
- **Caching:** File-based static content caching

## Security

- All database access uses prepared statements (PDO)
- Form inputs are sanitized and validated server-side
- CSRF protection on all forms
- JWT sessions managed server-side; no secrets exposed to the frontend
- Environment configuration is never committed or served from the web root
- Security headers applied (X-Frame-Options, XSS-Protection, etc.)

## Source code

This repository is the **public home** of the RRR Enterprises web application —
project documentation and release notes only.
The source code is proprietary and maintained privately.

## License

Proprietary — RRR Enterprises. All rights reserved.
