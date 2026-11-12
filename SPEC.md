# Brand Studio decisions

This is the durable agreement between the learner and agent. Keep it concise and update it only with agreed choices or actual evidence. `Not chosen yet` is a valid status. Persona cards are hypotheses unless supported by real research.

[LEARNING.md](LEARNING.md) holds the short, reviewable record of learner explanations and help received. Keep the brand decisions and implementation evidence here; link rather than duplicate them.

## Current stage

- Stage: BRAND-001 implementation in progress; selected identity applied locally.
- Current feature: `BRAND-001` — first branded storefront and live style guide.
- Status: Learner selected the modernist preview, approved the shared hero copy and SVG wordmark, approved two proposed ethical elements, chose to keep the current layout after desktop/mobile observations, and adopted a secondary audience hypothesis about a plain layer. The learner explained that Min's T-shirt can be there for someone who needs a white shirt to layer; this remains an unvalidated design hypothesis. The styling-tip benefit is accepted from an AI example; the learner explained how the inclusive line could help. Implementation is local and the full prepared check passes; test interpretation, issue update, and remaining project review are open.
- Next small decision: The actual test interpretation remains unaddressed; leave it open unless the learner wants to return to it.

## Product boundary

The product stays the same white T-shirt in both previews. The baseline has a size selector and temporary demo bag. No real orders, payment, accounts, or persistence. Do not add unsupported claims about materials, manufacturing, sustainability, fit, delivery, scarcity, reviews, or sales.

## Audience hypotheses

| Tiny card                    | Primary audience                                                                                                 | Secondary audience                                                                              |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| Situation                    | Someone who does not know what else to wear and needs a simple shirt to throw on; broad audience is a hypothesis | Someone seeking a plain layer under other clothes                                               |
| Goal or meaning              | An easy default when getting dressed feels uncertain                                                             | An uncomplicated white layer; learner reason: Min's shirt can be there for someone who needs it |
| Concern                      | Not chosen yet                                                                                                   | Not chosen yet                                                                                  |
| Page should help them decide | What to wear more easily and with less time spent pondering (learner paraphrase)                                 | Not chosen yet                                                                                  |
| Evidence                     | Assumption; not validated                                                                                        | Learner adopted an AI-proposed hypothesis and explained why it may help; not validated          |

## Early brand brief

| Decision                            | Agreement                                                                    |
| ----------------------------------- | ---------------------------------------------------------------------------- |
| Brand name                          | Min                                                                          |
| One-sentence promise                | “Just good old reliable for when you don't know what to wear”                |
| Primary archetype (brand character) | Innocent                                                                     |
| Three voice traits                  | Calm, reassuring, reliable (learner approved “reliable” after AI suggestion) |
| One example line in this voice      | Not chosen yet                                                               |
| Predicted audience effect           | “It will give them a sense of relief and comfort.”                           |

## Visual decision

The learner approved using their promise as the shared headline and wrote the support sentence below. The button label remains an AI draft. Both previews use the same product image, product facts, headline, support, and action.

