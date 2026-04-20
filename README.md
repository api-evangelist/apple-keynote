# Apple Keynote (apple-keynote)
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
