---
title: "Healthcare \u2014 Product Overview (Category Draft)"
status: draft
published: false
content_type: product-overview
draft_date: "2026-11-16"
owner: unassigned
product_mapping: unconfirmed
category: healthcare
required_reviews: ["product-owner", "editorial", "privacy", "security", "accessibility", "clinical-scope"]
---

# Healthcare — Product Overview

> **Draft for product, privacy, security, clinical-scope, and editorial review.** Healthcare is a confirmed editorial category, not a verified application. The capabilities below are proposed scope for discussion. No clinical efficacy, health outcome, privacy guarantee, security certification, regulatory compliance, deployment, or integration is established by this page.

**Next:** use the [Healthcare user guide](user-guide.md#walk-through-a-non-clinical-service-request) to evaluate a synthetic administrative journey. See the [documentation index](../README.md#coverage-matrix) for the full draft set.

## Purpose and positioning

The proposed Healthcare experience focuses on helping people understand how to reach an appropriate service and helping authorized staff coordinate non-clinical administrative work. The intended narrative is clearer access, understandable ownership, and responsible handling of information—not diagnosis, treatment advice, or improved clinical outcomes.

The existing [Healthcare industry spotlight](https://github.com/np10879/asf-app/blob/main/app-index/healthcare.html) names patient access, care-team coordination, and responsible information use as editorial themes. Those themes establish a documentation direction; they do not establish a shipped patient portal, scheduling system, medical record, or care-management application.

## Evidence and product boundaries

| Item | Current evidence | Publication treatment |
| --- | --- | --- |
| A Healthcare spotlight is present and marked published. | Confirmed repository content. | Link as editorial background. |
| Patient access, administrative handoffs, and appropriate information handling are the stated themes. | Confirmed editorial scope. | Use to frame a bounded product-discovery discussion. |
| A named application implements a non-clinical service-request journey. | Not confirmed. | Identify the product and demonstrate the journey before making a capability claim. |
| Scheduling, messaging, identity verification, audit logs, role controls, or integrations exist. | Unknown. | Do not describe them as available functions. |
| Clinical benefit or regulatory compliance has been demonstrated. | No supporting evidence in the repository. | Do not claim it. Obtain appropriate specialist review before any such statement. |

## Candidate audiences and responsibilities

The audiences below are proposed workflow participants, not verified software permission roles.

- **Person seeking service information:** needs to understand what a service covers, what the next administrative action is, and where to ask an appropriate question.
- **Administrative coordinator:** needs a clear request purpose, an accountable recipient, and an authorized process for resolving or redirecting it.
- **Service owner:** defines service boundaries, confirms contact details, and owns fallback and escalation processes.
- **Clinical, privacy, security, accessibility, and information-governance reviewers:** determine whether proposed content or workflows are appropriate within their respective scope. Their review is not implied merely by listing these roles.

Start with one non-clinical request type and one authorized team. Expanding across specialties, organizations, or systems requires new validation of ownership, permissions, information flows, and limitations.

## Capability validation matrix

| Proposed capability | User need | Evidence required before describing it as available |
| --- | --- | --- |
| Service discovery | Understand a service's purpose, boundaries, and contact route. | Approved service description, current owner, and verified destination. |
| Administrative request handling | Know how to initiate an appropriate request. | A demonstrated entry route, required fields, access requirements, and confirmation behavior. |
| Accountable handoffs | Know which authorized team owns the next administrative action. | A tested assignment or documented manual handoff process with a fallback owner. |
| Status communication | Understand the next step without relying on assumptions. | The actual status mechanism and communication channel; distinguish manual updates from automated notifications. |
| Responsible information handling | Provide only information needed for an approved purpose. | An approved data-flow description, access rules, retention decisions, and evidence that relevant controls operate as stated. |
| Accessible participation | Find information and request appropriate assistance. | Review of representative content and interactions, including documented limitations and alternatives. |

The [paired guide](user-guide.md) supplies an evaluation sequence, not proof these capabilities exist. The [Discovery overview](../discovery/overview.md) explains how to keep hypotheses separate from validated findings.

## Proposed end-to-end journey

1. **Understand the service.** Read an approved description, scope limits, and route for non-clinical questions.
2. **Confirm the administrative need.** Use the minimum approved information and an authorized channel. Clinical or urgent needs remain with the organization's established services.
3. **Establish ownership.** An authorized person or verified mechanism accepts responsibility for the next action.
4. **Communicate the next step.** Use a confirmed channel and accurate language. Do not imply an appointment, clinical review, or service commitment unless it has actually been arranged.
5. **Close or redirect with accountability.** Record the administrative result and any agreed follow-up under the local governance process.

No particular state labels, queues, forms, dashboards, buttons, or automated routes are documented in the source repository. Validate those details before turning this proposed journey into application instructions.

## Information handling and safety

Use synthetic requests in initial documentation and evaluation. Do not include names, dates of birth, addresses, medical identifiers, diagnoses, symptoms, attachments, or other patient-identifying information in public documentation, screenshots, issue reports, or sample data. Removing a name alone does not establish that a record is safe to share.

Before using real information, the authorized owners must define the purpose, minimum necessary data, permitted users, approved channels, storage, retention, and response to misdirected information. Verify any product controls against that approved design. Do not claim encryption, data residency, access restrictions, logging, automatic deletion, or third-party sharing behavior without evidence.

This draft is not an emergency service, clinical triage protocol, or medical recommendation. Any clinical question or urgent situation must follow the organization's established clinical and emergency processes rather than this documentation exercise. The final product documentation needs locally approved boundaries and escalation wording; no contact number or response-time promise is invented here.

## Pilot design and success criteria

Choose a synthetic administrative task, such as finding the correct route for a routine service-information request. Candidate observations include whether the participant can explain the service scope, locate the right route, identify the next owner, and understand whether a request has actually been accepted.

Define the test method, participants, permissions, and completion condition in advance. Administrative task observations must not be presented as evidence of faster care, better health, reduced clinical risk, regulatory compliance, or organization-wide efficiency. A specific, documented finding is a safer basis for iteration than an unsupported value claim.

## Dependencies and non-goals

A publishable product page depends on an identified product, accountable service owner, approved administrative workflow, and relevant specialist reviews. External identity services, electronic health records, scheduling tools, messaging providers, and analytics are neither confirmed dependencies nor supported integrations.

The proposed scope excludes diagnosis, treatment planning, clinical decision support, prioritization of medical urgency, automated triage, and assurances of clinical or regulatory suitability. It does not replace qualified professionals or local operational policy.

The [Education overview](../education/overview.md) offers a different context for access and service ownership. Similar wording does not imply equivalent safeguards, interchangeable information, or a shared application.

## Review and release checklist

- [ ] Identify the actual product, version, service owner, users, and environment.
- [ ] Approve a narrow non-clinical scope and document excluded situations.
- [ ] Validate every claimed action and any manual handoff against the real workflow.
- [ ] Confirm information flows, authorized participants, channels, and retention decisions.
- [ ] Complete the relevant privacy, security, accessibility, clinical-scope, and editorial reviews.
- [ ] Verify any screenshots and examples contain only approved, non-identifying material.
- [ ] Test the [user guide](user-guide.md) against the same product version.
- [ ] Approve publication separately from the pre-existing spotlight; do not imply certification or clinical benefit.

## Sources and maintenance

- [Healthcare spotlight source](https://github.com/np10879/asf-app/blob/main/app-index/healthcare.html): editorial themes and explicit limits on clinical, outcome, and compliance claims.
- [Publication metadata](https://github.com/np10879/asf-app/blob/main/app-index/metadata.json): current spotlight status, review notice, and unassigned ownership.
- [Existing app index](https://github.com/np10879/asf-app/blob/main/app-index/index.html): industry-level navigation, not an application inventory.

**Draft owner:** unassigned. Re-review after product, service, data-flow, integration, or governance changes.

## Documentation network

[Repository README](../../README.md) · [Documentation index](../README.md)

| Category | Product overview | User guide |
| --- | --- | --- |
| Education | [Overview](../education/overview.md) | [User guide](../education/user-guide.md) |
| Healthcare | **Overview (this page)** | [User guide](user-guide.md) |
| Discovery | [Overview](../discovery/overview.md) | [User guide](../discovery/user-guide.md) |

> All eight Markdown draft pages link directly to every other draft page through this navigation. The published HTML site has not been changed.
