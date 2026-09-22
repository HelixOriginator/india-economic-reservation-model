Indian Reservation System Reform Framework (IRS-RF)
An interactive policy simulation model and research framework proposing an income and asset-based alternative to India's traditional caste-based reservation structure.
This repository explores a multi-tiered affirmative action architecture designed to target socio-economic vulnerability, eliminate multi-generational benefit hoarding ("creamy layer"), and ensure equitable representation across all societal sectors—including underrepresented members of the General category and underprivileged SC/ST/OBC households.
🌟 Key Proposal Overview
The model replaces birth-based category assignment with dynamic household financial auditing, structured across three income tiers and strict wealth caps:
┌────────────────────────────────────────────────────────────────────────┐
│                        HOUSEHOLD FINANCIAL AUDIT                      │
└────────────────────────────────────────────────────────────────────────┘
                                   │
         ┌─────────────────────────┴─────────────────────────┐
         ▼                                                   ▼
[ Hard Exclusions Met? ]                             [ Under Threshold? ]
 • Class-I Officer Parent                             • < ₹4 Lakhs ➔ ST Category
 • Property ≥ 2,000 Sq Ft                            • < ₹6 Lakhs ➔ SC Category
 • Active Passive Income                             • < ₹9 Lakhs ➔ OBC Category
         │                                                   │
         ▼                                                   ▼
┌──────────────────┐                               ┌──────────────────┐
│ GENERAL / UNRESERVED │                           │ RESERVED CATEGORY│
└──────────────────┘                               └──────────────────┘


1. Tiered Gross Annual Income Brackets
ST Allocation Tier: Annual Household Income < ₹4.0 Lakhs
SC Allocation Tier: Annual Household Income < ₹6.0 Lakhs
OBC Allocation Tier: Annual Household Income < ₹9.0 Lakhs
2. Universal Hard Exclusion Rules (Creamy Layer)
Regardless of income bracket, an applicant is automatically categorized under General / Unreserved if any of the following conditions are met:
Class-I Officer Rule: Father or mother holds/held a Class-I / Gazetted Government Officer position (IAS, IPS, Class-I Central/State services).
Property Asset Cap: Household owns real estate/property totaling 2,000 sq ft or greater.
Passive Income Generation: Household generates active passive income (e.g., rental yields, stock dividends, commercial property income).
🚀 Interactive Dashboard Features
The accompanying index.html file contains a fully functional, dark-mode single-page application built with Tailwind CSS, Chart.js, and vanilla JavaScript:
Real-time Eligibility Engine: Adjust gross family income slider, property holdings slider, and boolean switches to compute dynamic category placement.
Rule Compliance Checklist: Visual indicator validating against property caps, Class-I officer status, and passive income flags.
Comparative Policy Analytics: Side-by-side evaluation of traditional caste-at-birth reservation dynamics versus the proposed multi-tier economic framework.
Visual Data Charts: Interactive population income bracket distribution and simulated quota beneficiary allocation metrics using Chart.js.
⚖️ Legal & Constitutional Context
Policy Dimension
Prevailing System
Proposed Reform Model
Primary Basis
Social backwardness & historical caste lineage (Articles 15 & 16).
Economic status, household asset caps, and multi-tier income limits.
Creamy Layer Scope
Applied only to OBC (₹8L) & EWS categories (Indra Sawhney precedent).
Universally applied across all tiers (ST, SC, OBC) to prevent privilege hoarding.
General Category Disadvantage
Addressed partially via 10% EWS quota (Janhit Abhiyan, 2022).
Low-income General category households directly qualify for lower-income tiers.
Constitutional Pathway
Existing Articles 15(4), 16(4), 341, and 342.
Requires Constitutional Amendments to Articles 15/16 and 341/342 or sub-classification framework.

🛠️ Installation & Usage
No build tools or server environments are required.
Clone the repository:
git clone https://github.com/your-username/india-economic-reservation-model.git


Open index.html directly in any modern web browser.
📄 License
This research framework is released under the MIT License. Feel free to fork, adapt, and build upon this model for academic and public policy analysis.
✍️ Attribution
Created by Kallol Chakrabarti, Global Independent Researcher
