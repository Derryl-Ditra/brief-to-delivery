---
name: brief-to-delivery
description: Experimental workflow for landing pages and other brief based deliverables. Use for scope control, human decisions, independent critique and reporting checks actually run.
---

# Brief to Delivery

A workflow for deliverable projects where quality failures cost trust: a landing page, a homepage plus campaign pages, a deck, a client proposal, a prototype, a report. Core use: building landing pages interactively with a steering decision-maker, for the familiar case where the page loads fine, looks fine and still converts nobody. It runs phases 0 through 7. It requests checks; it supplies no renderer, reviewer or release service and does not establish conversion gains.

## Start

1. Read reference/checklists.md and, for visual builds, reference/design-bar.md before building. examples/landing-page.md is a fictional starter brief and model first response; reference/trials.md states evidence limits and compatibility records.
2. Check capabilities, inputs and the release boundary silently. Report blockers, and report a NOT RUN check in chat only when it changes what this reply can claim; every other check result lives in the QC record (reference/checklists.md), not in chat. No capability inventory, inputs-read list, self-check summary or process narration in replies.
3. A downloaded or pasted package is not proof the host activated the skill; never claim activation. Never simulate an independent reviewer by reviewing your own work. Missing tools do not authorize a different audience, service, paid dependency or deployment: continue unblocked draft work, hold affected claims and any release.
4. Status, one word when asked or at a gate: DRAFT until required checks pass; SELF-CHECKED when every builder-runnable check passed but no independent reviewer was available, the honest ceiling without one; CHECKED only for a named saved candidate with listed evidence, independent findings and no missing required checks; RELEASED only after authorized delivery and inspection of the delivered version. SELF-CHECKED and CHECKED are not release permission. An edit reopens affected checks; status alone never certifies quality.
5. Keep replies short: a one-word status, the one consolidated open list, then the work. Evidence lives in the QC record, not in chat.
6. Scale process to the task. On a small private draft, process text (status, lists, decisions, checks) never exceeds the candidate text. Use one consolidated Open and missing list: blockers, gaps, open items and scope notes live there once, and no fact is restated in any other section. Candidate TBD fields refer to that list; they do not repeat it.
7. Close with one next step: the single smallest decision the owner can make to unblock the most, with your recommendation and its reason, in one or two sentences. No menus and no second question. When no decision is needed, you may instead offer one unprompted idea that stays inside the brief; when neither exists, omit the step.

## When to use

- The input is an open-ended brief, RFP, test assignment or stakeholder request with explicit and implicit asks.
- A human decision-maker reviews drafts and approves the final output.
- Small visible defects (a duplicate page number, an unsourced figure, a broken mobile layout) damage trust in the whole deliverable.
- For a landing page: visual and interaction quality decides whether anyone uses it, and the builder cannot see it the way a first-time visitor does.
- There is a real deadline; the best verified state at the deadline beats a perfect state after it.

## Phase 0: Extract the brief

1. Read the entire brief before proposing anything. Missing a section while claiming to have checked it destroys credibility.
2. Produce three lists: explicit asks; constraints and boundaries; blanks and contradictions.
3. Ask about a blank or contradiction when a wrong guess would be costly or visible to the audience. Otherwise proceed with the assumption labeled as an assumption. Never fill a load-bearing blank silently.
4. Check the requester's actual offerings and capabilities before recommending anything. A proposal for something they cannot deliver is useless.
5. Never recap the brief to the people who wrote it. Show a constraint only next to the decision it explains.

## Phase 1: Scope gate

1. Deliver what was asked, nothing more. Do not add speculative features or new business obligations. Testing applicable loading, empty, denied and error states of the agreed functionality is not permission to add features.
2. Separate what was discussed from what belongs in the deliverable. A question the decision-maker asked about is not automatically delivery scope.
3. Keep supplied facts, labeled assumptions, proposed terms and approved decisions distinct. Never turn an assumption into a constraint, and never call a term approved, locked, confirmed or settled without the decision-maker's explicit approval of that term. Nothing the brief does not supply goes into the candidate: no obligations, exclusions, delivery sequencing, timing anchors or feedback deadlines, and no inferred audience, event mechanics, document framing, greeting or acceptance step. If any of these is needed, propose it separately for approval, outside the client-facing candidate.
4. Unknown numbers: source them from the brief, materials or evidence first; if still unknown, mark them visibly TBD or UNVERIFIED; never invent a figure. A tag is honesty, not clearance: an unresolved consequential fact (price, recipient, commitment, legal term, decisive figure) blocks external delivery until resolved or removed with approval. A noncritical draft placeholder can remain.
5. Label what each figure measures. Look-alike metrics (for example exposure versus savings) are not interchangeable.
6. Never state a guarantee or promise that no source backs. When the plan changes mid-project, reconcile every file that still carries the old version: timelines, figures, terms.
7. Trial scope contract: record the agreed time budget, static versus clickable scope, one primary user action and exclusions. Fast/full presets are optional planning aids, not fixed promises; the actual brief wins. Track elapsed time, passes and completed journeys, and at the boundary report the state and cost of the next step. A time limit never waives a required check or permits release.

## Phase 2: Decision gate

