---
title: "Discovery \u2014 User Guide (Category Draft)"
status: draft
published: false
content_type: user-guide
draft_date: "2026-11-16"
owner: unassigned
product_mapping: unconfirmed
category: discovery
required_reviews: ["product-owner", "editorial", "research-methods", "privacy"]
---

# Discovery — User Guide

> **Product-neutral research workflow draft.** No Discovery application, interface, automation, or data controls have been verified. This guide explains how to plan and document a small, approved learning cycle. It does not assert that any research has taken place, that a hypothesis is validated, or that the workflow is implemented in software.

Read the [Discovery product overview](overview.md#evidence-model-and-decision-quality) for the evidence model. The [documentation index](../README.md) connects this guide to the other category drafts.

## Intended outcome

Produce a reviewable package containing one decision question, a hypothesis, an approved learning plan, appropriately handled evidence if the activity actually runs, a bounded interpretation, and a next-action record. A clearly documented “not run” or “inconclusive” state is acceptable and must not be converted into a positive result.

**Synthetic example:** a team is considering the [Education workflow](../education/user-guide.md#run-a-sample-learning-journey). It wants to learn whether a reviewer can locate the help route in an approved prototype without prompting. This is an example research question, not a result or a claim about an existing app.

## Prerequisites

- Identify the decision owner and a person responsible for the learning activity.
- Confirm the product or prototype being reviewed, or explicitly choose a document walkthrough.
- Obtain permission to use the source material and the approved place to store records.
- Secure the required review before participant contact, recruitment, recording, sensitive research, or external actions.
- Define who may see the evidence and what must not be copied into public documentation.
- Confirm any real application entry point and access permissions before interacting with it. Do not assume account creation, project workspaces, uploads, or integrations exist.

Use synthetic material for this documentation exercise unless a separately approved research plan permits otherwise.

## Run a small discovery cycle

### 1. Frame the decision and its boundary

Write the decision in plain language: who needs to choose what, by when if a deadline genuinely exists, and why more evidence is needed. List what the activity will not decide.

For the synthetic example, the decision might be whether to revise the location or wording of a help link in a prototype. It is not a decision about student learning outcomes, product-market fit, or overall accessibility.

**Output:** one decision statement, accountable owner, and explicit boundary. **Ready to proceed when:** the owner agrees that the proposed learning could inform the actual decision.

### 2. Inventory the available signals

List the materials you are permitted to use: approved notes, existing content, a prototype, or other relevant evidence. Record a source identifier, date, context, and access restrictions for each. Distinguish firsthand observation from someone else's reported experience.

Do not treat a link as evidence until the relevant reviewer can access and interpret it. Preserve the context needed to avoid misleading extracts. Do not copy personal or confidential material into a public Markdown page merely to make the reference convenient.

**Output:** a source list with provenance and usage limits. **Ready to proceed when:** each proposed source is usable for the intended purpose, or its absence is documented as a gap.

### 3. Write the hypothesis and plausible alternatives

Express one testable expectation. In the synthetic example: “The proposed help-link wording and placement will allow the intended reviewer to locate the approved support route in the prototype without prompting.” This statement remains untested.

List alternatives: unfamiliar terminology, an unclear starting page, layout constraints, or misunderstanding of the task could affect the observation. Define which uncertainty the activity can realistically address.

**Output:** hypothesis, assumptions, alternative explanations, and what evidence would challenge the expectation. **Ready to proceed when:** the team can describe a possible result that would count against its preferred idea.

### 4. Choose a proportionate method and predefine interpretation

Select an appropriate activity with the research owner. A walkthrough may be sufficient for checking instruction clarity; it is not sufficient for broad claims about a population. Agree the task, participants or reviewers, materials, permissions, observation method, and stop conditions.

Define decision criteria before observing results. The owner should choose criteria suited to the question and method; this guide does not prescribe an arbitrary universal sample size or success threshold. Record how mixed, blocked, or inconclusive evidence will be handled.

**Output:** a reviewed plan with boundaries and interpretation rules. **Ready to proceed when:** required permissions are in place and the activity can be run without unapproved contact or information handling.

### 5. Prepare the materials and evidence log

Check the exact product version, prototype snapshot, or document being reviewed. Prepare neutral task wording that does not reveal the desired answer. Define a concise observation format and a safe way to reference evidence.

If the activity is a simulation, label every example accordingly. If a tool is unavailable, use an approved manual record and identify it as manual. Do not describe automated capture, analysis, transcription, storage, or notifications unless their existence and behavior have been verified.

**Output:** reviewable materials and a ready evidence log. **Ready to proceed when:** another reviewer can understand the plan and detect missing permissions or dependencies.

### 6. Run only the approved activity

Record what actually happens and any departures from the plan. Do not coach a participant toward the desired answer and then record the task as unassisted. If an activity is blocked, stopped, or never started, record that state accurately and explain why.

Use only approved recording and storage methods. Pause if sensitive information is exposed, a participant withdraws where applicable, authorization is unclear, or the work moves beyond scope. Follow the organization's established process rather than improvising consent or escalation rules.

**Output:** observations with source references, context, deviations, and limitations. **Ready to proceed when:** the evidence record accurately reflects the activity that actually occurred.

### 7. Separate observations from interpretations

For each potential finding, write the observation first, then the interpretation and alternatives. An observation such as “A reviewer asked where to find help in this walkthrough” does not establish that all learners will have the same difficulty.

Preserve conflicting evidence. Do not delete inconvenient observations or treat missing evidence as support. Describe what the method and sample can and cannot justify. Where analysis requires statistical or specialist judgment, obtain it rather than inventing confidence levels or causal conclusions.

**Output:** bounded findings with supporting and contradictory evidence. **Ready to proceed when:** an authorized reviewer can trace the conclusion to the sources and understand its limits.

### 8. Record the decision and next action

Have the accountable owner choose the next action: revise the concept, run a different activity, continue with stated limits, pause, or stop. Explain how the evidence informed the choice and what remains uncertain.

Candidate documentation labels include “proposed,” “not run,” “inconclusive,” and “supported within this test context.” These are suggested record labels, not verified software statuses or proof of general validation.

**Output:** decision, rationale, owner, next action, and revisit trigger. **Ready to proceed when:** the next step is explicit and the wording does not overstate the evidence.

### 9. Share a safe summary and close the cycle

Prepare a summary suitable for the intended audience. Use approved evidence references and avoid copying identifying, sensitive, or proprietary details into public pages. A decision to share or publish findings requires its own authorization; completing this guide does not authorize publication.

Apply the approved retention process to records and materials. Preserve the minimum context needed to interpret the result responsibly. Where a finding affects another category, link to its documentation without implying the same result applies there.

**Output:** reviewed summary, access decision, and retention or follow-up record. **Completion condition:** open questions and responsibilities remain visible rather than being hidden behind a “completed” label.

## Learning-cycle record template

```yaml
cycle_id: D-001-synthetic
status: proposed
question: Can a reviewer locate the help route in the approved prototype?
decision_owner: to-be-assigned
product_or_prototype: to-be-confirmed
snapshot: to-be-confirmed
hypothesis: to-be-reviewed
sources_and_permissions: []
method_and_scope: to-be-approved
interpretation_criteria: to-be-agreed-before-running
stop_conditions: to-be-approved
activity_ran: false
observations: []
interpretations_and_alternatives: []
limitations: []
decision_and_next_action: pending
publication_approval: not-granted
```

This is a planning example. Empty observations and `activity_ran: false` must not be rewritten as evidence of success.

## Troubleshooting

| Issue | Recommended next step | Avoid |
| --- | --- | --- |
| The question is too broad. | Choose one decision and one uncertainty the activity can inform. | Treating a small test as a market or outcome validation. |
| Evidence cannot be accessed by an authorized reviewer. | Fix the approved reference or record the evidence as unavailable. | Assuming the source supports a claim just because a URL exists. |
| Findings conflict. | Preserve the disagreement and examine context and alternatives. | Removing counterevidence or averaging incompatible observations into a confident story. |
| The activity was not run. | Record “not run” and the dependency or permission gap. | Writing a result narrative from the plan alone. |
| The workflow or tool lacks a needed function. | Confirm scope with the owner and document a permitted manual step if appropriate. | Inventing an interface, automation, integration, or supported export. |
| A result is inconclusive. | State the uncertainty and agree a proportionate next decision. | Changing criteria after the fact to manufacture success. |
| Sensitive information appears in a record. | Restrict further sharing and use the established privacy or security process. | Copying it into public issues or claiming that removing names is sufficient. |

## Product-documentation readiness

Before publishing this as an operational user guide, identify the actual product, map every action to supported behavior, verify exact interface labels and permissions, test the guide against a named version, and complete product, research-method, privacy, and editorial review as appropriate. Unsupported steps must be removed or clearly separated as external manual work.

## Sources and category connections

- [Published Discovery spotlight](https://github.com/np10879/asf-app/blob/main/app-index/discovery.html): source scope and limits; no completed experiment is asserted.
- [Education overview](../education/overview.md): one possible context for accessible-learning research questions.
- [Healthcare overview](../healthcare/overview.md): another potential context, requiring its own specialist safeguards and approvals.

## Documentation network

[Repository README](../../README.md) · [Documentation index](../README.md)

| Category | Product overview | User guide |
| --- | --- | --- |
| Education | [Overview](../education/overview.md) | [User guide](../education/user-guide.md) |
| Healthcare | [Overview](../healthcare/overview.md) | [User guide](../healthcare/user-guide.md) |
| Discovery | [Overview](overview.md) | **User guide (this page)** |

> All eight Markdown draft pages link directly to every other draft page through this navigation. The homepage links to these review drafts on GitHub; the category guides remain unpublished.
