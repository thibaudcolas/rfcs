# RFC 116: Public roadmap updates

- RFC: 116
- Author: Thibaud Colas
- Created: 2026-05-05
- Last Modified: 2026-06-09

## Abstract

This RFC provides a high-level overview of proposed [public roadmap](https://github.com/wagtail/roadmap) updates for future releases.
For context, see [past roadmap-focused RFCs](https://github.com/wagtail/rfcs/pulls?q=is%3Apr+label%3Aroadmap) and the [Wagtail release schedule](https://github.com/wagtail/wagtail/wiki/Release-schedule).

## Proposed roadmap items to close

### [Draftail for general text entry](https://github.com/wagtail/roadmap/issues/26)

> Switch to a rich text style UI for plain text inputs, to support more advanced text interactions.

This kind of switch is still desirable but Draftail is likely not the right foundation as the underlying Draft.js library is [unmaintained since 2022](https://github.com/wagtail/draftail/issues/456).

### [Sustainability improvements](https://github.com/wagtail/roadmap/issues/72)

> Improvements across three key areas for Wagtail sites’ carbon footprints: measurements, awareness, tangible reductions.

Most of the improvements tracked in the roadmap item have been happening incrementally, and the remaining ones will be better served by more precise tracking either on the roadmap or directly in our feature backlog.

### [Fully accessible admin](https://github.com/wagtail/roadmap/issues/27)

> Work towards making [Wagtail’s accessibility](https://wagtail.org/accessibility/) world-class – stellar feedback from users of assistive technologies on the admin interface. Full compliance with relevant standards: WCAG, ATAG.

This is the right long-term goal but it’s not served well by being on the roadmap in "Future" with a vague roadmap item. We’re making continuous improvements to the accessibility of Wagtail, so this work is happening anyway.
