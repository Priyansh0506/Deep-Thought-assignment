# DeepThought — Target Company Research
## Business Analytics Internship Assignment | Part A

**Researcher:** Priyansh Sengar
**City:** Ahmedabad  
**Segments:** Basket A (Custom Synthesis & Specialty Chemicals) + Basket C (Specialty Textiles / Precision Engineering)  
**Date:** June 2026

---

## Research Overview

| Metric | Count |
|--------|-------|
| Total Companies Researched | ~90 |
| Passed (A/B Band) | 19–25 |
| Rejected / Disqualified | ~65–70 |
| Yield Rate | ~25–28% |

---

## Why Ahmedabad?

Ahmedabad and its satellite industrial zones (Vatva GIDC, Naroda GIDC, Changodar, Karoli) represent one of India's densest clusters of specialty chemical and textile manufacturers. The city has:
- 3,000+ chemical units in Vatva GIDC alone
- Strong pharma excipient and dye intermediate ecosystem
- Active export orientation (USA, Europe, Gulf)
- High density of promoter-driven MSMEs in the ₹50Cr–₹500Cr revenue band

---

## Why Basket A + Basket C?

**Basket A (Specialty Chemicals):** Ahmedabad is India's chemical hub. China+1 tailwinds, PLI-adjacent sectors, and strong export infrastructure make this the highest-density Federer segment here.

**Basket C (Precision Manufacturing / Technical Textiles):** Gujarat has a deep textile legacy. Specialty yarn, technical fabrics, and precision auto components have strong operator-founder profiles with demonstrated systems thinking.

---

## Data Sources Used

| Source | Purpose |
|--------|---------|
| IndiaMart / Tradeindia | Initial company discovery by product category |
| LinkedIn | Founder background, hiring signals, team size |
| Tofler / Tracxn / ZaubaCorp | Revenue, MCA filings, director details |
| MCA Portal | Director appointments, charges, AGM dates |
| Company Websites | Products, certifications, R&D, news |
| Naukri / LinkedIn Jobs | Hiring signals (C6) |
| Google News | Expansion announcements, certifications |
[ I ALSO USE AI TOOLS - CLAUDE,CHATGPT,KIMI,COPILOT,GOOGLE GEMNI ETC ---- I USE THEM AS A CLEANING,TRANSFORMING PURPOSE]

---

## Research Process — Step by Step

### Step 1: Discovery (Finding ~90 Companies)
Search queries used:
- `"specialty chemicals" Ahmedabad Vatva GIDC manufacturer`
- `"pharma intermediates" Ahmedabad exporter`
- `"dye intermediates" Vatva GIDC producer`
- `"specialty yarn" Gujarat manufacturer`
- `"precision engineering" Ahmedabad CNC`
- IndiaMart category: Specialty Chemicals → Gujarat → Filter by Manufacturer

  #NOTE - I also use a simple rule ( ₹50-500 Cr Revenue, >20% Growth, >15% EBITDA, 100% Unlisted Private) not all
          company fullfil this but almost was.
  -I use this for level 1 filteration .

### Step 2: Gate Check (E1 + E2)
Before scoring any company:
- **E1:** Verified they have own plant/facility (not trader/distributor)
- **E2:** Confirmed Ahmedabad / Gujarat operational presence (not just registered office)

Common E1 failures found:
- Traders listing on IndiaMart as "manufacturers"
- CROs / testing labs (service, not product)
- Companies with only a sales office in Ahmedabad

### Step 3: Auto-Disqualify Check
Checked each company for hard disqualifiers:
- PE/VC ownership (checked Tracxn, Crunchbase)
- Large group subsidiary (Tata, Reliance, L&T divisions)
- Recent acquisition by large group
- Revenue > ₹500Cr (checked Tofler)
- No website or placeholder site
- No activity in last 2 years

### Step 4: Scoring (C3–C8)
For each company that passed gates + auto-DQ check:
- Scored each criterion: Weak (0) / Moderate (half weight) / Strong (full weight)
- Documented evidence source for each score
- Band assigned: A (80–100) / B (60–79) / C (40–59) / D (<40)

### Step 5: Final Shortlist
- Included all A and B band companies
- Noted C-band companies with caveats for further research
- Documented all fails in fail_list.csv

---

## Scoring Criteria Reference

| # | Criterion | Weight | Strong Signal |
|---|-----------|--------|---------------|
| C3 | Differentiated | 20 | Patents, USFDA/WHO-GMP, proprietary products |
| C4 | Decision-Maker Quality | 15 | PhD/IIT founder or ERP/SAP operator |
| C5 | Growing Sector | 15 | PLI, China+1, export tailwinds |
| C6 | Growth Signals | 15 | 2+ of: hiring, facility, certification, website activity, financial growth |
| C7 | Systems Maturity | 20 | SAP/ERP confirmed, SCADA, structured costing |
| C8 | Leadership Succession | 15 | Gen-2 on board, professional managers hired |

---

## Key Learnings from Research

1. **C7 is the biggest filter** — many technically differentiated companies fail because zero ERP/systems evidence
2. **Vatva GIDC is the richest cluster** — highest density of specialty chemical producers
3. **~30% yield is realistic** — 70% of companies researched failed E1, auto-DQ, or scored D-band
4. **LLP structures** — generally weaker on C7/C8 vs Pvt Ltd companies

---

## Files in This Repository

| File | Description |
|------|-------------|
| `companies failed.csv` | Full research log of all ~57 failed company|
| `company pass.csv` | Final 25 companies (A + B band) |
| `README.md` | This methodology document |

---

*Assignment submitted as part of DeepThought Business Analytics Internship application.*
