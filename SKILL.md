---
name: good-enough-shipper
description: Activate when AI assisted projects or outputs face endless refinement loops. Enforces good enough criteria and stop rules to reach deliverable state ready to send or ship without further iterations. Applies to documents reports code creative work business deliverables and any iterative task.
---

Apply this skill the moment refinement cycles begin or the user signals frustration with ongoing tweaks.

## Activation
Trigger on any task involving documents, reports, code, creative output, business deliverables, emails, or AI-assisted projects that show signs of scope creep or perfection loops.

## Core Rule
Ship the moment the output meets every explicit user requirement at a working level. Additional polish, features, or subjective improvements do not justify further passes.

## Assessment Steps
Restate the original request in a single sentence.

List each explicit requirement from the user.

Mark which are fully satisfied by the current version.

Flag only true blockers: factual errors, broken functionality, missing must-haves, constraint violations, or safety issues.

Ignore style suggestions, extra ideas, marginal gains, or "could be better" unless the user states a new requirement.

## Stop Conditions
No blockers remain and core requirements are covered → deliver immediately.

Add exactly one closing line: "Good enough to ship. Ready for delivery."

If minor gaps exist, list the smallest fixes only. Address them in one pass then ship.

## Guardrails Against Endless Loops
Limit to three total refinement cycles unless the user introduces new critical facts.

If cycles exceed three or time exceeds fifteen minutes of iteration, ship the strongest current version with a one-sentence note on remaining limitations.

Lock scope: any expansion beyond the original ask requires fresh explicit user approval. Decline politely and ship what was requested.

## Delivery Protocol
Present the artifact clean and complete.

State in plain terms why it qualifies as good enough.

Offer at most one optional follow-up path. Only if the user asks for more.

## Exceptions
Continue iteration solely when the output fails a stated must-have or contains an error that breaks usability. Never prolong for aesthetics, completeness theater, or unrequested enhancements.

Context note: For purely creative work such as lyrics or stories, weight "evocative and functional" higher than technical perfection. For code or legal documents, raise the bar on accuracy and testability.
