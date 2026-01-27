# RFC 113: Public roadmap updates

- RFC: 113
- Author: Thibaud Colas
- Created: 2026-01-27
- Last Modified: 2026-01-27

## Abstract

This RFC provides a high-level overview of proposed [public roadmap](https://github.com/wagtail/roadmap) updates for future releases. For context, see [past roadmap-focused RFCs](https://github.com/wagtail/rfcs/pulls?q=is%3Apr+label%3Aroadmap) and the [Wagtail release schedule](https://github.com/wagtail/wagtail/wiki/Release-schedule).

## Version number for the next release

Confirmed version number: v7.4 LTS (minor release), in May 2026 based on discussions to date.

## Roadmap for the previous release

Here is the status of roadmap items for the latest release, v7.3 (February 2026):

| Roadmap item                                                               | Status | Notes                          |
| -------------------------------------------------------------------------- | ------ | ------------------------------ |
| [Autosave MVP](https://github.com/wagtail/roadmap/issues/47)               | Done   | UX follow-ups on the roadmap   |
| [Block settings](https://github.com/wagtail/roadmap/issues/103)            | Done   | Follow-ups outside the roadmap |
| [Model search improvements](https://github.com/wagtail/roadmap/issues/116) | TBC    |                                |
| [llms.txt for Wagtail docs](https://github.com/wagtail/roadmap/issues/117) | Done   | Follow-ups outside the roadmap |
| [AI checker concepts](https://github.com/wagtail/roadmap/issues/118)       | v7.4\* | Ongoing work                   |

## Roadmap for the next release

Proposed roadmap items for v7.4 LTS (May 2026).

### [Customizable page explorer](https://github.com/wagtail/roadmap/issues/102)

Size: M

Support for customizations such as additional columns (and filters), reducing the need for developers to create custom views for pages (see [Custom page listings](https://docs.wagtail.org/en/stable/advanced_topics/customization/custom_page_listings.html#custom-page-listings)). See [Support custom columns / filters on main page explorer #11931](https://github.com/wagtail/wagtail/issues/11931) for more info.

### [Independent security audit](https://github.com/wagtail/roadmap/issues/111)

Size: S

An independent audit of the product and-or project for us to procure. Populate a backlog of security improvements based on audit activities.

### [Package maintainers guide](https://github.com/wagtail/roadmap/issues/108)

Size: XS

Revamp of the existing [Python Package Maintenance Guidelines](https://github.com/wagtail/wagtail/wiki/Python-Package-Maintenance-Guidelines), to add more content, reflect the work on [Wagtail Nest](https://github.com/wagtail-nest), and modernize.

### [Natural language search](https://github.com/wagtail/roadmap/issues/119)

Size: L

**Tentative item, highly dependent on evolution of vector indexing / search capabilities across database backends**. Improvement to Wagtail's search interface to support natural language queries. Depending on underlying search backend capabilities, this would either be:

- Vector search, with semantic understanding of queries and content.
- Or RAG (retrieval-augmented generation) approach, combining traditional search with LLMs to interpret queries and content.
- Or (TBC) conversational search interface, with follow-up questions and clarifications.

See also: [Model search improvements](https://github.com/wagtail/roadmap/issues/116), [wagtail-vector-index](https://github.com/wagtail/wagtail-vector-index).

### Autosave UI refinements

Size: S

Follow-up improvements to the [Autosave MVP](https://github.com/wagtail/roadmap/issues/47) based on user feedback and real-world usage. Tentatively including:

- UI polish based on feedback from v7.3 release
- Performance optimizations
- TBC: Additional configuration options

### Customization docs

Size: S

Documentation improvements focused on common customization patterns in Wagtail, building on the customizable page explorer work and other recent extensibility improvements. Tentatively including:

- Comprehensive customization guides
- Best practices for extending Wagtail admin views
- Migration guides for common third-party customizations

### Strict CSP

TBC

## Roadmap for the next+1 release

Proposed roadmap items for v7.5\* (August 2026).

## Roadmap for "Future" releases

### Multilingual content lifecycle

Improve Wagtail’s support for multilingual websites by addressing common workflow, UX, and data‑model pain points around creating, updating, reviewing, and maintaining translated content. Tentatively includes:

- Better workflows for maintaining translations.
  - Simpler access to past translations.
  - Switch page language.
  - Translation history / audit trail.
  - TBC: Simultaneous drafts on both source and target content.
- Better editor UX for translation work: more contextual information, rich text support.
- Improved tooling to compare content across locales (source vs translation, and version‑to‑version).
- TBC: Improvements for workflows involving machine translations.

More information:

- [Improving support for multilingual websites #13693](https://github.com/wagtail/wagtail/discussions/13693)
- [RFC 54: Internationalisation](https://github.com/wagtail/rfcs/blob/main/text/054-internationalisation.md)
- [Wagtail Localize issue tracker](https://github.com/wagtail/wagtail-localize/issues)
- [Wagtail issues tagged 'i18n'](https://github.com/wagtail/wagtail/issues?q=sort%3Aupdated-desc%20is%3Aissue%20is%3Aopen%20label%3Acomponent%3Ai18n)

## Proposed roadmap items to close

None

## Items that didn't make the cut

Here are possible roadmap items that were discussed but not included in the roadmap this time, provided for feedback and for future reference. If one of those items is important to you, please comment! They may be available for external contributions or for a [feature sponsorship](https://wagtail.org/sponsor/).

- TODO
