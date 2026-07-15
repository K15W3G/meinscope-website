# Mein Scope — Brand & Product Brief

Handover doc for starting the marketing website as a **separate project, separate GitHub repo** from the Mein Scope PWA (the clinical app repo is `K15W3G/Mein-Scope` on GitHub, branch `ui-changes`). This file is the starting context for a new chat — read this first before writing any copy or code.

## Brand assets

All in `./assets/` next to this file:
- `Logo Icon.svg` — icon-only mark (heart + ECG pulse line)
- `Logo WIth Word.svg` — full wordmark lockup ("MeinScope")
- `512x512 Logo.png` — raster version of the icon mark

**Colors**
- Primary: `#52B1E8`
- Primary gradient (used on CTA buttons in the app): `#1D95DA → #52B1E8`, left to right
- Wordmark text color (the "Scope" half): `#3F3D56`

**Typography**
- Inter Variable (self-hosted, not Google Fonts CDN) — the app avoids external font requests since it's offline-first

## What Mein Scope actually is

An offline-first Progressive Web App (PWA) for endoscopy and colonoscopy patient intake, capture, and reporting (ENT support planned). Built for clinical use, not a generic EHR.

**Real, shipped capabilities** (don't invent features beyond this list without confirming):
- Works fully offline — patient data is stored locally (IndexedDB), no internet dependency to use the app day-to-day
- Installable as a PWA — no app store, no IT deployment needed
- Patient intake form with validation (gender, DOB, procedure date/type, physician, findings/diagnosis fields)
- In-app photo capture and video recording tied directly to a patient's record during intake
- One-click PDF report generation per patient, with clinic letterhead
- Full audit log (who did what, when — login events, record edits, backups)
- Role-based access: admin vs. clinician, with admin-only user management and audit log
- Manual backup/restore (export/import a full data snapshot as a file)
- Light/dark theme, responsive side navigation

**Explicitly NOT built yet** — do not market these as available:
- No cloud sync / multi-device access (single device, local storage only)
- No billing, licensing, or accounts system (no backend at all currently)
- MP4 video export is disabled in the current build (WebM only right now)
- No live chat / bug-report / contact-support system yet

## Positioning notes (starting point, not settled)

- Sharpest likely wedge: **works with zero/unreliable internet** — real differentiator for clinics in areas with inconsistent connectivity (this is a Uganda-built product; dates in the app already use DD/MM/YYYY local convention).
- Purpose-built for endoscopy/colonoscopy workflows rather than a bloated general-purpose EHR — the pitch is focus, not feature-count.
- Buyer isn't settled yet: individual clinician, clinic owner/admin, or hospital procurement/IT could each want a different pitch. Worth deciding before writing hero copy.
- Monetization (pricing tiers, monthly/annual) is a **planned but not yet built** direction — it requires backend work (auth, billing, licensing) that doesn't exist today. The website can talk about pricing intent, but shouldn't promise self-serve signup until that backend exists.

## What to actually do in the new chat

1. Confirm positioning (buyer + one-sentence value prop) before writing hero copy.
2. Use the `copywriting` / `content-strategy` skills for the actual writing pass.
3. Set up a fresh GitHub repo for the website (separate from `Mein-Scope`) — suggested name: `meinscope-website` or `mein-scope-marketing`.
4. Reuse the brand assets/colors above as-is; don't redesign the logo.
