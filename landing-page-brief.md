# Stop RV Leaks — Landing Page Build Brief
## Instructions for Claude Code

---

## Context

Stop RV Leaks is a mobile RV leak detection and repair business in Western Washington (Snohomish, Skagit, and North King counties). The owner is Brian — an independent technician with SealTech pressure testing equipment, dealership-level experience, and a flat-rate pricing model.

The current site (stoprvleaks.com) is hosted on Netlify with DNS via Namecheap. The existing site has been running Google Ads for over a week with 44 clicks and zero conversions — the landing page is the bottleneck. We're rebuilding the site around a channel-specific funnel strategy.

**The business has one completed job and one 5-star Google review (Stephen Morrison, 2001 Newmar Dutch Star).** The site needs to project competence and calm authority without overclaiming proof that doesn't exist yet.

---

## What to Build

Three pages sharing a common nav, footer, and brand identity:

1. **`/diagnostic`** — Primary Google Ads landing page (the money page)
2. **`/seal-check`** — Nextdoor/Facebook/community traffic landing page
3. **`/`** (homepage) — General brand page for organic/direct visitors

Each page has ONE job for ONE audience. Do not cross-pollinate the offers above the fold.

---

## Design Direction

**Tone:** Calm authority. The Wolf, not the salesman. Think "the guy your neighbor trusts to figure out what's wrong" — competent, direct, zero fluff. Not luxury. Not discount. Professional tradesman who documents everything and tells you the truth.

**Aesthetic:** Clean, utilitarian, slightly industrial. NOT generic SaaS. NOT "small business template." Think field report meets professional service page.

- Dark charcoal or navy as primary background option, with clean white/light sections for contrast
- One strong accent color (a deep teal, working blue, or forest green — something that says "water management" without being cliché)
- Typography: something with weight and clarity. A strong sans-serif for headlines (not Inter, not Roboto). A readable body font. This is a trades business, not a startup.
- Minimal decoration. Let whitespace, type hierarchy, and clear blocks do the work.
- Mobile-first. Most Google Ads clicks will be on phones. The phone number must be tap-to-call everywhere it appears.

**What to avoid:**
- Stock photos of RVs (use placeholder blocks for now — Brian will add real field photos)
- Anything that looks like a template
- Excessive animations or parallax
- Multiple competing CTAs above the fold
- Any sense of "luxury concierge service" — that positioning is being shelved for now

---

## Page 1: `/diagnostic` (Google Ads Landing Page)

### Purpose
Convert someone who just searched "RV leak repair near me" into a phone call. They have water in their rig. They're stressed. They want someone competent to tell them what's wrong.

### Scroll Structure

**SECTION 1 — Hero (first screen, above the fold)**

Headline:
```
RV Leak? Get Real Answers Before Damage Spreads.
```

Subheadline:
```
Mobile leak diagnostics in Snohomish and Skagit County. Pressure-test investigation, documented findings, and honest next steps — at your location.
```

Offer card (visually prominent, feels like a pricing card):
```
Founding Customer Leak Diagnostic
~~$695~~ $350
50% off intro pricing — limited availability

✓ SealTech pressure testing
✓ Full interior and exterior inspection
✓ Photo documentation of all findings
✓ Written diagnostic report
✓ Up to 1 hour of repair included
✓ 12-month workmanship warranty

[CALL NOW: (360) XXX-XXXX] ← tap-to-call button, large
[Or text us to schedule] ← secondary CTA, smaller
```

Nothing else above the fold. No other offers. No nav links to other services. Just the problem, the solution, and the phone number.

---

**SECTION 2 — Symptom Recognition ("Is this you?")**

Small header:
```
Signs You Need a Leak Diagnostic
```

List (can be a clean grid or icon-based layout — keep it scannable):
```
Water stains on ceiling or walls
Soft or spongy spots on floor or walls
Musty smell inside the coach
Water pooling after rain
Leak that keeps coming back after resealing
Bubbling, cracking, or separated exterior sealant
Buying a used RV and want to know what you're getting
```

Closing line:
```
If any of these sound familiar, guessing costs more than knowing. A diagnostic gives you the full picture.
```

---

**SECTION 3 — How It Works (process = trust)**

Header:
```
What Happens During a Diagnostic
```

Three or four steps, presented cleanly (numbered or as a horizontal flow):

