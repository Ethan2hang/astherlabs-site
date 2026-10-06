# SynthFlow product website

Compiled static build for https://astherlabs.ai/.
GitHub Pages serves the repository root on `main`; `.nojekyll` is intentional.

The homepage uses the accepted charcoal sound landscape, a solid lavender opening title, silver controls, and an always-visible header that contracts into a centred floating bar on scroll. The recorded Workbench stages sound/refinement selections silently and plays only on explicit Play.
Product routes: `/`, `/workflow/`, `/reference-audio/`, `/preview/`, at the domain root.
The actual frontend preview has been retired. `/interface/index.html` shows a static notice, and `/preview/` explains current availability.
Keep `CNAME` containing `astherlabs.ai` when replacing the compiled files.

## Scope and provenance

This is a development demonstration, not a verified SynthFlow product release.
The catalogue contains nine supplied WAV recordings for the homepage Bass, Lead, and Pad examples, plus 39 legacy AAC assets. It has eight prompts with only two distinct displayed parameter recipes. The rendering process for the supplied WAV files has not been independently verified. A verified keyed render is still required before formal release.
The page retains its exact offline-render disclosure, Audio provenance details, and backend/plugin availability boundaries.
The source project retains the failing catalogue release gate; this static repository does not run or bypass it.

The repository contains compiled browser assets, the recorded catalogue, the static retirement notice. It does not include the product backend, native plugin, API keys, node_modules or the React source project.

The old astherlabs.com domain remains on its existing Pages repository and redirects browsers here.

September 13, 2026: the runnable interface JS/CSS and original downloadable frontend ZIP were withdrawn. Hear it and its 48 recordings remain available.

September 19, 2026: replaced the homepage with the accepted sound-landscape full-site design. Team, beta status, development video and the three product-detail routes remain available. Private experiment pages are excluded from the published artifact.

September 28, 2026: integrated the approved Asther Labs mark into the homepage and product-page headers/footers and browser icon. SynthFlow remains the product name. Email signup remains unavailable while its delivery and storage are being configured.

September 30, 2026: enabled email-based beta requests to support@astherlabs.com after verifying two-way mailbox delivery and SPF, DKIM and DMARC authentication. The request action opens the visitor's email app with a subject; the visitor must send the message. This does not create an on-page signup list or guarantee an invitation. The Team section keeps Tony, Kevin and Ethan and uses one shared support contact; the retired individual email links have been removed.

October 3, 2026: replaced the nine homepage Bass, Lead, and Pad recordings with locally supplied WAV files. The Pad “Wider” demo is now labeled “Pitch bend”; its internal `wider` branch key is retained for compatibility with the compiled interface. The remaining 39 catalogue clips are legacy AAC recordings.

October 5, 2026: published the reviewed Workbench recovery with the ordered particle layout, current recording-to-terrain mapping, shared opening-to-Workbench geometry, smooth staged selection and explicit playback. This is the current-audio/current-mapping version reviewed locally on port 4256; private diagnostic controls and historical-media comparison routes are excluded. All recordings, catalogue data, images, videos, contact destinations and domain settings are preserved. Remaining Lead brightness/banding limitations and the formal 2/8 catalogue gate are not represented as resolved. Production build and 243 focused landscape tests passed; the catalogue checks retain the known release-gate failure.
