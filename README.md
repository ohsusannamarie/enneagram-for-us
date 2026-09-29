# S + G · A field guide to us

Open **index.html** in a modern browser, or upload that file as `index.html` to your GitHub Pages publishing folder. It is the entire application: no installation, build step, external assets, or backend is required. The accompanying images and this note are optional review material and are not needed to run it.

## What is included

- Susanna and Greg each have an interactive nine-type circle, internal committee, 17 personalized report insights, eight pattern-explorer situations, a distinct practical tool, a 17-prompt user manual, and a record of observations.
- Us includes 13 comparison dimensions, a two-way partner translator, two possible conflict loops, a repair sequence, support requests, a decision journal, relationship weather, eight discovery questions with a pass-the-device reveal, shared manuals, and confirmed observations.
- Six EPUBs informed the framework and source library. Each source note identifies relevant chapters and EPUB locations. No EPUBs or long book extracts are distributed.
- Source-backed theory, personalized inference, conditional responses, rejected hypotheses, and self-reported confirmations remain distinct. Shared confirmation needs both people to answer Yes.

## Personalization and backups

Writing and responses save automatically to this browser's localStorage. They do not sync between devices or between a local file and your hosted site. In **Library → Save, export & restore**, export a JSON backup or expand **Copy or paste a backup instead**. Both file selection and pasted JSON support restoration after validation and an explicit replace step. Manuals and observations also have text downloads.

Storage failures switch to session-only mode without breaking the guide. Export before closing in that case. Local notes are not encrypted or password-protected. Publishing the HTML publishes its built-in names and personalized analyses, but does not publish locally saved notes.

## Verification completed

44 local checks passed: all 28 views render, all six source-location references match the supplied EPUBs, evidence-state rules work, backup validation and serialization work, imported text is escaped, and unavailable/corrupt/full storage preserves usable session behavior. The standalone script also passed syntax validation.

In the Codex in-app browser:

- Confirmations and manual writing survived reloads.
- Confirmed individual insights and manuals appeared in Us.
- Rejecting a personal hypothesis removed it from the shared confirmed summary.
- One partner's Yes did not create a mutual confirmation; two did.
- Discovery hid the first answer during handoff, revealed both, and saved the result.
- Autonomy statements and Stay questions responded to inputs.
- Repair agreements, decisions, and weather check-ins saved; deleting a journal entry could be undone.
- File-import restoration preserved confirmations, manuals, and journal entries after reload. Imported markup remained literal text.
- Copyable JSON export and pasted-JSON restoration passed a round trip. Invalid option data was rejected.
- All 28 views were inspected at a 390px-wide viewport: no page-level horizontal overflow and no unlabeled form fields were found.
- The skip link moved keyboard focus to the main content; the type circle responded to keyboard activation.
- No JavaScript errors or warnings were reported during the final route sweep.

Native file-download completion could not be confirmed in the embedded browser: its download event timed out. The standard download controls remain implemented; the tested copyable-text backup is available when a browser restricts downloads. Printing has a dedicated stylesheet but was not tested through a physical printer or PDF dialog. This is not a full assistive-technology or cross-browser certification.

## Design review

The approved visual direction is recorded in **design-reference.png** (generated with the built-in image tool). The final browser capture is **preview.jpg**. The concept and final capture were inspected with the image viewer at the concept's 1435 × 1096 dimensions; mobile interaction checks used 390 × 844. **mobile-preview.jpg** is an additional phone-layout capture.

Five comparison points were inspected: the ivory/rust/forest palette, large serif title hierarchy, top navigation and left section rail, open divided sections with a peach action panel, and responsive reading order and spacing. The final implementation preserves this visual direction, with these intentional functional adaptations:

| Concept element | Final implementation and reason |
| --- | --- |
| Decorative navigation icons | Numbered section navigation, which also accommodates the longer relationship tool list. |
| Chart's separate type legend | Selected type appears in the circle, with a fuller explanation below; the circle is explicitly not a numeric score plot. |
| “How I work” navigation | “My full report” includes work, love, strengths, stress, blind spots, growth, and type nuances. |
| Generic confident portrait copy | Revised inference wording and evidence labels preserve the distinction between author theory and personal fact. |
| Predominantly serif small text | System sans-serif body and controls improve longer report and form readability; display headings retain the serif treatment. |

The above-the-fold copy review retained the brand, Susanna/Greg/Us/Library navigation, hero title and subtitle, action-panel question, and Explore a pattern action. The intentional additions are the inference label and more careful portrait wording. No remote imagery, fonts, or generated image is needed by the app itself. No clipping or page overflow remained in the checked layouts. This is a faithful adaptation of the approved design direction, not a pixel-identical copy of the concept image.

## Source and prior-context limits

The prior conversation supplied qualitative chart readings rather than verified numerical type scores. Susanna's Caretaking result is retained as the earlier report's recorded 19/20. Wings, instincts, attachment styles, and development levels are not assigned as facts.

The retrieved Greg report was substantive and complete; long Susanna and relationship messages were truncated by the conversation retrieval limit. Their available substantive analyses and the full interactive handoff architecture were preserved and revised, without inventing missing endings. The library explains the main source-informed corrections, including Hall's alternative 7–8 conflict pattern and the correct authorship of the intimacy book.

Test entries were removed from the preview state. The delivered HTML starts with empty personalization.