```
1. Phone intake — We discuss your symptoms, your rig, and your location. If I can help, we schedule. If I can't, I'll tell you.

2. Pressure testing — SealTech equipment pressurizes your RV's envelope from inside. Soapy solution on the outside reveals exactly where air (and water) gets through. No guesswork.

3. Full inspection — Interior moisture check, exterior seal assessment, documentation of every finding with photos.

4. Honest brief — I walk you through what I found, what it means, and what your options are. Written report and photos emailed after the visit.
```

---

**SECTION 4 — Proof**

If there's a real Google review to show, show it here. For now, build it to hold one testimonial block:

```
"Brian was thorough, professional, and honest about what he found. He explained everything clearly and didn't try to upsell me on work I didn't need."
— Stephen M., 2001 Newmar Dutch Star
⭐⭐⭐⭐⭐
```

[Placeholder for 1-2 field photos with captions like "Pressure test revealing leak at forward roof seam" — Brian will supply these]

---

**SECTION 5 — FAQ**

```
What if you can't find the leak?
It's rare, but possible — some leaks only show under specific conditions. If I can't find an active leak path, I document everything I checked, what I ruled out, and what to watch for. I'll credit the diagnostic toward a return visit if the problem reappears.

What happens after the diagnostic?
You get a complete picture of what's going on. If repairs are needed and I can handle them on-site, I'll quote them on the spot — no pressure. If it's beyond mobile service scope, I'll tell you what kind of shop work you need and what to ask for.

Do I have to commit to repairs?
No. The diagnostic stands on its own. You're paying for information and documentation, not a sales pitch. Many customers use the report to make informed decisions on their own timeline.

How long does it take?
Most diagnostics run 2-3 hours depending on the rig and complexity. I block a half-day window so there's no rush.

Where do you serve?
Snohomish County, Skagit County, and north King County. If your rig is parked at your home, a storage lot, or a local park in that area, I can come to you.
```

---

**SECTION 6 — Secondary offer (small, below the fold)**

Visually separated. Smaller type. Different background shade. This is not the focus — it's a catch for the rare person who clicked a Google ad but doesn't actually have symptoms.

```
No Active Symptoms?

If your rig has no signs of leaking and you just want a visual check of your exterior sealant condition, we offer a Preventive Seal Check for $190. Visual inspection only — not a leak diagnostic.

[Learn more →] (links to /seal-check)
```

---

**SECTION 7 — Final CTA (sticky or repeated)**

```
Ready to find out what's going on?

Call or text: (360) XXX-XXXX
brian@stoprvleaks.com

Serving Snohomish, Skagit, and North King counties.
Sunday and Monday availability.
```

Consider a sticky mobile CTA bar at the bottom of the screen with the phone number — always visible as they scroll.

---

## Page 2: `/seal-check` (Nextdoor / Facebook / Community Landing Page)

### Purpose
Convert someone who saw a Nextdoor or Facebook post about a $190 preventive seal check. They don't have a leak. They're cautious, curious, or just maintaining their rig. Lower urgency, lower price, lower friction.

### Scroll Structure

**SECTION 1 — Hero**

Headline:
```
Protect Your RV Before Small Sealant Problems Become Expensive Repairs
```

Subheadline:
```
A quick, affordable exterior sealant inspection — at your location in Snohomish or Skagit County.
```

Offer card:
```
Preventive Seal Check
$190 intro pricing

✓ Visual inspection of all accessible exterior seams and sealant lines
✓ Minor spot touch-up of clearly superficial defects
✓ Honest assessment of overall sealant condition
✓ Recommendations for maintenance or next steps

[CALL OR TEXT: (360) XXX-XXXX]
```

---

**SECTION 2 — Who this is for**

```
Best for:
Coaches stored outdoors or in uncovered lots
Rigs that haven't been inspected in 1+ years
Pre-trip or pre-season checkups
Recently purchased used RVs with no maintenance history
Owners who want peace of mind without a full diagnostic

Not the right fit if:
You're seeing water stains, soft spots, musty odor, or known leaks — that's a diagnostic, not a checkup.
```

Include a clear link: `[Seeing symptoms? Learn about our Leak Diagnostic →]` pointing to `/diagnostic`

---

