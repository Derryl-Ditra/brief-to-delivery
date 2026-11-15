---
name: brief-to-delivery
description: Interactive landing page builder workflow. Turn a brief into a verified landing page, homepage plus campaign pages, deck, document, prototype, or proposal, with scope control, human approval, independent critique, and final checks. Built for pages that get visits but no signups.
---

# Brief to Delivery

A workflow for deliverable projects where quality failures cost trust: a landing page, a homepage plus campaign pages for different traffic, a deck for a review panel, a client proposal, a prototype, a report. Its core use is building landing pages interactively with a steering decision-maker, for the familiar case where the page loads fine, looks fine, and still converts nobody. Distilled from real deliverable projects, including the mistakes made along the way and the rules that fixed them.

The workflow runs in eight phases, 0 through 7.

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

1. Deliver what was asked, nothing more. No edge cases or "maybe" scenarios the requester did not ask for.
2. Separate what was discussed from what belongs in the deliverable. A question the decision-maker asked about is not automatically delivery scope.
3. Keep supplied facts, working assumptions, proposed terms, and approved decisions distinct. Label assumptions where they appear; never turn an assumption into a constraint or call a term approved, locked, confirmed, or settled without the decision-maker's explicit approval of that term. Do not add client obligations, exclusions, delivery sequencing, timing anchors, or feedback deadlines that the brief does not supply. If one is needed, propose it separately for approval, outside the client-facing candidate.
4. Unknown numbers: first try to source them from the brief, the provided materials, or other available evidence. If they stay unknown, mark them visibly as TBD or UNVERIFIED. Never invent a figure to fill a gap. A tag is honesty, not clearance: an unresolved consequential fact (a price, recipient, commitment, legal term, or decisive figure) blocks external delivery of the affected deliverable until it is resolved or removed with approval; a noncritical draft placeholder can remain.
5. Label what each figure measures. Two metrics that look alike (for example exposure versus savings) are not interchangeable.
6. Never state a guarantee or promise that no source backs.
7. When the plan changes mid-project, reconcile every file that still carries the old version: timelines, figures, terms.

## Phase 2: Decision gate

1. Ask only about choices the brief leaves unresolved. Never re-ask what the brief or an earlier recorded answer already settles; re-asking settled questions wastes the decision-maker's time.
2. Batch open decisions as 2-3 options each plus one clear recommendation, and ask before the build starts, not after a draft exists. Decision-makers close fast in this format.
3. If the decision-maker prefers, ask one question at a time, then recap all answers into a decisions file before building.
4. Never put words in the decision-maker's mouth. A belief, doubt, or position appears in their voice only if they said it. Show the wording first.
5. When the decision-maker says "just build it", build it. That covers execution within the agreed scope; a structural change beyond that scope still gets review first. Report caveats; do not reopen settled choices.
6. Get review before structural changes. Narrow copy fixes execute directly only when that specific change was authorized. There is no blanket permission to edit.

## Phase 3: Content checkpoint

1. Freeze approved content as a timestamped snapshot before any design pass. Never overwrite the checkpoint.
2. Name working files CANDIDATE until the final checks pass. Never certify readiness early.
3. While the decision-maker is editing, do not rewrite. Answer questions and apply requested changes, but never overwrite their edits.

## Phase 4: Draft, content and design rules

1. Lead with the decision: the choice, the argument, why it stays within the brief, then the plan.
2. Thirty-second rule: one clear goal per slide, screen, or section. If it cannot be understood in 30 seconds, cut it down.
3. Hierarchy first: a visible focal point, summary stats before detail, records as a second layer. No flat wall of equal-weight information.
4. Wireframe in black and white until the hierarchy works, unless the brief says otherwise. Color and branding come last, accents stay small on a neutral base.
5. Plain language for the real audience. Cut jargon and clever phrasing. Be clear, not smart.
6. Keep transformations believable: adjacent steps, not leaps the audience will not buy.
7. Strip internal and draft-sounding copy before delivery. Keep the honesty, drop the process commentary.
8. Frame the reusable method (templates, rules, measurement tools) separately from case-specific content, so the work transfers.
9. When the decision-maker hands you a method, reference, or example to follow, apply it and state which parts you used and which you did not - before being asked. Reading or citing a method is not applying it.

### Visual builds: landing pages and page families

These rules apply when the deliverable is a screen: a landing page, a homepage with campaign pages for ads or different traffic, a dashboard, a map, a small tool. They come from a real project where the decision-maker rejected round after round of visual work; each rule is a rejection that became a fix.

1. Functional over decorative. Every element does a job. A beautiful screen that is hard to use fails, and passing a pixel checklist does not mean the screen passes the decision-maker's taste.
2. Mobile is its own design, not a shrunken desktop. Navigation, sheets, gestures, and reach zones need phone-native patterns. If the mobile layout is a desktop port, redo it.
3. One dominant primary action per screen. No flat row of equal-weight buttons; the main action (book, buy, share, directions) is visibly the biggest and stays reachable, for example in a sticky bar.
4. Icons must match their meaning. A wrong icon is a defect, not a style choice. For third-party links use the current official brand marks in brand colors, icon-only when the meaning is obvious; drop redundant text labels.
5. Reuse the product's existing elements. Do not invent a second visual language for a share card, a preview, or a new page inside the same product.
6. Test with real content, not placeholders: the longest real name, the minimum and maximum item counts, empty, denied, and error states, and tap targets large enough to avoid misclicks on a phone.
7. Parity across breakpoints: what mobile has, desktop has, and the reverse, unless the brief says otherwise.
8. Speed is part of the deliverable. Measure first content and full readiness under throttled mobile and report the measured numbers. Never claim "fast" without a measurement, and never present a simulator number as a real-device number.
9. Share and preview surfaces are screens too. The shared-link preview card and the share text are designed, written, and inspected on each target channel, including in-app browsers that strip native features (no share sheet, blocked location). Provide fallbacks: copy link, open in a full browser.
10. When the decision-maker rejects a visual direction, extract the rule from the rejection and record it, so the next round starts from the learned constraint instead of repeating the guess.
11. Multi-page builds share one design system. A homepage plus several landing pages for ads or different traffic reuse the same header, footer, components, and styles; only the message changes per audience. Inspect every page, not just the homepage, and give each page its own share preview.

## Phase 5: Independent critique

1. Before the decision-maker reviews, run a fresh-eyes attack pass with a separate reviewer, agent, or session. Feed the reviewer the original brief and the decision-maker's own feedback where permitted, never a summary of them. Hunt broken logic, scope drift, filler, generic AI-sounding output.
2. Verify every figure and name against its source. Anything without a source gets a visible TBD or UNVERIFIED tag, or comes out.
3. Timebox the critique. Fix or explicitly reject each finding with a reason.

## Phase 6: Verify before delivery

1. Check the final saved artifact, not an earlier state. QA reported on stale output is worse than no QA.
2. Enumerate, do not spot-check. List every visible string, slide, or screen and read each one semantically. A TODO search misses draft tone.
3. Look at pixels, not just markup. Render and inspect at every target size for overflow, overlap, clipping, and orphaned text. For web builds also inspect the shared-link preview and open the page in the target channels' in-app browsers, which behave differently from full browsers.
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

## Failure modes this workflow prevents

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

See reference/checklists.md for the decision-question format, the pre-delivery QC checklist, and the lessons-file template.
