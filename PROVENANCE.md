# Provenance

> **Unofficial copy — not the website of Eye Shop.** See `README.md`.

Where everything in this copy comes from, and what was changed to publish it. The same facts, as data, are in `PROVENANCE.json`.

## Words

Apart from the redesign's own words listed in the README, the pages' text comes from https://www.eyeshophouston.com/, read from a crawl of 150 addresses on the evening of October 20, 2026, Houston time (October 20, between 23:37 and 23:45 UTC).

## Pictures and video made for this redesign

6 stills and 1 loop, made on the evening of October 20, 2026, Houston time (October 21, between 01:24 and 01:30 UTC). None shows a person, the practice's office, a clinical result, lettering, a label or a named product. Every still was opened whole and then in enlarged regions at its full size, looking for lettering, numbers, marks that read as a brand, a recognisable product, a person or a hand, a malformed object and a border; the loop's poster and frames were looked at the same way. A still that failed was made again from a second prompt, two candidates each. The files here are re-encodings made by the private build (WebP through a browser canvas, H.264 without an audio track); each carries the AI label (README, Generated imagery) and was read for metadata before publishing (README, Verification). The manifest of the fal.ai originals says that an imperceptible SynthID watermark was applied (a watermark in the picture itself, not in its metadata); this copy did not test for it. 1 picture is used with a remark:

| Picture | Remark |
| --- | --- |
| still-why | The still itself is not shipped: the home page's navy band shows the loop made from it, with the loop's first frame as the poster. |

| File (under assets/generated/) | Kind | What it shows | Made with | Pages that show it |
| --- | --- | --- | --- | --- |
| loop-why | loop | thin gold-rimmed eyeglasses on a navy linen cloth at the edge of a wooden table, with sunlight that shifts slowly across the cloth and returns (made from one still, used as its first and last frame) | Higgsfield: kling-video/o3/first-last-frame, from the still still-why (fal.ai: nano-banana-pro) | 1 |
| still-contacts-alt-1 | still | an open white contact-lens case on a marble counter, with a navy cloth behind it | fal.ai: nano-banana-pro | 8 |
| still-drops-alt-1 | still | drops of water on a pale blue surface | fal.ai: nano-banana-pro | 3 |
| still-exam-alt-1 | still | a round lens in a polished metal rim, close up, against soft warm light | fal.ai: nano-banana-pro | 6 |
| still-frames | still | three pairs of eyeglass frames (tortoiseshell, gold wire and navy) on a pale stone slab, with a navy cloth | fal.ai: nano-banana-pro | 8 |
| still-lens-b-alt-1 | still | two clear eyeglass lenses on white stone, one standing and one lying flat, against a navy wall | fal.ai: nano-banana-pro | 10 |
| still-sun-alt-1 | still | tortoiseshell sunglasses with brown lenses on sand-coloured stone, in the shadow of palm leaves, with a navy cloth | fal.ai: nano-banana-pro | 7 |

## Pictures from the live site

145 file names of pictures published on the practice's site are used (182 counting each version: mostly the different cuts the redesign makes of one picture): the practice's logo, photographs of its office and of its displays of eyewear, the stock photographs and drawings of its pages, and the pictures and logos of the makers, insurers and payment cards its pages name. Most stand on the page where the live site shows them; the redesign also shows a page's picture on the cards and menus that lead to that page. The photographs of the practice's own people are not shown here (README, Hardening 6). 4 pictures that live pages name are not on the picture host (it answers "not found", HTTP 404), so those pages cannot show them on the live site either, and the rebuilt pages do not show them. 4 pictures named only by stylesheets of the old platform, on other hosts, could not be downloaded (3 not found, 1 refused, HTTP 403); the redesign does not use them.

## Typefaces

Merriweather and Merriweather Sans, both under the SIL Open Font License 1.1, served from this site; the licence texts are beside the font files.

## Changes made for publishing

| Change | Count |
| --- | --- |
| Pages given the robots tag `noindex, nofollow, noarchive, nosnippet, noimageindex` and a `no-referrer` tag | 148 |
| JSON-LD blocks removed | 1,195 |
| Link-preview picture tags removed | 296 |
| Pages whose link-preview tags carry the disclosure | 148 |
| Link-card titles marked "Unofficial preview:" | 148 |
| Icon links removed | 296 |
| Page descriptions replaced by the disclosure | 5 |
| Forms of the practice made inert | 3 |
| Boxes for directions not offered (a note there now) | 2 |
| Places where a portrait of the practice's people stood (an initials tile there now) | 54 |
| Other places where a photograph of the practice's people stood (taken out with its place, or an icon tile there now) | 10 |
| Films of a video site not shown (a note there now) | 2 |
| Notes "the words on this page are the live site's own" | 4 |
| Notes in Spanish on pages written in Spanish | 5 |
| Links to the former web address now to the same page of this copy | 8 |
| Links that dialled the other number, now words | 2 |
| Descriptions of pictures emptied (another city) | 1 |
| Map frames that carry `referrerpolicy="no-referrer"` | 148 (all carried it in the private build) |
| Canonical tags removed (pages the build makes itself) | 2 |
| Search-index entries reduced to their title, section and menu names | 8 |
| Comments taken out (stylesheet, script) | 235, 110 |
| Generated files given the AI label | 68 |
| Files of the private build not shipped | `.htaccess`, `llms.txt`, `sitemap.xml`, `_redirects` |
| `robots.txt` | replaced by the preview's own (`Disallow: /`) |
| Files nothing in this copy names, not shipped | 87 |
