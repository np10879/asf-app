---
title: "ASF App \u2014 Documentation Drafts"
status: draft
published: false
content_type: repository-readme
draft_date: "2026-11-16"
owner: unassigned
product_mapping: unconfirmed
required_reviews: ["product-owner", "editorial"]
---

# ASF App — Documentation Drafts

> **Review drafts only.** The current repository contains published industry spotlights, not an inventory of verified applications. This proposed README introduces six new category documentation drafts. Nothing in this draft set establishes a shipped product, an operational feature, a measured outcome, or permission to publish.

## Start here

Open the [documentation index](docs/README.md) for the coverage matrix, reading paths, and publication gates.

| Category | Product overview draft | User guide draft |
| --- | --- | --- |
| Education | [Audience, proposed scope, and evidence requirements](docs/education/overview.md) | [A sample learning journey](docs/education/user-guide.md) |
| Healthcare | [Non-clinical access and coordination scope](docs/healthcare/overview.md) | [A synthetic administrative service request](docs/healthcare/user-guide.md) |
| Discovery | [Research, experimentation, and opportunity validation](docs/discovery/overview.md) | [A bounded learning cycle](docs/discovery/user-guide.md) |

Each overview explains the audience, proposed value, capability-validation matrix, safety boundaries, evidence requirements, and release checks. Each guide supplies prerequisites, a detailed product-neutral workflow, completion checks, a synthetic example or record template, troubleshooting, and review requirements.

## Existing site and source material

The pre-existing pages remain editorial overviews:

- [Site home source](https://github.com/np10879/asf-app/blob/main/index.html)
- [Existing app-index source](https://github.com/np10879/asf-app/blob/main/app-index/index.html)
- [Education spotlight](https://github.com/np10879/asf-app/blob/main/app-index/education.html)
- [Healthcare spotlight](https://github.com/np10879/asf-app/blob/main/app-index/healthcare.html)
- [Discovery spotlight](https://github.com/np10879/asf-app/blob/main/app-index/discovery.html)
- [Publication metadata for those spotlights](https://github.com/np10879/asf-app/blob/main/app-index/metadata.json)

The existing publication approval applies to those spotlights, not these new Markdown drafts. The HTML pages and their navigation have not been edited. Links to the source pages are provenance references, not evidence that proposed product functions exist.

## Reading and previewing

Read these Markdown files in GitHub's file viewer or a Markdown viewer that resolves relative file links. All eight draft Markdown pages have direct reciprocal navigation in their “Documentation network” section.

For the existing static HTML site, the current home page documents this local-preview approach from a repository checkout:

```sh
python3 -m http.server 8000
```

Open `http://localhost:8000/` to inspect the HTML site. This command does not convert these Markdown drafts into new website pages or validate any product capability.

## Repository layout after adding the proposed files

```text
README.md                         proposed repository entry point
app-index/                        existing industry spotlights; unchanged
docs/
  README.md                       draft documentation index
  education/
    overview.md                   category product-overview draft
    user-guide.md                 category workflow-guide draft
  healthcare/
    overview.md
    user-guide.md
  discovery/
    overview.md
    user-guide.md
index.html                        existing site home; unchanged
thumbnails/                       existing assets; unchanged
```

## What needs review before publication

1. Map each category to the actual product or explicitly keep it as an industry concept.
2. Assign product and documentation owners.
3. Verify supported actions, interfaces, permissions, data flows, availability, and help routes.
4. Replace hypothetical product descriptions only where there is approved evidence.
5. Complete the category-specific reviews and guide walkthroughs.
6. Decide whether to publish Markdown, build rendered pages, or change website navigation; none of those decisions has been applied by this draft package.

The `status: draft`, `published: false`, and `product_mapping: unconfirmed` front-matter fields communicate review state. They are not access controls or a guarantee of how every site generator behaves.

## Provenance

Drafted on 2026-11-16 from the repository's current `main` content, checked against root tree `c10a08c02eea98d83832cce35fbb41e8dfd48683`. Existing spotlights establish themes only. No additional app categories, product features, integrations, pricing, customers, outcomes, or approval decisions have been invented as facts.

## Documentation network

**Repository README (this page)** · [Documentation index](docs/README.md)

| Category | Product overview | User guide |
| --- | --- | --- |
| Education | [Overview](docs/education/overview.md) | [User guide](docs/education/user-guide.md) |
| Healthcare | [Overview](docs/healthcare/overview.md) | [User guide](docs/healthcare/user-guide.md) |
| Discovery | [Overview](docs/discovery/overview.md) | [User guide](docs/discovery/user-guide.md) |

> All eight Markdown draft pages link directly to every other draft page through this navigation. The published HTML site has not been changed.
