# Images, pages, and WeChat articles

## Follow the content

Respect the article order already established by the author. Identify what the reader actually needs to see: model outputs, interface locations, structural relationships, changes over time, data comparisons, or a scene. The material determines the number of images; not every heading needs one.

A project screenshot can sometimes replace a paragraph of explanation; a principle may instead need a written derivation. An illustration can establish atmosphere but should relate to the topic and visual language. Do not default to glowing brains, robot heads, purple-blue gradients, stacked cards, or “zero to expert” covers.

## Sources and visual forms

| Content | Suitable visual | Placement and treatment |
|---|---|---|
| Projects such as MNIST or YOLO | Real predictions, user images, or official demos | Place after the result is introduced; retain enough detail to see classes and output quality. |
| Papers and model mechanisms | Original paper figures or accurate diagrams | Keep beside the mechanism and cite the source. Preserve relationships, notation, and scale when redrawing. |
| Tool use | Actual screenshots or short recordings | Place beside the relevant operation; show the useful region instead of shrinking a whole desktop. |
| Courses and videos | Official page screenshots, covers, or user-supplied video screenshots | Keep resource names and links accessible as text. |
| Relationships or comparisons | Simple diagrams, tables, or side-by-side results | Arrange for direct comparison; do not force complex relationships into a linear arrow chain. |
| Covers and editorial illustration | Appropriate photography or original illustration | Establish character without repeating the entire title and introduction in the image. |

Inspect existing visuals and user-provided material before generating replacements. If a key screenshot is missing, identify the needed view and complete independent work. Do not fabricate interfaces, experimental results, or citations. Record external-image sources and known usage conditions in captions or material notes rather than long disclaimers in the article.

For original raster images or edits to existing images, use the available image-generation or image-editing tools under their applicable instructions. For precise diagrams and data figures, use methods that preserve labels, connections, and numerical accuracy. A tool's favorite visual style should not dictate every image.

Before generation, establish the subject, paragraph placement, aspect ratio, and relationship to the layout. Inspect the result before using it. A multi-image article can have a short record of placement, source or generation method, filename, and caption. A single illustration does not require a complicated approval process.

## Page hierarchy

For multi-page knowledge bases or course collections, also use [knowledge-base review](knowledge-base-review.en.md). Apply the main skill's proactive review to actual pages: text links, readable images, distinct prompts, and clear resource roles must work together. Neither prose-only checks nor screenshots alone establish all of these. Inspect other authorized instances when a repeated component has a defect.

The title states the subject, the introduction establishes the reason for the piece, and subheadings separate content. Use connected prose. Lists and tables belong where information is parallel, comparative, or genuinely procedural.

Use paragraph spacing, heading hierarchy, image width, and whitespace for rhythm. Emphasize the information readers need to catch when scanning; do not bold every paragraph's first sentence or split an article into dozens of two-sentence cards.

Reuse the brand's colors, typography, and visual language. The research-guide example uses warm paper #f4f1ea, body text #20211e, green links #24583e, and accent #98432e. These are that project's preferences, not a universal skin.

## WeChat: turn the website into a readable article

Navigation, filters, dialogs, and collapsed sections need adaptation. For example, a site with 49 paper cards might become an article featuring the papers selected for that issue and linking the full catalog. The selection must follow the user's scope; do not silently reduce a complete resource collection to a few images.

Retain the original Markdown or other editable text. Check long code blocks, wide tables, equations, and complex figures at phone width. Splitting a table or figure, or using a short code example, often works better than shrinking the font. Key material should not exist only in a long screenshot that cannot be copied.

### Layout starting point

Without a specified style, start with a simple, single-column, left-aligned article: roughly 16px body type, 1.8 line height, and 20px side margins. Adjust for the font and actual preview; these are starting values, not platform specifications.

Avoid accidentally repeating the platform title inside the body. Use second-level headings for sections and third-level headings only where needed. Captions can be smaller but must remain readable. Links need recognizable styling, and accent colors should be restrained. A white body background can work with brand colors in headings and selected emphasis; the full website background need not be copied.

[wechat-base.css](../assets/wechat-base.css) is a dependency-free starting style for previews or renderers with custom CSS. Its root container uses `class="humanize-article"`. Inline the required styles when exporting to WeChat. A browser preview using a separate stylesheet is not a finished paste-ready article.

### Conversion and tools

Reuse an existing project converter where suitable. Otherwise choose among available tools such as doocs/md, baoyu's Markdown-to-HTML skill, or simple HTML with inline styles. See [tool references](github-references.en.md). A text edit does not require installing layout tools; a layout task does not require a publishing plugin.

Verify external links and images in the actual editor when that is part of the authorized task. If end references are requested or the editor does not support links as expected, keep resource names in the body and collect URLs in order at the end, deduplicating while preserving correspondence. Avoid dozens of bare URLs between paragraphs and do not claim arbitrary external links are clickable without checking.

Convert script-dependent images, equations, or Mermaid into supported forms. Technical labels and values must remain readable. Absolute positioning, multiple columns, or external fonts should not be prerequisites for reading the article. Replace any image placeholders before calling the output complete.

### Inspect the result

At phone reading width, inspect the opening, a dense middle section, images, and final resources. Check crowding, figure-label legibility, link density, table overflow, and whether pictures and text actually concern the same thing.

With authorized editor access, also inspect the pasted or imported styles, images, and links. If only a local preview was checked, deliver it accurately as a local preview rather than claiming publication or platform verification.

Deliver editable text, layout HTML, and actual images, with brief source notes for multi-image work. Do not create empty image folders when no pictures are needed or attach a long layout report to every article.
