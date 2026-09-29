# Enneagram for Us

### S + G · A field guide to us

A personal, interactive Enneagram field guide for Susanna and Greg: a place to explore individual patterns, understand each other, and turn reflection into useful conversations.

**[Open the field guide →](https://ohsusannamarie.github.io/enneagram-for-us/)**

## Explore

| Section | What you can do |
| --- | --- |
| **Susanna** | Explore a personalized report, nine-type circle, internal committee, pattern explorer, Stay tool, and personal user manual. |
| **Greg** | Explore a personalized report, nine-type circle, internal committee, pattern explorer, autonomy check, and personal user manual. |
| **Us** | Compare perspectives, translate possible needs, work through conflict and repair, request support, record decisions, check relationship weather, and answer discovery questions together. |
| **Library** | Read source notes, understand the evidence labels, and back up or restore your personalization. |

Across 28 sections, the guide includes 34 individual report insights, 13 relationship comparison dimensions, and eight discovery questions. You can mark an interpretation **Yes**, **Sometimes**, or **Nope**, add context, and build a record of what actually fits.

## A guide you can disagree with

The guide keeps three kinds of information distinct:

- **Source-backed theory:** ideas attributed to the Enneagram books in the library.
- **Personalized inference:** interpretations to explore, revise, or reject.
- **User-confirmed observations:** responses and experiences entered by the people using the guide. A shared confirmation requires both people to answer Yes.

Enneagram language is used for reflection, not diagnosis. Type patterns do not establish someone's motives, attachment style, or mental health. Qualitative chart readings are not presented as verified numeric scores, and wings, instincts, and development levels are not assigned as facts.

## Source library

The guide draws on six supplied EPUBs, with relevant chapters and EPUB locations documented inside the app:

- *The Enneagram, Relationships, and Intimacy* — David Daniels and Suzanne Dion
- *Discovering Your Personality Type* — Don Richard Riso and Russ Hudson
- *The Enneagram in Love* — Stephanie Barron Hall
- *The Wisdom of the Enneagram* — Don Richard Riso and Russ Hudson
- *Understanding the Enneagram* — Don Richard Riso and Russ Hudson
- *Enneagram: The Complete Guide* — Sierra Mackenzie

The repository does not include the EPUBs or long book extracts. Personalized content also draws on the prior conversation; some long source messages were only partially available during retrieval. The app's source notes explain the resulting limits and corrections.

## Your notes stay in your browser

Responses, manuals, and journal entries save automatically using localStorage. There is no account, backend, analytics, or cross-device syncing. Saved notes are not sent to this repository.

- Use **Library → Save, export & restore** to export a JSON backup or copy the backup text.
- Restore from a JSON file or pasted backup after validation and an explicit replace step.
- Back up before clearing browser data or switching devices. Local-file and hosted-site storage are separate.
- If browser storage is unavailable or full, the guide keeps working for the current session and offers backup options.

Local notes are not encrypted. The public website includes its built-in names and personalized analyses; those are separate from the private responses saved in your browser.

## Run or host it

The entire app is **[index.html](index.html)**. Open it in a modern browser, or serve it as a static page. It has no build step, package installation, external fonts, scripts, or image dependencies.

This repository is published through GitHub Pages from the root of `main`. The page uses responsive layouts, labeled controls, keyboard focus styles, a skip link, and reduced-motion support.

## Verification

The delivered build passed **44 local checks**, including all 28 views, source-reference validation, evidence-state rules, backup validation, imported-text escaping, and unavailable, corrupt, or full storage behavior.

Browser checks covered persistence after reload, mutual confirmations, discovery answer hiding and reveal, practical tools, journal save/delete/undo, file import, and copy/paste backup restoration. All 28 sections were checked at a 390px viewport for page overflow and unlabeled fields. The final route sweep reported no JavaScript errors or warnings.

**Known verification limits:** native download completion could not be confirmed in the embedded test browser; the copyable-text backup passed a round trip. Print output, a full screen-reader audit, and comprehensive cross-browser testing remain unverified.
