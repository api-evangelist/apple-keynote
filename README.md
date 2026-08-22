# Apple Keynote (apple-keynote)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Apple Keynote is a presentation software application developed by Apple Inc. as part of the iWork productivity suite, available on macOS, iOS, iPadOS, and the web via iCloud. It enables creating visually rich presentations with animations, transitions, charts, and real-time collaboration. Keynote supports automation via AppleScript, JavaScript for Automation (JXA), and Apple Shortcuts, and provides iCloud-based access for cross-device sync and sharing.

**URL:** [Visit APIs.json URL](https://www.apple.com/keynote/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Apple, Design, iWork, Presentations, Productivity, Slides

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### Keynote iCloud API
Cloud-based API for accessing and manipulating Keynote presentations through iCloud, enabling programmatic creation, management, slide operations, and multi-format export of presentations stored in iCloud.

**Human URL:** [https://www.icloud.com/keynote](https://www.icloud.com/keynote)

#### Tags:

 - Cloud Storage, Collaboration, Presentations, Slides, iCloud

#### Properties

- [Documentation](https://developer.apple.com/documentation/)
- [OpenAPI](openapi/apple-keynote-icloud-openapi.yaml)
- [JSONSchema - Presentation Schema](json-schema/apple-keynote-presentation-schema.json)
- [JSONSchema - Slide Schema](json-schema/apple-keynote-slide-schema.json)
- [JSONSchema - Theme Schema](json-schema/apple-keynote-theme-schema.json)
- [JSONSchema - Export Request Schema](json-schema/apple-keynote-export-request-schema.json)

### Keynote AppleScript API
Local automation API for Keynote using AppleScript, enabling programmatic control of presentations, slides, and elements on macOS.

**Human URL:** [https://developer.apple.com/library/archive/documentation/AppleScript/Conceptual/AppleScriptLangGuide/](https://developer.apple.com/library/archive/documentation/AppleScript/Conceptual/AppleScriptLangGuide/)

#### Tags:

 - Automation, Local API, macOS, Scripting

#### Properties

- [Documentation](https://developer.apple.com/library/archive/documentation/AppleApplications/Conceptual/KeynoteScriptingGuide/)
- [APIReference](https://developer.apple.com/library/archive/documentation/AppleApplications/Conceptual/KeynoteScriptingGuide/)

### Keynote JavaScript for Automation API
JavaScript-based automation interface for controlling Keynote on macOS using JXA and the Open Scripting Architecture.

**Human URL:** [https://developer.apple.com/library/archive/releasenotes/InterapplicationCommunication/RN-JavaScriptForAutomation/](https://developer.apple.com/library/archive/releasenotes/InterapplicationCommunication/RN-JavaScriptForAutomation/)

#### Tags:

 - Automation, JavaScript, macOS, Scripting

#### Properties

- [Documentation](https://developer.apple.com/library/archive/releasenotes/InterapplicationCommunication/RN-JavaScriptForAutomation/)

### Keynote Shortcuts Actions
Shortcuts app actions for Keynote on iOS, iPadOS, and macOS, enabling automated presentation workflows.

**Human URL:** [https://developer.apple.com/shortcuts/](https://developer.apple.com/shortcuts/)

#### Tags:

 - Automation, iOS, Shortcuts, Workflows

#### Properties

- [Documentation](https://developer.apple.com/documentation/appintents/app-shortcuts)

## Common Properties

- [Portal](https://developer.apple.com/)
- [Documentation](https://support.apple.com/guide/keynote/)
- [Support](https://developer.apple.com/support/)
- [TermsOfService](https://developer.apple.com/support/terms/)
- [PrivacyPolicy](https://www.apple.com/privacy/)
- [StackOverflow](https://stackoverflow.com/questions/tagged/keynote)
- [YouTube](https://www.youtube.com/@AppleDeveloper)

## Features

| Name | Description |
|------|-------------|
| Multi-Platform Availability | Available on macOS, iOS, iPadOS, and web browsers via iCloud |
| Real-Time Collaboration | Multiple users can edit presentations simultaneously via iCloud sharing |
| Magic Move Transitions | Intelligent morph transitions that animate elements between slides |
| AppleScript Automation | Full scripting support via AppleScript and JavaScript for Automation |
| Shortcuts Integration | Apple Shortcuts actions for automated presentation workflows on iOS and macOS |
| Multi-Format Export | Export to PDF, PowerPoint (.pptx), HTML, images, and native .key format |
| Live Video Presenter | Present with live video overlays in video conferencing applications |
| Cinematic Animations | Rich build-in and build-out animations for slide elements |
| Charts and Data Visualization | Built-in chart types including bar, line, pie, scatter, and more with live data |

## Use Cases

| Name | Description |
|------|-------------|
| Business Presentations | Creating professional pitch decks, board presentations, and quarterly reviews |
| Educational Content | Designing lecture slides, course materials, and educational presentations |
| Marketing Materials | Producing brand presentations, product launches, and sales decks |
| Automated Report Generation | Using AppleScript or Shortcuts to programmatically generate recurring presentation reports |
| Conference Presentations | Creating polished conference talks with animations and transitions |
| Training Materials | Building step-by-step training and onboarding presentations |

## Integrations

| Name | Description |
|------|-------------|
| iCloud Drive | Automatic sync and storage of presentations across Apple devices |
| Apple Numbers | Import live chart data from Numbers spreadsheets |
| Apple Pages | Cross-link documents and share content between Pages and Keynote |
| Microsoft PowerPoint | Import and export PPTX files for cross-platform compatibility |
| Zoom | Present directly from Keynote in Zoom video calls |
| Apple Shortcuts | Automate presentation creation and export workflows on iOS and macOS |
| Spotlight | Index and search Keynote presentation content via macOS Spotlight |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apple Keynote iCloud API](openapi/apple-keynote-icloud-openapi.yaml)

### JSON Schema

- [Presentation Schema](json-schema/apple-keynote-presentation-schema.json)
- [Slide Schema](json-schema/apple-keynote-slide-schema.json)
- [Theme Schema](json-schema/apple-keynote-theme-schema.json)
- [Export Request Schema](json-schema/apple-keynote-export-request-schema.json)

### JSON Structure

- [Presentation Structure](json-structure/apple-keynote-presentation-structure.json)
- [Slide Structure](json-structure/apple-keynote-slide-structure.json)
- [Theme Structure](json-structure/apple-keynote-theme-structure.json)
- [Export Request Structure](json-structure/apple-keynote-export-request-structure.json)

### JSON-LD

- [Apple Keynote Context](json-ld/apple-keynote-context.jsonld)

### Examples

- [Presentation Example](examples/apple-keynote-presentation-example.json)
- [Slide Example](examples/apple-keynote-slide-example.json)
- [Theme Example](examples/apple-keynote-theme-example.json)
- [Export Request Example](examples/apple-keynote-export-request-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Apple Keynote iCloud API](capabilities/shared/apple-keynote-icloud.yaml) — 8 operations for iCloud presentation management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Presentation Automation](capabilities/presentation-automation.yaml) | Keynote iCloud API | 6 | Content Creator, Marketing Professional |

## Vocabulary

- [Apple Keynote Vocabulary](vocabulary/apple-keynote-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 7 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Apple Keynote Spectral Rules](rules/apple-keynote-spectral-rules.yml) — 22 rules across 8 categories enforcing Apple Keynote API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
