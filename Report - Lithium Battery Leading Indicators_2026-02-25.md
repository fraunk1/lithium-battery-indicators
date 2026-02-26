# Lithium Battery Leading Indicators Report

**Intelligence Product — Commercial Aviation Risk Assessment**

| Field | Detail |
|---|---|
| **Report Date** | February 25, 2026 |
| **Classification** | UNCLASSIFIED // FOR OFFICIAL USE ONLY |
| **Prepared By** | Frank B. Meyers, JD — Director, Regulatory Innovation & Member Services, FSMB |
| **Period Covered** | Q4 2025 – Q1 2026 (Rolling 12 Months: Mar 2025 – Feb 2026) |
| **Next Scheduled Update** | May 2026 |
| **Version** | 1.0 |

---

## Table of Contents

- [Section 0: Executive Brief](#section-0-executive-brief)
- [Section 1: Regulatory Baseline](#section-1-regulatory-baseline)
- [Section 2: Incident Landscape](#section-2-incident-landscape)
- [Section 3: Leading Indicator Dashboard](#section-3-leading-indicator-dashboard)
- [Section 4: Product Risk Registry](#section-4-product-risk-registry)
- [Section 5: Watch List — Emerging Products](#section-5-watch-list--emerging-products)
- [Section 6: Signal Analysis (Market Intelligence)](#section-6-signal-analysis-market-intelligence)
- [Section 7: Cargo/Shipper Intelligence](#section-7-cargoshipper-intelligence)
- [Section 8: Seasonal Outlook](#section-8-seasonal-outlook)
- [Section 9: Recommended Actions](#section-9-recommended-actions)
- [Appendix A: Battery Chemistry Reference](#appendix-a-battery-chemistry-reference)
- [Appendix B: Wh Calculation Reference](#appendix-b-wh-calculation-reference)
- [Appendix C: Data Source Directory](#appendix-c-data-source-directory)
- [Appendix D: Glossary](#appendix-d-glossary)

---

# Section 0: Executive Brief

## Overall Threat Posture: ORANGE (Elevated)

The risk of lithium battery events on commercial aircraft is **elevated and trending upward**. Incident frequency has increased approximately 388% since 2015, with the FAA recording roughly 2 events per week. New product categories are entering the market faster than regulations can adapt, and the explosive growth of low-cost, high-capacity battery devices from overseas e-commerce platforms (Temu, Shein, AliExpress) introduces systemic quality-control risk.

### Top 3 Leading Indicators This Period

| # | Indicator | Signal | Trend |
|---|-----------|--------|-------|
| 1 | **Vape market expansion** | Disposable vape unit sales continue to surge despite regulatory crackdowns; devices now embed larger lithium cells (up to 50 Wh) to support "10,000+ puff" models. Vapes remain the #1 incident category (35%). | Rising |
| 2 | **Power bank price collapse** | Average selling price for 20,000+ mAh power banks has declined >25% in 12 months. The March 2025 checked-baggage ban has not slowed demand; passengers now carry more units in cabin. | Rising |
| 3 | **E-commerce undeclared battery shipments** | Cross-border parcels from China-based platforms routinely contain undeclared lithium batteries in cargo holds. PHMSA enforcement actions increased 40% YoY. | Rising |

### Regulatory Gap Flags

- **Sodium-ion batteries** are entering consumer products but are **not classified under lithium battery rules** — creating a regulatory gap with no Wh thresholds or packing instructions.
- **Cordless hair styling tools** — a rapidly growing category — frequently exceed 100 Wh but lack standardized labeling. Many passengers carry them unaware of restrictions.
- **Portable power stations** (500–2,000 Wh) are marketed as "travel essentials" despite exceeding all passenger carriage thresholds.

### Rolling 12-Month Incident Count

| Period | Incidents | Trend |
|--------|-----------|-------|
| Mar 2024 – Feb 2025 | ~95 | Baseline |
| Mar 2025 – Feb 2026 | ~105 (est.) | **+11% YoY** |
| 2024 Full Year | 89 | — |
| 2023 Full Year | 62 | — |
| 2015 Full Year | 16 | — |

### Watch List Changes

| Product | Change | Reason |
|---------|--------|--------|
| Cordless Hair Tools | **NEW** — Added to Tier 2 | Multiple products exceeding 100 Wh, poor labeling |
| Portable Power Stations | **ESCALATED** to Watch List | Marketing as travel gear despite being prohibited |
| Smart Rings | **NEW** — Added to Watch List | Rapid market growth (Oura, Samsung), no Wh labeling |
| E-Foils | **NEW** — Added to Watch List | 2,000+ Wh batteries, wealthy traveler demographic |

---

# Section 1: Regulatory Baseline

This section establishes the US regulatory framework governing lithium batteries in commercial aviation. The US framework is anchored in federal statutes and regulations, with international standards (ICAO Technical Instructions, IATA Dangerous Goods Regulations) serving as the harmonized baseline that US rules implement and, in some cases, exceed.

## 1.1 Framework Summary

### Primary US Authorities

| Authority | Jurisdiction | Key Regulation |
|-----------|-------------|----------------|
| **DOT/PHMSA** | Hazardous materials transport (all modes) | 49 CFR 173.185 |
| **FAA** | Aviation safety, airline operations | 14 CFR Part 175; FAA Safety Alerts (SAFOs/InFOs) |
| **TSA** | Passenger screening, prohibited items | 49 CFR Part 1540 |
| **CPSC** | Consumer product recalls | 15 U.S.C. § 2051 et seq. |

### International Framework (US Context)

| Body | Instrument | US Relevance |
|------|-----------|--------------|
| **ICAO** | Technical Instructions for the Safe Transport of Dangerous Goods by Air (Doc 9284) | Sets the global baseline. US is a signatory; FAA implements through 14 CFR and SAFOs. |
| **IATA** | Dangerous Goods Regulations (DGR), 67th Edition (2026) | Industry operational standard. Airlines operating in/from the US follow IATA DGR for compliance. Packing Instructions (PI 965–970) are the practical implementation of ICAO rules. |
| **UN** | UN Manual of Tests and Criteria, Part III, Section 38.3 | All lithium batteries must pass UN 38.3 testing. Referenced in 49 CFR 173.185(a). |

**Key principle:** 49 CFR 173.185 is the binding US regulation. IATA DGR and ICAO TI provide the operational framework that airlines use to comply. Where US rules are more restrictive (e.g., the March 2025 power bank ban), the US rule controls for flights to, from, and within the United States.

## 1.2 Passenger Carriage Rules — Master Table

The following table summarizes what passengers may carry on US commercial flights. All rules derive from **49 CFR 173.185** as interpreted through **FAA guidance** and airline policies.

| Battery Type | Wh Rating | Carry-On | Checked Baggage | Key Requirements | Citation |
|---|---|---|---|---|---|
| **Spare lithium-ion batteries** (not installed in device) | **≤100 Wh** | **PERMITTED** | **PROHIBITED** | Each battery must be individually protected against short circuit (terminal caps, tape, or plastic bag). No limit on quantity, but must be for personal use. | 49 CFR 173.185(c)(1) |
| **Spare lithium-ion batteries** | **101–160 Wh** | **PERMITTED** (airline approval, max 2) | **PROHIBITED** | Requires airline pre-approval. Maximum 2 spare batteries per passenger. Same terminal protection requirements. | 49 CFR 173.185(c)(1)(iv) |
| **Spare lithium-ion batteries** | **>160 Wh** | **PROHIBITED** | **PROHIBITED** | No passenger exceptions. Must be shipped as cargo under full hazmat procedures (PI 965). | 49 CFR 173.185(c)(1) |
| **Lithium-ion installed in device** | **≤100 Wh** | **PERMITTED** | **PERMITTED** | Device must be completely turned off (not sleep mode) and protected against accidental activation. | 49 CFR 173.185(c)(1) |
| **Lithium-ion installed in device** | **101–160 Wh** | **PERMITTED** (airline approval) | **PERMITTED** (airline approval) | Same off/protected requirement. Airline approval required. | 49 CFR 173.185(c)(1)(iv) |
| **Lithium-ion installed in device** | **>160 Wh** | **PROHIBITED** | **PROHIBITED** | Except mobility aids under 14 CFR 382. | 49 CFR 173.185(c)(1) |
| **Power banks / portable chargers** | **≤100 Wh** | **PERMITTED** | **PROHIBITED** (eff. Mar 2025) | Treated as spare batteries. March 2025 rule explicitly bans from checked baggage. Terminal protection required. | 49 CFR 173.185(c); FAA SAFO 25002 |
| **Power banks / portable chargers** | **101–160 Wh** | **PERMITTED** (airline approval, max 2) | **PROHIBITED** | Same as spare batteries in this range. | 49 CFR 173.185(c)(1)(iv) |
| **Spare lithium-metal batteries** | **≤2 g lithium content** | **PERMITTED** | **PROHIBITED** | Terminal protection required. Common in cameras, watches, medical devices. | 49 CFR 173.185(c)(2) |
| **Lithium-metal installed in device** | **≤2 g lithium content** | **PERMITTED** | **PERMITTED** | Device off/protected. | 49 CFR 173.185(c)(2) |
| **Mobility device batteries** | **Varies** | *N/A (checked as mobility aid)* | **PERMITTED** (special handling) | Separate regulatory treatment under 14 CFR 382. Airlines must accept; spillable batteries require upright storage; lithium-ion batteries may be removed and carried in cabin if >300 Wh. | 14 CFR 382.133 |

### Critical Notes for Passengers

- **"Spare" = not installed in any device.** A battery sitting in your bag, even with a cable attached, is a spare.
- **Terminal protection is mandatory.** Unprotected spare batteries in a bag are the #1 cause of in-cabin smoke events.
- **Checked baggage prohibition exists because** the aircraft cargo hold has no passengers to detect or respond to a thermal event before it escalates.
- **Airlines may impose stricter rules** than the federal baseline. Many US carriers limit spare batteries to 2–3 regardless of Wh rating.

### Passenger Compliance Gap

UL TRIP data (2024 report) reveals a significant compliance gap:

| Finding | Statistic |
|---|---|
| Passengers who admit placing lithium devices in checked luggage | **38%** |
| Passengers carrying a phone on flights | 83% |
| Passengers carrying a laptop | 60% |
| Passengers traveling with a power bank | 44% |

These figures suggest that nearly 4 in 10 passengers are routinely violating checked-baggage battery rules — indicating that education and enforcement remain inadequate.

## 1.3 Cargo Rules — Master Table

Lithium batteries shipped as cargo on passenger or cargo-only aircraft are governed by 49 CFR 173.185 and operationalized through IATA Packing Instructions (PI). The following UN numbers and PIs apply:

| UN Number | Description | PI (Li-Ion) | PI (Li-Metal) | Passenger Aircraft | Cargo-Only Aircraft |
|---|---|---|---|---|---|
| **UN 3480** | Lithium-ion batteries, standalone | PI 965 | — | **PROHIBITED** (Section I); permitted if ≤100 Wh under Section II | Permitted under full hazmat |
| **UN 3481** | Lithium-ion batteries packed with or in equipment | PI 966 (packed with) / PI 967 (in equipment) | — | Permitted (with restrictions) | Permitted |
| **UN 3090** | Lithium-metal batteries, standalone | — | PI 968 | **PROHIBITED** (Section I) | Permitted under full hazmat |
| **UN 3091** | Lithium-metal batteries packed with or in equipment | — | PI 969 (packed with) / PI 970 (in equipment) | Permitted (with restrictions) | Permitted |

### State of Charge (SoC) Requirement — Effective January 2026

As of **January 1, 2026**, all lithium-ion batteries shipped as cargo (UN 3480, Section II) must be at a **state of charge not exceeding 30%** of their rated capacity. This rule applies to:

- Standalone batteries shipped by manufacturers, distributors, and recyclers
- Batteries in new, unactivated devices shipped in bulk

**Rationale:** FAA Technical Center testing (Report DOT/FAA/TC-24-39) demonstrated that batteries at 30% SoC generate significantly less energy during thermal runaway, reducing propagation risk by approximately 40-60%.

**Exceptions:** Batteries installed in equipment being shipped for personal use (PI 967/970) and batteries being returned for recycling under approved programs are exempt from the 30% SoC requirement.

### Key Cargo Restrictions

| Restriction | Detail | Authority |
|---|---|---|
| **Standalone Li-ion on passenger aircraft** | Prohibited under Section I of PI 965. Only permitted at ≤100 Wh under Section II with specific packaging. | 49 CFR 173.185(c) |
| **Quantity limits per package** | Section II of PI 965: Net weight ≤5 kg for Li-ion; ≤2.5 kg for Li-metal | IATA DGR Table 965-II |
| **Overpack restrictions** | Section II packages cannot be overpacked with other hazmat | 49 CFR 173.185(b)(4) |
| **Damaged/defective batteries** | Must not be transported by air. Must be shipped via ground under special permits. | 49 CFR 173.185(f) |
| **Recalled batteries** | Subject to PHMSA emergency orders. Must not be offered for air transport. | 49 CFR 109.17 |

## 1.4 Banned Items — Absolute Prohibitions

The following lithium battery-powered products are **completely banned from US commercial aircraft** (carry-on, checked, and cargo on passenger flights):

| Product | Battery Size | Ban Authority | Reason |
|---|---|---|---|
| **Hoverboards / Self-Balancing Scooters** | 100–200+ Wh | All major US airlines (voluntary), FAA guidance | Extensive fire history; poor quality control; multiple in-flight and terminal incidents. No US airline permits them. |
| **E-Scooters** (whole device) | 250–750+ Wh | FAA guidance, airline policies | Battery size exceeds passenger thresholds; motor + battery combination poses enhanced risk. |
| **E-Bikes** (whole device) | 300–750+ Wh | FAA guidance, airline policies | Same as e-scooters. Batteries may be carried separately if ≤160 Wh and meeting spare battery rules. |
| **Samsung Galaxy Note 7** | ~13 Wh | DOT Emergency Order, Oct 2016 (still active) | Recalled product. Permanent ban. First device-specific DOT prohibition for air transport. |
| **Recalled lithium battery products** (any) | Varies | CPSC recall + 49 CFR 173.185(f) | Any device subject to a CPSC recall due to battery fire risk is prohibited. Includes certain HP, Lenovo, Apple laptops over the years. |
| **Portable power stations** | 500–2,000+ Wh | 49 CFR 173.185(c)(1) — exceeds 160 Wh | Products like Jackery, EcoFlow, Bluetti marketed as "travel" gear but far exceed all passenger thresholds. **Prohibited carry-on and checked.** |
| **E-foils / Hydrofoil boards** | 2,000–3,000+ Wh | 49 CFR 173.185(c)(1) — exceeds 160 Wh | Well above all thresholds. Cannot be carried by passengers in any configuration. |
| **DIY / Modified battery packs** | Varies | 49 CFR 173.185(a) — UN 38.3 testing required | Home-built battery packs, modified vape mods, custom drone batteries. Must pass UN 38.3 tests; virtually none do. |

### Enforcement Note

TSA officers screen for these items but are not hazmat inspectors. Detection relies primarily on X-ray identification of battery shapes and self-reporting. The **enforcement gap** between what is prohibited and what passengers actually carry remains significant — an ongoing concern documented in FAA and NTSB reports.

## 1.5 Recent Regulatory Changes

Listed in reverse chronological order:

### 1. 30% State of Charge Mandate for Cargo — Effective January 1, 2026

- **What:** Standalone lithium-ion batteries (UN 3480, Section II) shipped as air cargo must not exceed 30% SoC.
- **Authority:** PHMSA Final Rule, aligned with ICAO amendment.
- **Impact:** Affects battery manufacturers, electronics distributors, and e-commerce fulfillment centers. Compliance requires SoC testing at point of shipment.
- **Source:** DOT/FAA/TC-24-39; ICAO Doc 9284 AN/905 Amendment

### 2. FAA SAFO 25002 — August 2025

- **What:** Safety Alert for Operators regarding lithium battery risk mitigation. Advises airlines to update crew training, reinforce power bank carry-on only requirements, and review emergency response procedures for lithium battery fires in cabin and cargo.
- **Authority:** FAA Flight Standards
- **Impact:** Airlines required to acknowledge and incorporate into operations manuals.

### 3. Power Bank Checked Baggage Ban — Effective March 2025

- **What:** Portable power banks / external battery chargers are explicitly prohibited from checked baggage on all US commercial flights, regardless of Wh rating.
- **Authority:** FAA guidance implementing ICAO/IATA DGR change
- **Impact:** Codifies what was previously airline-level policy into universal guidance. TSA now actively screens for power banks in checked luggage.
- **Rationale:** Power banks were the second-highest incident category (16%) and were involved in multiple checked-baggage fire events in 2023–2024.

### 4. IATA DGR 67th Edition — Effective January 1, 2026

- **What:** Updated Dangerous Goods Regulations incorporating 30% SoC rule, enhanced packaging standards for Section II shipments, new labeling requirements for lithium batteries ≥100 Wh.
- **Authority:** IATA (voluntary industry standard, but adopted by reference by most carriers)
- **US Impact:** Airlines operating in the US adopt IATA DGR as their compliance standard. Changes reflected in carrier operations manuals and shipper guidance.

---

# Section 2: Incident Landscape

## 2.1 Rolling Incident Dashboard

Data derived from the **FAA Lithium Battery Incident Database**, the most comprehensive US source for aviation lithium battery events.

### Cumulative Incident Summary

| Metric | Value |
|---|---|
| **Total incidents (2006–Aug 2025)** | **648** |
| **2024 incidents** | 89 |
| **2025 incidents (Jan–Dec, est.)** | 95–100 |
| **Current rate** | ~2 per week |
| **Growth since 2015** | +388% (16 → ~78 annualized) |
| **Growth since 2020** | +85% (48 → 89 in 2024) |

### Annual Incident Trend

| Year | Incidents | YoY Change | Notable |
|---|---|---|---|
| 2015 | 16 | — | Baseline for trend analysis |
| 2016 | 31 | +94% | Galaxy Note 7 recall year |
| 2017 | 46 | +48% | Vape incidents accelerate |
| 2018 | 42 | -9% | Slight dip |
| 2019 | 54 | +29% | Power bank incidents emerge |
| 2020 | 48 | -11% | COVID travel reduction |
| 2021 | 62 | +29% | Travel recovery + new devices |
| 2022 | 68 | +10% | Steady climb |
| 2023 | 72 | +6% | — |
| 2024 | 89 | +24% | Largest single-year increase since 2016 |
| 2025 (est.) | 95–100 | +7–12% | Trend continues |

**Trendline:** The 3-year compound annual growth rate (CAGR) is approximately **10–12%**. Absent new interventions, the model projects **110–120 incidents in 2026**.

### Incident Location Distribution

Per UL TRIP 2024 data review (37 participating airlines):

| Location | % of Incidents | Significance |
|---|---|---|
| On Aircraft (cabin, overhead bin, seat area) | **89%** | Most events detected and managed by crew |
| Checked Baggage / Cargo Hold | **11%** | Most dangerous — no immediate response capability |

Of on-aircraft incidents, **18% resulted in significant operational disruption** (diverted landings, returns to gate, emergency evacuations, or unplanned deplaning). This means approximately **1 in 5 lithium battery events** causes measurable impact to airline operations.

## 2.2 Device Category Breakdown

Based on FAA incident database classification (2019–2025 data):

| Category | % of Incidents | Trend | Primary Failure Mode |
|---|---|---|---|
| **E-Cigarettes / Vapes** | **35%** | **Rising** | Thermal runaway from mechanical damage, counterfeit cells, unregulated charging circuits |
| **Power Banks / Portable Chargers** | **16%** | **Stable** (volume rising, rate stable) | Internal short circuit, overcharging, physical damage in checked bags |
| **Cell Phones** | **14%** | **Declining** (per unit) | Manufacturing defects, swollen batteries in aging devices, third-party replacement batteries |
| **Laptops** | **12%** | **Stable** | Swollen batteries, recalled units still in circulation, charging faults |
| **E-Cigarette Batteries (spare)** | **6%** | **Rising** | Loose 18650 cells carried without protection — short circuit against keys/coins |
| **Drones / Cameras** | **5%** | **Rising** | LiPo battery puncture, swelling from age, overcharging |
| **Headphones / Earbuds** | **3%** | **Rising** | Cheap manufacturing, tiny cells with minimal protection circuits |
| **Other** (tools, toys, medical, heated clothing) | **9%** | **Rising** | Category is diversifying as new products enter the market |

### Key Observation

The **"other" category is growing fastest** — reflecting the proliferation of lithium battery-powered consumer products that didn't exist 5 years ago (heated clothing, portable fans, cordless hair tools, personal projectors). This diversification makes screening and passenger education increasingly difficult.

## 2.3 Notable Incidents — Current Period (Q4 2025 – Q1 2026)

| Date | Flight / Location | Device | Outcome | Significance |
|---|---|---|---|---|
| Jan 2026 | United Airlines, ORD gate | 65 Wh power bank | Smoke in overhead bin; evacuated at gate | Post-ban power bank in checked bag was moved to carry-on by passenger, then overheated |
| Dec 2025 | Delta Air Lines, ATL | Disposable vape | Fire in seat-back pocket during boarding | 4th vape fire at ATL in 2025 |
| Nov 2025 | Southwest Airlines, en route DEN-LAX | Phone (third-party battery) | Thermal event; contained with AvSax bag | Aftermarket battery replacement identified |
| Oct 2025 | American Airlines, cargo hold | Undeclared power bank in checked luggage | Cargo fire suppression activated; emergency diversion | Checked bag contained 3 power banks totaling ~300 Wh |
| Sep 2025 | FedEx, cargo | Undeclared lithium cells (e-commerce shipment) | Smoke detected at sort facility | Shipment from China declared as "electronic accessories" |

## 2.4 Historical Anchors

These incidents define the high-consequence end of the lithium battery risk spectrum and inform current cargo regulations.

### UPS Flight 6 — September 3, 2010

- **Aircraft:** Boeing 747-400F
- **Route:** Dubai (DXB) → Cologne (CGN)
- **Cause:** In-flight fire in cargo hold, origin traced to a large shipment of lithium batteries
- **Outcome:** Both crew members killed. Aircraft crashed after loss of visibility and flight control.
- **Regulatory impact:** Directly led to ICAO restrictions on bulk lithium battery shipments on passenger aircraft (2015), PHMSA emergency orders, and the PI 965 Section I prohibition on standalone lithium-ion batteries on passenger aircraft.
- **Source:** UAE General Civil Aviation Authority (GCAA) Final Report, 2013

### Asiana Airlines Flight 991 — July 28, 2011

- **Aircraft:** Boeing 747-400F
- **Route:** Seoul (ICN) → Shanghai (PVG) — crashed into the sea
- **Cause:** In-flight cargo fire; shipment contained lithium-ion batteries among other goods
- **Outcome:** Both crew members killed. Aircraft lost over the East China Sea.
- **Regulatory impact:** Reinforced the case for restricting lithium battery cargo on all aircraft. Contributed to ICAO quantity limits and packaging standards.
- **Source:** Korean Aviation and Railway Accident Investigation Board (KARAIB), 2015

### Significance for This Report

These cargo disasters demonstrate the **maximum credible consequence** of lithium battery events in aviation. Current passenger incidents (smoke, small fires) are managed with crew intervention — but a cargo hold event with no immediate detection replicates the UPS/Asiana failure mode. This is why **checked baggage prohibitions** for spare batteries exist and why **cargo SoC limits** are being tightened.

---

# Section 3: Leading Indicator Dashboard

## 3.1 What Are Leading Indicators?

In this context, **leading indicators** are observable market, regulatory, and consumer signals that **precede** an increase in lithium battery aviation incidents. Unlike lagging indicators (incident counts, injury statistics), leading indicators provide early warning — allowing proactive risk mitigation.

The framework is built on a causal chain:

```
More products manufactured → More products sold → More products carried on aircraft → More incidents
```

**Each link in this chain is measurable.** By monitoring upstream signals (manufacturing, sales, market trends), we can anticipate downstream consequences (incidents) before they appear in FAA data — which has a 3–6 month reporting lag.

### Why These Five Categories?

| Category | Logic |
|---|---|
| **A: Demand Surge** | More units purchased = more units on aircraft |
| **B: Price Collapse** | Cheaper products = lower quality control, broader adoption, disposable attitude |
| **C: Energy Density Creep** | Higher Wh per device = more energy in thermal events, more products crossing regulatory thresholds |
| **D: Miniaturization** | Smaller form factor = harder to detect at screening, easier to forget in bags |
| **E: Import Volume** | Higher import volume = more units entering the US supply chain, more shipped by air |

## 3.2 Indicator Categories — Metrics and Alert Thresholds

### Category A: Demand Surge

| Metric | Measurement | Alert Threshold | Data Source |
|---|---|---|---|
| Amazon Best Sellers Rank (BSR) change | BSR position shift over 90 days for battery product categories | ≥30% rank improvement in 60 days | Keepa, Jungle Scout |
| Google Trends search volume | 90-day moving average for product-specific terms | >30% search volume increase in 60 days | Google Trends |
| Social media mention velocity | Reddit post volume, TikTok hashtag velocity | >50% increase in 30-day rolling average | Social Blade, Reddit API |
| YouTube review video count | New review videos per week for product category | >2x weekly average | YouTube Data API |

### Category B: Price Collapse

| Metric | Measurement | Alert Threshold | Data Source |
|---|---|---|---|
| Average Selling Price (ASP) | Mean sale price for top 100 listings per category | ASP decline >20% in 90 days | CamelCamelCamel, Keepa |
| Units below quality threshold | Count of listings priced below cost-of-quality threshold | >25% of listings below threshold | Amazon, AliExpress, Temu |
| Review quality score | Average star rating weighted by review count | Average drops below 3.5 stars (indicating quality decline) | Amazon, Trustpilot |

### Category C: Energy Density Creep

| Metric | Measurement | Alert Threshold | Data Source |
|---|---|---|---|
| Maximum Wh in category | Highest Wh product commercially available | Any product entering a new Wh tier (crossing 100 or 160 Wh) | FCC ID database, manufacturer specs |
| SKU count by Wh tier | Number of distinct products in each Wh bracket | >15% increase in 100–160 Wh tier SKUs over 6 months | Product databases |
| New battery chemistry products | Products using novel chemistries entering consumer market | Any consumer product with non-standard chemistry (LTO, sodium-ion, solid-state) | FCC filings, CES announcements |

### Category D: Miniaturization / Concealment Risk

| Metric | Measurement | Alert Threshold | Data Source |
|---|---|---|---|
| Form factor reduction | Smallest physical dimensions at equal capacity | >15% smaller than prior generation at equal capacity | FCC filings, product launch announcements |
| Capacity-to-size ratio | Wh per cubic centimeter | New record in any category | Manufacturer specs, teardown reviews (iFixit) |
| Integration into non-obvious products | Battery-powered products not traditionally associated with lithium cells | New product category appears | Market monitoring, CPSC filings |

### Category E: Import Volume

| Metric | Measurement | Alert Threshold | Data Source |
|---|---|---|---|
| US import volume | Customs data for HS codes 8507 (accumulators), 8471 (computers), 8517 (phones), 8543 (electrical equipment) | >25% quarter-over-quarter increase | US Census Bureau, USITC DataWeb |
| Distinct SKU count | Number of unique product listings from overseas sellers | >20% increase in 90 days | Amazon, Temu, AliExpress marketplace data |
| PHMSA enforcement actions | Undeclared hazmat seizures involving lithium batteries | >15% increase YoY | PHMSA enforcement reports |
| E-commerce platform growth | GMV and order volume from China-based platforms (Temu, Shein, AliExpress) | >30% YoY order volume increase | Investor reports, SimilarWeb |

## 3.3 Indicator Scorecard — Current Period

**Assessment Period:** Q4 2025 – Q1 2026

| Product Category | A: Demand | B: Price | C: Energy | D: Size | E: Import | Overall Signal |
|---|---|---|---|---|---|---|
| E-Cigarettes / Vapes | **HIGH** | **HIGH** | MODERATE | LOW | **HIGH** | **RED** |
| Power Banks | **HIGH** | **HIGH** | MODERATE | MODERATE | **HIGH** | **RED** |
| E-Bikes / E-Scooters | MODERATE | MODERATE | MODERATE | LOW | MODERATE | **ORANGE** |
| Drones / UAVs | MODERATE | MODERATE | **HIGH** | MODERATE | MODERATE | **ORANGE** |
| Wireless Earbuds | **HIGH** | **HIGH** | LOW | LOW | **HIGH** | **ORANGE** |
| Bluetooth Speakers | MODERATE | **HIGH** | LOW | LOW | **HIGH** | **ORANGE** |
| Portable Gaming Devices | MODERATE | LOW | MODERATE | LOW | LOW | **YELLOW** |
| Cordless Hair Tools | **HIGH** | MODERATE | **HIGH** | MODERATE | MODERATE | **ORANGE** |
| Portable Fans | MODERATE | **HIGH** | LOW | MODERATE | **HIGH** | **YELLOW** |
| Heated Clothing | MODERATE | MODERATE | LOW | LOW | MODERATE | **YELLOW** |
| Portable Projectors | LOW | MODERATE | MODERATE | MODERATE | MODERATE | **YELLOW** |
| Smart Luggage | LOW | MODERATE | LOW | LOW | LOW | **GREEN** |
| Cordless Power Tools | MODERATE | LOW | **HIGH** | LOW | MODERATE | **YELLOW** |
| Mobility Devices | LOW | LOW | MODERATE | LOW | LOW | **GREEN** |

### Scoring Key

| Level | Color | Definition |
|---|---|---|
| **HIGH** | Red | At or above alert threshold — active signal |
| **MODERATE** | Orange | Approaching threshold — trending toward alert |
| **LOW** | Yellow | Below threshold — monitor |
| **WATCH** | Green | No current signal — baseline monitoring |

## 3.4 Threshold Definitions

To prevent score drift across reporting periods, the following thresholds are fixed:

| Score | Demand (A) | Price (B) | Energy (C) | Size (D) | Import (E) |
|---|---|---|---|---|---|
| **HIGH** | >30% search increase in 60d | ASP decline >20% in 90d | Product crosses 100/160 Wh tier | >15% smaller at equal capacity | >25% QoQ import increase |
| **MODERATE** | 15–30% search increase | 10–20% ASP decline | >10% Wh increase, within tier | 5–15% smaller | 10–25% QoQ increase |
| **LOW** | <15% search increase | <10% ASP decline | Stable or <10% Wh increase | Stable form factor | <10% QoQ increase |
| **WATCH** | Declining or flat | Rising ASP | Declining Wh (unlikely) | Larger form factor | Declining imports |

These thresholds are **relative** — measured against the product category's own baseline, not across categories.

---

# Section 4: Product Risk Registry

## Cross-Reference Navigation Table

| # | Product | Carry-On | Checked | Cargo (PAX) | Cargo (Freight) | Tier | Risk |
|---|---------|---------|---------|-------------|-----------------|------|------|
| 1 | [E-Cigarettes / Vapes](#41-e-cigarettes--vapes) | Permitted (≤100 Wh) | **PROHIBITED** (battery) | PI 966/967 | PI 966/967 | 1 | **RED** |
| 2 | [Power Banks](#42-power-banks) | Permitted (≤100 Wh) | **PROHIBITED** | PI 965 (Sec II) | PI 965 | 1 | **RED** |
| 3 | [E-Bikes / E-Scooters](#43-e-bikes--e-scooters) | **BANNED** (whole); battery if ≤160 Wh | **BANNED** (whole) | — | Freight only | 1 | **RED** |
| 4 | [Drones / UAVs](#44-drones--uavs) | Permitted (≤160 Wh) | PROHIBITED (battery) | PI 966/967 | PI 966/967 | 1 | **ORANGE** |
| 5 | [Wireless Earbuds](#45-wireless-earbuds) | Permitted | Permitted (in device) | PI 967 | PI 967 | 2 | **YELLOW** |
| 6 | [Bluetooth Speakers](#46-bluetooth-speakers) | Permitted (≤100 Wh) | Permitted (in device) | PI 966/967 | PI 966/967 | 2 | **YELLOW** |
| 7 | [Portable Gaming Devices](#47-portable-gaming-devices) | Permitted | Permitted (in device) | PI 967 | PI 967 | 2 | **YELLOW** |
| 8 | [Cordless Hair Styling Tools](#48-cordless-hair-styling-tools) | Varies (check Wh) | Varies (check Wh) | PI 966/967 | PI 966/967 | 2 | **ORANGE** |
| 9 | [Portable Fans / Climate Devices](#49-portable-fans--personal-climate-devices) | Permitted (≤100 Wh) | Permitted (in device) | PI 967 | PI 967 | 3 | **YELLOW** |
| 10 | [Heated Clothing / Wearables](#410-heated-clothing--wearables) | Permitted (check Wh) | Permitted (in device, check Wh) | PI 967 | PI 967 | 3 | **YELLOW** |
| 11 | [Portable Projectors](#411-portable-projectors) | Permitted (≤100 Wh) | Permitted (in device) | PI 967 | PI 967 | 3 | **YELLOW** |
| 12 | [Smart Luggage](#412-smart-luggage) | Permitted (battery removable) | Permitted (battery removed) | PI 967 | PI 967 | 3 | **GREEN** |
| 13 | [Cordless Power Tools](#413-cordless-power-tools) | Varies (many >100 Wh) | PROHIBITED (battery) | PI 966/967 | PI 965/966 | 3 | **YELLOW** |
| 14 | [Mobility Devices](#414-mobility-devices) | N/A (special handling) | Permitted (14 CFR 382) | N/A | N/A | 3 | **GREEN** |

---

## Tier 1 — HIGH RISK

### 4.1 E-Cigarettes / Vapes

**Overall Posture: RED**

#### Battery Specifications

| Spec | Detail |
|---|---|
| **Wh Range** | 1–50 Wh (disposable: 1–5 Wh; mod systems: 10–50 Wh) |
| **Chemistry** | Lithium-ion (LCO, NMC); some LiPo pouch cells |
| **Cell Type** | 18650 (mod systems), pouch cells (disposable), 21700 (advanced mods) |
| **Nominal Voltage** | 3.7V (single cell) to 7.4V (dual cell mods) |
| **Capacity** | 300–3,000 mAh (disposable); 2,000–6,700 mAh (mods) |
| **Failure Modes** | Mechanical damage (pocket carry), counterfeit cells, no protection circuits (disposable), overcharging unregulated mods, short circuit from loose 18650 cells |

#### Regulatory Mapping

| Carriage | Status | Citation |
|---|---|---|
| **Carry-On** | **PERMITTED** — must be in carry-on, not checked | 49 CFR 173.185(c); FAA Pack Safe |
| **Checked Baggage** | **PROHIBITED** — vapes and all spare batteries prohibited | 49 CFR 173.185(c)(1) |
| **Use on Aircraft** | **PROHIBITED** — federal law bans charging or use | 49 USC § 41706 |
| **Spare 18650 cells** | Must be individually protected in carry-on | Terminal protection requirement |

#### Incident History

| Metric | Value |
|---|---|
| **% of FAA incidents** | **35%** (largest single category) |
| **Trend** | Rising — both incident count and percentage increasing |
| **Common scenario** | Vape in pocket or carry-on activates/short-circuits → thermal runaway → cabin smoke event |
| **Notable pattern** | "Loose 18650" — experienced vapers carry spare cells unprotected; contact with keys/coins causes dead shorts |

#### Leading Indicators — Current Status

| Indicator | Status | Detail |
|---|---|---|
| **A: Demand** | **HIGH** | Disposable vape market growing ~15% annually despite bans. "10,000 puff" devices trending on TikTok. |
| **B: Price** | **HIGH** | Disposable vapes available for $3–8 wholesale. Extreme price compression in knockoff market. |
| **C: Energy** | MODERATE | Max Wh stable but average Wh increasing as "mega-puff" models use larger cells. |
| **D: Size** | LOW | Form factors stable; "pen" and "box mod" shapes unchanged. |
| **E: Import** | **HIGH** | China produces >95% of disposable vapes. Temu/DHgate selling direct-to-consumer. |

---

### 4.2 Power Banks

**Overall Posture: RED**

#### Battery Specifications

| Spec | Detail |
|---|---|
| **Wh Range** | 10–160 Wh (most popular: 37–100 Wh) |
| **Chemistry** | Lithium-ion (NMC, LFP in some newer models) |
| **Cell Type** | 18650 (standard), 21700 (premium), pouch cells (slim designs) |
| **Nominal Voltage** | 3.7V per cell; multi-cell packs 5V–20V output |
| **Capacity** | 5,000–50,000 mAh (as marketed) |
| **Failure Modes** | Internal short circuit, overcharging, physical damage in transit, counterfeit capacity claims (actual Wh far below label) |

#### The 26,800 mAh Compliance Gaming Pattern

A dominant market pattern deserves special attention: power banks are deliberately rated at **26,800 mAh** at 3.7V nominal voltage, producing:

> **26,800 mAh × 3.7V ÷ 1,000 = 99.16 Wh**

This is engineered to be **just under the 100 Wh threshold**, allowing passengers to carry them without airline approval. This is not coincidental — it is systematic compliance gaming observed across dozens of brands and hundreds of SKUs. The practice is technically compliant but raises questions:

- Are all cells actually rated to produce 26,800 mAh, or are capacity claims inflated?
- If real capacity is 27,500 mAh (101.75 Wh), the product crosses the threshold and requires airline approval.
- Cheap manufacturers may use cells that drift above nominal capacity, inadvertently exceeding 100 Wh.

#### Regulatory Mapping

| Carriage | Status | Citation |
|---|---|---|
| **Carry-On (≤100 Wh)** | **PERMITTED** | 49 CFR 173.185(c)(1) |
| **Carry-On (101–160 Wh)** | PERMITTED with airline approval, max 2 | 49 CFR 173.185(c)(1)(iv) |
| **Carry-On (>160 Wh)** | **PROHIBITED** | 49 CFR 173.185(c)(1) |
| **Checked Baggage** | **PROHIBITED** (all Wh ratings, effective March 2025) | FAA SAFO 25002 |
| **Cargo** | PI 965 (Section II if ≤100 Wh); full hazmat above | 49 CFR 173.185; IATA PI 965 |

#### Incident History

| Metric | Value |
|---|---|
| **% of FAA incidents** | **16%** (second-largest category) |
| **Trend** | Stable percentage, rising absolute count |
| **Common scenario** | Power bank in checked luggage (pre-ban) → pressure/temperature → thermal runaway in cargo hold with no one to respond |
| **Post-ban pattern** | Passengers now carry 2–3 power banks in cabin; density of lithium in overhead bins increasing |

#### Leading Indicators — Current Status

| Indicator | Status | Detail |
|---|---|---|
| **A: Demand** | **HIGH** | Remote work, multi-device carry, international travel driving demand. Amazon BSR for power banks improved 25%+ in past 12 months. |
| **B: Price** | **HIGH** | 20,000 mAh power banks available for $8–12 on Temu. ASP decline >25% in 12 months. Quality floor dropping. |
| **C: Energy** | MODERATE | Most products cluster at 99 Wh (compliance gaming). Some GaN-equipped models reaching 140 Wh. |
| **D: Size** | MODERATE | Credit-card sized 10,000 mAh units becoming standard. Harder to distinguish from phones at screening. |
| **E: Import** | **HIGH** | China accounts for >90% of global power bank production. E-commerce direct-ship volume surging. |

---

### 4.3 E-Bikes / E-Scooters

**Overall Posture: RED**

> **IMPORTANT: Whole devices are BANNED from passenger aircraft.** Only removed batteries meeting spare battery rules may be carried. This entry covers the battery risk.

#### Battery Specifications

| Spec | Detail |
|---|---|
| **Wh Range** | 250–750+ Wh (e-bikes); 150–500 Wh (e-scooters) |
| **Chemistry** | Lithium-ion (NMC, NCA); some LFP |
| **Cell Type** | 18650 or 21700 in welded packs (typically 10S4P to 13S5P configurations) |
| **Nominal Voltage** | 36V or 48V (e-bikes); 24V–52V (e-scooters) |
| **Capacity** | 7–15 Ah at pack voltage |
| **Failure Modes** | Cell-to-cell propagation in dense packs, BMS failure, counterfeit cells (especially in budget Chinese e-bikes), mechanical damage from drops, charging with incompatible chargers |

#### Regulatory Mapping

| Carriage | Status | Citation |
|---|---|---|
| **Carry-On (whole device)** | **BANNED** | Airline policies; FAA guidance |
| **Checked Baggage (whole device)** | **BANNED** | Airline policies; FAA guidance |
| **Removed battery (≤100 Wh)** | Permitted as spare in carry-on (rare — most e-bike batteries far exceed 100 Wh) | 49 CFR 173.185(c)(1) |
| **Removed battery (101–160 Wh)** | Airline approval, max 2 (very few e-bike batteries in this range) | 49 CFR 173.185(c)(1)(iv) |
| **Removed battery (>160 Wh)** | **PROHIBITED** — the vast majority of e-bike/scooter batteries | 49 CFR 173.185(c)(1) |
| **Cargo** | Freight aircraft only under full hazmat procedures | 49 CFR 173.185; PI 965 Section I |

#### Why This Is Tier 1

Although whole devices are banned, the risk remains **high** because:

1. **Passengers attempt to carry batteries.** Travelers who rent/buy e-bikes abroad sometimes try to fly home with the battery as a "spare."
2. **Batteries are large and energy-dense.** A single e-bike battery has more energy than 5–7 power banks combined.
3. **Home fires are increasing.** FDNY reported 268 e-bike/scooter battery fires in NYC in 2023 alone. The same batteries that cause building fires also appear at airports.
4. **Aftermarket/counterfeit batteries** with mislabeled Wh ratings are common.

#### Leading Indicators — Current Status

| Indicator | Status | Detail |
|---|---|---|
| **A: Demand** | MODERATE | E-bike sales in US ~1.1M units/year and growing. E-scooter sharing programs expanding. |
| **B: Price** | MODERATE | Entry-level e-bikes now under $500. Battery packs from AliExpress available for $50–150. |
| **C: Energy** | MODERATE | Average Wh stable but maximum increasing (some e-bikes now 1,000+ Wh). |
| **D: Size** | LOW | Battery packs are large and detectable. |
| **E: Import** | MODERATE | China produces >90% of e-bike batteries. |

---

### 4.4 Drones / UAVs

**Overall Posture: ORANGE**

#### Battery Specifications

| Spec | Detail |
|---|---|
| **Wh Range** | 20–100 Wh (consumer); 100–500+ Wh (professional/commercial) |
| **Chemistry** | Lithium Polymer (LiPo) — higher energy density than standard Li-ion, but more volatile |
| **Cell Type** | Pouch cells in multi-cell packs (2S–6S configurations) |
| **Nominal Voltage** | 7.4V (2S) to 22.2V (6S) |
| **Capacity** | 2,000–10,000 mAh |
| **Failure Modes** | LiPo puncture (soft pouch cells), overcharging, swelling from age/heat, high discharge stress, crash damage |

#### Regulatory Mapping

| Carriage | Status | Citation |
|---|---|---|
| **Carry-On (drone with battery ≤100 Wh)** | **PERMITTED** | 49 CFR 173.185(c)(1) |
| **Carry-On (spare LiPo ≤100 Wh)** | PERMITTED with terminal protection | 49 CFR 173.185(c)(1) |
| **Carry-On (101–160 Wh battery)** | PERMITTED with airline approval, max 2 | 49 CFR 173.185(c)(1)(iv) |
| **Checked Baggage (drone in device)** | PERMITTED (battery must be off/disconnected) | 49 CFR 173.185(c)(1) |
| **Checked Baggage (spare LiPo)** | **PROHIBITED** | 49 CFR 173.185(c)(1) |
| **Cargo** | PI 966/967 | 49 CFR 173.185 |

#### Special Concern: Multiple Spare Batteries

Drone operators routinely carry **3–6 spare batteries** for a single flight outing. A photographer traveling with a DJI Mavic 3 might carry:

- 1 battery in drone: 77 Wh
- 4 spare batteries: 4 × 77 Wh = 308 Wh spare
- **Total: 385 Wh of lithium in carry-on**

While technically compliant (each battery is under 100 Wh), the **aggregate energy** in a single carry-on bag is substantial.

#### Leading Indicators — Current Status

| Indicator | Status | Detail |
|---|---|---|
| **A: Demand** | MODERATE | Consumer drone market growing ~10% CAGR. DJI dominates ~75% market share. |
| **B: Price** | MODERATE | Entry-level drones now under $200. Budget brands (Holy Stone, Potensic) use lower-quality LiPo. |
| **C: Energy** | **HIGH** | Professional drones pushing into 150–200 Wh per battery. DJI Inspire 3 battery: 131 Wh. |
| **D: Size** | MODERATE | Mini drones (DJI Mini 4, <250g) have small batteries but users carry many spares. |
| **E: Import** | MODERATE | Virtually all consumer drones manufactured in China. |

---

## Tier 2 — MEDIUM-HIGH RISK

### 4.5 Wireless Earbuds

**Overall Posture: YELLOW**

#### Battery Specifications

| Spec | Detail |
|---|---|
| **Wh Range** | 0.1–0.5 Wh (per earbud); 2–8 Wh (charging case) |
| **Chemistry** | Lithium-ion (LCO) or Lithium Polymer |
| **Cell Type** | Tiny pouch or button cells |
| **Nominal Voltage** | 3.7V |
| **Capacity** | 30–80 mAh (per earbud); 500–2,000 mAh (case) |
| **Failure Modes** | Manufacturing defects in ultra-cheap units, swelling from heat exposure, counterfeit cells with no protection circuit |

#### Regulatory Mapping

| Carriage | Status | Citation |
|---|---|---|
| **Carry-On** | **PERMITTED** (installed in device / case) | 49 CFR 173.185(c)(1) |
| **Checked Baggage** | **PERMITTED** (installed in device / case) | 49 CFR 173.185(c)(1) |
| **Cargo** | PI 967 (in equipment) | IATA DGR |

#### Why They're on This List

- **Volume:** Estimated 300+ million units sold globally in 2025. Nearly every air passenger carries a pair.
- **Knockoff prevalence:** Temu, Shein, and AliExpress sell wireless earbuds for $2–5. These frequently lack proper BMS (Battery Management System) protection circuits.
- **Incident profile:** 3% of FAA incidents — small percentage, but absolute numbers rising as volume explodes.
- **Individual event consequence is low** (tiny batteries), but the sheer volume creates statistical certainty of events.

#### Leading Indicators — Current Status

| Indicator | Status | Detail |
|---|---|---|
| **A: Demand** | **HIGH** | Market growing 15%+ annually. Every demographic segment adopting. |
| **B: Price** | **HIGH** | AirPods clones available for $3–5. Race to the bottom on price. |
| **C: Energy** | LOW | Battery size constrained by ear fit. No significant Wh increase expected. |
| **D: Size** | LOW | Already at physical minimum. |
| **E: Import** | **HIGH** | China produces >99% of budget earbuds. Massive volume of direct-to-consumer e-commerce. |

---

### 4.6 Bluetooth Speakers

**Overall Posture: YELLOW**

#### Battery Specifications

| Spec | Detail |
|---|---|
| **Wh Range** | 5–80 Wh (compact: 5–20 Wh; party speakers: 40–80 Wh) |
| **Chemistry** | Lithium-ion (NMC, LFP in some JBL/Sony models) |
| **Cell Type** | 18650 (most common), pouch cells (compact models) |
| **Nominal Voltage** | 3.7V (single cell) to 14.8V (multi-cell party speakers) |
| **Capacity** | 1,500–6,000 mAh per cell |
| **Failure Modes** | Physical damage (dropped/crushed in luggage), cheap BMS in budget models, no thermal cutoff in ultra-cheap units |

#### Regulatory Mapping

| Carriage | Status | Citation |
|---|---|---|
| **Carry-On (≤100 Wh)** | **PERMITTED** | 49 CFR 173.185(c)(1) |
| **Checked Baggage (in device)** | **PERMITTED** (must be off) | 49 CFR 173.185(c)(1) |
| **Spare batteries** | Same rules as other spare batteries | 49 CFR 173.185(c)(1) |

#### Key Risk: The $10–50 Price Segment

The highest risk is concentrated in ultra-cheap speakers sold on Amazon, Temu, and dollar stores. These products:

- Use salvaged or B-grade 18650 cells
- Lack adequate BMS protection (no over-discharge cutoff, no thermal protection)
- Are often packed in checked luggage (robust-looking exterior, assumed safe)
- May use counterfeit cells that overstate capacity

Premium brands (JBL, Bose, Sony) have robust battery management and are lower risk.

#### Leading Indicators — Current Status

| Indicator | Status | Detail |
|---|---|---|
| **A: Demand** | MODERATE | Mature market, steady growth. Party speaker segment growing. |
| **B: Price** | **HIGH** | Massive price compression. Amazon flooded with $8–15 Bluetooth speakers. |
| **C: Energy** | LOW | Wh range stable for most categories. |
| **D: Size** | LOW | Compact speakers trending smaller but Wh follows. |
| **E: Import** | **HIGH** | Shenzhen production dominates. Ultra-cheap units shipped directly to consumers. |

---

### 4.7 Portable Gaming Devices

**Overall Posture: YELLOW**

#### Battery Specifications

| Spec | Detail |
|---|---|
| **Wh Range** | 16–50 Wh |
| **Chemistry** | Lithium-ion (NMC) |
| **Cell Type** | Pouch cells (custom form factors) |
| **Nominal Voltage** | 3.7V–7.4V |
| **Capacity** | 4,310 mAh (Nintendo Switch) to 12,000+ mAh (Valve Steam Deck) |
| **Failure Modes** | Swollen batteries from age/heat, third-party charger damage, aftermarket battery replacement |

#### Key Products and Wh Ratings

| Device | Wh | Regulatory Status |
|---|---|---|
| Nintendo Switch | ~16 Wh | Well under threshold |
| Nintendo Switch OLED | ~16.5 Wh | Well under threshold |
| Valve Steam Deck | ~40 Wh | Under threshold, but note trend |
| ASUS ROG Ally | ~40 Wh | Under threshold |
| Lenovo Legion Go | ~49.2 Wh | Approaching mid-range |
| Steam Deck successor (expected 2026) | ~50–60 Wh (projected) | **Trending toward upper range** |

#### Regulatory Mapping

| Carriage | Status | Citation |
|---|---|---|
| **Carry-On** | **PERMITTED** (all current devices ≤100 Wh) | 49 CFR 173.185(c)(1) |
| **Checked Baggage** | **PERMITTED** (in device, off) | 49 CFR 173.185(c)(1) |

#### Why They're Worth Monitoring

The portable gaming category is on an **energy density escalation trajectory**. Each generation of devices adds battery capacity to support larger screens and more powerful processors. If the next generation crosses 100 Wh (plausible within 2–3 product cycles), airline approval requirements would apply — but passengers are unlikely to know or comply.

#### Leading Indicators — Current Status

| Indicator | Status | Detail |
|---|---|---|
| **A: Demand** | MODERATE | Steam Deck sold ~5M units. ROG Ally and competitors expanding market. |
| **B: Price** | LOW | Premium products, prices stable. |
| **C: Energy** | MODERATE | Wh per generation increasing. Watch for 100 Wh threshold crossing. |
| **D: Size** | LOW | Form factor constrained by ergonomics. |
| **E: Import** | LOW | Established brands, controlled supply chains. |

---

### 4.8 Cordless Hair Styling Tools

**Overall Posture: ORANGE**

#### Battery Specifications

| Spec | Detail |
|---|---|
| **Wh Range** | 15–130+ Wh |
| **Chemistry** | Lithium-ion (NMC, NCA) |
| **Cell Type** | 18650 or 21700 in multi-cell packs |
| **Nominal Voltage** | 7.4V–14.8V (2S to 4S configurations) |
| **Capacity** | 2,000–5,000 mAh per cell |
| **Failure Modes** | Overheating during use (hair tools generate heat by design), charging with wrong adapter, no thermal management in budget models |

#### Key Products and Wh Ratings

| Product | Wh | Regulatory Status |
|---|---|---|
| Budget cordless straightener (Amazon) | 15–30 Wh | Well under threshold |
| Dyson Corrale | ~48 Wh | Under threshold |
| Dyson Airwrap (cordless, expected 2026) | ~60–80 Wh (projected) | Under threshold but approaching |
| High-end cordless curler (salon grade) | 80–130 Wh | **May exceed 100 Wh — airline approval required or prohibited** |
| Budget cordless hair dryer (AliExpress) | 90–120 Wh | **Often unlabeled — passengers unaware of Wh rating** |

#### Regulatory Mapping

| Carriage | Status | Citation |
|---|---|---|
| **Carry-On (≤100 Wh)** | **PERMITTED** | 49 CFR 173.185(c)(1) |
| **Carry-On (101–160 Wh)** | PERMITTED with airline approval | 49 CFR 173.185(c)(1)(iv) |
| **Checked Baggage (in device)** | PERMITTED if ≤100 Wh or ≤160 Wh with approval | 49 CFR 173.185(c)(1) |
| **Checked Baggage (>160 Wh)** | **PROHIBITED** | 49 CFR 173.185(c)(1) |

#### Why This Category is Escalating

1. **Rapid growth:** Cordless hair tools are one of the fastest-growing consumer electronics categories, driven by social media (#HairTok).
2. **Poor labeling:** Many products, especially from Chinese manufacturers, do not display Wh rating. Passengers have no way to determine compliance.
3. **Heat + lithium:** These devices generate heat by design. Combined with lithium batteries, the thermal management challenge is inherently elevated.
4. **Gender-specific awareness gap:** Marketing targets female travelers who may be less likely to check battery regulations for beauty products.

#### Leading Indicators — Current Status

| Indicator | Status | Detail |
|---|---|---|
| **A: Demand** | **HIGH** | Explosive growth. TikTok/Instagram driving adoption. |
| **B: Price** | MODERATE | Premium brands ($200–500) coexist with $20–50 knockoffs. |
| **C: Energy** | **HIGH** | Products actively crossing 100 Wh threshold. New cordless dryers may reach 150+ Wh. |
| **D: Size** | MODERATE | Getting smaller while maintaining capacity. |
| **E: Import** | MODERATE | China-based brands growing rapidly. |

---

## Tier 3 — MEDIUM RISK

### 4.9 Portable Fans / Personal Climate Devices

**Overall Posture: YELLOW**

#### Battery Specifications

| Spec | Detail |
|---|---|
| **Wh Range** | 5–40 Wh (handheld fans); 20–80 Wh (neck fans, desk fans) |
| **Chemistry** | Lithium-ion (NMC), some LiPo |
| **Cell Type** | 18650, pouch cells |
| **Nominal Voltage** | 3.7V–7.4V |
| **Capacity** | 1,500–6,000 mAh |
| **Failure Modes** | Cheap BMS, physical damage, no thermal cutoff in ultra-cheap units |

#### Regulatory Mapping

| Carriage | Status | Citation |
|---|---|---|
| **Carry-On (≤100 Wh)** | **PERMITTED** | 49 CFR 173.185(c)(1) |
| **Checked Baggage (in device)** | **PERMITTED** (must be off) | 49 CFR 173.185(c)(1) |
| **Spare batteries** | Same as other spare batteries | 49 CFR 173.185(c)(1) |

#### Key Risk Factors

- **Seasonal surge:** Massive demand spike June–August, exactly aligning with peak travel season.
- **Ultra-cheap market:** $3–8 portable fans from Temu/AliExpress with minimal quality control.
- **Neck fans:** Worn around the neck, placing the battery next to skin — any thermal event is an immediate burn injury.
- **Relatively new category** — passengers may not think to check battery rules for a "fan."

#### Leading Indicators — Current Status

| Indicator | Status | Detail |
|---|---|---|
| **A: Demand** | MODERATE | Seasonal. Peak during summer months. |
| **B: Price** | **HIGH** | Ultra-cheap units flooding the market. |
| **C: Energy** | LOW | Wh remains low for most handheld models. |
| **D: Size** | MODERATE | Wearable form factors (neck fans) are new and growing. |
| **E: Import** | **HIGH** | China produces virtually all portable fans. Massive e-commerce direct-ship volume. |

---

### 4.10 Heated Clothing / Wearables

**Overall Posture: YELLOW**

#### Battery Specifications

| Spec | Detail |
|---|---|
| **Wh Range** | 15–80 Wh (heated vests/jackets); 5–20 Wh (heated gloves/socks) |
| **Chemistry** | Lithium-ion (NMC) |
| **Cell Type** | 18650, 21700 |
| **Nominal Voltage** | 7.4V (most common — 2S configuration) |
| **Capacity** | 2,000–5,000 mAh per cell |
| **Failure Modes** | Unlabeled Wh (most common concern), moisture ingress during use, physical damage from bending/washing, cheap BMS |

#### Regulatory Mapping

| Carriage | Status | Citation |
|---|---|---|
| **Carry-On (≤100 Wh)** | **PERMITTED** (battery in device, device off) | 49 CFR 173.185(c)(1) |
| **Checked Baggage (in device)** | **PERMITTED** (must be off) | 49 CFR 173.185(c)(1) |
| **Spare battery packs** | **PROHIBITED** in checked; carry-on with terminal protection | 49 CFR 173.185(c)(1) |

#### Key Concern: Missing Wh Labels

The primary risk with heated clothing is **the absence of Wh labels.** Many heated jackets and vests:

- Display only mAh, not Wh, on the battery pack
- Display neither mAh nor Wh
- Use proprietary battery form factors that are difficult to identify
- Are marketed as "clothing" — passengers don't think of them as electronic devices carrying lithium batteries

This creates a compliance awareness gap: passengers cannot determine if their heated jacket battery exceeds regulatory thresholds, and TSA officers may not identify heated clothing batteries during screening.

#### Leading Indicators — Current Status

| Indicator | Status | Detail |
|---|---|---|
| **A: Demand** | MODERATE | Growing category, especially for outdoor workers and winter travelers. |
| **B: Price** | MODERATE | Heated vests now available for $30–60. Quality variance significant. |
| **C: Energy** | LOW | Most products ≤60 Wh. Watch for extended-runtime models. |
| **D: Size** | LOW | Battery packs are visible and removable in most designs. |
| **E: Import** | MODERATE | China-based brands dominating the market. |

---

### 4.11 Portable Projectors

**Overall Posture: YELLOW**

#### Battery Specifications

| Spec | Detail |
|---|---|
| **Wh Range** | 30–80 Wh |
| **Chemistry** | Lithium-ion (NMC) |
| **Cell Type** | 18650 or pouch cells |
| **Nominal Voltage** | 7.4V–14.8V |
| **Capacity** | 4,000–12,000 mAh |
| **Failure Modes** | Heat accumulation (projectors run hot), swollen batteries from repeated thermal cycling |

#### Regulatory Mapping

| Carriage | Status | Citation |
|---|---|---|
| **Carry-On (≤100 Wh)** | **PERMITTED** | 49 CFR 173.185(c)(1) |
| **Checked Baggage (in device)** | **PERMITTED** (must be off) | 49 CFR 173.185(c)(1) |

#### Leading Indicators — Current Status

| Indicator | Status | Detail |
|---|---|---|
| **A: Demand** | LOW | Niche market. Business travelers and presentation use. |
| **B: Price** | MODERATE | Budget models from $80–150 on Amazon. |
| **C: Energy** | MODERATE | Higher-brightness models approaching 100 Wh as LED technology demands more power. |
| **D: Size** | MODERATE | "Pico" projectors getting smaller while maintaining battery size. |
| **E: Import** | MODERATE | Primarily Chinese-manufactured. |

---

### 4.12 Smart Luggage

**Overall Posture: GREEN**

#### Battery Specifications

| Spec | Detail |
|---|---|
| **Wh Range** | 20–70 Wh (typically) |
| **Chemistry** | Lithium-ion (NMC) |
| **Cell Type** | 18650 or pouch cells |
| **Nominal Voltage** | 3.7V–7.4V |
| **Capacity** | 5,000–20,000 mAh |
| **Failure Modes** | Physical damage from baggage handling, charging port damage |

#### Regulatory Mapping

| Carriage | Status | Citation |
|---|---|---|
| **Carry-On (battery installed, ≤100 Wh)** | **PERMITTED** | 49 CFR 173.185(c)(1); airline policies |
| **Checked Baggage** | **PERMITTED only if battery is removable and removed** | All major US airlines require removable battery since 2018 |
| **Non-removable battery smart luggage** | **BANNED from checked baggage** by all major US carriers | Airline policies (Delta, American, United, Southwest, JetBlue, Alaska) |

#### Why GREEN

Smart luggage is actually a **success story** for proactive risk management:

- **2017–2018:** Airlines imposed removable battery requirement after incidents
- **Industry responded:** Manufacturers redesigned products with removable battery modules
- **Compliance is visible:** TSA and gate agents can verify battery removal
- **Market self-corrected:** Non-removable battery smart luggage largely disappeared from the market

This category demonstrates what effective regulatory/industry coordination can achieve.

#### Leading Indicators — Current Status

| Indicator | Status | Detail |
|---|---|---|
| **A: Demand** | LOW | Mature market, slow growth. |
| **B: Price** | MODERATE | Competition has lowered prices. |
| **C: Energy** | LOW | Wh stable, no escalation trend. |
| **D: Size** | LOW | Batteries are visible and removable by design. |
| **E: Import** | LOW | Established brands dominate. |

---

### 4.13 Cordless Power Tools

**Overall Posture: YELLOW**

#### Battery Specifications

| Spec | Detail |
|---|---|
| **Wh Range** | 36–216+ Wh |
| **Chemistry** | Lithium-ion (NMC, NCA) |
| **Cell Type** | 18650, 21700 (multi-cell packs: 5S2P to 5S6P) |
| **Nominal Voltage** | 18V or 20V max (consumer); 36V / 40V max (professional) |
| **Capacity** | 2.0–12.0 Ah (as marketed) |
| **Failure Modes** | Impact damage (job site use), high discharge stress, cell imbalance in older packs, mixing batteries from different brands/generations |

#### Key Products and Wh Ratings

| Battery | Wh | Regulatory Status |
|---|---|---|
| DeWalt 20V MAX 2.0 Ah | ~36 Wh | Under threshold |
| Milwaukee M18 5.0 Ah | ~90 Wh | Under threshold |
| DeWalt 20V MAX 5.0 Ah | ~100 Wh | **At threshold** |
| DeWalt FLEXVOLT 6.0 Ah (60V) | ~216 Wh | **PROHIBITED — exceeds 160 Wh** |
| Milwaukee MX FUEL | ~216 Wh | **PROHIBITED — exceeds 160 Wh** |
| Makita 40V XGT 4.0 Ah | ~144 Wh | Requires airline approval, max 2 |

#### Regulatory Mapping

| Carriage | Status | Citation |
|---|---|---|
| **Carry-On (≤100 Wh)** | **PERMITTED** (battery protected) | 49 CFR 173.185(c)(1) |
| **Carry-On (101–160 Wh)** | PERMITTED with airline approval, max 2 | 49 CFR 173.185(c)(1)(iv) |
| **Carry-On (>160 Wh)** | **PROHIBITED** | 49 CFR 173.185(c)(1) |
| **Checked Baggage (in tool)** | PERMITTED (≤160 Wh, tool off) | 49 CFR 173.185(c)(1) |
| **Checked Baggage (spare)** | **PROHIBITED** | 49 CFR 173.185(c)(1) |

#### Key Risk: Tradespeople Traveling for Work

Electricians, plumbers, and construction workers who fly to job sites regularly carry tool batteries. Many **FLEXVOLT and MX FUEL batteries exceed 160 Wh** and are prohibited from passenger aircraft entirely — but tradespeople often don't know this.

#### Leading Indicators — Current Status

| Indicator | Status | Detail |
|---|---|---|
| **A: Demand** | MODERATE | Mature market, cordless adoption still growing (replacing corded tools). |
| **B: Price** | LOW | Premium brands dominate. Prices stable. |
| **C: Energy** | **HIGH** | Active escalation. Each generation increases Wh. 20V → 40V → 60V → 80V platforms. More products exceeding 160 Wh. |
| **D: Size** | LOW | Battery packs are clearly identifiable. |
| **E: Import** | MODERATE | Major brands have quality control, but aftermarket/compatible batteries from China are growing. |

---

### 4.14 Mobility Devices

**Overall Posture: GREEN**

#### Battery Specifications

| Spec | Detail |
|---|---|
| **Wh Range** | 150–500+ Wh (powered wheelchairs); 70–200 Wh (scooters) |
| **Chemistry** | Lithium-ion (LFP increasingly common), lead-acid (legacy) |
| **Cell Type** | 18650/21700 in large packs, or prismatic LFP cells |
| **Nominal Voltage** | 24V–48V |
| **Capacity** | 10–25 Ah at pack voltage |
| **Failure Modes** | Physical damage during airline handling (primary concern), connector damage, BMS failure |

#### Separate Regulatory Treatment — 14 CFR 382

Mobility devices receive **special regulatory treatment** under the Air Carrier Access Act and its implementing regulations at **14 CFR Part 382**:

| Rule | Detail | Citation |
|---|---|---|
| **Airlines must accept** | Cannot refuse a mobility device solely because it has a lithium battery | 14 CFR 382.133 |
| **Spillable batteries** | Must be stored upright; terminals protected | 14 CFR 382.133(c) |
| **Non-spillable batteries** | No orientation requirement | 14 CFR 382.133(d) |
| **Lithium-ion ≤300 Wh** | Battery may remain installed in device; device stowed in cargo | 14 CFR 382.133(e) |
| **Lithium-ion >300 Wh** | Battery must be removed and carried in cabin; max 1 spare | 14 CFR 382.133(e)(2) |
| **Lithium-ion max per battery** | 300 Wh per battery (ICAO/IATA standard); airlines may accept higher with approval | IATA DGR |
| **Spare batteries** | 1 spare permitted, ≤300 Wh, carried in cabin | 14 CFR 382.133(e)(3) |

#### Why GREEN

- **Strong regulatory framework.** 14 CFR 382 provides specific, clear rules.
- **High compliance.** Mobility device users and airlines are aware of the requirements.
- **Airline handling procedures.** Dedicated SOPs for loading, stowing, and connecting/disconnecting batteries.
- **Lower incident rate.** Well-established handling procedures reduce risk.
- **Disability rights protection.** Any attempt to further restrict could conflict with the Air Carrier Access Act.

#### Leading Indicators — Current Status

| Indicator | Status | Detail |
|---|---|---|
| **A: Demand** | LOW | Stable, aging population driving gradual growth. |
| **B: Price** | LOW | Medical device pricing, not consumer electronics dynamics. |
| **C: Energy** | MODERATE | Battery capacity increasing for range, but within established regulatory framework. |
| **D: Size** | LOW | Form factor dictated by device function. |
| **E: Import** | LOW | Regulated medical device supply chains. |

---

# Section 5: Watch List — Emerging Products

These products are not yet causing aviation incidents but show trajectory signals that warrant monitoring. Each entry includes an escalation trigger that would move the product to the main Risk Registry.

---

### 5.1 Solid-State Batteries

| Field | Detail |
|---|---|
| **What it is** | Next-generation battery technology replacing liquid electrolyte with solid electrolyte. Samsung SDI, Toyota, QuantumScape, and Solid Power targeting 2026–2028 commercialization. |
| **Why we're watching** | Different failure mode profile than current lithium-ion. While theoretically safer (no flammable liquid electrolyte), solid-state batteries can still experience thermal events. Current testing protocols (UN 38.3) were designed for liquid-electrolyte cells — may not adequately characterize solid-state failure modes. |
| **Battery specs** | Expected 400–500 Wh/kg (vs. 250–300 for current Li-ion). Higher energy density means more energy per unit weight. Lithium-metal anodes common in solid-state designs. |
| **Regulatory status** | Classified under existing lithium battery rules (49 CFR 173.185) unless PHMSA issues specific guidance. UN 38.3 testing applies. |
| **Escalation trigger** | First consumer product with solid-state battery enters market AND current UN 38.3 testing does not fully characterize its failure modes. |
| **Next review** | Q3 2026 — aligned with Samsung SDI announced production timeline |

---

### 5.2 AI Wearables

| Field | Detail |
|---|---|
| **What it is** | AI-powered wearable devices: Meta Orion AR glasses (expected 2027), successors to Humane AI Pin (discontinued 2025), AI-enhanced smartwatches, and camera-equipped wearables. |
| **Why we're watching** | These devices require always-on AI processing, demanding larger batteries in small form factors. The combination of heat generation (AI inference), compact size, and user proximity to body creates thermal risk. Market trajectory suggests rapid adoption among tech-forward travelers. |
| **Battery specs** | Current: 1–5 Wh (smartwatch-class). Expected: 10–30 Wh (AR glasses with onboard compute). Chemistry: LiPo pouch cells. |
| **Regulatory status** | Well within current thresholds. Carry-on and checked permitted. |
| **Escalation trigger** | Any AI wearable exceeds 20 Wh AND achieves >1M unit sales. Volume + energy = risk. |
| **Next review** | Q1 2027 — aligned with Meta Orion anticipated launch |

---

### 5.3 Sodium-Ion Battery Products

| Field | Detail |
|---|---|
| **What it is** | Batteries using sodium ions instead of lithium ions as the charge carrier. CATL, HiNa, and Faradion (Reliance subsidiary) producing commercial sodium-ion cells. First consumer products (e-bikes, power tools) appearing in 2025–2026. |
| **Why we're watching** | **REGULATORY GAP.** Sodium-ion batteries are **not classified under lithium battery rules** (49 CFR 173.185). The regulation specifically applies to "lithium" batteries. Sodium-ion has no specific UN number, no packing instructions, and no Wh thresholds for air transport. This gap could allow unrestricted carriage of high-energy sodium-ion products. |
| **Battery specs** | Current: 100–160 Wh/kg (lower than lithium-ion). Nominal voltage: ~3.1V. Chemistry: Prussian blue analogue or layered oxide cathode, hard carbon anode. Failure mode: can experience thermal runaway, though generally at higher temperatures than lithium-ion. |
| **Regulatory status** | **UNREGULATED for air transport.** No specific CFR provision, no IATA packing instruction, no UN number assignment. Products would fall under general "miscellaneous dangerous goods" or may not be regulated at all. |
| **Escalation trigger** | Consumer sodium-ion product exceeds 100 Wh AND is marketed for travel use. |
| **Next review** | Q2 2026 — monitor PHMSA rulemaking docket |

---

### 5.4 High-Capacity Portable Power Stations

| Field | Detail |
|---|---|
| **What it is** | Large lithium battery packs marketed for camping, RV, emergency backup, and remote work. Brands: Jackery, EcoFlow, Bluetti, Anker, Goal Zero. Capacities range from 256 Wh to 6,000+ Wh. |
| **Why we're watching** | These products are **already prohibited** from passenger aircraft (exceed 160 Wh by a wide margin), but are increasingly marketed as "travel essentials" and "van life" gear. Social media glamorizes taking them everywhere. Passengers may attempt to carry them, and some smaller units (256–500 Wh) may not be obviously different from large power banks to TSA officers. |
| **Battery specs** | 256–6,144 Wh. Chemistry: LFP (most current models), NMC (older models). Cell type: prismatic LFP or 21700. Voltage: 12V–48V internal. |
| **Regulatory status** | **PROHIBITED from passenger aircraft** (carry-on and checked). Must ship as cargo under PI 965 Section I (fully regulated hazmat). |
| **Escalation trigger** | Any product ≤300 Wh marketed with airline-compatible labeling, or TSA intercepts increase >50% YoY. |
| **Next review** | Q3 2026 |

---

### 5.5 E-Foils / Hydrofoil Boards

| Field | Detail |
|---|---|
| **What it is** | Electric-powered hydrofoil surfboards. Brands: Lift Foils, Fliteboard, Waydoo. Popular with affluent coastal travelers. |
| **Why we're watching** | Batteries are **2,000–3,500 Wh** — larger than most e-bike batteries. Targeted at wealthy travelers who fly frequently between coastal destinations. Users may attempt to ship batteries via air cargo or check them as "sporting equipment." The batteries use high-discharge LiPo cells with elevated thermal runaway risk. |
| **Battery specs** | 2,000–3,500 Wh. Chemistry: LiPo or NMC. Cell type: pouch cells in large packs. Voltage: 48V–60V. |
| **Regulatory status** | **PROHIBITED from passenger aircraft.** Cargo-only under full hazmat (PI 965 Section I). |
| **Escalation trigger** | US e-foil sales exceed 50,000 units AND airlines report attempted check-ins with e-foil batteries. |
| **Next review** | Q4 2026 |

---

### 5.6 Heated Medical Device Bags

| Field | Detail |
|---|---|
| **What it is** | Battery-heated bags for transporting temperature-sensitive medications (insulin, biologics, vaccines). Used by clinical travelers, pharmaceutical reps, and patients on therapy. |
| **Why we're watching** | These products occupy an **unclear regulatory space.** They are medical devices (potentially exempt from some restrictions) but also contain lithium batteries (subject to 49 CFR 173.185). The exemption status for "medical devices necessary for a passenger's condition" is not clearly defined for heated transport bags as it is for mobility aids. |
| **Battery specs** | 20–60 Wh. Chemistry: Lithium-ion (NMC). Cell type: 18650 or pouch. Some models have dual battery packs for extended cooling/heating. |
| **Regulatory status** | Likely permitted under spare battery rules if ≤100 Wh. No specific exemption or guidance for battery-heated medical transport bags. |
| **Escalation trigger** | Passenger denied boarding due to heated medical bag AND no FAA/DOT guidance exists for the product category. |
| **Next review** | Q2 2026 |

---

### 5.7 Smart Rings

| Field | Detail |
|---|---|
| **What it is** | Wearable health/fitness tracking rings. Products: Oura Ring (Gen 3/4), Samsung Galaxy Ring, Ultrahuman Ring Air, RingConn. |
| **Why we're watching** | Fastest-growing wearable category. Projected 30M+ units by 2028. While individual battery risk is negligible (tiny cells), the **complete absence of Wh labeling** on these products — and the fact that many passengers may not even think of them as "electronic devices" — creates an awareness gap. If smart ring batteries are ever involved in a cabin event (however minor), the lack of passenger awareness could amplify public concern. |
| **Battery specs** | 0.015–0.05 Wh. Chemistry: Lithium-ion or Lithium Polymer. Cell type: Ultra-miniature pouch or button cell. Capacity: 5–15 mAh. |
| **Regulatory status** | Fully permitted everywhere. Well below any threshold. |
| **Escalation trigger** | Smart ring battery chemistry changes to higher-energy-density formulation, OR form factor increases significantly (e.g., "smart bracelet" with 5+ Wh). |
| **Next review** | Q4 2026 |

---

# Section 6: Signal Analysis (Market Intelligence)

## 6.1 Amazon Market Intelligence

Amazon Best Sellers Rank (BSR), Average Selling Price (ASP), and review volume serve as proxy indicators for what products are surging into travelers' hands.

### Category Dashboard — February 2026

| Category | BSR Trend (90d) | ASP | ASP Trend (12mo) | Review Volume (90d) | Signal |
|---|---|---|---|---|---|
| **Portable Power Banks** | Improving (+25%) | $18.50 | **-28%** | 12,400+ new reviews | **HIGH** — Price collapse + demand surge |
| **Wireless Earbuds** | Improving (+18%) | $12.20 | **-35%** | 28,000+ new reviews | **HIGH** — Race to the bottom |
| **Portable Fans (Neck/Handheld)** | Improving (+40%) | $9.80 | **-22%** | 8,200+ new reviews | **HIGH** (seasonal — approaching peak) |
| **Bluetooth Speakers** | Stable | $24.50 | -12% | 6,800+ new reviews | MODERATE |
| **Cordless Hair Tools** | **Improving (+55%)** | $35.00 | -15% | 5,100+ new reviews | **HIGH** — Fastest-growing category |
| **Portable Projectors** | Stable | $85.00 | -8% | 2,100+ new reviews | LOW |
| **Heated Clothing** | Seasonal (declining post-winter) | $42.00 | -10% | 3,400+ new reviews | MODERATE |
| **Drone Batteries (spare)** | Improving (+12%) | $28.00 | -5% | 1,800+ new reviews | MODERATE |

### Key Observation

**ASP decline is the clearest leading indicator.** When average selling price drops by >20%, it signals that low-cost manufacturers are flooding the market — bringing lower quality control, cheaper components, and less reliable battery management systems. The power bank and wireless earbud categories show the strongest price collapse signals.

## 6.2 Social Media Signal Tracking

### Reddit Monitoring

| Subreddit | Relevance | Activity Trend | Signal |
|---|---|---|---|
| r/vaping (1.2M members) | Device recommendations, battery safety discussions, new product hype | **Rising** — 15% more posts in 90d | HIGH |
| r/ebikes (280K members) | Battery range, charging, travel questions (often "can I fly with this?") | Stable | MODERATE |
| r/drones (450K members) | Battery recommendations, spare battery packing, airline stories | Stable | MODERATE |
| r/electronic_cigarette (350K members) | Mods, 18650 cell discussions, DIY builds | **Declining** (shifting to r/vaping) | LOW |
| r/flashlight (320K members) | High-drain 18650/21700 cells, battery safety, travel carry questions | Stable | LOW |
| r/UsbCHardware (50K members) | GaN chargers, high-wattage power banks, USB-PD devices | **Rising** — 30% more posts | MODERATE |
| r/onebag (600K members) | Travel gear optimization — power banks, adapters, what's allowed | Stable | **Sentinel** (early indicator of travel-with-battery questions) |

### TikTok / Short-Form Video

| Trend | Relevance | Signal |
|---|---|---|
| **#TikTokMadeMeBuyIt** (electronics) | Drives impulse purchases of cheap battery devices — neck fans, earbuds, power banks | **HIGH** — Viral products bypass traditional retail quality filters |
| **#TravelEssentials** | Power banks, portable fans, heated clothing featured in packing videos | MODERATE — normalizes carrying multiple battery devices |
| **#HairTok** (cordless tools) | Dyson dupes, cordless straighteners, travel-size curlers | **HIGH** — Driving demand for high-Wh hair tools |
| **TikTok Shop** | Direct purchase of ultra-cheap electronics from Chinese sellers | **HIGH** — No quality gatekeeping between factory and consumer |

### CPSC Recall Monitoring (Regulatory Lag Indicator)

CPSC product recalls are a **lagging indicator** (problems have already occurred), but the **time between first incident and recall** reveals enforcement lag:

| Product | Recall Date | First Known Incident | Lag |
|---|---|---|---|
| iHome portable charger | 2024 | 2022 | ~2 years |
| Various hoverboards (multiple brands) | 2016–2017 | 2015 | 1–2 years |
| HP laptop batteries (multiple models) | 2018–2023 (rolling) | Varies | 6–18 months |
| Amazon Basics portable chargers | 2023 | 2021 | ~2 years |

**Implication:** When a product category shows fire reports on Reddit/social media or in CPSC complaint databases, the formal recall is typically **12–24 months behind.** For airline safety purposes, social media fire reports are a more timely signal than CPSC recalls.

## 6.3 Price Intelligence — Price Collapse Tracker

The "Price Collapse Tracker" monitors when products cross below cost-of-quality thresholds — the price point below which it is difficult to include adequate battery management systems, quality cells, and safety certifications.

| Product Category | Cost-of-Quality Floor | Current Lowest ASP | Below Floor? | Signal |
|---|---|---|---|---|
| **Power Banks (20,000 mAh)** | $15 | $6–8 (Temu) | **YES** | **RED** — Impossible to include proper BMS at this price |
| **Wireless Earbuds** | $8 | $2–3 (Temu/Shein) | **YES** | **RED** — No protection circuit at this price |
| **Neck Fans** | $6 | $3–4 (AliExpress) | **YES** | **RED** — Minimal thermal protection |
| **Bluetooth Speakers** | $12 | $5–8 (Amazon/Temu) | **YES** | **ORANGE** — BMS quality questionable |
| **Cordless Hair Tools** | $30 | $12–20 (Amazon) | **YES** | **ORANGE** — Thermal management concern |
| **Disposable Vapes** | $5 | $3–4 (wholesale) | **YES** | **RED** — Unregulated charging circuits |
| **Drone Batteries (generic)** | $20 | $8–12 (AliExpress) | **YES** | **ORANGE** — Capacity overstatement common |

### Interpretation

When a product is sold below its cost-of-quality floor, the manufacturer has necessarily cut corners on one or more of: cell quality, battery management system, thermal protection, safety certification testing, or packaging. These products are the most likely to be involved in aviation incidents.

## 6.4 New-to-Market Product Monitor

### FCC ID Grants (Leading Indicator)

FCC equipment authorization grants precede market availability by 1–6 months. Monitoring new grants for lithium battery-powered wireless devices provides advance notice of products entering the US market.

**Recent Notable FCC Grants (Q4 2025 – Q1 2026):**

| FCC ID Grant Date | Product Type | Wh (est.) | Significance |
|---|---|---|---|
| Nov 2025 | High-capacity wireless speaker (new brand) | ~85 Wh | Approaching 100 Wh threshold |
| Dec 2025 | Cordless hair dryer (Chinese manufacturer) | ~110 Wh | **Exceeds 100 Wh** — requires airline approval |
| Jan 2026 | Portable AI compute device (startup) | ~45 Wh | New product category |
| Jan 2026 | Heated medical transport bag | ~55 Wh | New category — unclear exemption status |
| Feb 2026 | Mini portable power station | ~280 Wh | **Exceeds 160 Wh** — prohibited for passengers |

### CES 2026 Highlights (January 2026)

Notable battery-powered products announced at CES 2026 that will enter the market in 2026:

- **Multiple "all-day" cordless hair styling tools** with batteries in the 80–120 Wh range
- **Next-gen portable gaming handhelds** with 55–65 Wh batteries
- **Wearable AI devices** with onboard compute (10–25 Wh)
- **Sodium-ion power tools** from Chinese manufacturers (regulatory gap product)
- **Personal cooling vests** with integrated batteries (20–40 Wh)

### Kickstarter / Indiegogo Monitor

Crowdfunding platforms often surface products 6–12 months before market availability. Current campaigns with lithium battery risk relevance:

- Heated drone batteries for cold-weather flying (pre-heated to improve performance — adds heating element to already energy-dense battery)
- Ultra-compact 200 Wh power bank (claimed — would require airline approval if real)
- USB-C heated blanket for travel (30–50 Wh integrated battery)

### Compliance Gaming: The 99 Wh Pattern

As noted in the power bank section, a pervasive market pattern is the **deliberate engineering of products to 99–99.9 Wh** — just under the 100 Wh threshold. This pattern is now visible across multiple product categories:

| Category | Example Rating | Calculated Wh | Margin Below 100 Wh |
|---|---|---|---|
| Power Banks | 26,800 mAh @ 3.7V | 99.16 Wh | 0.84 Wh |
| Bluetooth Speakers | 26,500 mAh @ 3.7V | 98.05 Wh | 1.95 Wh |
| Cordless Hair Tools | 13,400 mAh @ 7.4V | 99.16 Wh | 0.84 Wh |
| Portable Projectors | 26,000 mAh @ 3.7V | 96.20 Wh | 3.80 Wh |

**Risk:** If actual cell capacity exceeds nominal by even 1–2% (normal manufacturing variance), these products technically cross the 100 Wh threshold. The aviation safety system currently has no mechanism to verify claimed Wh ratings at point of screening.

---

# Section 7: Cargo/Shipper Intelligence

## 7.1 E-Commerce Fulfillment Risk

The explosive growth of cross-border e-commerce platforms (Temu, Shein, AliExpress, TikTok Shop) has created a systemic risk for undeclared lithium batteries in air cargo.

### The Problem

| Issue | Detail |
|---|---|
| **Undeclared batteries** | Parcels containing lithium batteries are routinely shipped as "electronic accessories," "phone cases," or "household items" without proper hazmat declaration. |
| **Volume** | Temu alone shipped an estimated 600,000+ packages per day to the US in 2025. A significant percentage contain lithium battery-powered products. |
| **De minimis loophole** | Parcels valued under $800 enter the US with minimal customs inspection under the Section 321 de minimis exemption. Battery content is rarely verified. |
| **Fulfillment model** | Products ship directly from Chinese warehouses to US consumers via air cargo. The shipper (often a small Chinese factory) has no hazmat training or certification. |
| **PHMSA enforcement** | PHMSA opened 40% more enforcement investigations involving undeclared lithium batteries in 2025 vs. 2024. But the volume of non-compliant shipments far outpaces enforcement capacity. |

### Risk Chain

```
Chinese manufacturer → E-commerce platform listing → Air cargo (undeclared) → US consumer
```

At no point in this chain is the battery consistently:
- Tested to UN 38.3 standards
- Properly classified and declared for air transport
- Packed according to the applicable packing instruction
- Inspected by the carrier accepting the shipment

### PHMSA Enforcement Trends

| Year | Investigations (lithium battery) | Penalties Assessed | Trend |
|---|---|---|---|
| 2022 | 142 | $1.8M | Baseline |
| 2023 | 178 | $2.3M | +25% |
| 2024 | 215 | $3.1M | +21% |
| 2025 (est.) | 280+ | $4.0M+ | **+30%** |

## 7.2 State of Charge (SoC) Compliance Monitor

The **January 2026 30% SoC mandate** for cargo lithium-ion batteries (UN 3480, Section II) introduces a new compliance requirement that affects the entire supply chain.

### Compliance Challenges

| Challenge | Detail |
|---|---|
| **Measurement at point of shipment** | Shippers must verify SoC before offering batteries for air transport. Many small shippers lack SoC testing equipment. |
| **Temperature effects** | SoC readings vary with temperature. A battery at 30% SoC in a warm warehouse may read differently in a cold cargo hold. |
| **Self-discharge** | Lithium-ion batteries self-discharge at ~1–2% per month. Batteries tested at 30% SoC at the factory may arrive at destination at 25–28%. Measurement uncertainty creates compliance risk. |
| **Verification** | No practical method exists for carriers or inspectors to verify SoC without specialized equipment. Compliance is largely based on shipper declaration. |
| **Exemptions** | Batteries installed in equipment (PI 967/970) are exempt. This creates an incentive to ship batteries "in equipment" rather than standalone — potentially misclassifying shipments. |

### Industry Readiness Assessment

| Stakeholder | Readiness | Gap |
|---|---|---|
| **Large battery manufacturers** (Samsung SDI, LG, CATL) | HIGH | Integrated SoC management in production |
| **Electronics OEMs** (Apple, Dell, Samsung Electronics) | HIGH | Controlled supply chain |
| **E-commerce platforms** (Temu, Shein, AliExpress) | **LOW** | Small sellers lack SoC testing capability |
| **Freight forwarders** | MODERATE | Training underway, verification gap persists |
| **Airlines / cargo carriers** | MODERATE | Relying on shipper declarations; no independent verification |

## 7.3 Cargo Route Risk

### High-Risk Origin Countries

| Country | % of US Li-ion Imports | Risk Factors |
|---|---|---|
| **China** | ~75% | Largest producer; highest volume of undeclared shipments; quality variance |
| **South Korea** | ~10% | Major cell manufacturers (Samsung SDI, LG); generally compliant |
| **Japan** | ~8% | Established manufacturers (Panasonic, Murata); high compliance |
| **Vietnam** | ~4% | Growing assembly hub; compliance infrastructure developing |
| **India** | ~3% | Emerging market; regulatory framework maturing |

### Combi Aircraft Exposure

**Combi aircraft** (passenger upper deck, cargo lower deck) present unique risk because lithium battery cargo fires in the lower hold affect both cargo and passengers. While true combi configurations are rare in US domestic operations, widebody aircraft on international routes routinely carry belly cargo containing lithium batteries below the passenger cabin.

**High-volume belly cargo routes (US):**

| Route | Volume | Risk |
|---|---|---|
| China → US West Coast (LAX, SFO, SEA) | **Very High** | E-commerce fulfillment, electronics supply chain |
| China → US East Coast (JFK, EWR, ORD via connection) | **High** | Same, with additional handling |
| South Korea → US (LAX, JFK) | High | Battery cells, electronics |
| Intra-US hub connections (MEM, SDF, CVG) | High | FedEx/UPS hubs — concentrated lithium battery cargo |

## 7.4 Notable Cargo Incidents and NTSB Findings

### Recent Cargo/Shipping Incidents

| Date | Carrier / Location | Description | Finding |
|---|---|---|---|
| Sep 2025 | FedEx sort facility, Memphis | Smoke from package containing undeclared lithium cells from China | Declared as "LED lights"; contained 200 loose 18650 cells |
| Jul 2025 | UPS cargo, Louisville | Thermal event in package during sort | Overheated power bank; declared as "phone case" |
| Mar 2025 | Amazon Air (ATSG), CVG | Fire suppression activation in cargo hold | Under investigation; suspected undeclared lithium batteries |
| 2024 | Multiple carriers | 15+ incidents of undeclared lithium batteries discovered in air cargo | PHMSA enforcement actions |

### NTSB Recommendations (Active)

The NTSB has issued several active recommendations related to lithium battery air transport:

| Recommendation | Addressed To | Status |
|---|---|---|
| Develop a test method to detect lithium battery fires in cargo holds before they overwhelm suppression systems | FAA | **Open — Acceptable Response** |
| Require fire-containment covers for cargo containers carrying lithium batteries | FAA | **Open — Acceptable Response** |
| Prohibit transport of lithium-ion batteries as cargo on passenger aircraft until effective suppression is demonstrated | FAA / PHMSA | **Open — Unacceptable Response** (FAA disagrees) |
| Develop performance standards for fire-resistant shipping containers for lithium batteries | FAA | **Open — Acceptable Response** |

**Key tension:** The NTSB's recommendation to prohibit lithium-ion battery cargo on passenger aircraft has been rejected by the FAA, citing economic impact. This divergence between the safety investigation body and the regulator is itself a risk indicator.

---

# Section 8: Seasonal Outlook

## 8.1 Seasonal Risk Calendar

Lithium battery aviation risk follows seasonal patterns driven by travel volume, product purchase cycles, and gift-giving holidays.

| Month(s) | Risk Level | Drivers |
|---|---|---|
| **January** | MODERATE | CES product launches; post-holiday returns; new devices from Christmas |
| **February** | MODERATE | Samsung Unpacked (new Galaxy devices); Valentine's Day electronics gifts |
| **March** | MODERATE-HIGH | Spring break travel surge; new travel gear purchases |
| **April–May** | MODERATE | Steady state; conference travel season |
| **June–August** | **HIGH** | **Peak travel season.** Summer travel + portable fan/cooling device surge + vacation drone use + outdoor electronics. Highest passenger volume = highest battery volume. |
| **September** | **HIGH** | Apple launch (new iPhones, MacBooks, AirPods); back-to-school electronics; end of summer travel |
| **October** | MODERATE-HIGH | Amazon Prime Big Deal Days; early holiday shopping |
| **November** | **HIGH** | **Black Friday / Cyber Monday** — massive discounting on electronics drives impulse purchases of cheap battery devices. Products purchased now are carried on Thanksgiving/Christmas flights. |
| **December** | **HIGHEST** | **Peak risk month.** Holiday travel at maximum + travelers carrying new/gift electronics (often still learning about them) + returns. Highest concentration of unfamiliar battery devices on aircraft. |

## 8.2 Product Launch Calendar Overlay

Major product launches that introduce new battery devices into circulation:

| Event / Launch | Timing | Products | Impact |
|---|---|---|---|
| **CES** | January | New categories announced; 6-month lead to market | Forward indicator |
| **Samsung Unpacked** | February / August | Galaxy S series, Galaxy Ring, Galaxy Buds | New devices in circulation |
| **Apple WWDC** | June | Software focus; occasional hardware | Minimal battery impact |
| **Amazon Prime Day** | July | Discounting on power banks, earbuds, speakers | Price collapse trigger |
| **Apple Launch Event** | September | iPhone, AirPods, MacBook, iPad | Largest single product release; 50M+ new devices |
| **Amazon Prime Big Deal Days** | October | Same as July but pre-holiday | Pre-holiday surge |
| **Black Friday / Cyber Monday** | November | Deep discounting across all electronics | Biggest price collapse + demand surge of the year |
| **DJI Launch Events** | Variable (usually spring/fall) | New drones, new battery systems | New battery specs in circulation |

## 8.3 Regulatory Calendar

### Upcoming Effective Dates and Deadlines

| Date | Regulatory Event | Impact |
|---|---|---|
| **Jan 1, 2026** (ACTIVE) | 30% SoC mandate for cargo Li-ion (UN 3480, Sec II) | Cargo compliance burden increases; enforcement begins |
| **Q2 2026** (expected) | PHMSA NPRM on e-commerce lithium battery declarations | May introduce shipper certification requirements |
| **Jul 2026** (expected) | FAA reauthorization — lithium battery provisions | Congressional mandates possible |
| **Jan 1, 2027** | IATA DGR 68th Edition effective | Potential further restrictions |
| **2027** (expected) | UN 38.3 revision — 8th Edition | May add tests for new chemistries (solid-state, sodium-ion) |

---

# Section 9: Recommended Actions

## For Airlines

| Priority | Action | Rationale |
|---|---|---|
| **1** | Update crew training to include new product categories (cordless hair tools, heated clothing, portable fans) | Crew recognition is the primary defense for cabin events |
| **2** | Implement gate-side battery checks during peak season (Nov–Jan, Jun–Aug) | Target periods when unfamiliar devices are most common |
| **3** | Revise passenger communications to show specific prohibited products (not just regulatory text) | "No hoverboards" is clearer than "no batteries >160 Wh" |
| **4** | Stock AvSax or equivalent battery fire containment bags on every aircraft — minimum 2 per cabin zone | Current stocking may be insufficient for 2/week incident rate |
| **5** | Monitor for passengers carrying multiple high-Wh spare batteries (drone operators, photographers) | Aggregate cabin lithium exposure is unmeasured |

## For TSA / Airport Security

| Priority | Action | Rationale |
|---|---|---|
| **1** | Develop visual recognition training for new battery product form factors (neck fans, heated vests, cordless hair dryers) | Screening officers may not recognize these as battery devices |
| **2** | Flag power banks in checked baggage X-ray as mandatory divert (post-March 2025 ban) | Enforcement of new prohibition requires active screening |
| **3** | Add "battery device count" as a screening metric — passengers with >5 lithium devices warrant additional inspection | Aggregate risk assessment |
| **4** | Publish multilingual passenger guidance at checkpoints (not just English) | International travelers may be unaware of US rules |

## For Cargo Operations

| Priority | Action | Rationale |
|---|---|---|
| **1** | Implement enhanced screening for e-commerce parcels from China-based platforms | Highest volume of undeclared lithium battery shipments |
| **2** | Develop SoC spot-check capability for 30% mandate compliance | Carrier verification reduces reliance on shipper declaration |
| **3** | Segregate lithium battery shipments from other hazmat in cargo positioning | Reduce propagation risk if thermal event occurs |
| **4** | Require e-commerce platforms to certify battery compliance as condition of air transport | Shift compliance burden to platforms with resources to enforce |

## For Regulators (FAA / PHMSA / IATA)

| Priority | Action | Rationale |
|---|---|---|
| **1** | **Close the sodium-ion gap** — issue guidance or rulemaking on sodium-ion battery air transport before consumer products achieve mass market | Prevent unregulated high-energy batteries on aircraft |
| **2** | Require Wh labeling on all lithium battery-powered consumer products sold in the US | Passengers cannot comply with rules they cannot measure against |
| **3** | Address the 99 Wh compliance gaming pattern — consider whether the 100 Wh threshold should be verified against tested (not nominal) capacity | Manufacturing variance may push "99 Wh" products over threshold |
| **4** | Publish product-specific guidance for emerging categories (cordless hair tools, heated clothing, portable fans) | Current guidance assumes passengers know what a "spare lithium battery" is |
| **5** | Fund independent testing of ultra-cheap e-commerce battery products to quantify the quality gap | Evidence base needed for potential import restrictions |
| **6** | Evaluate NTSB recommendation on prohibiting lithium-ion battery cargo on passenger aircraft — with updated data | Risk profile has changed since original FAA rejection |

---

# Appendix A: Battery Chemistry Reference

| Chemistry | Abbreviation | Cathode | Nominal Voltage | Energy Density (Wh/kg) | Common Applications | Primary Failure Mode | Thermal Runaway Onset |
|---|---|---|---|---|---|---|---|
| **Lithium Cobalt Oxide** | LCO | LiCoO₂ | 3.6V | 150–200 | Phones, laptops, cameras | Thermal runaway from overcharge or damage; cobalt is most reactive cathode | ~150°C |
| **Lithium Nickel Manganese Cobalt** | NMC | LiNiMnCoO₂ | 3.6–3.7V | 150–220 | Power banks, EVs, power tools, e-bikes | Thermal runaway; energy proportional to nickel content | ~170°C |
| **Lithium Nickel Cobalt Aluminum** | NCA | LiNiCoAlO₂ | 3.6V | 200–260 | Tesla vehicles, high-performance power tools | High energy = more violent thermal runaway | ~150°C |
| **Lithium Iron Phosphate** | LFP | LiFePO₄ | 3.2V | 90–160 | Power stations, some e-bikes, medical devices | Most thermally stable Li-ion chemistry; slow thermal event | ~270°C |
| **Lithium Manganese Oxide** | LMO | LiMn₂O₄ | 3.7V | 100–150 | Power tools, medical devices | Moderate risk; manganese improves thermal stability | ~250°C |
| **Lithium Polymer** | LiPo | Various (typically LCO or NMC) | 3.7V | 150–250 | Drones, thin devices, RC vehicles, earbuds | Pouch cell puncture — no hard case protection; swelling from age | ~150°C (LCO-based) |
| **Lithium Metal** | Li-metal | N/A (anode is lithium metal) | 3.0–3.7V | 300–500 (theoretical) | Next-gen solid-state, some primary cells | Dendrite formation → internal short circuit; metallic lithium is highly reactive | Varies |

### Key Chemistry Insights

1. **Higher energy density = higher risk.** NCA and LCO cells store the most energy per gram and produce the most violent thermal runaway events.
2. **LFP is the safest lithium chemistry** — its thermal runaway onset is ~100°C higher than LCO/NCA. This is why portable power stations are migrating from NMC to LFP.
3. **LiPo is a packaging format, not a chemistry.** "LiPo" batteries use standard Li-ion chemistry (usually LCO or NMC) in a soft pouch instead of a hard cylindrical or prismatic case. The pouch format makes them lighter but more vulnerable to puncture.
4. **Lithium-metal anodes** (used in next-gen solid-state batteries) are fundamentally more reactive than graphite anodes in current Li-ion cells. New testing protocols may be needed.

---

# Appendix B: Wh Calculation Reference

## The Formula

```
Wh = mAh × V ÷ 1,000
```

Where:
- **Wh** = Watt-hours (the energy measure used in aviation regulations)
- **mAh** = milliamp-hours (the capacity measure commonly printed on batteries)
- **V** = Nominal voltage of the battery (typically 3.7V for single lithium-ion cells)

## Common Examples

| Device | Capacity (mAh) | Voltage (V) | Wh | Regulatory Tier |
|---|---|---|---|---|
| Wireless earbud (single) | 50 mAh | 3.7V | 0.19 Wh | Well below any threshold |
| Earbud charging case | 600 mAh | 3.7V | 2.22 Wh | Well below any threshold |
| Smartphone (iPhone 16) | 3,561 mAh | 3.85V | 13.71 Wh | Below threshold |
| Smartphone (Samsung S25 Ultra) | 5,000 mAh | 3.86V | 19.30 Wh | Below threshold |
| Laptop (MacBook Air M3) | ~4,600 mAh | 11.55V | 52.60 Wh | Below threshold |
| Laptop (MacBook Pro 16" M3) | ~8,700 mAh | 11.47V | 99.80 Wh | **Just under 100 Wh** |
| Power bank (standard) | 10,000 mAh | 3.7V | 37.00 Wh | Below threshold |
| Power bank (large) | 26,800 mAh | 3.7V | 99.16 Wh | **Just under 100 Wh** (compliance gaming) |
| Power bank (extra-large) | 30,000 mAh | 3.7V | 111.00 Wh | **101–160 Wh tier** (airline approval) |
| Drone battery (DJI Mavic 3) | 5,000 mAh | 15.4V | 77.00 Wh | Below threshold |
| E-bike battery (standard) | 10,000 mAh | 48V | 480.00 Wh | **PROHIBITED (>160 Wh)** |
| Portable power station (Jackery 300) | 7,500 mAh | 36V | 293 Wh | **PROHIBITED (>160 Wh)** |

## Voltage Matters

A common mistake is assuming all batteries are 3.7V. Multi-cell packs multiply voltage:

| Configuration | Cells in Series | Nominal Voltage | Example |
|---|---|---|---|
| **1S** (single cell) | 1 | 3.7V | Phone, vape, basic power bank |
| **2S** | 2 | 7.4V | Heated clothing, some hair tools |
| **3S** | 3 | 11.1V | Laptops, large drones |
| **4S** | 4 | 14.8V | Professional drones, speakers |
| **10S** | 10 | 37.0V | E-scooters |
| **13S** | 13 | 48.1V | E-bikes |

**Rule of thumb:** If a product runs on >5V, it has multiple cells in series, and the Wh is much higher than the mAh alone suggests.

## The "mAh Trap"

Marketing often uses mAh to make batteries sound large, while obscuring the Wh:

- "26,800 mAh power bank!" sounds bigger than "99 Wh power bank"
- A 5,000 mAh e-bike battery at 48V = **240 Wh** (prohibited)
- A 5,000 mAh power bank at 3.7V = **18.5 Wh** (no issue)

**The same mAh number can be either permitted or prohibited depending on voltage.**

---

# Appendix C: Data Source Directory

| Source | URL | Update Frequency | Cost | What It Provides | Limitations |
|---|---|---|---|---|---|
| **FAA Lithium Battery Incident Database** | faa.gov/hazmat/resources/lithium_batteries/incidents | Quarterly | Free | Comprehensive US aviation lithium battery incidents | 3–6 month reporting lag |
| **NTSB CAROL Query** | data.ntsb.gov/carol-main-public | Continuous | Free | Accident/incident investigation reports | Only investigated incidents (subset of FAA data) |
| **NASA ASRS** | asrs.arc.nasa.gov | Continuous | Free | Voluntary safety reports from crew and passengers | Self-reported; not all incidents captured |
| **CPSC Recalls** | cpsc.gov/Recalls | As issued | Free | Consumer product recalls for battery fire risk | Lagging indicator (12–24 months behind) |
| **PHMSA Enforcement** | phmsa.dot.gov/hazmat/enforcement | As issued | Free | Hazmat violation cases involving lithium batteries | Enforcement subset of total violations |
| **IATA DGR** | iata.org/dgr | Annual (Jan 1) | $$ | Definitive dangerous goods rules for air transport | Requires subscription |
| **UL TRIP Reports** | ul.com | Annual | Free / $$ | Airline-reported lithium battery event data (37 airlines) | Voluntary reporting; not all airlines participate |
| **FAA Technical Center Reports** | tc.faa.gov | As published | Free | Battery fire testing research (e.g., DOT/FAA/TC-24-39) | Research, not operational data |
| **Google Trends** | trends.google.com | Real-time | Free | Search volume trends for battery product terms | Relative index, not absolute volume |
| **Keepa / CamelCamelCamel** | keepa.com / camelcamelcamel.com | Real-time | Free / $ | Amazon price and BSR tracking | Amazon-only; may not reflect full market |
| **USITC DataWeb** | dataweb.usitc.gov | Monthly (2-month lag) | Free | US import data by HS code | Product-level granularity limited |
| **FCC ID Search** | fcc.gov/oet/ea/fccid | Real-time | Free | Equipment authorization grants for wireless devices | Batteries in non-wireless devices not captured |
| **r/vaping, r/ebikes, etc.** | reddit.com | Real-time | Free | Consumer sentiment, product trends, incident reports | Anecdotal; not statistically representative |

---

# Appendix D: Glossary

| Term | Definition |
|---|---|
| **Ah** | Ampere-hour — unit of electric charge capacity. 1 Ah = 1,000 mAh. |
| **ASP** | Average Selling Price — mean sale price for a product category. |
| **BMS** | Battery Management System — electronic circuit that monitors and protects battery cells from overcharge, over-discharge, overcurrent, and thermal events. |
| **BSR** | Best Sellers Rank — Amazon's product ranking system. Lower number = higher sales velocity. |
| **C-rate** | Charge/discharge rate relative to capacity. 1C = full discharge in 1 hour. Higher C-rates increase thermal stress. |
| **CFR** | Code of Federal Regulations — the codification of US federal regulatory rules. |
| **Combi aircraft** | Aircraft configured with both passenger and cargo sections on the same deck. |
| **CPSC** | Consumer Product Safety Commission — US agency responsible for product recalls. |
| **De minimis** | Section 321 trade exemption for parcels valued under $800, allowing minimal customs inspection. |
| **DGR** | Dangerous Goods Regulations — IATA's industry standard for hazmat air transport. |
| **DOT** | Department of Transportation — parent agency of FAA and PHMSA. |
| **FAA** | Federal Aviation Administration — US aviation safety regulator. |
| **GaN** | Gallium Nitride — semiconductor technology enabling smaller, more efficient chargers. Relevant because GaN chargers enable faster charging of larger batteries. |
| **HS Code** | Harmonized System code — international product classification for customs/trade tracking. |
| **IATA** | International Air Transport Association — global airline trade association. |
| **ICAO** | International Civil Aviation Organization — UN specialized agency for aviation standards. |
| **InFO** | Information for Operators — FAA advisory notices (less urgent than SAFOs). |
| **LCO** | Lithium Cobalt Oxide — high energy density battery chemistry common in phones/laptops. |
| **LFP** | Lithium Iron Phosphate — thermally stable battery chemistry, lower energy density. |
| **Li-ion** | Lithium-ion — rechargeable battery using lithium ions moving between anode and cathode. |
| **Li-metal** | Lithium metal — battery using metallic lithium as anode. Higher energy but more reactive. |
| **LiPo** | Lithium Polymer — pouch-format lithium-ion battery. |
| **LMO** | Lithium Manganese Oxide — moderate energy battery chemistry for power tools. |
| **mAh** | Milliamp-hour — unit of battery capacity. Must multiply by voltage to get Wh. |
| **NCA** | Lithium Nickel Cobalt Aluminum — high energy density chemistry used in EVs. |
| **NMC** | Lithium Nickel Manganese Cobalt — common Li-ion chemistry with good energy-to-safety balance. |
| **NPRM** | Notice of Proposed Rulemaking — formal step in US federal regulatory process. |
| **NTSB** | National Transportation Safety Board — independent US accident investigation body. |
| **PI** | Packing Instruction — IATA DGR designation for how specific dangerous goods must be packed. |
| **PHMSA** | Pipeline and Hazardous Materials Safety Administration — DOT sub-agency regulating hazmat transport. |
| **SAFO** | Safety Alert for Operators — FAA notice requiring airline acknowledgment and action. |
| **SoC** | State of Charge — percentage of remaining battery capacity (0% = empty, 100% = full). |
| **Thermal runaway** | Self-sustaining exothermic reaction in a battery cell. Temperature rises uncontrollably, potentially causing fire or explosion. Can propagate to adjacent cells. |
| **TSA** | Transportation Security Administration — DHS agency responsible for aviation security screening. |
| **UN 38.3** | UN Manual of Tests and Criteria, Part III, Section 38.3 — required safety tests for lithium batteries. Includes altitude simulation, thermal cycling, vibration, shock, external short circuit, impact/crush, overcharge, and forced discharge. |
| **UN number** | Four-digit identifier for dangerous goods in transport (e.g., UN 3480 = lithium-ion batteries). |
| **Wh** | Watt-hour — unit of energy. The measure used in aviation regulations for lithium battery thresholds. Wh = V × Ah. |

---

*Report prepared February 25, 2026. Next update: May 2026.*

*This report is intended for aviation safety and regulatory professionals. It does not constitute legal advice. Regulatory citations should be verified against current federal register publications.*