- **Shared headline (approved):** “Just good old reliable for when you don't know what to wear”
- **Support sentence (learner wording):** “A reliable t-shirt for your times of uncertainty”
- **Action (learner approved):** “See the shirt”
- **Paired preview index:** [Open both explorations](public/explorations/index.html)
- **Logo (approved):** [Preview at navigation and small sizes](public/explorations/min-logo-proposal.html); [SVG asset](public/explorations/min-logo-proposal.svg). It is a one-color geometric wordmark, inspected at 108px and 52px. It is not applied to the storefront yet.
- **Modernist:** [Preview](public/explorations/min-modernist.html) — Josef Müller-Brockmann, _Musica Viva_ (1957), [MoMA record](https://www.moma.org/collection/works/4885). The inspected poster has aligned type columns, a warm field, and sparse diagonal bars. The exploration uses a two-column grid, clear type hierarchy, muted ink, and restrained diagonal accents. Intended effect: steady and easy to scan. Risk: could feel formal or distant.
- **Postmodernist:** [Preview](public/explorations/min-postmodernist.html) — April Greiman, _Your Turn, My Turn_ (1983), [Cooper Hewitt reference](https://www.cooperhewitt.org/2017/08/30/26363/). The inspected poster layers offset red/cyan type, a globe photograph, and scattered shapes. The exploration overlaps type and panels and uses muted clay, blue, and butter tones. Intended effect: make the default feel human and memorable. Risk: could feel visually busy.
- **Chosen direction:** Modernist preview selected by learner. **Visible detail noticed:** Clear headline hierarchy. The connection to visitor relief/comfort remains assisted and not yet explained in the learner's own words.
- **Original SVG logo:** Learner approved the one-color geometric wordmark; applied at [storefront asset](public/assets/min-wordmark.svg).
- **Monochrome and small-size variants:** The same one-color SVG is used at header and guide sizes.
- **Logo review at actual use size:** Rendered in the shared header at 120×40 and in the live guide at large and small sizes; one-color geometric artwork is legible in these views.
- **Shared palette, typography, spacing, assets:** Clean/minimal and soft/warm; live tokens in [shared stylesheet](public/styles.css), reused by storefront, style guide, and studio.

## Ethical persuasion

Choose two applications that help the visitor make a voluntary, informed decision. Record the actual interface/copy, mechanism, and visitor benefit. Required size selection or validation alone does not establish consistency. Do not invent social proof, scarcity, authority, or product facts.

| Principle                                    | Actual copy or interaction                                                        | Visitor benefit / factual support                                                                                                                                |
| -------------------------------------------- | --------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Reciprocity (approved proposal; implemented) | “A simple start: pair the white T-shirt with something you already like wearing.” | Free useful styling suggestion; gives an unsure visitor a place to start. Learner accepted this AI-suggested benefit; no conversion effect claimed.              |
| Unity (approved proposal; implemented)       | “For anyone who wants getting dressed to feel simpler.”                           | Learner said it could make deciding what to wear easier and take less time. This is a design hypothesis, not customer research; no popularity or product claims. |

## BRAND-001 — first branded storefront and live style guide

**Scope:** turn the working neutral storefront into the chosen brand's first coherent page. Keep the existing size selector and demo bag usable. Do not add checkout or all future features.

Keep when:

- The learner chooses audience hypotheses, brief, visual direction, and logo; the page visibly expresses those choices.
- Two annotated hero directions compare modernist/postmodernist thinking with the same content and real source links.
- The selected SVG logo works at small size and in one color.
- The storefront and live style guide share CSS variables, typography, components, and assets.
- Two ethical persuasion applications are visible and their claims are supportable.
- Prepared checks pass, one actual check is discussed, and the learner reports browser, keyboard, and mobile observations.
- The issue, branch, commit, and PR explain the feature in the learner's repository; the learner approves keeping and merging it, and the merge into `main` is verified. Publishing is separate.

## Evidence

| Spec ID   | Files                                                                                                                                                                                                                  | Issue / PR                                                                         | Checks and observations                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| --------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BRAND-001 | [Storefront](public/index.html), [live style guide](public/styleguide.html), [shared stylesheet](public/styles.css), [Min wordmark](public/assets/min-wordmark.svg), [paired previews](public/explorations/index.html) | [Issue #1](https://github.com/Asu245/t-shirt/issues/1); branch `feature/brand-001` | Hero previews: Chromium inspection at 1440×1000 and 390×844; shared copy matched, shirts loaded, no visible overflow/errors. Logo proposal rendered at 960×720; SVG legible at 108px and 52px. Final storefront/guide/studio renders inspected at 1440×1000 and 390×844; no horizontal overflow or page errors. `npm run format` applied; Windows lint globs corrected; preview aria labels and CSS lint issues fixed. Full `npm run check` passes: format, lint, 7 server tests, and 10 Chromium tests. Learner described the page as simple and easy to understand; while tabbing, identified the size controls and Add to bag as focus targets; on narrow view, said spacing felt comfortable and not cramped, then approved keeping the layout. Learner adopted the secondary plain-layer hypothesis and explained that someone needing a white layering shirt can count on Min's tee; still unvalidated. Test interpretation pending. Issue update and implementation review pending. |

## Later

No follow-up is selected. After keeping `BRAND-001`, choose one next cycle: perhaps a brand story, a supported fit guide, or richer demo-bag behavior. Agree its scope and add one new spec ID at that time.
