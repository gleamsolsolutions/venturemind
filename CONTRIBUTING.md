# Contributing to VentureMind

Thank you for considering a contribution to VentureMind. This project aims to make business and product research more rigorous, transparent, and useful for real decisions.

## Ways to contribute

- Improve an existing research engine or reference guide.
- Add a research method, checklist, or reusable report template.
- Fix unclear, duplicated, outdated, or contradictory instructions.
- Improve source evaluation, evidence handling, or verification.
- Report bugs, propose features, or improve documentation.

## Before you start

1. Search existing [Issues](https://github.com/gleamsolsolutions/venturemind/issues) and pull requests to avoid duplicate work.
2. For a substantial change, open an issue first and describe the problem, proposed solution, expected benefit, and possible trade-offs.
3. Keep changes focused. One pull request should normally address one coherent improvement.

## Contribution standards

### Evidence and accuracy
- Never invent sources, customer quotes, search volumes, prices, ratings, market sizes, or domain availability.
- Distinguish verified facts, estimates, assumptions, and hypotheses.
- Include source URLs and access dates for time-sensitive claims.
- State when a platform, dataset, or source could not be accessed.
- Do not treat search interest as proof of willingness to pay.
- Do not treat competitor presence alone as proof that a market is saturated.

### Research quality
- Prefer primary sources for product features, pricing, policies, and technical claims.
- Seek independent corroboration for important claims.
- Note geography, date, sample size, and methodology when relevant.
- Explain uncertainty and conflicting evidence.
- Include the strongest counterargument, not only evidence supporting the opportunity.

### Privacy, safety, and compliance
- Do not recommend bypassing authentication, paywalls, access controls, or platform restrictions.
- Do not collect or expose personal or sensitive information.
- Respect site terms, robots restrictions, API terms, and applicable laws.
- Flag legal, financial, privacy, security, and platform-policy issues rather than presenting guesses as legal advice.

### Writing and structure
- Use clear Markdown headings and concise language.
- Prefer reusable, topic-specific instructions over duplicating the main `SKILL.md`.
- Keep the main skill as the orchestrator; place specialist procedures in `engines/` and supporting standards in `references/`.
- Update the README or relevant documentation when user-facing behavior changes.

## Adding a research engine

A proposed engine should normally include:

1. **Purpose:** the decision or research problem it supports.
2. **Inputs:** what information the agent needs.
3. **Workflow:** ordered steps, including source discovery and verification.
4. **Evidence rules:** how to distinguish facts, estimates, and unknowns.
5. **Outputs:** expected tables, findings, and recommendations.
6. **Failure modes:** likely data gaps, bias, stale information, and tool limitations.
7. **Handoff:** how findings connect to the main VentureMind workflow.

Avoid making an engine dependent on a specific paid service unless the dependency is optional and clearly documented.

## Pull request process

1. Fork the repository.
2. Create a descriptive branch, for example `docs/improve-domain-method`.
3. Make the smallest complete change.
4. Check Markdown formatting, links, file names, and internal references.
5. Test any scripts or examples you changed.
6. Update relevant documentation.
7. Open a pull request against `main`.

A useful pull request description includes:
- **Problem:** what is missing or incorrect?
- **Change:** what did you change?
- **Evidence:** why is this change justified?
- **Validation:** how did you check it?
- **Limitations:** what remains uncertain?

## Reporting issues

When filing an issue, include:
- A clear title and expected behavior.
- The relevant file and section.
- Reproduction steps or a concrete example.
- Tool/model environment details where relevant.
- Sources or screenshots, with private information removed.

Do not include API keys, credentials, private customer data, or confidential business information.

## Code of conduct

Be respectful, constructive, and specific. Critique ideas and evidence, not people. Harassment, discrimination, personal attacks, and deliberate misinformation are not acceptable.

## License

By submitting a contribution, you agree that your contribution is provided under the repository's MIT License. You retain copyright to your contribution while granting the permissions described by that license.

Thank you for helping make VentureMind more reliable.
