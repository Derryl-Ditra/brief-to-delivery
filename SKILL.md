---
name: brief-to-delivery
description: Experimental workflow for landing pages and other brief based deliverables. Use for scope control, human decisions, independent critique and reporting checks actually run.
---

# Brief to Delivery

A workflow for deliverable projects where quality failures cost trust: a landing page, a homepage plus campaign pages for different traffic, a deck for a review panel, a client proposal, a prototype, a report. Its core use is building landing pages interactively with a steering decision-maker, for the familiar case where the page loads fine, looks fine, and still converts nobody. Distilled from real deliverable projects, including mistakes observed along the way and safeguards proposed in response.

The workflow runs in eight phases, 0 through 7. It requests checks; it does not supply a renderer, reviewer or release service, and does not establish conversion gains.

## Start: capability and status preflight

Before building, read reference/checklists.md and report:

1. Inputs actually read, skill version or commit, explicit asks, settled decisions and unresolved blockers. A downloaded file is not proof the host activated the skill.
2. Capabilities available now: source access, file creation, rendering, browser interaction, independent reviewer, performance measurement and permitted release route. State unavailable checks as NOT RUN with a reason. Never simulate an independent reviewer by reviewing your own work.
3. Scope and release boundary. Missing tools do not authorize a different audience, service, paid dependency or deployment. Continue unblocked draft work; hold affected claims or release.
4. Candidate status: DRAFT until required checks pass; SELF-CHECKED when every required check that the builder can run has passed but no independent reviewer was available (independent review NOT RUN; this is the honest ceiling without a reviewer); CHECKED only for an identified saved candidate with listed evidence, an independent reviewer's findings and no required checks missing; RELEASED only after authorized delivery and inspection of the actual delivered version. SELF-CHECKED and CHECKED are not permission to release. A changed candidate reopens affected checks; release status alone never certifies quality.

Use examples/landing-page.md for a fictional starter brief and expected first response. Use reference/trials.md for repeatable cases, evidence limits and dated compatibility records.

## When to use

- The input is an open-ended brief, RFP, test assignment, or stakeholder request with explicit and implicit asks.
- A human decision-maker reviews drafts and approves the final output.
- Small visible defects (a duplicate page number, an unsourced figure, a broken mobile layout) damage trust in the whole deliverable.
- For a landing page: the visual and interaction quality decides whether anyone uses it, and the builder cannot see the result the way a first-time visitor does.
- There is a real deadline and the best verified state at the deadline beats a perfect state after it.

## Phase 0: Extract the brief

1. Read the entire brief before proposing anything. Missing a section while claiming to have checked it destroys credibility.
2. Produce three lists: explicit asks, constraints and boundaries, blanks and contradictions.
3. Bring a blank or contradiction back as a question when a wrong guess would be costly or visible to the audience. Otherwise proceed with the assumption labeled as an assumption. Never fill a load-bearing blank silently.
4. Check the requester's actual offerings and capabilities before recommending anything. A proposal for something they cannot deliver is useless.
5. In the deliverable, never recap the brief to the people who wrote it. Show a constraint only next to the decision it explains.

## Phase 1: Scope gate

1. Deliver what was asked, nothing more. Do not add speculative features or new business obligations. Test applicable loading, empty, denied and error states of the agreed functionality; these checks are not permission to add features.
2. Separate what was discussed from what belongs in the deliverable. A question the decision-maker asked about is not automatically delivery scope.
3. Keep supplied facts, working assumptions, proposed terms, and approved decisions distinct. Label assumptions where they appear; never turn an assumption into a constraint or call a term approved, locked, confirmed, or settled without the decision-maker's explicit approval of that term. Do not add client obligations, exclusions, delivery sequencing, timing anchors, or feedback deadlines that the brief does not supply. If one is needed, propose it separately for approval, outside the client-facing candidate.
4. Unknown numbers: first try to source them from the brief, the provided materials, or other available evidence. If they stay unknown, mark them visibly as TBD or UNVERIFIED. Never invent a figure to fill a gap. A tag is honesty, not clearance: an unresolved consequential fact (a price, recipient, commitment, legal term, or decisive figure) blocks external delivery of the affected deliverable until it is resolved or removed with approval; a noncritical draft placeholder can remain.
5. Label what each figure measures. Two metrics that look alike (for example exposure versus savings) are not interchangeable.
6. Never state a guarantee or promise that no source backs.
7. When the plan changes mid-project, reconcile every file that still carries the old version: timelines, figures, terms.

