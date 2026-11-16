---
title: "ASF App \u2014 Documentation Index (Draft)"
status: draft
published: false
content_type: documentation-index
draft_date: "2026-11-16"
owner: unassigned
product_mapping: unconfirmed
required_reviews: ["product-owner", "editorial"]
---

# Documentation Index

> **Eight-page Markdown draft network.** Education, Healthcare, and Discovery are confirmed industry categories; actual app names and capabilities are not documented. This index connects proposed product-overview and user-guide pairs without implying that the products exist or the new pages are approved for publication.

Return to the [repository README](../README.md) for the project context and local preview of the existing HTML site.

## Coverage matrix

| Category | Existing editorial source | New product-overview draft | New user-guide draft | Product mapping |
| --- | --- | --- | --- | --- |
| Education | [Published Education spotlight](https://github.com/np10879/asf-app/blob/main/app-index/education.html) | [Education overview](education/overview.md) | [Education guide](education/user-guide.md) | Unconfirmed; owner needed. |
| Healthcare | [Published Healthcare spotlight](https://github.com/np10879/asf-app/blob/main/app-index/healthcare.html) | [Healthcare overview](healthcare/overview.md) | [Healthcare guide](healthcare/user-guide.md) | Unconfirmed; owner needed. |
| Discovery | [Published Discovery spotlight](https://github.com/np10879/asf-app/blob/main/app-index/discovery.html) | [Discovery overview](discovery/overview.md) | [Discovery guide](discovery/user-guide.md) | Unconfirmed; owner needed. |

All three categories already have an editorial overview. The gap addressed by this draft set is deeper product framing and practical workflow guidance. No additional named app can be identified from the repository alone, so this is not a definitive list of undocumented applications.

## Choose a reading path

### Evaluate the proposed product narrative

1. Start with the relevant [Education](education/overview.md), [Healthcare](healthcare/overview.md), or [Discovery](discovery/overview.md) overview.
2. Review the capability-validation matrix before interpreting any proposed capability as an available function.
3. Confirm the product boundary and the evidence required to support the narrative.
4. Use the paired guide to test whether the narrative maps to a real supported workflow.

### Plan an Education workflow review

Read the [Education overview](education/overview.md#purpose-and-positioning), then follow [Run a sample learning journey](education/user-guide.md#run-a-sample-learning-journey). If a question needs user research, use [Run a small discovery cycle](discovery/user-guide.md#run-a-small-discovery-cycle) rather than making an unsupported claim about learner needs.

### Plan a Healthcare administrative walkthrough

Read the [Healthcare boundaries](healthcare/overview.md#information-handling-and-safety), then follow [Walk through a non-clinical service request](healthcare/user-guide.md#walk-through-a-non-clinical-service-request). Keep the exercise synthetic and within approved administrative scope; clinical and urgent situations stay with established local processes.

### Plan a Discovery learning cycle

Read the [Discovery evidence model](discovery/overview.md#evidence-model-and-decision-quality), then use the [Discovery guide](discovery/user-guide.md). The goal is a bounded, reviewable decision—not a manufactured success narrative or a claim that an unrun experiment validated a hypothesis.

## Evidence and status conventions

Every proposed page distinguishes these states:

| State | Meaning | Example |
| --- | --- | --- |
| Confirmed repository fact | Supported by the reviewed source content. | An industry spotlight exists and names certain editorial themes. |
| Proposed concept or workflow | A draft direction needing product confirmation. | A learner-to-educator feedback journey or an administrative handoff. |
| Unverified product detail | Not established by the repository. | App name, screen labels, permissions, integrations, pricing, support channels, or availability. |
| Review gate | Work required before the draft can become approved documentation. | Product validation, an interface walkthrough, or relevant specialist review. |

A publication date on an existing spotlight does not approve a new product page. A plausible workflow is not proof that software implements it. A stated control is not evidence that it operates as described.

The front matter marks these pages `status: draft`, `published: false`, and `product_mapping: unconfirmed`. Treat those fields as editorial metadata, not a publication firewall or an access-control mechanism.

## Required app-inventory follow-up

Before claiming app-level coverage, complete an authoritative mapping with accountable owners:

| Category | Actual product name | Product owner | Verified product version | Evidence location | Documentation decision |
| --- | --- | --- | --- | --- | --- |
| Education | Not confirmed | Unassigned | Not confirmed | Not supplied | Keep category draft until reviewed. |
| Healthcare | Not confirmed | Unassigned | Not confirmed | Not supplied | Keep category draft until reviewed. |
| Discovery | Not confirmed | Unassigned | Not confirmed | Not supplied | Keep category draft until reviewed. |

If a category maps to several products, create one overview-and-guide pair per actual product rather than merging incompatible workflows. If it maps to no product, keep the editorial spotlight and label any future content as a concept or industry guide instead of product documentation.

## Review workflow

1. **Scope review:** confirm the actual product, audience, version, and supported use case.
2. **Evidence review:** replace or remove proposed claims according to approved product evidence. Avoid invented UI labels, endpoints, integrations, metrics, or customers.
3. **Guide walkthrough:** have an authorized reviewer follow every action in the correct environment, noting manual and unsupported steps.
4. **Specialist review:** complete the relevant accessibility, privacy, security, safeguarding, clinical-scope, or research-method review identified in the page.
5. **Editorial review:** verify clarity, source context, status labels, examples, link labels, and reciprocal navigation.
6. **Publication decision:** obtain explicit approval for the final content and delivery method. The approved homepage promotion links to the GitHub Markdown drafts; any rendered guide publication still needs a separate decision.

Ownership remains unassigned in this draft set. Listing a reviewer type does not imply that someone has accepted the task or granted approval.

## Link structure and maintenance

The “Documentation network” section on every draft page links directly to all seven other draft pages. Overview-and-guide pairs also link within their task context, and category-specific cross-links explain when another guide is relevant. Existing industry spotlights are linked as source material and remain unchanged. The homepage links to this draft network on GitHub.

Use relative Markdown file links within the draft network and descriptive headings for section anchors. If you rename a file or heading, update all referring links. If you add a category, add its pair to this index, the root README, and every shared navigation table; then check the link graph again. Cross-links do not imply shared software, permissions, data stores, or test results.

## Existing publication references

- [Site home source](https://github.com/np10879/asf-app/blob/main/index.html)
- [Existing app-index source](https://github.com/np10879/asf-app/blob/main/app-index/index.html)
- [Existing publication metadata](https://github.com/np10879/asf-app/blob/main/app-index/metadata.json)

These references establish provenance for the editorial baseline. The Markdown files are available as review drafts in the repository. Merging them and promoting their GitHub links does not approve their proposed capabilities or publish them as validated product guides.

## Documentation network

[Repository README](../README.md) · **Documentation index (this page)**

| Category | Product overview | User guide |
| --- | --- | --- |
| Education | [Overview](education/overview.md) | [User guide](education/user-guide.md) |
| Healthcare | [Overview](healthcare/overview.md) | [User guide](healthcare/user-guide.md) |
| Discovery | [Overview](discovery/overview.md) | [User guide](discovery/user-guide.md) |

> All eight Markdown draft pages link directly to every other draft page through this navigation. The homepage links to these review drafts on GitHub; the category guides remain unpublished.
