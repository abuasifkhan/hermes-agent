---
name: startup-company-analysis
description: Use when extracting, mapping, or researching startup/company information from investor decks, screenshots, KIIS documents, financial models, websites, or data rooms. Provides the AKKA-style analysis structure and diligence checklist for future company reviews.
version: 1.0.0
author: Hermes Agent
license: MIT
metadata:
  hermes:
    tags: [startup-research, company-analysis, investment-diligence, akka, second-brain]
    related_skills: []
---

# Startup Company Analysis

## Overview

Use this skill to extract and organize information about a company, especially a startup investment candidate. The structure is based on the AKKA/Fideum review pattern Asif asked to preserve: simple explanation, why now, solution, technology, market, business model, traction, financials, valuation, competitors, risks, and exit logic.

Default outcome: a clean company map that can be saved into the Second Brain or another knowledge base and reused for follow-up diligence, investment decisions, or comparison against other companies.

## When to Use

Use when asked to:

- Map a company to a knowledge base.
- Extract details from a pitch deck, KIIS, business plan, investor memo, screenshots, data room export, website, or financial model.
- Find information about a startup/company and organize it for future use.
- Build an AKKA-style startup writeup.
- Compare a company against competitors or valuation benchmarks.
- Prepare due diligence questions before investing.

Do **not** use as a substitute for legal, tax, or regulated financial advice. Mark source claims as source claims until verified.

## Required Workflow

1. **Collect sources**
   - Uploaded documents: preserve the file path and extract text/visual content.
   - Screenshots/images: OCR or vision-analyze them; capture exact labels and numbers.
   - Websites/current facts: use web search/fetch with source URLs.
   - Financial workbooks: extract tables, line items, assumptions, and formulas where possible.

2. **Separate source claims from verified facts**
   - Use phrasing like “the deck claims,” “the memo states,” or “management projects.”
   - Flag unverified regulatory, revenue, profitability, customer-count, and valuation claims.

3. **Map the company using the AKKA-style structure**
   - Fill the sections below.
   - Prefer tables for financials, traction metrics, competitors, and valuation comps.
   - Capture contradictions across sources explicitly.

4. **Save to a knowledge base when requested**
   - Company entity: a living company page.
   - Source summaries: one summary page per major source.
   - Reusable framework/template: a skill or reference page if the workflow should persist.
   - Parent updates: update relevant indexes/hubs/logs if the target knowledge base requires bookkeeping.

5. **Finish with a diligence view**
   - What is attractive.
   - What must be verified.
   - Red flags / open questions.
   - Requested next artifacts.

## References and Templates

- Template: `templates/akka-company-analysis-template.md` — copyable skeleton for future company reviews.
- Reference: `references/akka-fideum-session-pattern-2026-05-20.md` — concise session pattern from the Fideum/AKKA extraction that motivated this skill; use as an example, not a one-company constraint.

## AKKA-Style Company Analysis Template

### 1. Why invest in [Company]?

Capture the investor hook. Common angles:

- Capital efficiency.
- Founder-market or regulatory fit.
- Deep infrastructure stickiness.
- Explosive traction or growth inflection.
- Attractive valuation entry.
- Timing catalyst.

### 2. Understanding the basics

Explain plainly:

- What the company does.
- Who the customer is.
- What the customer buys.
- What pain it removes.
- “X for Y” analogy if useful.
- Why customers buy instead of building internally.

### 3. Opportunity

Explain why the market opens now:

- Regulatory mandate or compliance deadline.
- Technology adoption inflection.
- Market behavior shift.
- Incumbent inability to build fast enough.
- Institutional/customer adoption catalysts.

### 4. Solution

Break the product into concrete modules:

- Core product components.
- Workflow replaced.
- Deployment modes.
- White-label/API/embedded model if relevant.
- Customer-facing vs infrastructure-facing surfaces.

### 5. Technology

Assess infrastructure depth:

- System architecture layers.
- APIs/SDKs/integrations.
- Data model and persistence.
- Security and observability.
- Compliance automation.
- Proprietary algorithms/routing/automation.
- IP and defensibility.

If an architecture diagram exists, extract each layer and component exactly. Label it conceptual unless implementation evidence is provided.

### 6. Market opportunity

Capture:

- TAM, SAM, SOM.
- Target segments.
- Geography.
- Market drivers and trends.
- Source of market-size claims.
- Whether TAM is actual addressable revenue or a broader asset/volume number.