**SECTION 3 — What this includes (and what it doesn't)**

```
This is a visual exterior inspection, not a leak diagnostic. I walk your roof and perimeter, assess sealant condition at seams, windows, doors, vents, and trim, and touch up minor superficial cracks with appropriate sealant.

What it does NOT include:
- Pressure testing
- Interior moisture mapping
- Hidden leak investigation
- Any guarantee of watertightness

If I find something during the inspection that suggests active water intrusion, I'll tell you — and we can discuss upgrading to a full diagnostic on the spot or scheduling one later.
```

---

**SECTION 4 — Proof block** (same review as diagnostic page — reuse what you have)

---

**SECTION 5 — FAQ (shorter)**

```
How long does it take?
About 60-90 minutes depending on rig size.

What if you find a problem?
I'll show you what I see and recommend next steps. No surprise charges — if it needs a diagnostic, we discuss that separately.

Do you do this on any RV?
Travel trailers, fifth wheels, and motorhomes. If I can safely access the roof and exterior, I can inspect it.
```

---

**SECTION 6 — Final CTA**

```
Keep your rig ahead of the weather.

Call or text: (360) XXX-XXXX
brian@stoprvleaks.com
$190 intro pricing — limited availability.
```

---

## Page 3: `/` (Homepage)

### Purpose
General brand page for people who find Stop RV Leaks organically, type the URL directly, or arrive from a Google Business Profile click. This is the "who is this guy" page.

### Scroll Structure

**Hero:**
```
Mobile RV Leak Detection & Repair
Snohomish · Skagit · North King County
```

Brief positioning line:
```
Pressure-test-based leak diagnostics, honest findings, and documented repairs — at your location.
```

Two clear pathways below the hero (card-style):

Card 1:
```
Suspect a Leak?
Founding Customer Diagnostic — $350 (normally $695)
Pressure testing, full inspection, documentation, and up to 1 hour of repair.
[Learn More →] → /diagnostic
```

Card 2:
```
Preventive Checkup
Seal Check — $190
Visual exterior inspection and minor sealant touch-up for symptom-free coaches.
[Learn More →] → /seal-check
```

**Below that:**
- Brief "About" section: who Brian is, what his approach is, why he started this. Keep it short — 3-4 sentences. Competence and honesty, not a life story. Mention SealTech equipment and dealership-level experience without sounding like a résumé.
- Proof section (review + field photos as available)
- Service area section (list of counties, maybe a simple map)
- Contact section with phone, email, and service hours

---

## Technical Notes

- Host on Netlify (existing setup)
- Static HTML/CSS/JS is fine — no framework needed unless there's a reason
- Mobile-first responsive. Test at 375px width as primary viewport.
- Tap-to-call links on all phone numbers: `<a href="tel:+1XXXXXXXXXX">`
- Page speed matters for Google Ads Quality Score — keep it lean. No heavy frameworks, no unnecessary JS. Optimize images.
- Google Ads conversion tracking tag needs to go in the `<head>` of at least the `/diagnostic` page (Brian will add the specific tag — leave a comment placeholder for it)
- Google tag / analytics placeholder in `<head>` as well
- Favicon and meta tags (title, description) for each page — write them for the audience:
  - `/diagnostic` title: "RV Leak Diagnostic — Mobile Pressure Testing | Stop RV Leaks"
  - `/seal-check` title: "Preventive RV Seal Check — $190 | Stop RV Leaks"
  - `/` title: "Stop RV Leaks — Mobile RV Leak Detection & Repair | WA"

---

## Phone Number

Brian's business number is through Google Voice. Use this placeholder in the build: `(360) 555-0199` — Brian will replace with real number before deploying. Mark every instance with a comment so they're easy to find-and-replace.

---

## What NOT to Include

- No mention of the Complete Reseal / Verified Watertight package anywhere on these pages. That offer comes later in the funnel during post-diagnostic conversations.
- No "About Camping World" or any reference to Brian's current employer.
- No pricing for repairs beyond what's described in the diagnostic offer card.
- No stock photography. Use solid color blocks or subtle texture as placeholders where photos will go. Label them clearly: `[PHOTO: field diagnostic in progress]`, `[PHOTO: pressure test bubbles on seam]`, etc.
- No chat widgets, pop-ups, or email capture forms. The conversion action is a phone call or text. Keep it simple.
- No social media links in the header. They can go in the footer if needed but they should not pull attention from the CTA.

---

## Summary

The site has three pages with three jobs:

| Page | Audience | Offer | Traffic Source |
|------|----------|-------|---------------|
| `/diagnostic` | Has a leak, stressed, searching | $350 diagnostic (normally $695) | Google Ads |
| `/seal-check` | No symptoms, curious, cautious | $190 preventive check | Nextdoor, Facebook, campgrounds |
| `/` | General visitors, organic, GBP | Both offers as pathways | Direct, organic, referral |

Every page has one primary CTA: call or text Brian's phone number. Everything on each page either builds toward that action or gets out of the way.
