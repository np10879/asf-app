---
title: "Education \u2014 Product Overview (Category Draft)"
status: draft
published: false
content_type: product-overview
draft_date: "2026-11-16"
owner: unassigned
product_mapping: unconfirmed
category: education
required_reviews: ["product-owner", "editorial", "accessibility", "privacy", "safeguarding-as-applicable"]
---

# Education — Product Overview

> **Draft for product and editorial review.** Education is a documented industry category, not a confirmed app name. This page proposes a product narrative; it does not establish that the workflows, controls, or capabilities below are implemented. Product identity, availability, interface, access model, and support arrangements remain unverified.

**Next:** follow the [Education user guide](user-guide.md#run-a-sample-learning-journey) for a product-neutral pilot workflow. Use the [documentation index](../README.md#coverage-matrix) to compare category coverage.

## Purpose and positioning

The proposed Education experience would help learners, educators, and student-service teams navigate a clearer learning journey: discover relevant material, understand the next activity, receive appropriate human support, and know where to go when something blocks progress. Its strongest editorial themes are accessible digital learning, educator enablement, and connected student services.

This positioning is grounded in the existing [Education industry spotlight](https://github.com/np10879/asf-app/blob/main/app-index/education.html). The spotlight is an editorial overview, not proof of a shipped learning platform, completed deployment, measured improvement, or customer endorsement. The product page must retain that distinction until a product owner supplies verifiable evidence.

## What is confirmed and what is proposed

| Statement | Evidence status | How to use it |
| --- | --- | --- |
| An Education spotlight exists in the repository and is marked published. | Confirmed from repository content. | Link to it as background and editorial context. |
| Accessible learning, educator workflows, and student-service journeys are its stated themes. | Confirmed editorial scope. | Use them to organize discovery and documentation. |
| A single app delivers learning content, feedback, and service requests. | Proposed product concept; not verified. | Confirm the actual product boundary before presenting it as a feature. |
| Enrollment, assessment, notifications, role-based access, analytics, or integrations are supported. | Unknown. | Do not promise them or name an interface without product evidence. |

## Intended audiences and jobs to be done

These are candidate audiences, not verified application roles or permission groups.

| Audience | Job to be done | Proposed value to validate |
| --- | --- | --- |
| Learner | Find an appropriate activity and understand how to participate. | A more understandable route from learning goal to next action. |
| Educator | Prepare material, review a learner's work, and provide human feedback. | Less ambiguity around preparation and review responsibilities. |
| Student-service colleague | Route a question or support need to the right person. | A visible owner and next step for the learner's request. |
| Content or service owner | Keep instructions accurate, accessible, and appropriate for the audience. | Clear ownership, review history, and evidence for updates. |

A product owner should choose one initial audience and a narrow workflow. A general promise to cover every stage of the student lifecycle would exceed the available evidence.

## Capability validation matrix

The items below are candidate capabilities, not a shipped feature list.

| Candidate capability | Intended user outcome | Evidence required before publication |
| --- | --- | --- |
| Accessible learning materials | Learners can understand the content and identify the next activity. | A representative content sample, tested navigation, and an accessibility review with documented limitations. |
| Educator preparation and review | Educators can prepare one activity and give appropriate feedback. | A reproducible workflow showing the actual supported actions, user permissions, and human review point. |
| Connected student-service handoff | A learner can identify where a non-learning request goes. | A confirmed contact or routing process, accountable recipient, and fallback when the route is unavailable. |
| Progress or status visibility | Participants know which actions are complete and which are pending. | Proof of the actual status mechanism; a documented manual process if no product mechanism exists. |
| Connection to other systems | Users avoid unnecessary re-entry between approved tools. | Named, tested integration behavior and approved data flows. Do not infer this capability from the word “connected.” |

For the matching draft workflow, see [Run a sample learning journey](user-guide.md#run-a-sample-learning-journey). For testing methods without outcome claims, see the [Discovery user guide](../discovery/user-guide.md#run-a-small-discovery-cycle).

## Proposed end-to-end experience

1. **Define the learning goal.** State what the learner should understand or be able to attempt. Identify the educator and a contact for questions.
2. **Prepare a small activity.** Use approved, readable content with clear instructions and appropriate alternatives. Record prerequisites and any known access limitations.
3. **Walk through the learner journey.** Check whether a representative user can find the activity, understand the instructions, attempt it, and locate help.
4. **Retain educator oversight.** Agree how a qualified person reviews work and communicates feedback. Do not assume automated assessment or recommendations exist.
5. **Close the loop.** Record observations, unresolved barriers, and the owner of the next change. A completed pilot is not automatically evidence of better learning outcomes.

The [user guide](user-guide.md) expands this sequence into tasks, acceptance checks, and troubleshooting. It deliberately avoids invented screen names, buttons, and API calls.

## Data, accessibility, and safeguarding

Use synthetic examples for initial documentation and testing. Real student information, assessment records, and support requests should only be handled in an authorized environment under the organization's applicable policies. Do not place identifying student data in public issues, screenshots, or these Markdown files.

Accessibility is a validation obligation, not a certification claim. Review headings, link descriptions, reading order, text alternatives, keyboard operation where applicable, and an appropriate route to assistance. Record the devices and assistive technologies actually tested; do not generalize a limited check into universal accessibility.

Where learners may be minors or otherwise require additional safeguards, obtain the relevant institutional and specialist review before collecting information or running research. No consent, age-verification, retention, or safeguarding mechanism has been verified in the product.

## Evaluating a pilot

Candidate measures include whether a participant can identify the next action, the points where assistance is needed, the clarity of educator feedback, and the time taken to find the correct service contact. Define the observation method, baseline if one is needed, sample limitations, and permission to use the evidence before beginning.

Report observations narrowly: “Two participants could not locate the support contact in this prototype” is different from “The product improves student retention.” Do not turn a workflow test into a learning, equity, privacy, or performance claim without appropriate evidence and review.

## Boundaries and non-goals

This draft does not establish a learning-management system, student-information system, enrollment service, grading engine, accessible-platform certification, or integration with any third-party tool. It does not set institutional policy or replace educator judgment. Commercial terms, supported deployments, service levels, and product availability are unknown.

For another sector's proposed coordination needs, see the [Healthcare overview](../healthcare/overview.md); the shared theme does not imply shared software or interchangeable data policies.

## Review and release checklist

- [ ] Name the actual product, product owner, version, and intended audience.
- [ ] Decide which proposed capabilities are supported, unsupported, or out of scope.
- [ ] Replace abstract workflow actions with verified interface instructions where appropriate.
- [ ] Attach approved screenshots or reproducible product evidence without identifying student data.
- [ ] Complete accessibility, privacy, safeguarding, and editorial reviews relevant to the release.
- [ ] Confirm help contacts, data handling, availability, and any commercial statements.
- [ ] Validate the [paired guide](user-guide.md) against the same product version.
- [ ] Approve publication separately; this draft does not inherit approval from the existing spotlight.

## Sources and maintenance

- [Education spotlight source](https://github.com/np10879/asf-app/blob/main/app-index/education.html): editorial themes and stated evidence boundaries.
- [Existing app-index source](https://github.com/np10879/asf-app/blob/main/app-index/index.html): current industry navigation.
- [Publication metadata](https://github.com/np10879/asf-app/blob/main/app-index/metadata.json): existing spotlight status and unassigned ownership; not approval of this draft.

**Draft owner:** unassigned. Review again when product scope changes, a guide step changes, or new evidence is added.

## Documentation network

[Repository README](../../README.md) · [Documentation index](../README.md)

| Category | Product overview | User guide |
| --- | --- | --- |
| Education | **Overview (this page)** | [User guide](user-guide.md) |
| Healthcare | [Overview](../healthcare/overview.md) | [User guide](../healthcare/user-guide.md) |
| Discovery | [Overview](../discovery/overview.md) | [User guide](../discovery/user-guide.md) |

> All eight Markdown draft pages link directly to every other draft page through this navigation. The homepage links to these review drafts on GitHub; the category guides remain unpublished.