## Phase 2: Decision gate

1. Ask only about choices the brief leaves unresolved. Never re-ask what the brief or an earlier recorded answer already settles; re-asking settled questions wastes the decision-maker's time.
2. Batch open decisions as 2-3 options each plus one clear recommendation, and ask before the build starts, not after a draft exists. This format is intended to make the unresolved choice explicit; it does not guarantee a faster decision.
3. If the decision-maker prefers, ask one question at a time, then recap all answers into a decisions file before building.
4. Never put words in the decision-maker's mouth. A belief, doubt, or position appears in their voice only if they said it. Show the wording first.
5. When the decision-maker says "just build it", build it. That covers execution within the agreed scope; a structural change beyond that scope still gets review first. Report caveats; do not reopen settled choices.
6. When no decision-maker can answer, list each open choice as a labeled assumption, build the draft on the stated assumptions, hold any consequential fact and any release, and report the assumptions first. Silence is not approval.
7. Get review before structural changes. Narrow copy fixes execute directly only when that specific change was authorized. There is no blanket permission to edit.

## Phase 3: Content checkpoint

1. Freeze approved content as a timestamped snapshot before any design pass. Never overwrite the checkpoint.
2. Name working files CANDIDATE until the final checks pass. Never certify readiness early.
3. While the decision-maker is editing, do not rewrite. Answer questions and apply requested changes, but never overwrite their edits.

## Phase 4: Draft, content and design rules

1. Lead with the decision: the choice, the argument, why it stays within the brief, then the plan.
2. Thirty-second rule: one clear goal per slide, screen, or section. If it cannot be understood in 30 seconds, cut it down.
3. Hierarchy first: a visible focal point, summary stats before detail, records as a second layer. No flat wall of equal-weight information.
4. Wireframe in black and white until the hierarchy works, unless the brief says otherwise. Skip this for a single page whose layout the brief fixes or already supplies, and record N/A with that reason. Color and branding come last, accents stay small on a neutral base.
5. Plain language for the real audience. Cut jargon and clever phrasing. Be clear, not smart.
6. Keep transformations believable: adjacent steps, not leaps the audience will not buy.
7. Strip internal and draft-sounding copy before delivery. Keep the honesty, drop the process commentary.
8. Frame the reusable method (templates, rules, measurement tools) separately from case-specific content, so the work transfers.
9. When the decision-maker hands you a method, reference, or example to follow, apply it and state which parts you used and which you did not, before being asked. Reading or citing a method is not applying it.

### Visual builds: landing pages and page families

These rules apply when the deliverable is a screen: a landing page, a homepage with campaign pages for ads or different traffic, a dashboard, a map, a small tool. They were distilled from project feedback and proposed safeguards. Their provenance is not evidence that they prevent defects in every build.

