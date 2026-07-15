# Mein Scope — Home Page Copy (Draft 1)

Positioning: universal/feature-led. No single buyer persona — the page leads with what the product actually does and lets clinicians, clinic owners, and IT each find what matters to them.

---

## Hero

**Headline (primary):**
> Endoscopy records that don't need the internet to work.

**Alternates:**
- A. *Purpose-built for endoscopy and colonoscopy. Works with or without the internet.* — more literal, safer if "records" framing tests too narrow.
- B. *Your scope room doesn't wait for a good connection. Neither should your records.* — punchier, leans on the rhetorical-contrast pattern.

**Subheadline:**
> Mein Scope handles patient intake, photo and video capture, and PDF reporting — all from one app that keeps working through outages, dead zones, and everything in between.

**Primary CTA:** `Request a Demo`
**Secondary CTA:** `See How It Works` (anchor-scrolls to workflow section)

*Annotation:* Headline leads with the sharpest real differentiator (offline-first) rather than a generic "manage your patients" claim — per the brief, that's the wedge most competitors in this space can't credibly make. CTA avoids "Sign up" / "Start free trial" since there's no self-serve backend yet.

---

## Problem framing

**Header:**
> Built for clinics the internet doesn't always reach

**Body:**
> Most clinical software assumes a constant connection. In a lot of clinics, that assumption doesn't hold — a dropped connection mid-procedure shouldn't mean lost patient data, and waiting on IT to deploy new software shouldn't be the cost of digitizing your intake.
>
> Mein Scope was built the other way around: offline first, install-and-go, with no server dependency for day-to-day use. It's designed specifically for endoscopy and colonoscopy workflows, not stretched from a general-purpose EHR.

*Annotation:* Names the pain (connectivity assumptions, IT deployment friction) without inventing a villain competitor. Second paragraph pivots straight into the two clearest differentiators: offline-first and purpose-built.

---

## How it works (3-step workflow)

**Header:**
> One app, from intake to report

**Step 1 — Intake**
> Capture patient details before the procedure starts: demographics, DOB, procedure type and date, physician, findings and diagnosis fields — with validation built in, so nothing critical gets skipped.

**Step 2 — Capture**
> Take photos and record video directly into the patient's record during the procedure. No separate camera roll to manage, no manual matching of files to patients afterward.

**Step 3 — Report**
> Generate a PDF report for the patient in one click, formatted with your clinic's letterhead — ready to print, save, or hand over.

*Annotation:* Organizing by workflow (rather than a flat feature list) shows the product end-to-end and implicitly answers "how does this fit into my day," which matters more here than a features grid.

---

## Built for real clinics (cross-cutting strengths)

**Header:**
> The details that matter once you're actually using it

- **Works anywhere.** Patient data is stored locally on the device. No internet connection required to use the app day-to-day.
- **Install and go.** Mein Scope installs like an app, directly from the browser — no app store, no IT deployment project.
- **Accountability built in.** Role-based access separates admin and clinician permissions. A full audit log tracks logins, record edits, and backups, so you always know who did what and when.
- **Your data, your control.** Back up and restore a full data snapshot manually, whenever you choose — export it, keep it, move it.
- **Comfortable either way.** Light and dark themes, with a responsive layout that works from a side navigation panel.

*Annotation:* This is the section where a clinic owner or IT reader gets what they came for (audit log, roles, backup) without the page having to fork into separate persona-specific pages. Each bullet is one capability → one concrete outcome, per the "benefits over features" rule.

---

## Closing CTA

**Header:**
> See Mein Scope on your own device

**Body:**
> The best way to evaluate Mein Scope is to watch it run through an actual intake, capture, and report cycle — including with the network off.

**CTA:** `Request a Demo`

*Annotation:* Reiterates the offline claim as something we're willing to prove live, which is stronger than restating it as a claim a third time.

---

## Meta (for later HTML build)

- **Page title:** Mein Scope — Offline-First Endoscopy & Colonoscopy Records
- **Meta description:** Purpose-built PWA for endoscopy and colonoscopy intake, capture, and reporting. Works fully offline, installs in seconds, no IT required.

---

## Open questions for next pass

1. Do we keep "Request a Demo" as the single CTA everywhere, or introduce a lighter-weight secondary path (e.g. "Download a one-pager") given there's no live chat/support system yet to handle inbound demo requests?
2. ENT support is "planned" — worth a single forward-looking line on the roadmap, or hold it out entirely until closer to shipping?
3. Confirm gradient CTA button (`#1D95DA → #52B1E8`) is legible with white button text at the sizes we'll use for hero buttons — check once we're in code.
