---
title: "Healthcare \u2014 User Guide (Category Draft)"
status: draft
published: false
content_type: user-guide
draft_date: "2026-11-16"
owner: unassigned
product_mapping: unconfirmed
category: healthcare
required_reviews: ["product-owner", "editorial", "privacy", "security", "accessibility", "clinical-scope"]
---

# Healthcare — User Guide

> **Synthetic, non-clinical workflow draft.** No Healthcare app, interface, permission model, or information-handling control has been verified. This guide describes how to review an administrative service journey without using real patient information. It is not medical advice, a clinical triage protocol, or an operational substitute for approved local procedures.

Start with the [Healthcare product overview](overview.md#capability-validation-matrix) for scope and evidence requirements. Use the [documentation index](../README.md) to navigate the other drafts.

## Outcome and example

The intended output is a reviewed description of how a non-clinical request reaches an accountable owner and how the requester learns the next administrative step. You will record gaps and limits rather than asserting that an application can deliver the journey.

**Synthetic example:** “Test Request H-001: Where can I find the approved information about a routine service's opening hours?” This example contains no real person's details and makes no request for diagnosis, treatment, clinical priority, or an appointment.

If a real clinical or urgent need arises, stop this exercise and follow the organization's established processes. Do not use the draft workflow to assess urgency or route clinical care.

## Before you begin

- Confirm the service owner, administrative scope, and authorized participants.
- Obtain an approved service description and an appropriate contact or test route.
- Use a permitted test environment or clearly labeled document walkthrough.
- Confirm where synthetic observations may be stored and who may review them.
- Obtain the relevant privacy, security, accessibility, clinical-scope, and editorial review for the planned exercise.
- Verify that any action reaching a real person or system is authorized. Prefer simulation when the goal is documentation review.

“Requester,” “coordinator,” and “service owner” refer to responsibilities in this draft, not application roles. Do not create accounts, change permissions, send messages, or access production information solely because this guide mentions a role or handoff.

## Walk through a non-clinical service request

### 1. Set the scope and stop conditions

Write down the one administrative question being tested, the audience, and what would count as a correct next step. Identify which situations are out of scope, including symptoms, diagnoses, clinical advice, urgency assessment, or a request requiring identifiable records.

Define stop conditions such as uncertainty about authorization, accidental exposure of real information, an unapproved destination, or a clinical question. Agree who handles each condition through the existing organizational process.

**Completion check:** every participant understands the purpose and boundaries before any system interaction occurs.

### 2. Confirm the service information and entry route

Ask the service owner to verify the description, hours or contact information relevant to the example, and the approved route for the request. Record the evidence date so stale information can be identified later.

If a product exists, verify its actual entry point and access requirements. Do not assume a public portal, self-service account, booking form, single sign-on, or invitation mechanism. If there is no confirmed product, label the exercise a workflow walkthrough rather than application validation.

**Completion check:** the route and its owner are confirmed; the guide does not invent a destination or a response-time promise.

### 3. Prepare the synthetic request

Use a fictional request identifier and a short, non-clinical question. Include only fields needed for the exercise. Do not use real contact details, clinical descriptions, identifiers, attachments, or copied patient records. A superficially redacted real case is not necessary for this test.

Where a tool requires additional information, verify whether a permitted synthetic value or approved test fixture is available. Stop rather than entering real information to satisfy an unknown requirement.

**Completion check:** a second reviewer can inspect the example and confirm it contains no patient-identifying information.

### 4. Trace how the request would be initiated

Walk through the verified entry route using the permitted test method. Observe how the requester finds the right service information and understands what action to take next. Confirm whether the action is a simulation, a manual process, or a real supported product action.

Do not infer successful submission from a page view or assume that an email, notification, or service record was created. Only describe effects you can verify. Obtain separate authorization before any action that would contact real recipients or change a production record.

**Completion check:** the documentation clearly distinguishes the requested action, the observed result, and what remains unknown.

### 5. Establish an accountable administrative owner

Have an authorized coordinator explain how responsibility would be accepted and transferred, if applicable. Identify the receiving team, the minimum information required, and the fallback if the initial recipient cannot act.

If there is no verified assignment function, document the approved manual handoff and its owner. Do not describe a routing engine, work queue, audit trail, or automatic escalation without evidence.

**Completion check:** a named responsible function has accepted the next administrative action; no assumption of ownership is left implicit.

### 6. Review the next-step communication

Draft a non-clinical response explaining what is known, what happens next, and where the requester can ask an appropriate follow-up. Use only confirmed service information and an authorized channel. Review the wording for readability and accessibility.

Do not imply that a request has been accepted, an appointment booked, or a clinician notified unless those events have been verified. Do not promise response times, confidentiality properties, or service availability that have not been approved.

**Completion check:** the requester can distinguish an informational response from confirmation of a service action.

### 7. Test one exception and fallback

Use a synthetic exception such as an outdated contact route, a request outside the administrative scope, or an unavailable recipient. Confirm the approved fallback without introducing symptoms, urgency triage, or patient data.

Record who owns the correction and how the user is directed appropriately. If the next step is uncertain, mark the workflow blocked and obtain owner review rather than inventing a route.

**Completion check:** the failure mode has an accountable, approved next action, or is explicitly recorded as unresolved.

### 8. Close the exercise and record limitations

Record the administrative result, evidence references, unresolved questions, manual steps, and decisions. Confirm what was not tested, such as identity verification, access enforcement, retention behavior, integration delivery, or production operations.

Retain or remove synthetic artifacts only under the approved process. Do not claim that a local deletion removes logs, backups, copies, or linked records. Keep real operational details in their authorized location, not a public Markdown file.

**Completion check:** an owner has accepted each open issue and the evidence is not being presented as proof of clinical, privacy, security, or compliance outcomes.

## Suggested review record

```yaml
exercise_id: H-001-synthetic
status: planned
purpose: Review a routine non-clinical information request
product_or_walkthrough: to-be-confirmed
version_or_snapshot: to-be-confirmed
service_owner: to-be-assigned
approved_entry_route: to-be-verified
authorized_participants: to-be-confirmed
uses_real_patient_information: false
observed_actions: []
manual_or_unverified_steps: []
exception_tested: to-be-selected
open_issues_and_owners: []
review_decision: pending
```

This is a documentation record, not an application configuration or an authorization to process information.

## Troubleshooting and escalation boundaries

| Problem | Safe response | Do not assume |
| --- | --- | --- |
| The request might require clinical assessment. | Stop the administrative exercise and follow the established local clinical process. | That this guide can assess symptoms or urgency. |
| The service route is outdated or ambiguous. | Ask the service owner for a current approved route and mark the draft blocked. | That a nearby team or unverified address is a suitable substitute. |
| You cannot access a screen or record. | Verify authorization and the approved test environment. | That restrictions should be bypassed or another person's account used. |
| There is no evidence a request was received. | Check the real workflow with the authorized owner and describe the uncertainty accurately. | That opening a page or selecting an action created a record or notification. |
| Real information appears in a test artifact. | Stop sharing it and invoke the organization's privacy or security incident process. | That removing a name alone makes the artifact safe. |
| A handoff has no accountable recipient. | Leave the workflow incomplete and obtain an owner and fallback. | That a link, queue label, or draft message establishes accepted responsibility. |

## Before this becomes a live user guide

The product owner must replace abstract actions with verified screen labels, supported fields, accurate confirmation behavior, environment details, and authorized help routes. The relevant reviewers must approve the administrative scope, information handling, exception behavior, and any screenshots. Each action must be tested against a specific product version.

Until then, this is a detailed workflow draft, not an operational runbook. Approval of the older industry spotlight does not approve this guide.

## Related reading and sources

- [Healthcare overview](overview.md): proposed audiences, capabilities, and non-goals.
- [Discovery guide](../discovery/user-guide.md#run-a-small-discovery-cycle): planning a bounded test and reporting findings without overclaiming.
- [Education guide](../education/user-guide.md): a different context for understandable instructions and accountable handoffs; data rules are not interchangeable.
- [Existing Healthcare spotlight](https://github.com/np10879/asf-app/blob/main/app-index/healthcare.html): source themes and evidence limits.

## Documentation network

[Repository README](../../README.md) · [Documentation index](../README.md)

| Category | Product overview | User guide |
| --- | --- | --- |
| Education | [Overview](../education/overview.md) | [User guide](../education/user-guide.md) |
| Healthcare | [Overview](overview.md) | **User guide (this page)** |
| Discovery | [Overview](../discovery/overview.md) | [User guide](../discovery/user-guide.md) |

> All eight Markdown draft pages link directly to every other draft page through this navigation. The homepage links to these review drafts on GitHub; the category guides remain unpublished.