### 7. Business model

Extract all revenue streams:

- Setup fees.
- Monthly platform/subscription fees.
- Transaction/usage fees.
- FX/spread/OTC/take-rate income.
- Services/integration fees.
- Contract length and ACV.
- Gross margin drivers.
- Revenue concentration and churn.

### 8. Commercial traction and financial elements

Capture metrics:

- ARR / revenue / MRR.
- Gross transaction volume / booking value.
- Customer count and active vs signed definitions.
- Churn / retention / NRR.
- Gross margin / EBITDA / profit.
- Cash in bank / burn / runway.
- Team size and revenue per employee.
- Capital raised to date.

### 9. Business plan / financial forecast

Extract historical and projected P&L:

- ARR.
- Revenue.
- Gross margin.
- EBITDA / operating income.
- Assumptions by year.
- Hiring plan.
- Expansion/geography assumptions.
- Use of funds.

Always note if different source versions conflict.

### 10. Go-to-market

Capture:

- Sales motion.
- Channel partners.
- Geography expansion.
- Enterprise vs SMB motion.
- Sales-cycle length.
- Pipeline quality.
- Existing-client expansion / ARPA growth.

### 11. Competitors and comparables

Separate:

- Direct product competitors.
- Valuation comparables.
- Strategic acquirer comparables.
- Adjacent incumbents.

Use a table with company, valuation, ARR/revenue, multiple, and key signal when available.

### 12. Round size and goal

Extract:

- Round size.
- Instrument/security.
- Pre-money / post-money / valuation cap.
- Minimum and maximum ticket.
- SPV terms and fees.
- Use of funds.
- Closing timeline.

### 13. Valuation calculation

Assess:

- Revenue/ARR multiple.
- Forward multiple based on run-rate.
- Peer discount/premium.
- Profitability adjustment.
- Growth-risk adjustment.
- Whether ARR includes non-recurring or usage revenue.

### 14. Why this valuation makes sense

Summarize the strongest valuation defense:

- Profitability vs peers.
- Run-rate compression.
- Strategic category premiums.
- Scarcity / timing.
- Comparable exits or acquisitions.

Then write the counterargument.

### 15. Notable investors and validation

Capture:

- Existing investors.
- Accelerator/program wins.
- Strategic partners.
- Customer logos.
- Regulatory or licence validation.

Mark logos as “shown in source” unless independently verified.

### 16. Risks, red flags, and open questions

Always include:

- Entity/legal mismatch.
- Licence/regulatory gaps.
- Revenue quality and recurrence.
- Customer concentration.
- Forecast aggressiveness.
- Margin assumptions.
- Technical/security evidence gaps.
- Competitive pressure.
- Reputation/litigation signals.
- SPV fee/friction issues.

### 17. Exit strategy

Infer only when supported:

- Strategic acquirers.
- Platform consolidation.
- Later-stage growth round.
- IPO path.
- Comparable M&A.

If not present, write “not evidenced in sources” and list what to ask.

## Knowledge Base Output Pattern

For an investment candidate, create/update this cluster when the target system supports linked notes:

1. Living company entity and diligence page.
2. Investment-platform/source tracker when there is a platform like AKKA.
3. One source-summary page per major source.
4. Optional red-flag memo.
5. Parent/index/hub/log updates where required by the knowledge base.

## Verification Checklist

Before reporting:

- [ ] Every extracted number has a source or is clearly marked as inferred.
- [ ] Source-claim vs verified-fact language is clear.
- [ ] Contradictions across sources are captured.
- [ ] Company entity page and source summary pages are linked when saved.
- [ ] Parent/index/hub/log pages are updated when the knowledge base requires it.
- [ ] Diligence questions are actionable and specific.

## Common Pitfalls

1. **Treating deck numbers as facts.** Investor material is advocacy. Preserve the number but label the source.
2. **Mixing ARR, revenue, MRR, GMV, and booking value.** Keep definitions separate.
3. **Ignoring entity scope.** Verify whether revenue/profit belongs to the company, group, issuer, or SPV.
4. **Over-trusting TAM.** Many decks use asset/transaction volume as TAM rather than software revenue opportunity.
5. **Missing regulatory dependency.** Licences and partner models can drive both legality and margins.
6. **Creating one giant note.** Use a company entity plus source summaries so the graph remains navigable.
