# Skala Legal Skills

Curated legal skills for [Claude](https://claude.ai) and other AI Agents built by lawyers at [Skala](https://skala.io).

Designed for startup founders, investors, and attorneys working with early-stage companies.

## Skills

| Skill | Description |
|-------|-------------|
| **client-alert-drafting** | Draft professional legal client alerts and publications about new legislation, regulations, or case law. Supports all practice areas. Output as `.docx` or `.md`. |
| **jurisdiction-advisor** | Choose the best jurisdiction and entity type for a startup based on industry, funding strategy, team structure, and tax residency. Covers Delaware, Wyoming, BVI, Panama, Singapore, Cayman, and more. |
| **open-source-license** | Select an open source license, check compatibility between licenses, review projects for OSS compliance, and generate LICENSE/NOTICE files. Covers permissive, copyleft, and specialty licenses. |
| **reg-s-offering** | Guidance on Regulation S offshore securities offerings under U.S. law. Determine eligibility, identify transaction categories, and navigate distribution compliance periods. |
| **safe-review** | Review and advise on YC SAFE (Simple Agreement for Future Equity) agreements. Compare against canonical YC templates, analyze SAFE stacks, and draft standard SAFEs. Includes official YC templates. |
| **saft-review** | Review SAFTs (Simple Agreement for Future Tokens), token warrants, and token side letters. Covers securities law implications, token economics, and jurisdiction-specific guidance. |
| **startup-due-diligence** | Legal due diligence for seed/Series A startups. Document review, cap table analysis, red flag identification, and report generation with `.docx` templates. |
| **term-sheet-review** | Analyze VC term sheets clause by clause. Identify investor-friendly vs. founder-friendly terms, flag deviations from market standards, and provide negotiation guidance. |

## Installation

### Any AI Agents (as skill)

**Option 1** — Install from GitHub:

```bash
npx skills add skala-io/legal-skills
```

**Option 2** — Ask AI directly in the chat:

```
Install skills from https://github.com/skala-io/legal-skills
```

**Option 3** — Manual setup:

```bash
git clone https://github.com/skala-io/legal-skills.git
```

Copy the skill folders from `skills/` into your project's `.claude/skills/` directory or into `~/.claude/skills/` to make them available across all projects.

### Claude Code / Cowork (as plugin)

```
/plugin marketplace add skala-io/legal-skills
/plugin install legal-skills@skala-io-legal-skills
```

### Claude Web / Desktop

1. Download the `.zip` archive of the desired skill.
2. Go to **Settings** → **Capabilities** → **Skills**.
3. Upload the `.zip` archive.
4. The skill will appear in your skills list — toggle it on to enable.

## Usage

Once installed, the skills activate automatically based on your prompt.

## License

Apache 2.0 — see [LICENSE](LICENSE.txt) and [NOTICE](NOTICE.txt).
