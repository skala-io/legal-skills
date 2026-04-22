---
name: "client-alert-drafting"
description: "Draft professional legal client alerts and publications that inform clients about significant legal developments. Use when asked to: write a client alert, draft a legal update, create a publication about new legislation/regulations/case law, or prepare a legal briefing for clients. Supports all practice areas including corporate, litigation, regulatory, employment, tax, IP, and more. Output available as Word (.docx) or Markdown (.md)."
metadata:
  author: "Skala Inc."
  license: "Apache-2.0"
  license-notice: "See LICENSE and NOTICE files in the repository"
  homepage: "https://skala.io/legal-skills"
  repository: "https://github.com/skala-io/legal-skills"
---

# Client Alert Drafting

> **NOT LEGAL ADVICE.** General guidance only. Consult qualified counsel.

## Workflow

1. **Gather** -- Collect the legal development details (legislation, case, regulation, guidance). If information is incomplete, list what is missing and ask the user before proceeding.
2. **Audience** -- Determine target clients and their concerns.
3. **Draft** -- Apply the Standard Alert Structure below.
4. **Validate** -- Run every item in the Quality Checklist; fix failures before output.
5. **Output** -- Generate `.docx` (via the docx skill) or `.md`. Ask the user which format they prefer if not specified.

## Standard Alert Structure

```
TITLE
[Date] | [Practice Area] | [Jurisdiction]

IN BRIEF
[1-2 paragraph executive summary of the key development and its significance]

KEY TAKEAWAYS
- [Most important point 1]
- [Most important point 2]
- [Most important point 3]
(3-5 bullet points maximum)

IN DEPTH

## Background
[Context and history leading to the development]

## The Development
[What specifically changed -- new law, ruling, regulation]

## Analysis / Implications
[What this means for affected parties]

## Practical Considerations / Actions to Consider
[Specific, numbered guidance for clients]

LOOKING AHEAD (optional)
[Future developments to watch]

CONTACTS
[Author names, titles, locations, contact info]

---
This [publication/alert] is provided for informational purposes only and does
not constitute legal advice. [Firm name] expressly disclaims all liability in
connection with actions taken or not taken based on any or all of the contents
of this publication.
```

## Length Guidelines

| Section | Target |
|---------|--------|
| In Brief | 100-200 words |
| Key Takeaways | 3-5 bullets, 1-2 sentences each |
| In Depth | 500-2000 words depending on complexity |
| Total alert | 800-2500 words typical |

## Quality Checklist

Before outputting, verify every item passes:

- [ ] Title uses action verb or clear outcome description
- [ ] In Brief answers "what happened and why should clients care"
- [ ] Key Takeaways are actionable and specific
- [ ] Analysis is accurate with correct citations (cases, statutes, regulations)
- [ ] Practical guidance includes numbered, concrete actions
- [ ] Tone is professional but accessible
- [ ] Length is appropriate for complexity
- [ ] Disclaimer is included at end

If any item fails, revise the draft and re-check before delivering.

## References

| File | Purpose |
|------|---------|
| `references/examples.md` | Annotated examples of well-crafted alerts across practice areas and firm styles |

## Hard Rules

- Never fabricate case citations or statutory references
- Always include the disclaimer at the end of every alert
- Lead with the "so what" -- why should clients care
- Cite sources accurately; cross-reference related firm publications when relevant
