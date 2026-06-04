# Word/PDF Print Specification

Design figures for formal A4 government application documents. The figure must remain clear after Word insertion, PDF export, and paper printing.

## Page Fit

- Default body figure width: 150-160 mm, matching common A4 Word text width.
- Compact portrait figure height: 70-110 mm.
- Complex portrait figure height: up to 160 mm if the surrounding text allows it.
- Landscape A4 figure: use only when the logic cannot be read in portrait; keep a clear caption and body reference.
- Appendix figure: acceptable for dense architecture or indicator matrices, but keep the main text figure simpler.

## Typography

- Minimum in-figure Chinese text: 8.5-9 pt at final Word insertion size; treat this as a lower bound, not the default.
- Preferred module text: 10-11 pt for card, route, principle, closed-loop, and architecture figures. Use 9-10 pt mainly for compact matrices or dense architecture cells.
- Figure title inside artwork, if needed: 10.5-12 pt.
- Caption outside artwork: follow the document's Word style, usually 10.5 pt or body-caption style.
- Use common Chinese fonts such as SimSun, SimHei, Microsoft YaHei, or the document's existing font style.
- Avoid long sentences inside boxes. Use short phrases, numbering, and line breaks.
- For compact document matrices, prefer 9 pt text with 1.05-1.15 line spacing; avoid loose paragraph spacing inside cells.
- For numbered cards, badges, corner tags, or icons, reserve a separate layout band. Do not place the badge and the title on the same crowded baseline. If the title is long, move the badge above the title, reduce the title one step, or wrap the title into two centered lines.
- Every text box must pass a fit check at final Word insertion size: no glyph may touch the border, overlap a badge/icon, or exceed the box boundary after SVG/PDF/PNG export.
- For tall cards with sparse content, vertically balance the badge/title/body group within the usable card area. Do not leave all text clustered near the top with a large blank lower half; either move the text group toward the center, add concise technical evidence text, or reduce the card height.
- If print proof or a printed-page photo shows weak figure text, enlarge the core labels first and remove redundant in-artwork titles or blank canvas before reducing information content.

## Lines And Shapes

- Minimum visible line width: 0.75 pt.
- Preferred module border: 1.0 pt.
- Important boundary or main flow arrow: 1.1-1.5 pt.
- Use arrowheads large enough to survive PDF export.
- Keep spacing consistent; avoid crowded arrows crossing text.
- Prefer straight or orthogonal connectors in formal document figures; avoid long diagonal connectors unless they are the only clear way to show the relation.
- Similar modules must align to a visible grid and use consistent sizes; avoid boxes floating in open canvas space.
- Similar cards must reserve the same internal zones for badge/title/body/note text. Do not let decorative markers intrude into the text area.

## Color And Contrast

- Default background: white.
- Primary line/text: dark gray or near black.
- Primary accent: restrained government blue.
- Secondary accents: gray-blue, teal, or muted gold only when useful.
- Do not rely on color alone. Use position, numbering, shape, line style, or labels to encode meaning.
- Avoid gradients, glow, transparency, heavy shadows, large dark backgrounds, and low-contrast pale colors.

## Compact Document Matrix

Use these rules for formal matrix figures such as bottleneck-technology-validation-evidence tables.

- Make the matrix body occupy at least 80-88% of the artwork height; avoid large title, subtitle, footer, or note areas inside the image.
- Keep artwork outer margins tight: about 3-5 mm on each side at final print size.
- Use compact cell padding: about 2.5-4 mm horizontally and 2-3 mm vertically at final print size.
- Center text horizontally and vertically in every header and body cell by default, including multi-line Chinese phrases.
- Keep row numbers exactly centered in the dedicated `序号` column; they must not sit above, below, or outside the cell center.
- Use left alignment only as an explicit exception for long paragraph-like evidence text, and keep it vertically centered within the cell.
- Use consistent row heights. For 4-row matrices, target about 22-30 mm per row within a 150-160 mm wide portrait figure.
- Keep column headers to one short phrase each. Use a light gray-blue or pale blue header fill, not large high-saturation color blocks.
- Put row numbers in a dedicated narrow first column labeled `序号`; width should be about 7-10% of the table width.
- Use plain centered numbers `1`, `2`, `3`, `4`; do not use floating circles, badges, icons, or decorative markers for row numbers.
- Keep the table compact but readable: do not reduce Chinese text below 8.5-9 pt, line width below 0.75 pt, or padding below the point where text touches borders.
- Avoid sparse cells. If a cell contains only one short phrase while surrounding cells are empty-looking, add a concise second phrase, merge redundant rows, or reduce row height.
- If the matrix needs more than 5 columns or the cells become crowded, split into two figures or move detail to a document table.

## Raster Export

Prefer vector output. If raster export is unavoidable:

- Minimum: 300 DPI at the final printed size.
- Recommended for line diagrams: 600 DPI.
- For a 160 mm wide figure, use at least 1890 px wide at 300 DPI or 3780 px wide at 600 DPI.
- Export with sharp text and no compression artifacts.

## Print Readability Check

Before final delivery, check:

- Can the smallest label be read when the figure is viewed at A4 page size?
- On a real printed sample, do the core labels read comfortably without leaning in? If not, increase type size and reduce unused canvas.
- Is the figure still understandable in grayscale?
- Are arrows and line boundaries visible after PDF export?
- Are repeated modules aligned and evenly spaced?
- Do all cards and text boxes keep badges, titles, body text, and notes in separate non-overlapping zones?
- Does every text label fit inside its box at final Word/PDF size without touching borders or colliding with markers?
- Do tall cards avoid top-heavy text placement and excessive empty lower space?
- Does the figure avoid floating boxes, long diagonal arrows, and large unused canvas areas?
- Does the figure contain only the information needed for the current section?
- For matrices, does the first column contain serial numbers as its own column rather than floating markers?
- For matrices, are all headers, row numbers, and body text horizontally and vertically centered unless a long evidence note is explicitly left-aligned?
- For matrices, does the figure avoid a "few words in a large box" look while preserving A4 readability?
