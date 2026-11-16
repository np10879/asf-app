---
title: "Education \u2014 User Guide (Category Draft)"
status: draft
published: false
content_type: user-guide
draft_date: "2026-11-16"
owner: unassigned
product_mapping: unconfirmed
category: education
required_reviews: ["product-owner", "editorial", "accessibility", "privacy", "safeguarding-as-applicable"]
---

# Education — User Guide

> **Product-neutral workflow draft, not verified application instructions.** The repository does not identify an Education app or document its interface. Use this guide to prepare and evaluate a small, approved learning journey. Do not interpret a step as proof that a particular feature exists. Validate the actual product, permissions, screens, and support route before using this as live product documentation.

Read the [Education product overview](overview.md#capability-validation-matrix) for the proposed scope. Return to the [documentation index](../README.md) for the wider draft collection.

## What this guide helps you do

Plan one learning activity, check the learner's route through it, retain educator oversight, and record specific barriers and next actions. The deliverable is a reviewed sample journey and evidence log—not a production course deployment or a claim of improved learning outcomes.

**Example:** an educator wants learners to understand a short introductory topic and complete one practice activity. Use “Sample Learner A” and synthetic work. No real student account, record, or support request is necessary for this draft exercise.

## Before you begin

- Identify a responsible educator or content owner and the audience for the activity.
- Confirm an authorized test environment. If no application is available, run a clearly labeled prototype or document walkthrough; do not call it a product test.
- Obtain approved sample content and any required permission to use it.
- Choose a safe place to record observations and agree who may access it.
- Establish a route for questions and access barriers. Do not invent support addresses or response-time commitments.
- If participants or real information are involved, complete the applicable privacy, safeguarding, accessibility, and research approvals first.

The terms **learner**, **educator**, and **service owner** describe responsibilities here; they are not verified permission roles in an application.

## Run a sample learning journey

### 1. Define one learning objective and completion condition

Write a short objective, such as “After reading the example, the learner can identify the two actions needed to begin the activity.” Define what an acceptable attempt looks like and where a learner should ask for help.

**Record:** objective, audience, prerequisites, educator, support contact, and the boundaries of the exercise. **Checkpoint:** another reviewer can explain what the learner is being asked to do without additional verbal instructions.

### 2. Confirm the real workflow before writing interface instructions

With the product owner, identify how a participant would access the material, where an attempt would be made, and how an educator would review it. If access requires an account, verify the approved invitation or sign-in process and authorization with that owner. Do not assume self-service registration, single sign-on, enrollment, or a particular permission model.

If a task has no supported product action, either remove it from the product scope or explicitly document the approved manual handoff. A manual process must not be presented as an automated feature.

**Record:** product or prototype name, version, environment, actual entry point, permitted participants, and unsupported steps. **Checkpoint:** all prerequisites are confirmed before a learner is asked to proceed.

### 3. Prepare the sample activity

Create a compact content package: a descriptive title, the learning objective, a short explanation, one practice task, the completion condition, and a clear next step. Use meaningful link labels and an understandable heading order. Provide text alternatives for essential visual information and appropriate alternatives for media where required.

Check that the material does not depend on unnecessary personal information. Review licensing or permission for any reused content. Do not claim support for uploads, rich media, offline use, or assistive technology until it has been tested in the actual delivery method.

**Record:** approved content location, reviewer, review date, media or format requirements, and known limitations. **Checkpoint:** the activity can be reviewed from start to finish in the chosen environment.

### 4. Walk through the learner route

Use synthetic information and attempt the journey from the user's starting point. Ask the reviewer to find the activity, explain what to do, attempt the practice task, locate the completion condition, and identify where to ask for help. Observe rather than coaching immediately; record where instructions were unclear.

Where appropriate to the interface, test keyboard navigation, visible focus, reading order, understandable links, small-screen layout, and any alternative content supplied. Document the actual test setup. These checks inform remediation; they do not by themselves establish accessibility conformance.

**Record:** actions attempted, observed behavior, assistance needed, and blocked tasks. **Checkpoint:** any blocking access issue has an owner and a safe alternative before wider testing.

### 5. Perform the educator review

Have the responsible educator inspect the synthetic attempt and provide feedback through the verified review process. Check that the response explains what was understood, what needs attention, and the learner's next action. Use an approved manual review process if necessary and label it as manual.

Do not infer automatic grading, feedback generation, progress analytics, or notification delivery. If a product supports one of these, document and test its specific behavior separately.

**Record:** reviewer, review method, feedback example, and any unresolved interpretation. **Checkpoint:** the learner-facing next step and accountable educator are clear.

### 6. Exercise a non-learning support handoff

Introduce a synthetic support need, such as not understanding where to request an alternative format. Confirm how the learner finds the appropriate contact, what information is necessary, who owns the response, and what to do if the initial route is unavailable. Keep assessment details and sensitive personal information out of the example.

**Record:** request type, approved contact or route, minimum information, fallback, and closure condition. **Checkpoint:** a real owner has accepted responsibility; a link alone is not proof of a functioning service workflow.

### 7. Review findings and decide the next change

Separate direct observations from interpretations. Summarize which tasks were attempted, which were completed, where help was required, and what was not tested. Agree one or two improvements, an owner, and a review point. If the question concerns user needs rather than product behavior, use the [Discovery guide](../discovery/user-guide.md#run-a-small-discovery-cycle) to plan a proportionate follow-up.

**Record:** observations, limitations, proposed changes, owner, and decision. **Checkpoint:** the team has not converted a small walkthrough into a broad learning-outcome or efficiency claim.

### 8. Close the exercise safely

Remove or retain test material according to the approved local process and permissions. Do not assume a delete action removes every copy, backup, or audit record. Store only the evidence needed for the agreed purpose. Record unresolved privacy, accessibility, or safeguarding concerns and escalate them through the institution's established channels.

**Checkpoint:** all retained artifacts have an owner, permitted audience, and review or retention decision.

## Observation log template

Copy this structure into an approved working location. Do not put identifying student information in a public repository.

```yaml
exercise: Introductory learning journey — synthetic example
status: planned
product_or_prototype: to-be-confirmed
version_or_snapshot: to-be-confirmed
audience: to-be-confirmed
learning_objective: to-be-defined
responsible_educator: to-be-assigned
entry_point_and_access: to-be-verified
content_review: pending
observations: []
unsupported_or_manual_steps: []
accessibility_limitations: []
next_change_and_owner: to-be-agreed
retention_decision: to-be-approved
```

These values describe unfinished review work; they are not production settings.

## Troubleshooting

| Problem | Safe next action | What to record |
| --- | --- | --- |
| The entry point or sign-in route is unknown. | Stop product testing and obtain the approved route from the product owner. Do not improvise credentials or permissions. | Missing prerequisite and responsible owner. |
| The learner cannot understand the next task. | Clarify instructions and have another reviewer repeat the walkthrough. | Original instruction, observed difficulty, and revised wording. |
| Content is inaccessible in the tested setup. | Provide an approved alternative, record the barrier, and obtain appropriate accessibility review. | Environment, barrier, workaround, and remediation owner. |
| Feedback or progress is not visible. | Verify whether the function exists; document an approved manual process if needed. | Expected versus observed behavior and product evidence. |
| A support request has no owner. | Do not represent the handoff as complete. Establish an accountable contact and fallback. | Ownership gap and closure condition. |
| Identifying student information appears in test material. | Stop sharing the artifact, follow the institution's incident process, and ask the authorized owner about remediation. | Only the minimum non-identifying incident reference in documentation. |

## Handoff and readiness checklist

- [ ] The actual product and version are identified.
- [ ] All proposed actions map to supported features or explicitly labeled manual steps.
- [ ] The sample uses approved, non-identifying material.
- [ ] The learning objective, help route, and educator review are understandable.
- [ ] Observations and limitations are separated from benefit claims.
- [ ] Open accessibility, privacy, and safeguarding issues have owners.
- [ ] Exact interface labels and screenshots have been verified before this becomes an operational guide.
- [ ] Product and editorial reviewers have approved this guide and its [overview](overview.md) together.

## Sources and related reading

The [published Education spotlight](https://github.com/np10879/asf-app/blob/main/app-index/education.html) supports the category themes, not the proposed product actions. For another service-handoff context, compare the [Healthcare guide](../healthcare/user-guide.md); do not transfer education permissions or data rules to healthcare.

## Documentation network

[Repository README](../../README.md) · [Documentation index](../README.md)

| Category | Product overview | User guide |
| --- | --- | --- |
| Education | [Overview](overview.md) | **User guide (this page)** |
| Healthcare | [Overview](../healthcare/overview.md) | [User guide](../healthcare/user-guide.md) |
| Discovery | [Overview](../discovery/overview.md) | [User guide](../discovery/user-guide.md) |

> All eight Markdown draft pages link directly to every other draft page through this navigation. The homepage links to these review drafts on GitHub; the category guides remain unpublished.
