# Community Hall Booking

A single-page web app for residents to check hall availability and plan their booking setup — built for the Malaysian community context (dewan & surau).

**Try it live:** https://lonjak.github.io/community_hall_booking/

Or download `index.html` and open it in any browser — it's fully self-contained with no build step, no dependencies, and no backend.

## What it does

**1. Availability** — Browse sample free slots for three halls (Dewan Seri Melati, Dewan Anggerik, Surau Al-Hidayah). Filter by hall type, then tap a slot to select it and pre-fill the booking form.

**2. Layout Planner** — Customise the hall setup with a live floor preview:
- Add or remove round tables and chairs, arranged instantly around each table
- One-tap presets: **Kenduri** (10 tables × 80 chairs), **Talk / Doa** (40 chairs in rows), **Meeting** (2 tables × 16 chairs)
- Capacity hints ("8 tables × 8 seats = up to 64 guests") with gentle warnings when the setup looks off
- Purpose of booking (kenduri, majlis doa, mesyuarat) that auto-suggests a matching layout
- Guest count with smart suggestions — type "120 pax" and apply the right table/chair count

**3. Request Summary** — A live review of the whole request that updates as you type, highlights anything missing, and finishes with a confirmation screen.

## Notes

- All data is generated sample data for demo purposes — no real bookings, no live values.
- Nothing is saved between visits; refresh for a clean slate.
- Mobile-first design, works on any phone browser.

## Tech

One `index.html` — HTML, CSS, and vanilla JavaScript. No frameworks, no npm, no build step.
