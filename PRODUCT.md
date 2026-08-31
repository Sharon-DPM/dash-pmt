# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

The primary users are the internal leasing / property management team at Dash PMT (dashpm.ca) — a small team managing a portfolio of rental buildings and units they operate directly. It is not sold or provisioned to outside property-management companies as customers.

## Product Purpose

Dash PMT gives the team one shared place to track unit inventory (buildings, units, rent, occupancy status, tenants) and the leasing pipeline (leads, showings, lead stage, hot leads) for the properties they manage, so vacancy and lead status stay visible and up to date across the team.

## Positioning

A lightweight internal tool built for this team's exact workflow, not a general-purpose or multi-tenant SaaS property management product (unlike AppFolio, Buildium, etc.). It stays deliberately narrow — unit inventory plus a leasing/CRM pipeline and showing scheduling — rather than growing into full property/accounting management.

## Operating Context

- Team members sign in with a shared Google account to access a common property database.
- Units, leads, and activity are tracked per building/unit; leads move through a pipeline of stages toward "Leased."
- Showings are booked directly to Google Calendar from within the app.
- Data can be exported to CSV.

## Capabilities and Constraints

- Dashboard: KPIs (active leads, hot leads, vacancy, revenue from occupied units) and quick views into the lead pipeline and vacancy overview.
- Units (Inventory): building/address, unit number, beds, monthly rent, occupancy status, tenant, availability, notes.
- CRM: lead records (name, email, phone, stage, target unit/beds, budget, source, date, hot flag, notes) with a stage pipeline and per-lead activity/notes panel.
- Calendar: books property showings into Google Calendar (guest/lead name & email, unit address, notes).
- Sync / Export: "Sync Now" and "Export CSV" actions in the nav.
- Undecided/open: whether payments, invoicing, or accounting will ever be in scope — not currently implemented and not assumed.

## Brand Commitments

Name: Dash PMT ("Dash PMT — Property Management").

## Evidence on Hand

- The app already contains real operational data referencing actual buildings (e.g. "SXSW1 — Vaughan CC"), not placeholder/demo content — treat existing units, leads, and building names as live data, not fixtures to invent or discard.
- No testimonials, pricing, case studies, or press exist for this product; do not fabricate any.

## Product Principles

- Stay narrow: unit inventory + leasing pipeline + showings, not a full PM/accounting suite.
- The Google Sheet is the source of truth — the app is a shared interface over it, not an independent database; UI and sync behavior must keep the sheet and app consistent.
- Keep the tool fast and low-friction for a small internal team, not configurable/multi-tenant for external customers.
- Preserve real operational data (buildings, units, leads) already in use; never treat it as disposable sample data.
