# Changelog

[中文版本](CHANGELOG-CN.md)

All notable changes to ElasticPDF are documented in this file.

## [0.9.1] - 2026-08-26

This Web Preview update expands PDF editing with redaction, text replacement, and annotation workflows, while improving mobile interaction, document tabs, and browser/API integration.

### Added

#### Page Management and Editing

- Added a dedicated page-management workspace in the thumbnail view.
- Added single-page and multi-page selection, including range selection and rubber-band selection.
- Added drag-and-drop page reordering with a drag preview and directional drop markers.
- Added insertion of blank pages and pages from another PDF before or after a selected page.
- Added page actions to move a page up, down, to the top, or to the bottom, delete selected pages, and export a page or selection as PDF or images.

#### PDF Redaction

- Added text-selection redaction and rectangular area redaction.
- Added removal of covered text, images, and vector page content with a configurable color overlay.
- Added apply, clear, and color controls for pending redaction marks before saving.
- Added mobile redaction controls and matching popup actions.

#### Text Search and Replacement

- Added a replacement input and active-match replacement to the PDF search panel.
- Added case-sensitive and whole-word search filters, match navigation, progressive result loading, and replacement progress feedback.
- Replaced text is saved back to the PDF and rendered again through the existing editing pipeline.
- Improved text-resize feedback so the completed edit appears as one stable result instead of exposing intermediate line movement.

#### Annotation Workflows

- Added JSON import and export for annotations, including associated image attachments.
- Improved annotation filtering, page grouping, count stability, and list-to-page synchronization.
- Improved annotation popup actions and standardized action icons.

### Improved

#### PDF Reader and Mobile Experience

- Changed the mobile page indicator to a current-page / total-pages format.
- Centered the mobile loading indicator and preserved consistent side spacing.
- Improved mobile search-result display and reading-settings panel behavior.
- Fixed pinch zoom on WebKit-based browsers.
- Prevented duplicate zoom recalculation after editing on WebKit-based browsers.
- Reworked responsive top and bottom toolbars, the file-operation menu, and reading-settings entry points.
- Improved mobile reading, search, annotation-property, and settings-panel open, back, and viewport behavior.
- Improved touch gesture handling for text selection, drag-to-create annotations, and tool cancellation.

#### PDF Annotations and Text Editing

- Added mobile highlight, underline, strikethrough, and squiggly annotation actions.
- Prevented duplicate annotation creation after mouse selection and tool cancellation while preserving touch behavior.
- Added double-click cancellation for annotation tools.
- Standardized the default highlight-related color to `rgb(255, 205, 69)` and removed the duplicate default color option.
- Improved the mobile annotation entry icon and reduced annotation flicker during zoom.
- Improved page-based annotation deletion and annotation-property editing.
- Kept existing annotations visible while editing PDF text.
- Updated associated annotations and paths when edited text moves.
- Prevented duplicate temporary line drawing during text editing.
- Improved the commit timing for object resizing.
- Fixed coordinate offsets for text containing hyphens.
- Improved selection stability after repeatedly rotating text objects.

#### Page Structure and Rendering

- Synchronized the main canvas, thumbnails, annotations, and page navigation after page insertion, deletion, and reordering.
- Improved incremental refresh and cache invalidation after page-structure changes.
- Preserved annotations from inserted PDF pages and remapped annotation page indexes after page mutations.

#### Document State, UI, and Developer Experience

- Preserved loaded document state when switching between document tabs.
- Fixed repeated opening of the same file returning to the home view.
- Simplified top-level toolbar labels and refined compact toolbar spacing and icon sizing.
- Improved edited-text font resolution and bundled theme-font loading for production assets.
- Added HTTP and HTTPS development/preview commands with automatic local certificate support.
- Updated the browser API example to work with both source modules during development and packaged API builds, with visible initialization errors.
- Updated PWA metadata and application branding.

### Fixed

- Prevented invalid toolbar and popup icon references from rendering as `undefined`.
- Kept redaction confirmation and clear actions visually consistent between the toolbar and selection popup.
- Added safeguards around asynchronous text replacement and editing updates to prevent partial visual states from being committed.

### Validation

- Added regression coverage for page selection, page-drop geometry, thumbnail mutations, page-structure annotation remapping, redaction runtime and image handling, text search replacement, text-resize visuals, annotation transfer, toolbar icon references, development protocol scripts, and production font assets.
- Verified the release with targeted regression tests, production asset checks, and Vite builds.

---

## [0.9.0] - 2026-08-08

ElasticPDF v0.9.0 was the first public Web Preview release.

This version brought PDF reading, text editing, image and graphics editing, annotations, page operations, and document export together in a unified browser-based experience.

### Added

#### PDF Reader

- Page thumbnails and bookmark navigation.
- Full-document text search.
- Zoom from 10% up to 6400%.
- Continuous and page-by-page reading modes.
- Single-page, double-page, and book views.
- Horizontal and vertical scrolling.
- Page rotation.
- Light and dark modes.

#### PDF Text Editing

- Direct editing of existing PDF text without converting to Word.
- Inserting, deleting, and modifying text.
- Resizing and repositioning text blocks.
- Editing rotated, vertical, and angled text.
- Bold, text color, and alignment controls.
- Styled copy and paste.
- Preservation of original fonts, styles, and positions where possible.
- Exporting edited content back to standard PDF.

#### Image and Graphics Editing

- Direct selection and editing of existing PDF images and graphics.
- Moving, resizing, and rotating objects.
- Cropping and replacing images.
- Horizontal and vertical image flipping.
- Opacity adjustment.
- Precise object-size controls.
- Layer management.
- Bringing objects to the front or sending them to the back.
- Saving original images locally.
- Deleting selected objects.

#### PDF Annotations

- Highlight, underline, strikethrough, and squiggly annotations.
- Freehand drawing.
- Callouts and sticky notes.
- Text boxes and image annotations.
- Stamps and handwritten signatures.
- Editing annotation position, range, color, line width, line style, opacity, and other properties after creation.

#### Shapes and Markup

- Rectangle, circle, ellipse, line, arrow, polygon, polyline, and arc annotations.
- Hyperlink editing.
- Editing position, size, rotation, border, fill, line style, arrow endpoints, and path nodes after creation.

#### Page and Document Operations

- Adding pages.
- Deleting pages.
- Merging pages.
- Exporting documents.
- Saving edited PDFs.

#### Privacy and Platform

- Browser-side PDF processing for normal reading and editing workflows.
- Support for major modern browsers.
- Cross-platform architecture designed for Web, desktop, and mobile integration.

### Notes

- This release focused on the ElasticPDF Web experience.
- Desktop and mobile applications were still under development and improvement.
- v0.9.0 was published as a Web Preview rather than the final v1.0.0 release.

---

**ElasticPDF — Rediscover the Joy of Reading.**