1. Functional over decorative. Every element does a job. A beautiful screen that is hard to use fails, and passing a pixel checklist does not mean the screen passes the decision-maker's taste.
2. Mobile is its own design, not a shrunken desktop. Navigation, sheets, gestures, and reach zones need phone-native patterns. If the mobile layout is a desktop port, redo it.
3. One dominant primary action per screen. No flat row of equal-weight buttons; the main action (book, buy, share, directions) is visibly the biggest and stays reachable, for example in a sticky bar.
4. Icons must match their meaning. A wrong icon is a defect, not a style choice. For third party links, use official marks only when permitted and verified. Every link and icon control needs a meaningful accessible name. Use visible text when an icon is ambiguous; never remove a label just for appearance.
5. Reuse the product's existing elements. Do not invent a second visual language for a share card, a preview, or a new page inside the same product.
6. Test representative content: the longest expected name, minimum and maximum item counts, applicable loading, empty, denied and error states, and tap targets large enough for phone use. For fictional demos, label invented content and generated assets; never present them as real customer proof or product photography.
7. Functional parity across breakpoints: preserve the same essential information, actions and outcomes unless the brief says otherwise. Layout, navigation pattern and placement may differ. Record any intentional omission and its approved reason.
8. Speed is part of the deliverable. Report First Contentful Paint (FCP) and a defined readiness milestone, such as hero visible plus primary control usable. Name the tested URL or candidate, browser, viewport, cache state, network and CPU settings, sample count and result range. Define the milestone before measuring. For a local file or private demo with no network, report only local numbers labeled "local, unthrottled, not device evidence", or mark timing NOT RUN. If instrumentation is unavailable, mark timing NOT RUN. Never claim "fast" without measurement or present simulation as real device evidence.
9. For authorized share surfaces, design and inspect the link preview card and share text on each configured target channel, including applicable in app browsers. Check necessary fallbacks such as copy link or open in a full browser. Record N/A with the scope reason for a private local demo with no sharing; do not publish just to run this check.
10. Generated assets: use one shared style description for every generated image so the set looks like one brand, and keep the prompts with the project. Label generated images as such unless real photography is supplied. Do not depict a real person or copy a real brand. Give each informative image alt text, and compress images to web size before delivery.
11. When the decision-maker rejects a visual direction, extract the rule from the rejection and record it, so the next round starts from the learned constraint instead of repeating the guess.
12. Multi-page builds share one design system. A homepage plus several landing pages for ads or different traffic reuse the same header, footer, components, and styles; only the message changes per audience. Inspect every page, not just the homepage. Give each page its own share preview only when sharing is authorized and part of scope; record N/A for a private local demo with no sharing.

## Phase 5: Independent critique

1. Before the decision-maker reviews, run a fresh-eyes attack pass with a separate reviewer, agent, or session. Feed the reviewer the original brief and the decision-maker's own feedback where permitted, never a summary of them. Hunt broken logic, scope drift, filler, generic AI-sounding output.
2. Verify every figure and name against its source. Anything without a source gets a visible TBD or UNVERIFIED tag, or comes out.
3. Timebox the critique. Fix or explicitly reject each finding with a reason.

## Phase 6: Verify before delivery

1. Check the final saved artifact, not an earlier state. QA reported on stale output is worse than no QA.
2. Enumerate, do not spot-check. List every visible string, slide, or screen and read each one semantically. A TODO search misses draft tone.
3. Look at pixels, not just markup. Render and inspect at 320, 390, 768 and 1440 CSS pixels (or the sizes the brief names) for overflow, overlap, clipping, and orphaned text. For web builds with authorized share surfaces and configured target channels, also inspect the link preview and applicable in app browsers. Record these channel checks as N/A with the scope reason for a private local demo with no sharing; do not add a release to make them possible.
4. Run one dedicated pass for mechanical defects: page numbers, repeated headers and footers, cross-references, and links after any renumbering.
5. Technical QA is not editorial readiness. A build that passes every test can still read like internal notes. These are two separate passes.
6. If the deliverable is published, verify the live bytes from the public URL against the intended build.
7. Each new change request gets a fresh review of the artifact as it is now, not a rubber stamp of the last pass.
8. Narrow changes stay narrow. Make only the authorized change and re-verify its blast radius. No incidental improvements mid-review.
9. Report exactly what was inspected and what was not.
10. If a check cannot be run (no independent reviewer, no renderer, no source or live access), mark it NOT RUN with the reason. A readiness claim covers only the checks that actually ran.

## Phase 7: Deliver, clean up, capture lessons

1. Folder structure: final deliverables, handoff, sources (inputs, untouched), drafts. Keep the approved checkpoint plus one working draft; archive extra drafts, delete only with the owner's permission.
2. Meet hard deadlines with the best verified state. Do not chase perfection past the deadline. If approval never landed, hand the best verified state to the decision-maker as a draft visibly marked not yet approved; silence is never approval. Publishing, sending, or sharing it with an external audience always needs explicit approval.
3. Respect account boundaries the owner sets: personal projects on personal accounts, work on work accounts.
4. After delivery, write a lessons file: each mistake made and the rule that prevents it next time. Save it with the project and read it before starting similar work.

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
- Icons, labels, or buttons whose meaning does not match what they do.

See reference/checklists.md for decision questions, the QC record and lessons template. See reference/trials.md for test cases and evidence limits. No wording change alone proves these failure modes are fixed.
