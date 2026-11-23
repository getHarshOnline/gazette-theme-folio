# Composing Folio pages

The [presentation package](../presentation.toml) declares the exact component and resource contract. The [world brief](../WORLD.md) records the accepted composition and its reasons. Base’s `docs/page-families.md`, `docs/reading.md`, `docs/listings-and-cards.md` and `docs/films-and-scenes.md` own the shared behavior.

## Authored programme and project pages

Select `folio/home.html` for Home, `folio/programme.html` for a programme account and `folio/research.html` for an ordinary research project, or `folio/directory.html` for an authored research directory. `programme-opening` retains the programme's registers. Project entrances use Base's `page-opening`; `research-opening` remains a compatibility adapter to that anatomy, with explicit question and premise copy roles. Section components keep a question beside its continuous `register-copy`. `comparison-plate` gives an authored table the field it needs.

For a simultaneous comparison, `research-comparison` holds an introductory label and boundary, two `comparison-case` sections, and shared `comparison-criteria`. Conditions, responses and criteria are ordinary Markdown in those bodies; the theme adds no scores or implied progression.

`register-copy` carries continuous Markdown by default. Its optional `question`, `premise`, `context` and `conclusion` roles identify the opening and comparison registers explicitly; each role can contain several paragraphs through Base’s prose flow in `docs/reading.md`.

A directory's `programme-section` puts its `context` register before the heading and continuous copy. Paragraph position does not assign a role. All copy, distinctions and evidence remain in Content. These forms do not create formal papers, computed results or a finished cinematic sequence.

## Ambient editorial opening

`editorial-film` is one viewport in ordinary flow. Content supplies `editorial-copy` containing `editorial-title` and `editorial-details`. Without `editorial-source`, the opening uses the current mineral stock, with an optional `editorial-reveal-source` film behind the shared dither aperture. An authored foreground film still uses a resolved `editorial-source` and complete poster in `editorial-still`. The latter groups `editorial-caption` beside `editorial-description`; no paragraph position infers these roles.

The opening uses restrained reading type, one hairline and staggered entry. The actual publication identity stays centred within bounded navigation across page families; five-destination directories balance three links before it and two plus utilities after it. Base selects the compact menu independently; reading rails retain their own layout.

The controller-bound Home masthead stays fixed over the film and its continuation. Base’s existing ambient-position state returns the header to the current stock palette after the film; shared film-ink support follows that palette and the measured header clearance remains active. Without the controller, the full native navigation retains its original readable overlay fallback.

Base's optional `module:ambient-video` owns the shared visibility, preferences and teardown lifecycle. Its `mountAmbientSurface` export activates the reveal without creating or acquiring a foreground video; `mountAmbientVideo` adds muted looping playback and poster fallback. The shared Settings motion preference controls the atmospheric scene; it has no separate playback control, scroll clock or sampled frame list. Reduced motion, unavailable foreground playback and no script retain the supplied poster and complete copy. The quiet opening retains its stock and complete copy when motion or scripts are unavailable. Print retains ordinary text without scenic height. Navigation changes to stock as the opening leaves, and the continuation and bounded colophon keep their own reading groups. The composing workspace selects the media resource. Loading it locally does not establish permission to publish it.

## Collection bookmarks

Collection directories inherit Base’s bookmark composition in `docs/listings-and-cards.md`. This world supplies type, material and artwork; shared anatomy determines capacity and spacing.

## Generated editorial indexes

Generated article listings inherit Base's compact `reading-list`: each entry keeps its linked title, supplied author attribution and publication date, and summary in one reading track. Base owns the anatomy, measure and responsive spacing; this world supplies its existing type and material roles. Missing metadata stays absent. Authored collection and sequence contents retain their `publication-index` forms, while explicitly selected collection directories keep their bookmark composition.

## Canonical project and service selectors

`folio/product.html`, `folio/product-listing.html` and `folio/services.html` inherit Base's detail, directory and service compositions. The world selectors add the existing font declarations; Base owns their shared body roles and anatomy. Content owns introductions, demonstrations, status, destinations, questions and answers. The composing workspace selects the service composition only where actual offers are supplied; templates supply no copy or offers.

`folio/research.html` and `folio/directory.html` remain compatibility selectors for product detail and product listing respectively. The directory retains its ordinary footer policy.

## Shared frame and focus ownership

The opening retains its source composition while navigation responds to the current surface. Base owns focus painting and menu behavior, described in its `docs/settings-and-states.md`. Folio supplies contextual ink and role colours; scholarly stock and analytical rows keep their own contours.

The authored account uses its source headings while the native document title remains available to navigation and metadata.

Part of [gazette-theme-folio](../README.md).
