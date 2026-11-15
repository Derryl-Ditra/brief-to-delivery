# Brief to Delivery

An experimental, human-reviewed workflow for building landing pages (a homepage plus campaign pages) and other brief-based deliverables, with scope gates, independent critique and final checks.

It separates scope, open decisions, content checkpoints, critique and final checks. It is a set of instructions and a checklist, not an autonomous delivery service.

## Status: experimental beta

This is **not a production-grade reliability guarantee**. In the latest two user-run Claude scenarios, supplied quantities and missing-price safeguards held. One proposal still added an acceptance/signature mechanism that the brief did not supply. Another assumed an unspecified supplier role. These failures remain unresolved in the package here.

Only two different scenarios were completed once each. Repeat consistency, broad model compatibility and reliable improvement over a baseline have not been established. Keep human review before external release.

## Files

- `SKILL.md`: the workflow, phases 0 through 7.
- `reference/checklists.md`: decision format, final-check checklist and a scope-boundary example.

No scripts, API keys, dependencies or external services are bundled.

## Use it

1. Put this folder into the skill location supported by your agent, or ZIP the folder and import it using the platform's custom-skill interface.
2. For Claude's web app, follow the [official custom-skill instructions](https://support.claude.com/en/articles/12512198-how-to-create-custom-skills). Feature availability depends on your account and settings.
3. For coding agents that read skill files (for example Claude Code), place this folder in the skills directory your tool reads and name the skill in your prompt. Check your tool's current documentation; skill locations and conventions change.
4. Provide the original brief, constraints and source material. Ask for a private candidate and name what may not be sent, published or changed.
5. Review assumptions and consequential missing facts before external delivery. Do not treat a `TBD` label as approval to publish.
6. Ask the agent to state which checks actually ran. Rendering, source access and independent review need real capabilities in the environment; otherwise they must be reported as `NOT RUN`.

Example request:

> Use brief-to-delivery. Draft a private candidate proposal for four newsletter drafts in two weeks, one revision per draft. No price has been supplied. Do not invent one, send anything or publish. Identify what can be drafted now and what prevents external release.

This is a usage example, not a claim that every run will obey it.

## What it does not do

- Guarantee source fidelity, correct commercial terms or legal suitability.
- Supply a renderer, independent reviewer, source integrations or a publishing service.
- Replace the user's approval, an agent's own permission controls, or artifact inspection.
- Prove that Claude, Gemini or another model is better than another.

The workflow asks for a separate critique and visual QA. A model claiming those happened is not evidence that they ran.

## Version and provenance

The workflow files are the v2 scope package dated 3 November 2026, plus a visual-build section for landing pages and page families added in November 2026. The v2 scope rules were exercised in the two test reviews above; the visual-build section is distilled from a real shipped project and has not been through scripted model tests. README and repository packaging are separate additions. No raw conversations, private briefs or account material are included.

## Contributing

Bug reports, clearer documentation and narrow fixes are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) for the fork-and-pull-request process and safe example requirements. Maintainer review is required before merge.

## Usage rights

Licensed under the [MIT License](LICENSE). You may use, modify and redistribute it, including commercially, while preserving the copyright and license notice. It is provided without warranty.
