# Design bar for landing pages

Experimental design guidance. Use with the scope, source and release gates in SKILL.md, not instead of them. This is a review method, not a promise of awards, conversion gains or production readiness. A high visual score cannot waive a broken journey or an unsupported claim.

## Before layout

1. Inspect two or three real reference sites for the level of detail to reach. Prefer references supplied by the decision-maker, then relevant award galleries or strong work in the same field. Record the URL, date, what actually loaded and one technique worth studying: composition, type, color, motion or pacing. Borrow a technique, not a site's layout, copy, assets or identity.
2. A blocked page is a blocked source. A supplied teardown can inform a draft, but label it as a supplied teardown, not live-site inspection. Do not score reference parity against a site nobody could inspect; mark that criterion NOT RUN and hold the full design-pass claim.
3. Write a one-sentence visual idea tied to this product and audience. If any brand could replace the name unchanged, try another direction. Keep the idea, references and intended primary action in the decisions file.
4. Compare a different composition before choosing the familiar split hero. A split hero is valid when it fits; cream backgrounds and serif type are not defects by themselves.
5. For unrelated concepts in one review, vary palette, type and composition to fit each brief, rather than reskinning one template. Pages inside one real product still share its design system. A concept's copy can be very short, but never cut essential product facts, accessible labels or required legal text for visual effect.

## Build the idea, not a pile of effects

- The idea must be visible in the first viewport and recur in at least one later section. It should explain the composition, not sit on top as decoration.
- Adapt stock patterns to the content. Challenge interchangeable card rows and headings that survive a brand swap. Existing product conventions and familiar usable controls remain valid; distinctiveness is not permission to replace them with puzzles.
- Include at least three intentional craft details that support the idea, such as type composition, meaningful asymmetry, structural imagery or a considered transition. Do not add effects just to reach a count.
- Animation and custom JavaScript may support the idea within the agreed stack. Keep code, fonts and assets local by default; an external service or library needs the brief's or decision-maker's permission. Do not add paid services or telemetry.
- Respect reduced-motion preferences. With motion disabled, preserve information, actions and outcomes. Touch and keyboard users must reach anything exposed on hover.
- Define the readiness milestone and motion's performance budget before building. Measure with motion on, using the timing record in SKILL.md. If motion exceeds the agreed target, reduce the motion, not the test. No fabricated live counters, activity or data.
- Keep actions in normal flow on static concept pages. A sticky action in a functional product needs a usability reason and checks for covered content, keyboard focus and narrow-screen behavior; do not add it as a default visual pattern.

## Render, critique, repeat

Inspect the first screen and full page at the required widths. Check type collisions, decoration crossing letters, balance, dense sections and the closing section. Check text on every colored surface: at least 4.5:1 for normal text and 3:1 for large text. Inspect actual pixels as well as computed styles; ratios alone do not prove readability. Fix, rerender and recheck the changed candidate.

Use the rubric below as a trial internal bar. Score the exact saved candidate against its recorded idea and inspected references. Score self-checks and independent review separately. Preserve disagreements rather than relabeling a self-score as validation.

| Criterion | 0 | 1 | 2 |
| --- | --- | --- | --- |
| Idea fidelity | No visible idea | First viewport only | First viewport and a later section |
| Reference level | Clearly below the inspected references | Some comparable detail | Comparable intentional detail without copying |
| Template tells | Three or more interchangeable patterns | One or two | None left unadapted without a usability or system reason |
| Craft details | None | One or two | At least three purposeful details |
| Restraint | Effects hurt reading or use | Some unjustified detail | Every effect earns its place; reduced motion preserves the journey |

A full rubric pass needs at least 8/10, a 2 each for idea fidelity, template tells and craft details, and no zero. Any NOT RUN criterion prevents a full pass. Attach phone and desktop first-screen and full-page renders for the identified candidate, plus the reviewer's findings. The score is a recorded judgment, not a measured user outcome. Passing it does not replace functional, content, accessibility or release checks.

For a claim that one method beats another, give a fresh reviewer anonymous candidates and the same original brief. Record candidate versions, rubric, reviewer identity/count and disagreements. Audit brief identity before accepting the score. One judge cannot establish general superiority.

If publication is authorized, open the delivered URL and inspect the actual hosted first screen and full page at phone and desktop widths before reporting delivery. Local screenshots are not hosted-page evidence. For a multi-concept review, prefer one navigable review artifact and one link when the requested format permits; that does not authorize hosting or changing its audience.

## Functional screen rules

Apply to every screen build (landing page, page family, dashboard, map, small tool), with the design bar above. Distilled from project feedback and proposed safeguards; that provenance is not evidence the rules prevent defects in every build.

1. Functional over decorative: every element does a job; a beautiful screen that is hard to use fails, and a pixel-checklist pass is not the decision-maker's taste bar.
2. Mobile is its own design, not a shrunken desktop: phone-native navigation, sheets, gestures and reach zones; a desktop port gets redone.
3. One dominant primary action per screen; avoid equal-weight competing buttons. Keep it reachable without covering content; a sticky bar is not a default (see the sticky-action rule above).
4. Icons match their meaning; a wrong icon is a defect, not a style choice. Official third-party marks only when permitted and verified; every icon control has a meaningful accessible name; never remove a label just for appearance.
5. Reuse the product's existing elements; never invent a second visual language inside one product. Multi-page builds share one design system; only the message changes per audience. Inspect every page, not just the homepage.
6. Test representative content: longest expected name, minimum and maximum item counts, applicable loading, empty, denied and error states, phone-sized tap targets. Keep the same essential information, actions and outcomes across breakpoints unless the brief says otherwise; record omissions and their approved reason. Label invented demo content and generated assets; never as real customer proof or product photography.
7. Speed is part of the deliverable: define the readiness milestone (for example hero visible plus primary control usable) before measuring; report FCP and the milestone with the test conditions the QC record lists. Label local or private-demo numbers "local, unthrottled, not device evidence"; no instrumentation means timing NOT RUN. Never claim "fast" without measurement or present simulation as device evidence.
8. Share previews only on authorized surfaces: inspect the link preview card and share text on each configured channel, including in app browsers, with fallbacks such as copy link. Record N/A with the scope reason for a private local demo; never publish just to run this check. Per-page previews only when sharing is authorized and in scope.
9. Generated assets: one shared style description per set, prompts kept with the project, images labeled as generated unless real photography is supplied, no real people or copied brands, alt text on informative images, compressed to web size.
10. A rejected visual direction becomes a recorded rule, so the next round starts from the learned constraint instead of repeating the guess.

## Optional design references

These are upstream references, not bundled dependencies or installed skills. Choose a lead method that fits the task, read its current instructions and required references, and record the version and steps actually applied. Check license and installation effects before copying or installing anything. Do not blend conflicting directions or claim a method ran because it was listed.

- [Impeccable](https://github.com/pbakaus/impeccable): direction, critique, layout and polish.
- [Taste Skill](https://github.com/Leonxlnx/taste-skill): page direction, reference study and rendered iteration.
- [Typography and layout skills](https://github.com/jakubkrehel/skills): type, spacing and grouping.
- [Hallmark](https://github.com/Nutlope/hallmark): alternative composition and interaction references.

No upstream scripts or source text are redistributed here. The workflow can be used without installing these references; unavailable checks and partial use must stay visible.

