# Market Intelligence Agent — Global Corporate Competitive Positioning

Agentic AI-driven market intelligence project built with **Amazon Quick**, combining structured financial datasets with AI-generated research to produce an executive-ready strategic brief on global corporate competitive positioning.

## Overview

This project used an Amazon Quick chat agent — configured as a market intelligence analyst — to synthesize structured company-ranking datasets with independently generated research reports, cross-validate the findings against each other, and produce a leadership-ready brief with explicit confidence ratings on every insight.

The objective: assess the competitive positioning, valuation structures, and regional distribution of the world's top 100 corporations across 9 sectors and 5 regions, to inform strategic capital allocation and risk decisions through 2032.

## Process

### 1. Agent Setup
- Selected a real-world financial dataset from Kaggle (*World's Top Companies — Key Financial Analysis*), comprising 5 interconnected CSV files ranking companies by market cap, revenue, earnings, P/E ratio, and dividend yield
- Built a custom **Market Intelligence Agent** in Amazon Quick, with a defined persona and instructions to synthesize multi-source data into structured, executive-ready briefs grounded strictly in available evidence

### 2. External Research Generation
- Used Quick Research to generate two independent research reports (*Global Enterprise Competitive Positioning, Valuation, and Regional Distribution Analysis*, v1 and v2) covering the same domain from an external, web-informed perspective
- Attached both the datasets and research reports to the agent's knowledge sources, so every downstream analysis could draw on both quantitative and qualitative evidence

### 3. Market Analysis
Directed the agent to produce a full market analysis including:
- A competitive landscape summary
- Key trends and signals
- Opportunities and risks, each with supporting evidence and strategic implications

### 4. Reliability & Confidence Evaluation
For each of the five headline insights, the agent was directed to:
- Cross-reference dataset evidence against external research corroboration
- Explicitly document gaps, missing context, and assumptions
- Assign a confidence level (High / Medium-High / Medium) based on source agreement and evidentiary strength
- State what **cannot** be concluded from the evidence — a deliberate check against overstating confidence

This produced 136 cross-validated data points with 99.3% cross-source consistency (135 of 136 consistent), with the single inconsistency — a directional disagreement between Morgan Stanley and PIMCO on China's outlook — surfaced explicitly rather than resolved artificially.

### 5. Final Deliverable
Compiled the validated insights into a final Market Intelligence Brief, organized in Quick Spaces alongside all supporting research, datasets, and validation artifacts for full traceability.

## Key Findings

1. **AI is reshuffling the global market hierarchy** — AI-related capex exceeded $800B in 2026; the semiconductor sector trades at the highest implied P/E (28.0x) of any sector.
2. **US technology concentration is extreme but earnings-supported** — US firms hold 59% of top-100 market cap on 41% of revenue, but Nasdaq-100 valuations (~20.7x) remain near their 25-year median, unlike the dot-com era.
3. **Semiconductor supply chain concentration is the most acute systemic risk** — the top 3 semiconductor firms control 76.3% of sector market cap, with TSMC representing a single point of geopolitical failure.
4. **Earnings growth is set to decelerate sharply** — from 24–33% in 2026 to ~11% by 2027–2028 as AI capex tailwinds normalize.
5. **China's valuation discount is structural, not temporary** — China holds 19% of top-100 earnings on just 11% of market cap, the widest gap of any region, with institutional views on the outlook currently unreconciled.

## Tools & Skills

**Tools:** Amazon Quick (Chat Agents, Quick Research, Spaces), CSV dataset analysis, AI-assisted research synthesis

**Skills demonstrated:** Multi-source data validation, confidence-tiered evidence assessment, agentic AI workflow design, executive brief writing, critical evaluation of AI-generated research (identifying gaps and unreconciled conflicting sources rather than accepting outputs at face value)
## Screenshots
<img width="405" height="403" alt="image" src="https://github.com/user-attachments/assets/5bca60ad-affd-40c4-abac-222cc19e9b2c" />
<img width="940" height="622" alt="image" src="https://github.com/user-attachments/assets/aca722c7-cbfd-4547-94a7-2c4d06dc53c4" />
<img width="940" height="640" alt="image" src="https://github.com/user-attachments/assets/7ac54f08-fda7-4480-9bc3-f1d24f509ced" />
<img width="940" height="429" alt="image" src="https://github.com/user-attachments/assets/d64108cb-cd13-4109-be07-1697b61a6f98" />
<img width="940" height="409" alt="image" src="https://github.com/user-attachments/assets/51a45b6d-aa90-469b-acb1-cf491c145dd9" />
<img width="940" height="404" alt="image" src="https://github.com/user-attachments/assets/c74cafc6-7db6-4291-a9f2-b7525a6a7eff" />
<img width="940" height="429" alt="image" src="https://github.com/user-attachments/assets/bed26969-6196-4e8e-b90d-ff0df625d160" />
<img width="940" height="428" alt="image" src="https://github.com/user-attachments/assets/d2275e28-a1b1-4e47-b5fc-84d7e23891c0" />
<img width="940" height="425" alt="image" src="https://github.com/user-attachments/assets/f23c1782-3a22-482c-8057-6e49c706b349" />
<img width="940" height="430" alt="image" src="https://github.com/user-attachments/assets/740c445e-fa39-4fb1-932e-b08c96ba25fb" />
<img width="940" height="429" alt="image" src="https://github.com/user-attachments/assets/3a501126-2938-4011-ac9f-98025aa699f1" />
<img width="491" height="429" alt="image" src="https://github.com/user-attachments/assets/bb89a156-db27-461a-af4c-a7b57c8c2b16" />

<img width="940" height="428" alt="image" src="https://github.com/user-attachments/assets/9bcb2c48-9efb-4ae9-9560-05ce7a9fd9c8" />
<img width="940" height="428" alt="image" src="https://github.com/user-attachments/assets/3aa603ec-35a2-4c06-8324-0155733168d3" />
<img width="940" height="429" alt="image" src="https://github.com/user-attachments/assets/ab2db6d9-93a4-4373-92f1-ed29daf58733" />

<img width="940" height="424" alt="image" src="https://github.com/user-attachments/assets/8a08b17c-6c5b-4a50-8dee-e50f046be354" />
<img width="940" height="425" alt="image" src="https://github.com/user-attachments/assets/20c5fe2f-c573-4462-b1f3-91d75eb91bde" />
<img width="940" height="439" alt="image" src="https://github.com/user-attachments/assets/82d8abfa-9237-4ca9-a008-a4b304c202a5" />
<img width="940" height="430" alt="image" src="https://github.com/user-attachments/assets/d119a1e8-0d73-4e5e-8b6b-2731049a47cd" />
<img width="940" height="426" alt="image" src="https://github.com/user-attachments/assets/7b086dbe-50c0-44ca-8342-d80135649ba7" />

## Notes

[MarketIntelligence_Agent_README.md](https://github.com/user-attachments/files/32711580/MarketIntelligence_Agent_README.md)

[Supporting evidence from both the dataset and Quick Research.pdf](https://github.com/user-attachments/files/32711142/Supporting.evidence.from.both.the.dataset.and.Quick.Research.pdf)

[Reliability-confidence evaluation section.pdf](https://github.com/user-attachments/files/32711141/Reliability-confidence.evaluation.section.pdf)

[Global Enterprise Competitive Positioning Analysis_Version 2.pdf](https://github.com/user-attachments/files/32711140/Global.Enterprise.Competitive.Positioning.Analysis_Version.2.pdf)

[Global Enterprise Competitive Positioning Analysis_Version 1.pdf](https://github.com/user-attachments/files/32711139/Global.Enterprise.Competitive.Positioning.Analysis_Version.1.pdf)

[final Market_Intelligence_Brief_2026.pdf](https://github.com/user-attachments/files/32711137/final.Market_Intelligence_Brief_2026.pdf)


This project was completed as a hands-on training exercise using Amazon Quick, with a deliberate focus on **validating and critically evaluating agentic AI outputs** — not just generating them — including surfacing conflicting institutional views and explicitly stating what conclusions the evidence does *not* support.
