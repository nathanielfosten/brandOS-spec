---
name: build-brandos
description: Populate or update a brandOS core from existing brand materials, a guided interview, or both. Use for brand onboarding, documenting an established identity, or filling gaps in a partially completed brandOS.
---

# Build a brandOS

Write each core entry for any team member or agent making a brand decision. Organize the guidance around the decision and its context. When evidence comes from one discipline or channel, capture where the choice is known to apply and ask about wider use if that matters. Work in the intended brand project. When working from the reusable spec, put brand-specific material in the brand's own copy. Follow the user's requested scope, including an interview-only or read-only review.

## Find what is already known

Read the target project's README and current core files. Their prompts are the intake outline. Bracketed fields and illustrative examples are scaffolding. For a partial update, start with the named area and its immediate dependencies. For a full intake, account for all the core areas in the routing table below.

Use materials already provided or identified for this brand, such as approved work, a deck, customer research, a design library, CSS or source assets. Note where each usable decision came from, down to the slide, selector or passage when helpful. A current decision from the team can also serve as a source. A pattern in a sample is grounds for a follow-up if its scope or approval is unclear.

## Interview where the evidence runs out

If starting from a blank slate, open with a piece of work: “Which recent piece feels most like you? What detail should someone carry into the next one?” If there are no examples yet, ask about the next thing the team needs to make and work through one choice it will require.

Ask one or two questions at a time. Choose the answer that would change the most useful decision. For instance, if a deck and a stylesheet use different accents, name both sources and ask which applies to the deliverable at hand. When the user identifies an exception, capture its context. Skip questions the materials already answer. If the user asks for a source-only pass, report unresolved choices at the end.

## When filling voice and tone

Read the [voice and tone template](../../../brand/verbal/voice-and-tone.md) and any existing entries. Ask for a piece the editor would still ship and, if available, the draft that preceded it. A routine message can reveal choices a campaign headline leaves out. Preserve exact wording, punctuation, and paragraph breaks. Ask which details were deliberate and which belonged to that particular brief.

When someone gives you an adjective, ask them to edit a line. Hold the facts and situation steady so the edit reveals a preference. Ask “Which words made you reach for the keyboard?” Capture both versions, their reason, and the context where that reason applies. To distinguish tone from format, change one thing at a time: keep the channel fixed while changing the reader’s situation, or carry the same message into a second format.

If the brand has little published work, ask the speaker to say what they would actually tell a reader in a real upcoming situation. Quote their answer and identify it as an interview sample. You can draft alternatives for comparison. Label those as proposals and record the editor’s choice in their own words. In a source-only pass, leave uncertain boundaries under Open questions.

When the user is available to review, try the guide on a fresh, short brief in a format they use. Ask which line they would change first and why. Fold that edit into the relevant section with its scope. A newly drafted test line becomes a reference sample only if the editor endorses it for reuse.

## Put each decision where it will be used

| What you learn | Destination in the target project |
| --- | --- |
| A recognizable action the team wants to repeat, with a reason and an example | [Signature Moves](../../../signature-moves.md) |
| Who the brand serves, what it promises, where it differs, what it says, how it sounds and which words it uses | Relevant [verbal guides](../../../brand/verbal/) |
| Choices about imagery, graphic elements, type, color, layout, effects or motion | Relevant [visual guides](../../../brand/visual/) |
| Exact design values and their intended roles | [Styles](../../../brand/styles/). Add confirmed values to the token source and mirror them in CSS. Refer to the token by name from the visual guide. |
| Approved logo, font and animation files, variants and usage | [Asset inventory](../../../brand/assets/). Record a supplied file or its canonical location. |

One source can answer several questions. A launch email might supply an approved greeting for voice, an exact product spelling for vocabulary, and a potential opening move. Ask whether the team wants to repeat the opening before recording it as a move. Templates and components can supply evidence; author them in the corresponding plugin when requested.

## Save and resume

Retain the core file paths and topic headings across brands. Repeat entries when the brand has distinct use cases. Use the guide’s Open questions section for outstanding choices and remove resolved questions on a later pass.

When populating files, replace the relevant prompts with supported decisions and their sources. If a source establishes a narrower rule, keep that scope. Preserve prior decisions unless the new evidence resolves or supersedes them. On a repeat pass, update the existing entry in place. Leave missing values unfilled and keep conflicting claims open until resolved. If the team explicitly doesn't use something, record that decision so it needn't be asked again.

After each useful batch, report what was filled, which evidence it used, and the most consequential remaining gap. For a full intake, distinguish areas covered, still open and explicitly inapplicable. Before finishing, check the edited links and assets, parse the token JSON, and confirm that every edited token agrees with its CSS property. A partial brandOS with traceable decisions is a usable handoff.
