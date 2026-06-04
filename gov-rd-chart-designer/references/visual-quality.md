# Visual Quality Standard

Use this standard to prevent government R&D proposal figures from looking temporary, sparse, or PPT-like. A finished figure should look like a formal Word/PDF body illustration prepared for expert review.

## Finished Figure Standard

A finished figure must satisfy these requirements:

- Use an obvious grid, lane, table, or symmetric structure; do not place boxes freely on a blank canvas.
- Similar modules use the same size, border, fill, typography, and internal padding.
- Edges, centers, arrows, and labels align deliberately; avoid modules that look positioned by eye.
- Empty space is controlled. The artwork should not have large blank corners while the main content sits loosely in the middle.
- The figure should look document-grade and restrained, not like a slide template, poster, casual sketch, or quick diagram.

## Anti-Ugly Rules

Reject and redraw the figure if any of the following appears:

- Independent boxes float around the canvas without a grid, lane, or table structure.
- Long diagonal arrows connect distant boxes and make the layout look scattered.
- The central module is boxed but does not align with surrounding modules.
- Peer modules have inconsistent widths, heights, or text baselines without a logical reason.
- Text is off-center, too close to borders, or unevenly distributed across similar cells.
- A numbered badge, corner tag, icon, or label overlaps the title, shares a cramped title baseline, or causes title text to spill outside the card.
- Text inside any box clips, touches the border, or extends beyond the box boundary after export.
- Sparse text sits near the top of a tall card while the lower half is mostly empty, making the module look underfilled.
- Core labels look acceptable on screen but become weak or hard to read in a printed-page photo.
- Large unused areas remain after the core content is placed.
- Lines touch text, collide with box borders awkwardly, or cross other connectors.
- The color palette uses unrelated accent colors for peer modules without encoding a real difference.

## Preferred Layout Patterns

Choose one stable pattern before drawing:

- Matrix or evidence mapping: use a real table grid with compact rows and centered cell text.
- Technical route: use a left-to-right or top-to-bottom lane flow with consistent step cards.
- Closed-loop validation: use a compact four-step cycle, a two-row feedback lane, or a 2x2 quadrant with a clear loop arrow path.
- Principle figure: use layered input-method-output structure, not scattered components.
- Task decomposition: use grouped lanes or a tree with aligned child modules.

## Closed-Loop Figure Rules

For closed-loop innovation, validation, iteration, or application figures:

- Do not draw four detached rectangular boxes around a center box with long diagonal arrows.
- Prefer a compact loop made from four equal step blocks connected by short orthogonal arrows.
- If a central concept is needed, use a small center label or a narrow central band aligned to the loop, not a large isolated box.
- Use one restrained accent color for the loop and one neutral color for supporting notes; do not give every node a different accent unless the colors encode categories.
- Keep the loop footprint compact enough that the body of the figure fills the artwork rather than floating in open space.

## Typography And Alignment

Text must look intentionally typeset:

- Use one Chinese font family per figure unless the document requires otherwise.
- Use at most two in-figure text levels: group label and body label.
- Keep body labels to 1-3 concise lines. Rewrite text before shrinking it below the print minimum.
- Center text horizontally and vertically in modules, matrix cells, and numbered nodes unless an explicit paragraph note needs left alignment.
- For card layouts, reserve distinct vertical zones: badge/tag first, title second, body third, note last. Badges and titles must not overlap or compete for the same horizontal space.
- Before finalizing, check all card titles and body labels against the actual box width; wrap, shorten, or reduce by one type step before allowing overflow.
- For tall cards with little text, place the combined badge/title/body group around the visual center of the card or shorten the card. Avoid top-aligned text that makes the module look empty.
- For printed proposal figures, prefer 10-11 pt equivalent text for core labels. Do not preserve decorative title bands or large blank margins at the cost of print readability.
- Do not use oversized titles inside the artwork. Put the official figure caption outside the image.

## Editable Source Requirements

When producing editable source, encode alignment directly:

- SVG: use explicit centered coordinates for text and calculate multi-line `tspan` placement; avoid relying on visual guessing.
- draw.io: use `align=center;verticalAlign=middle;whiteSpace=wrap;html=1;` for modules and matrix cells.
- PPT/Word shapes: set horizontal alignment to center and vertical alignment to middle for modules and table cells.
- Mermaid: use only when the result can satisfy the layout and alignment requirements; otherwise prefer SVG or draw.io.
