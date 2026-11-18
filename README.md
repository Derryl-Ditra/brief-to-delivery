# Brief to Delivery

An experimental workflow for turning a brief into a landing page or another reviewed deliverable. It separates scope, decisions, content, critique and final checks.

This is an instruction package, not a runnable website template. It bundles no app, renderer, model, independent reviewer or publishing service. You need an agent host that reads skills; terminal examples below also require Git. No API keys or runtime dependencies are bundled.

## Status: experimental beta

Human review is required before external release. This package does not guarantee source fidelity, legal suitability, conversion gains or reliable model behavior.

Historical reports describe two single run proposal scenarios with mixed results. They do not prove the current landing page workflow works. The trial design bar adds reference study, a brief-specific visual idea, a rendered taste rubric and separate functional proof. It has not established conversion gains or general design superiority. See [trial records](reference/trials.md) for the limits and dated compatibility table. A model saying it checked something is not proof.

## Quickstart

Choose one host. These paths follow official documentation read on 15 November 2026; they are not runtime compatibility certifications. Commands below create a new folder and do not update an existing installation. Stop and inspect an existing copy rather than overwriting it.

### Claude Code, local terminal

```sh
mkdir -p ~/.claude/skills
git clone https://github.com/Derryl-Ditra/brief-to-delivery.git ~/.claude/skills/brief-to-delivery
```

Start Claude Code in your working project. Enter `/brief-to-delivery` with your brief, or explicitly ask it to use `brief-to-delivery`. If the command is absent, restart the session and inspect the installed `SKILL.md`; do not assume activation. Local personal skills are not the same as account skills for cloud sessions.

### Antigravity IDE

```sh
mkdir -p ~/.gemini/config/skills
git clone https://github.com/Derryl-Ditra/brief-to-delivery.git ~/.gemini/config/skills/brief-to-delivery
```

Confirm the skill is listed in the host's skills or customization view. In a new conversation, ask it to use `brief-to-delivery` and read `SKILL.md` plus its companion references. If it is not listed, check the host documentation and location before continuing. The documented legacy global path is `~/.gemini/antigravity/skills/brief-to-delivery`; choose one location, not both.

### Claude web app

Follow the [official custom skill guide](https://support.claude.com/en/articles/12512198-how-to-create-custom-skills) to upload a ZIP containing the skill folder and enable it. Feature availability depends on account and settings. The folder must contain `SKILL.md`, `reference/` and `examples/`; confirm the uploaded skill appears before using it. Actual upload and activation have not been verified here.

### First request

Use the complete [fictional landing page brief](examples/landing-page.md). It includes an example first response, not a claimed model output.

> Use brief-to-delivery. Read examples/landing-page.md and reference/checklists.md. Build the private fictional demo described in the brief. First report inputs read, scope, settled choices, blockers, available capabilities and checks you cannot run. No external publishing, messages, payments or data collection. Do not claim installed, tested or ready from reading files alone.

For your own project, replace the fictional brief with your original source material and constraints. Review consequential missing facts before build or release. `TBD` is not approval to publish.

## Included files

1. [SKILL.md](SKILL.md): preflight and phases 0 through 7.
2. [reference/checklists.md](reference/checklists.md): decisions, QC record and lessons template.
3. [examples/landing-page.md](examples/landing-page.md): fictional brief and example first response.
4. [reference/trials.md](reference/trials.md): dated evidence limits and results. Repeatable cases are kept private so trials stay uncontaminated.
5. [reference/design-bar.md](reference/design-bar.md): direction, motion, rendered rubric and optional upstream design references. References are not bundled or installed dependencies.

## Status language

DRAFT means required checks remain. SELF-CHECKED means every check the builder could run passed but no independent reviewer was available. CHECKED means named checks passed, including independent review, for the identified candidate and no required check is missing; it is not release permission. RELEASED means authorized delivery happened and the delivered version was inspected. Always list what ran and what did not. A missing required check blocks CHECKED status, not independent draft work.

## Documentation sources

Read on 15 November 2026, not a claim of actual host testing:

1. [Claude Code skills](https://code.claude.com/docs/en/skills): personal folder and invocation.
2. [Antigravity skills](https://antigravity.google/docs/skills): IDE locations and Customizations.
3. [Claude custom skills](https://support.claude.com/en/articles/12512198-how-to-create-custom-skills): upload guidance and 200 character description limit.
4. [Agent Skills specification](https://agentskills.io/specification): metadata and 1024 character description limit.

The description is kept below 200 characters to fit both published limits. That is a packaging choice, not proof of acceptance by a host.

## Provenance and contributing

The scope workflow began as the v2 package dated 3 November 2026. A visual workflow was added in November 2026. This revision adds setup guidance, a fictional starter, capability reporting and narrower wording. It includes no raw private briefs, conversations or account material.

See [CONTRIBUTING.md](CONTRIBUTING.md) for safe examples and the contribution process. Maintainer review is required before merge. Licensed under [MIT](LICENSE), without warranty.

