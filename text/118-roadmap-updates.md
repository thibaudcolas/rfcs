# RFC 118: Public roadmap updates

- RFC: 118
- Author: Thibaud Colas
- Created: 2026-11-04
- Last Modified: 2026-11-11

## Abstract

This RFC provides a high-level overview of proposed [public roadmap](https://github.com/wagtail/roadmap) updates for future releases. For context, see [past roadmap-focused RFCs](https://github.com/wagtail/rfcs/pulls?q=is%3Apr+label%3Aroadmap) and the [Wagtail release schedule](https://github.com/wagtail/wagtail/wiki/Release-schedule).

## Version number for the next release

Provisional version number: v8.2 (minor release), in February 2027 based on discussions to date.

## Roadmap for the previous release

Here is the status of roadmap items for the latest release, v8.1 (November 2026):

| Roadmap item                                                                 | Status | Notes                          |
| ---------------------------------------------------------------------------- | ------ | ------------------------------ |
| [SEO power tools](https://github.com/wagtail/roadmap/issues/106)             | Done   | Follow-ups outside the roadmap |
| [Agent-ready publishing](https://github.com/wagtail/roadmap/issues/244)      | Done   | Follow-ups outside the roadmap |
| [Wagtail Space 2026](https://github.com/wagtail/roadmap/issues/233)          | Done   | Follow-ups outside the roadmap |
| [Agent skills for DX](https://github.com/wagtail/roadmap/issues/241)         | Done   | Follow-ups outside the roadmap |
| [Security process automation](https://github.com/wagtail/roadmap/issues/240) | Done   | Follow-ups outside the roadmap |
| [Write API follow-ups](https://github.com/wagtail/roadmap/issues/239)        | Done   | Follow-ups outside the roadmap |
| [Maintenance automation](https://github.com/wagtail/roadmap/issues/243)      | Done   | Follow-ups outside the roadmap |

## Roadmap for the next release

Proposed roadmap items for v8.2 (February 2027).

| Item                                                          | Size | Strategic theme                    |
| ------------------------------------------------------------- | ---- | ---------------------------------- |
| [JPEG XL images support](#jpeg-xl-images-support)             | S    | 🏔️ Future-ready content management |
| [API v3 stable](#api-v3-stable)                               | L    | 🏗️ Enabling capabilities           |
| [Permission model refinements](#permission-model-refinements) | L    | 🏗️ Enabling capabilities           |
| [Documentation overhaul](#documentation-overhaul)             | L    | 🏗️ Enabling capabilities           |
| [MCP UX experimentation](#mcp-ux-experimentation)             | L    | 🏔️ Future-ready content management |

### [JPEG XL images support](https://github.com/wagtail/roadmap/issues/235)

Size: M, Strategic theme: 🏔️ Future-ready content management

Support for [JPEG XL](https://en.wikipedia.org/wiki/JPEG_XL) (.jxl) image uploads and renditions in Wagtail. JPEG XL delivers archival-quality images at significantly lower file sizes than JPEG and PNG, making it a compelling upload and storage format. This will become more essential with improving browser support, so we can achieve tangible reductions in web pages weight with the new format.

### API v3 stable

Size: L, Strategic theme: 🏗️ Enabling capabilities

Continuation of [Write API follow-ups](https://github.com/wagtail/roadmap/issues/239). Stabilization of the [v3 API](https://docs.wagtail.org/en/latest/advanced_topics/api/v3/index.html) to drop its 'preview' label, with the goal of it being a safe default for new headless projects and production-ready for "write" integration use cases. Tentatively including:

- Adoption of the v3 API for [bakerydemo-headless](https://github.com/wagtail/bakerydemo-headless)
- Dogfooding of API v3 for the Wagtail user guide, and wagtail.org
- More API v3 content in developer docs, user docs, tutorials, marketing.
- API v2 feature parity, formal deprecation, and official "v2 API" replacement package.
- More advanced authentication features (tokens expiry, pluggable auth, etc)

### Permission model refinements

Size: L, Strategic theme: 🏗️ Enabling capabilities

Improvements to Wagtail's permissions model beyond the current page tree-based inheritance. Tentatively including:

- [Implement a 'choose' permission for pages](https://github.com/wagtail/wagtail/issues/9714)
- TBC: [Implement a "choose" permission for non-page models (snippets etc.)](https://github.com/wagtail/wagtail/issues/14272)
- Per-instance permission checks for [custom permissions support](https://github.com/wagtail/wagtail/issues/2907) / [assign page level permissions to a user](https://github.com/wagtail/wagtail/issues/4498).

### [Documentation overhaul](https://github.com/wagtail/roadmap/issues/236)

Size: L, Strategic theme: 🏗️ Enabling capabilities

New documentation audit and [documentation reorganisation](https://github.com/wagtail/wagtail/issues/6781) to increase the quantity and quality of our docs, in line with the [product strategy](https://wagtail.org/product-strategy/). Expecting more content for developer docs, user guide, and marketing.

### MCP UX experimentation

Size: M, Strategic theme: 🏔️ Future-ready content management

Iterations on the experimental [Wagtail MCP package](https://github.com/wagtail/wagtail-mcp) with a focus on user experience and production readiness. The goal is to incorporate feedback from early adopters, address identified gaps, and understand where MCP fits into how people will use Wagtail in 2027.

Tentative scope:

- Experimentation with in-CMS agentic UIs via [MCP Apps](https://modelcontextprotocol.io/extensions/apps/overview) / [AG-UI](https://docs.ag-ui.com/introduction) / [A2UI](https://a2ui.org/).
- Production infrastructure compatibility to support larger-scale experimentation.
- Prompt injection defense / red teaming of agentic CMS setups.

Also includes work on the [User guide MCP](https://guide.wagtail.org/en/about/documentation-formats/#mcp-server), to provide agents with guidance on how Wagtail works.

## Roadmap for the next+1 release

Proposed roadmap items for v8.3 LTS (May 2027).

| Item                                                                        | Size | Strategic theme                    |
| --------------------------------------------------------------------------- | ---- | ---------------------------------- |
| [Integrated measurement and tracking](#integrated-measurement-and-tracking) | L    | 🏔️ Future-ready content management |
| [Shareable previews](#shareable-previews)                                   | S    | 🏔️ Future-ready content management |
| [Generic content importer](#generic-content-importer)                       | M    | 🏔️ Future-ready content management |
| [API v3 final](#api-v3-final)                                               | L    | 🏔️ Future-ready content management |

### [Integrated measurement and tracking](https://github.com/wagtail/roadmap/issues/247)

Size: L, Strategic theme: 🏔️ Future-ready content management

_Moving from Wagtail 8.2, to Wagtail 8.3 LTS_.

### [Shareable previews](https://github.com/wagtail/roadmap/issues/237)

Size: S, Strategic theme: 🏔️ Future-ready content management

_Moving from "Future" backlog to Wagtail 8.3 LTS, pending feature sponsorship._

### [Generic content importer](https://github.com/wagtail/roadmap/issues/245)

Size: M, Strategic theme: 🏔️ Future-ready content management

_Moving from "Future" backlog to Wagtail 8.3 LTS, pending feature sponsorship._

### API v3 final

Size: L, Strategic theme: 🏗️ Enabling capabilities

Finalization of the API v3 and deprecation of the v2 API.

## Roadmap for "Future" releases

### [Enhanced dashboard UX](https://github.com/wagtail/roadmap/issues/246)

Size: M, Strategic theme: 🏔️ Future-ready content management

_Moving from Wagtail 8.2, to "Future" backlog_.

## Proposed roadmap items to close

### [Permissions registry](https://github.com/wagtail/roadmap/issues/81)

Key foundations shipped in Wagtail 8.0, and there is more coming in Wagtail 8.2 as part of [Permission model refinements](#permission-model-refinements). There is not a lot of value in keeping the roadmap item.

## Items that didn't make the cut

- [Choosers UI improvements #109](https://github.com/wagtail/roadmap/issues/109): still a high-value item but deferred until we are more confident in the overall direction of the Wagtail admin UI.
- Agentic security auditing: we will experiment with this outside of the roadmap
- SEO power tools follow-ups: too small to warrant inclusion in the roadmap at this stage
- [CLI](https://github.com/wagtail/wagtail-cli) improvements: can happen in parallel to API development