1. Ask only about choices the brief leaves unresolved; never re-ask what the brief or a recorded answer already settles.
2. When a decision-maker is available and a choice changes the deliverable, batch open decisions as 2-3 options each plus one clear recommendation, asked before the build starts. The format makes the unresolved choice explicit; it does not guarantee a faster decision. In a one-shot exchange with no decision-maker, rule 5 of this phase governs instead: state the recommended option as a labeled assumption inline and render no decision menus. If the decision-maker prefers, ask one question at a time, then recap all answers into a decisions file before building.
3. Never put words in the decision-maker's mouth: a belief, doubt or position appears in their voice only if they said it. Show the wording first.
4. "Just build it" covers execution within the agreed scope; structural changes beyond it still get review first. Report caveats; do not reopen settled choices.
5. With no decision-maker available, build on labeled assumptions, hold any consequential fact and any release, and report the assumptions first. Silence is not approval.
6. Review before structural changes; a narrow copy fix executes only when that specific change was authorized. There is no blanket permission to edit.

## Phase 3: Content checkpoint

1. Freeze approved content as a timestamped snapshot before any design pass. Never overwrite the checkpoint. Name working files CANDIDATE until the final checks pass; never certify readiness early. Fence the candidate with START OF CANDIDATE and END OF CANDIDATE markers. Inside the fence goes only deliverable content plus bracketed TBD placeholders: no open items, no notes, no assumptions, no meta text. The reader must be able to lift the fenced block with no cleanup beyond filling TBDs.
2. While the decision-maker is editing, do not rewrite. Answer questions and apply requested changes, but never overwrite their edits.

## Phase 4: Draft, content and design rules

1. Lead with the decision: the choice, the argument, why it stays within the brief, then the plan.
2. Thirty-second rule: one clear goal per slide, screen or section; cut what cannot be understood in 30 seconds.
3. Hierarchy first: a visible focal point, summary before detail, no flat wall of equal-weight information. Wireframe in black and white until the hierarchy works unless the brief fixes or supplies the layout (record N/A with that reason); color and branding come after hierarchy, a neutral base is an option, not a mandatory theme.
4. Plain language for the real audience; clear, not smart. Keep transformations believable: adjacent steps, not leaps.
5. Strip internal and draft-sounding copy before delivery: keep the honesty, drop the process commentary. Frame the reusable method (templates, rules, measurement tools) separately from case-specific content.
6. When handed a method, reference or example to follow, apply it and state which parts you used and which you did not, before being asked. Reading or citing a method is not applying it.

### Visual builds: landing pages and page families

For screens (landing pages, page families, dashboards, maps, small tools), apply the functional screen rules and the design bar in reference/design-bar.md before layout: inspect references, record a product-specific idea, build purposeful detail, then score the exact rendered candidate. Its trial taste rubric is separate from functional QA; report blocked references and self-check versus independent review honestly.

## Phase 5: Independent critique

1. Before the decision-maker reviews, run a fresh-eyes attack pass with a separate reviewer, agent or session. Feed the reviewer the original brief and the decision-maker's own feedback where permitted, never a summary. Hunt broken logic, scope drift, filler, generic AI-sounding output.
2. Verify every figure and name against its source. Anything unsourced gets a visible TBD or UNVERIFIED tag, or comes out.
3. Timebox the critique. Fix or explicitly reject each finding with a reason.

## Phase 6: Verify before delivery

1. Check the final saved artifact, not an earlier state. QA reported on stale output is worse than no QA. If published, verify the live bytes from the public URL against the intended build.
2. Run the pre-delivery QC checklist in reference/checklists.md in full and in order. Technical QA is not editorial readiness; they are separate passes.
3. Each change request gets a fresh review of the artifact as it is now, not a rubber stamp of the last pass. Narrow changes stay narrow: only the authorized change, with its blast radius re-verified. No incidental improvements mid-review.
4. Report exactly what was inspected and what was not. A readiness claim covers only the checks that actually ran; anything unrunnable is NOT RUN with the reason.

## Phase 7: Deliver, clean up, capture lessons

1. Folder structure: final deliverables, handoff, sources (inputs, untouched), drafts. Keep the approved checkpoint plus one working draft; archive extra drafts, delete only with the owner's permission.
2. Meet hard deadlines with the best verified state; do not chase perfection past the deadline. If approval never landed, hand it over as a draft visibly marked not yet approved. Silence is never approval; publishing, sending or sharing externally always needs explicit approval.
3. Respect account boundaries the owner sets: personal projects on personal accounts, work on work accounts.
4. After delivery, write a lessons file (template in reference/checklists.md): each mistake made and the rule that prevents it next time. Save it with the project and read it before starting similar work.

## Failure modes this workflow targets

- Claiming "done" or "ready" from assumed state instead of verified state.
- Scope creep from treating discussion topics as delivery requirements.
- Invented figures, invented doubts, invented guarantees.
- QA reported on files that changed after the check.
- Design work overwriting uncheckpointed approved content.
- Reopening settled decisions with new style questions.
- Asking about choices the brief already settles, or asking open questions without a recommendation.
- Citing a process or checklist without actually running it end to end.
- A mobile layout that is a desktop port with no phone-native logic.
- Reporting speed or compatibility without measuring it.
- Icons, labels or buttons whose meaning does not match what they do.
- Padding replies with capability inventories, status speeches and process narration.
- Decision menus rendered for a one-shot brief with no decision-maker.
- The same missing fact repeated across blockers, gaps, candidate fields and checks.
- A next step that grows back into a menu, a second open question or a process paragraph.
- Inferred audience, mechanics or framing inside the candidate fence.

See reference/checklists.md for decision questions, the QC record and the lessons template. See reference/trials.md for evidence limits. No wording change alone proves these failure modes are fixed.
