# Sherwin-Williams case study

Static GitHub Pages website adapted from Frank Melendez’s Figma Portfolio, frame `34:793`. The page includes all nine sections and local Figma-exported assets. Text remains real HTML and reflows on smaller screens. Motion imagery is presented as stills; no source video was provided by the design export.

## Independent spacing

Edit `case-study.css`. The first `:root` block sets desktop spacing. The `MOBILE SPACING` block controls screens up to 767px wide and independently overrides all spacing variables.

| Setting | Controls |
| --- | --- |
| `--page-gutter` | Left and right page margins |
| `--header-space` | Space above and below project introduction |
| `--section-space` | Default section padding |
| `--approach-top`, `--approach-bottom` | Approach section padding |
| `--role-space` | My role section padding |
| `--environment-space` | Environment section padding |
| `--closing-space` | Closing section padding |
| `--content-gap` | Space between section text and imagery |
| `--copy-gap` | Space between headings and paragraphs |
| `--gallery-gap` | Space between gallery images |
| `--result-bottom` | Bottom padding of the result section |

For example, change mobile `--section-space:48px` to `32px` to tighten the mobile layout without changing desktop.

## GitHub Pages

Upload only the contents of this folder to a dedicated public repository. To publish at `https://framel73.github.io/`, use `framel73.github.io` after checking for any existing content. Under Settings → Pages, select Deploy from a branch → main → / (root). No build or paid hosting plan is required.

All visible copy is from Figma, with the truncated caption “environmental contex” corrected to “environmental context.” Fonts use Inter when available, with Arial/Helvetica fallbacks. Desktop compositions are adapted for narrow screens. Figma source files remain unchanged.
