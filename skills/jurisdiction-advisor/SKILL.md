---
name: "jurisdiction-advisor"
description: "Advise startup founders on choosing the best jurisdiction and legal entity for their business. Triggers when users ask about where to incorporate, which state/country to register a company, choosing between Delaware vs other states, offshore vs US incorporation, entity types (C-Corp, LLC, PBC), or jurisdiction selection for specific industries (crypto, AI, SaaS, GameDev, solopreneurs). Also triggers for questions about startup formation, company registration, or corporate structure decisions."
metadata:
  author: "Skala Inc."
  license: "Apache-2.0"
  license-notice: "See LICENSE and NOTICE files in the repository"
  homepage: "https://skala.io/legal-skills"
  repository: "https://github.com/skala-io/legal-skills"
---

> **NOT LEGAL ADVICE.** General guidance only. Consult qualified counsel.

# Jurisdiction Advisor

Advise founders on optimal jurisdiction and entity type selection based on their specific situation.

## Core Approach

1. **Gather key information** (if not provided). Required data points:
   - Industry/business type
   - Funding plans (VC-backed, bootstrapped, self-funded)
   - Team structure (solo, co-founders, employees)
   - Tax residency of founders
   - Target market/customers
   - Special requirements (token issuance, privacy needs, asset protection)

2. **Validate before recommending**: Confirm the user's priorities and flag any conflicting requirements (e.g., wanting both VC funding and offshore tax efficiency, or privacy and Delaware's public filing requirements). Resolve conflicts before proceeding.

3. **Provide concise recommendation** with:
   - Recommended jurisdiction and entity type
   - Key reasons (2-3 bullet points max)
   - Cost and timeline estimate (use ranges from the decision framework tables below)
   - Any important caveats

## Decision Framework

### By Funding Strategy

| Strategy | Recommended | Reason | Typical Cost | Timeline |
|----------|-------------|--------|-------------|----------|
| VC-backed | Delaware C-Corp | Industry standard, investor-familiar | $1,500–$2,500 | 1–2 weeks |
| Bootstrapped US | Wyoming C-Corp or LLC | Lower costs, privacy | $500–$1,000 | 1–2 weeks |
| Bootstrapped non-US | Delaware LLC or BVI | Tax efficiency | $1,500–$3,500 | 2–4 weeks |
| Token raise | BVI or Panama | Regulatory flexibility | $3,000–$8,000 | 3–6 weeks |

### By Industry

| Industry | Primary Choice | Alternative |
|----------|---------------|-------------|
| SaaS/General Tech | Delaware C-Corp | Wyoming C-Corp |
| AI (commercial) | Delaware C-Corp | Texas/Nevada C-Corp |
| AI (mission-driven) | Delaware PBC | — |
| Crypto (DevCo) | Delaware C-Corp | — |
| Crypto (token issuer) | BVI or Panama | — |
| GameDev (traditional) | Delaware C-Corp | — |
| GameDev (web3/tokens) | Panama | BVI |
| Solopreneur (US tax resident) | Delaware LLC | Wyoming LLC |
| Solopreneur (non-US) | Delaware LLC | Hong Kong |
| Space | Delaware C-Corp | Texas/Nevada C-Corp |
| SPV (onshore) | Delaware LLC | Delaware Series LLC |
| SPV (offshore) | BVI | — |
| Asset holding | Wyoming LLC | Nevada LLC, BVI |

### By Special Requirements

- **Need VC funding** → Delaware C-Corp (80% of VC-backed startups)
- **Need privacy/anonymity** → Wyoming (no public disclosure of shareholders)
- **Need zero corporate tax** → BVI, Panama, UAE Free Zone
- **Issuing tokens** → BVI (single issuance) or Panama (multiple issuances)
- **DAO structure** → Wyoming DAO LLC
- **Public benefit mission** → Delaware PBC

## Quick Reference

See [references/jurisdictions.md](references/jurisdictions.md) for detailed information on each jurisdiction including costs, timelines, tax rates, and specific use cases.

## Response Guidelines

- Keep recommendations **concise and actionable**
- Always include **cost estimate and timeline** using ranges from the tables above
- If situation is complex (multiple entities, restructuring), suggest consulting a lawyer
- End recommendations with: "This is general information, not legal advice. Consult a qualified attorney for your specific situation."
