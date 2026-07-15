# Mein Scope: Features Page Copy (Final, mirrors src/pages/features.astro)

Job of this page: give the reader who wants depth (clinician evaluating fit, IT evaluating security/control) the full capability list without re-selling the pitch from the home page.

---

## Header

**Eyebrow:** Features

**Headline:**
> Everything built specifically for endoscopy and colonoscopy

**Subheadline:**
> Not a general EHR with a gastroenterology module bolted on. Every part of Mein Scope is built around one workflow: intake, capture, and report.

---

## Section 1: Intake

**Header:** Patient intake, without the paper

> Structured intake form for demographics, date of birth, procedure type and date, physician, and findings/diagnosis fields. Built-in validation catches missing or malformed entries before they become a problem in the report.

- Gender, DOB, and procedure metadata captured in one form
- Physician and procedure-type fields structured for consistent reporting
- Findings and diagnosis fields tied directly to the patient record
- Validation on required fields, so nothing critical slips through

---

## Section 2: Capture

**Header:** Photos and video tied to the patient, not your camera roll

> Capture images and record video directly inside the app during the procedure. Every file is attached to the patient's record automatically. No exporting from a phone, no renaming files, no guessing which photo belongs to which patient later.

- In-app photo capture during intake
- In-app video recording during intake
- Media attaches directly to the patient record, no manual matching needed
- *Note: video recording currently saves in WebM format. MP4 export is planned but not yet available.*

*Annotation:* Calling out the WebM-only limitation directly (rather than hiding it) matches the brief's instruction not to overclaim. It's the kind of detail a technical evaluator will check anyway, so naming it builds trust instead of costing it.

---

## Section 3: Report

**Header:** One-click PDF reports, ready to hand over

> Generate a complete PDF report for the patient in a single click, formatted with your clinic's letterhead. No separate report-writing tool, no copying data between systems.

- One-click generation per patient
- Clinic letterhead built into the report format
- Pulls directly from the intake and capture data already on file

---

## Section 4: Built for offline from the ground up

**Header:** Built for offline from the ground up

> Patient data is stored locally on the device using IndexedDB. There's no server round-trip required to use the app day to day, which means no waiting on a connection during intake, capture, or reporting.

- Full offline functionality for daily use: intake, capture, and reporting all work without a connection
- Installable as a Progressive Web App directly from the browser, with no app store or IT deployment project needed
- *Note: Mein Scope currently runs on a single device, with data stored locally. Multi-device sync isn't available yet.*

*Annotation:* Naming the single-device limitation here (not just in an FAQ) keeps the offline claim honest. "Offline-first" and "no sync yet" are two sides of the same architectural fact, so they belong together.

---

## Section 5: Access, audit, and control

**Header:** Know who did what, and when

> Role-based access separates what admins and clinicians can do. Admins manage users and review the audit log; clinicians work in patient records. Every login, record edit, and backup is logged.

- Admin and clinician roles, with admin-only user management
- Full audit log: logins, record edits, and backups
- Manual backup and restore: export a full data snapshot as a file, on your schedule
- Light and dark theme, responsive side navigation

---

## Closing CTA

**Header:** See it running on an actual device

**CTA:** `Request a Demo`
