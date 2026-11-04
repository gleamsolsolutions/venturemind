# VentureMind
**Deep Research & Entrepreneurial Intelligence for Google Antigravity**

VentureMind is a modular Agent Skill package for evidence-led idea validation, market research, customer intelligence, entrepreneurial strategy, SEO/ASO, marketing, domain research, financial feasibility, red-team verification and polished PDF reporting.

## Install globally (all Antigravity workspaces)

Copy the `venturemind` folder into:

```bash
mkdir -p ~/.gemini/config/skills
cp -R venturemind ~/.gemini/config/skills/
```

The final path should be:

```text
~/.gemini/config/skills/venturemind/SKILL.md
```

## Install in one workspace only

Copy the folder into:

```text
<workspace-root>/.agents/skills/venturemind/
```

Antigravity's current documented skill locations are `~/.gemini/config/skills/<skill>/` for global use and `<workspace-root>/.agents/skills/<skill>/` for workspace use. Restart/reload skills if the agent does not discover it. In supported interfaces, invoke it with `/venturemind`.

## How to use

Examples:

- `/venturemind Evaluate this Android app idea for a global paid market.`
- `/venturemind Research whether this SaaS opportunity is worth building.`
- `/venturemind Find underserved problems in this market and recommend one product.`
- `/venturemind Audit this business model, SEO demand, competitors and domain options.`

## Important capability note

The skill is a set of instructions and reference playbooks. It does not itself grant access to private Facebook groups, paid SEO databases, Google Keyword Planner, Google Trends APIs, app-store review APIs, registrar checkout systems, trademark databases or other restricted services. The agent must use tools actually available in its environment, disclose inaccessible sources and never fabricate access or metrics.

For best results, connect appropriate browser/search, SEO, keyword research, app-store, domain registrar and PDF-generation tools. Specialist skills are optional and are used only when installed and accessible.

## Default domain budget

Prioritize standard registration under USD 20/year where possible. Always report renewal pricing and premium status. This is a target, not a guarantee. Never call a domain available without a live registrar/registry check.

## Package contents

- `SKILL.md`: Main orchestrator and mandatory workflow.
- `engines/`: Specialist playbooks.
- `references/`: Evidence, scoring, PDF and research standards.
- `templates/`: Report and validation templates.
- `scripts/`: Optional local helpers.
