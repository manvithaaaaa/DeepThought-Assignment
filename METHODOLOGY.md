# Methodology: Target Company Research
## DeepThought Business Analytics Assignment — Part A
**City:** Bengaluru | **Segment:** Medical Devices (IVD, implants, wearables, surgical instruments)
**Prepared for:** DeepThought Internship Application

---

## Why Bengaluru for Medical Devices

Bengaluru was chosen over Pune or Hyderabad for this segment for three reasons:

1. **Ecosystem density.** The city has 100+ medical device companies clustered around Peenya Industrial Area, Electronic City, Hebbal, and the IISc ecosystem. BioAsia and Karnataka's biotech policy have deliberately built this cluster since 2000.
2. **Technical talent.** IISc, IIIT-B, and BITS Pilani alumni concentration means the Federer profile — technically-trained promoter, building capability in-house — occurs more naturally here than in purely manufacturing cities like Coimbatore.
3. **Regulatory proximity.** CDSCO's Bengaluru office, CCAMP (Centre for Cellular and Molecular Platforms), and BIRAC's Southern regional presence make early-stage medtech companies cluster here.

---

## Sources Used

### Primary sources (where I started)
- **CDSCO Licensed Manufacturer Registry** (cdsco.gov.in) — Government list of all licensed medical device manufacturers by state. Filtered for Karnataka. This is the authoritative list of actual manufacturers vs. traders.
- **Tracxn.com** — Startup database with revenue, funding, cap table data for Indian startups. Used to verify revenue bands and ownership structures (critical for PE/VC filter).
- **LinkedIn company pages** — Verified founder backgrounds, IIT/IISc/NIT/BITS/IISc pedigree, employee count, recent hires.
- **Company websites** — Checked for: website copyright year (2024-2025 = active), certifications listed, news/press section, recent product launches.
- **MCA (Ministry of Corporate Affairs) Registrar** — Used via Tofler.in and TheCompanyCheck.com to verify revenue, incorporation date, directors, charges.

### Secondary sources (for validation)
- **Crunchbase / PitchBook** — Cross-referenced funding rounds and investor identity (flagged PE/VC-majority ownership).
- **BioBuzz India / BioSpectrum India / YourStory** — Industry news sources for recent announcements, certifications, expansion news.
- **BIRAC DPIIT grant database** — Identified BIRAC-funded deep tech medical device companies (strong signal for technical differentiation).
- **India MedTech Expo 2025 exhibitor list** — Companies that exhibit at this event are active manufacturers, not traders.

---

## Research Process

### Step 1: Universe generation (~60-80 companies identified)
I started with three parallel searches:
- CDSCO Karnataka manufacturer registry → ~40 Bengaluru-based registered manufacturers
- Tracxn "Medical Devices Bengaluru" → 175 companies listed, filtered by stage and funding
- LinkedIn "medical device manufacturer Bengaluru" + keyword filters for "CDSCO", "ISO 13485", "CE marked"

This gave me an initial universe of ~75 companies to investigate.

### Step 2: First-pass filter (removed ~30 companies)
Applied the auto-disqualify criteria:
- **Traders/distributors removed:** Companies with IndiaMart pages selling imported devices without manufacturing evidence, or "supplier" language on websites.
- **CROs/service companies removed:** Several companies like testing labs, analytical service providers, regulatory consulting firms — same industry language but sell services not products.
- **Large groups removed:** Companies with visible PE ownership or MNC subsidiary structure.
- **Revenue check:** Companies with public data showing >Rs.500Cr revenue (BPL Medical Technologies at Rs.516Cr FY25 was borderline; Skanray at ~Rs.900Cr estimate was likely above).

### Step 3: Deep-dive profiling (~45 companies researched in detail)
For each remaining company I spent 15-20 minutes verifying:
- **C1 (Manufacturer):** CDSCO license number on website or in registry, ISO 13485 certificate, plant address, headcount in manufacturing.
- **C3 (Differentiated):** Patents (IPO India / Google Patents), regulatory approvals (USFDA, CE, CDSCO Class C), "first in India" claims (verified, not just asserted).
- **C4 (Technical DM):** LinkedIn founder profile, educational background, previous employer (ex-GE Healthcare, ex-IISc, ex-ISRO are strong signals).
- **C6 (Growth):** LinkedIn job postings in last 6 months, press releases in 2024-2025, website copyright year, news section freshness.

### Step 4: Yield and final selection
Of ~45 deep-dived companies:
- **20 passed** all 6 criteria (or 5 with a caveat documented)
- **5 clear fails** were retained with documented reasons (PE-controlled, not manufacturer, MNC subsidiary, etc.)
- **Result: 25 companies in final spreadsheet**

The ~30% yield described in the brief was accurate — I eliminated roughly 55 companies to arrive at 25 qualified entries.

---

## Segment-Specific Learning

### What separates a specialty medical device maker from a disqualify
The trickiest call in this segment: **the line between a diagnostic device company and a testing lab**. Several Bengaluru companies (e.g., Anand Diagnostic Laboratory) appear in medical device searches but are service providers. The check: do they sell a physical product to a hospital, or do they perform tests as a service? Only product companies qualify.

**Class of device matters for differentiation scoring:**
- CDSCO Class C (highest risk, same as implantable devices): strong signal of technical differentiation — pacemakers, surgical robots, AI-SaMD with life-critical implications
- CDSCO Class B: still meaningful but more common
- Class A: low barrier, less differentiating

**IIT/IISc pedigree concentration in Bengaluru medtech** is unusually high compared to other cities. Multiple companies in this list have PhD or IIT/IISc founders — this is a genuine regional pattern, not selection bias.

### Key sector-level context
- India imports ~80% of medical devices — creates massive China+1 and import substitution opportunity
- PLI Scheme for medical devices launched 2020, Rs.3,420Cr outlay — companies actively applying are growth-mode
- CDSCO notified 23 new regulated categories in 2023 — driving compliance-driven differentiation
- MedTech exports grew 88% in 6 years to Rs.31,120Cr (FY24-25) — strong export tailwind

---

## What I Excluded and Why

| Company | Why Excluded |
|---|---|
| Healthium Medtech | KKR acquisition 2024 — PE controlled |
| Siemens Healthineers India | MNC subsidiary |
| Narayana Health (device mentions) | Hospital chain, not manufacturer |
| BPL Medical Technologies | Rs.516Cr FY25 — just above threshold; also flat/declining growth |
| Various IndiaMart "manufacturers" | Primarily traders selling Chinese imports under Indian brand names |
| Opto Circuits | Legacy company with debt/restructuring history; no active founder-led growth |
| Zynex Medical India | US parent company, India presence only |

---

## Code / Tools Used

**No scraping scripts written** — data was gathered through manual structured research using public sources. The research process was systematic rather than automated:
- Tracxn, MCA, CDSCO registry as primary databases
- LinkedIn for founder background verification
- Tofler / TheCompanyCheck for financial data

If given access to Tracxn API or CDSCO scraping permissions, the process described in Part B (1000-company proposal) would automate much of this.

**AI tools used:** Claude was used as a thinking partner for structuring the criteria evaluation framework and drafting the personalization hooks. All company data was verified against primary sources — no company profiles were generated by AI without source verification.
