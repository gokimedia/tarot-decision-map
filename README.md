# Tarot Decision Map

A concise five-step framework for reflective tarot readings and grounded decision-making.

The project publishes an indexable companion page for the visual board:

- [Open the live GitHub Pages resource](https://gokimedia.github.io/tarot-decision-map/)
- [View the Tarot Decision Map on Miro](https://miro.com/app/board/uXjVHsrwu5Q=/?share_link_id=546722677610)
- [Explore DeckAura's free interactive tarot reading](https://deckaura.com/pages/free-tarot-reading)
- [Read the Deckaura Tarot Reflection Journal](https://deckaura.amebaownd.com/)

## Choose a spread before drawing cards

- [DeckAura Tarot Spread Finder on Zite](https://tarot.zite.so/) suggests a daily-card or three-card format based on your focus and reflection preference.
- [DeckAura Tarot Spread Finder and Reflection Guide](https://deckaura-tarot-sprea-5e67.bolt.host/) adds a time-based suggestion, a format comparison and a worked journaling example.
- [Browse the DeckAura resource collection](https://gokimedia.github.io/tarot-decision-map/deckaura-resources.html) to compare these tools with printable guides and journals.

Both finders recommend a format and prompt; neither draws cards or predicts events.

## Question builders and journals

- [DeckAura Tarot Question Builder and Spread Planner](https://deckaura-t95r17.public.builtwithrocket.new) creates a topic-based question and a reflection plan to copy or print.
- [The Symbol & Spread Journal](https://the-symbol-spread-journal.webflow.io/) provides an Observe, Question, Reflect method, a three-card practice and five journaling prompts. This is the published site; its `design.webflow.com` address leads to the Webflow sign-in screen.

## Session planner previews

- [DeckAura Tarot Reflection Planner on Emergent](https://mindful-card-session.preview.emergentagent.com/) includes a spread selector and a reflection worksheet with copy and print controls.
- [DeckAura Tarot Session Planner on Bubble](https://deckaura-tarot-session-planner.bubbleapps.io/version-test) suggests a session format based on focus and available time.

These are preview/test links, not confirmed Google-indexed production deployments. On September 12, 2026, the Emergent preview returned an `X-Robots-Tag: noindex, nofollow` header. Bubble's robots.txt disallowed `/version-test/`, and its production root returned HTTP 403. The supplied Bubble URL has no trailing slash, so that robots rule alone does not establish that the exact URL is blocked. Both need a verified public production URL for a reliable search-discovery plan. Adding links here does not override a destination's access controls or indexing directives.

## Additional guides, journals and shared previews

- [DeckAura Tarot Question Guide on B12](https://deckaura-tarot-question-guide.b12sites.com/) offers four sets of prepared question examples, spread guidance and a notebook template.
- [DeckAura Tarot Journal on 10Web](https://emerging-burro.10web.cloud/) provides one-card and three-card draws with a reflection journal and copy/print controls. The three-card draw was verified in the browser.
- [Tarot Reflection Guide on Dorik](https://ripe-louisa-5xq2tjwr.dcms.site/) contains daily and three-card exercises plus reflection prompts; it is labeled as a preview.
- [DeckAura Reflection Checklist design on UX Pilot](https://uxpilot.ai/s/68d3eece79a63726af27b65daa1a4540) presents before/during/after guidance inside an embedded design preview, not a standalone published app.

Access and crawlability checks on September 12, 2026:

| Resource | Observed status | Search-discovery limitation |
| --- | --- | --- |
| B12 | HTTP 200; public guide renders; self-referencing canonical; no noindex found in the returned HTML or HTTP header | robots.txt allows the homepage and declares a sitemap; this is not confirmation of Google indexing. |
| 10Web | HTTP 200; public journal renders and draws cards; self-referencing canonical | No noindex found; robots.txt allows the homepage and declares a sitemap. Google indexing remains unverified. |
| Dorik | HTTP 200; guide renders in the browser | The homepage sends `X-Robots-Tag: noindex,nofollow`. A backlink cannot override it. |
| UX Pilot | HTTP 200; the first shared screen contains the DeckAura checklist in a `srcdoc` iframe | The outer page has generic UX Pilot metadata. Rendering a design inside a sharing interface is not evidence that Google indexes it as a standalone guide. |
| [Softr preview](https://brenton66001.preview.softr.app/) | Redirects to `/login`; DeckAura sign-in page | robots.txt disallows `/` for general crawlers. Public content and crawl access are needed. |
| [Stitch shared preview](https://stitch.withgoogle.com/preview/12540677032030271381?node-id=aa4ca3f90d3f4aa189651fd79ba9ee2b&raw=1) | Outer page returns HTTP 200, but the embedded preview shows a 404 / nonexistent-or-unshared message | This is not an accessible public resource in the unauthenticated check. A working public share or published URL is needed. |

The four viewable resources have descriptive links and matching `ItemList` entries. Softr and Stitch are retained only in a clearly labeled access-notes section, not described as working resources or included in that list. Only this GitHub Pages site's own URLs belong in its sitemap. No destination settings were changed and no Google indexing was claimed or verified.

## Mixo introduction, Readdy planner and Airo access note

Checked September 13, 2026 (Europe/Istanbul):

- [DeckAura Tarot Journal Guide on Mixo](https://deckau-ti2v70.mixo.io) is a short Turkish-language introduction to one-card reflection, situation/challenge/advice and journaling, with an email signup. It is not presented here as a complete workbook or interactive card-drawing tool. The homepage returned HTTP 200, had a self-referencing canonical, and had no noindex in the returned HTML or HTTP header. Its robots.txt allows `/` and declares a sitemap. The visible resource link identifies the destination language with `hreflang="tr"` and uses a Turkish anchor.
- [DeckAura Reflection Planner on Readdy](https://readdy.cc/preview/b2245a00-c0f1-4b8b-80c7-08cf1b611ddf/13858978/) is an accessible preview with fixed-rule recommendations based on focus and time. The daily-theme / one-minute path produced a one-card reflection plan in the browser. The page includes one-card and three-card guidance, a notebook outline and a copy-plan control; it does not draw cards. HTTP 200 and relevant title/description were observed, with no noindex in the returned HTML or HTTP header. No canonical was present in that response. The robots.txt request failed with a TLS error, and a browser check was blocked by the client; its crawl rules remain unverified. No certificate or browser protections were bypassed.
- [Airo app preview](https://63r5e94qrw.preview.c40.airoapp.ai/) returned HTTP 401 for both the homepage and robots.txt. The browser explicitly states that the preview is private and requires an owner-provided share link or published app link. No app-content or functionality claim is made. The supplied URL is retained in the access-notes section and excluded from the viewable-resource `ItemList`.

Mixo and Readdy have descriptive resource cards and matching structured-data entries. Internal links connect the main page to their resource sections. The supplied preview URLs were preserved; no alternate production URL was guessed. Google indexing has not been requested through Search Console or verified, and linking cannot make a private destination public.

## Kleap practice guide and Landingsite content mismatch

Checked September 13, 2026:

- [DeckAura Tarot Practice Guide on Kleap](https://deckaura-tarot-practice-guide.kleap.io/) provides seven notebook prompts, one-card reflection, a situation/challenge/advice layout and a short FAQ. The public HTML and browser rendering both contain the guide. HTTP 200, a self-referencing canonical and `index,follow` were observed; no `X-Robots-Tag` was returned. The complete robots.txt allows the homepage for general search crawlers and declares `sitemap-index.xml`. A resource card and matching `ItemList` entry were added, together with a contextual link in the main page's review step. These checks establish no obvious access/indexing directive blocker, not inclusion in Google's index.
- The supplied Landingsite host, `dc-l8boo8so.share.landingsite.dev`, displayed **dc — Strategy, Advisory & Business Solutions**, covering business strategy, financial advisory, compliance and operations rather than DeckAura or tarot. Its homepage returned HTTP 200 with `X-Robots-Tag: noindex`, and the footer identifies it as a preview. It has not been added to the public tarot resource collection or structured data. A corrected DeckAura share/published URL is needed before a relevant resource link can be placed. No changes were made to the destination site.

Tarot can support reflection and journaling, but it is not a substitute for medical, legal, financial, or mental-health advice.
