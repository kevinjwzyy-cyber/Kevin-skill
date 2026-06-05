# Layout Template Library

Use a template before drawing. Good figures come from stable layout systems, not from placing boxes one by one on a blank canvas.

## Template Selection Rule

Before producing editable source, choose one template and state it briefly in the design intent. Do not invent a free-form layout unless none of these templates fits.

After choosing T1-T6, choose a style profile from `style-profiles.md` when the user asks for a formal proposal infographic, a full-document redesign, or a selected-reference style. The layout template defines structure; the style profile defines visual emphasis.

## Strong Theme Anchor Variant

For selected-quality proposal infographics, the official caption remains outside the artwork, but the artwork may include a short theme anchor that names the core subject or evidence logic.

- Overall framework: a central deep-blue spine or main block can anchor upstream pain points and downstream outputs.
- Scientific principle: a layered pyramid or band stack can carry large layer labels and concise mechanism phrases.
- Task/indicator mapping: a left-right mapping can emphasize acceptance quantities and output evidence.
- Technical route: a lane or milestone timeline can include dates, stage numbers, and evidence bands.
- Architecture: a layer stack should use project-specific module names instead of generic `数据层/模型层/服务层` only.
- Closed loop: use a compact 2x2 loop, circular lifecycle, or large validation loop that fills the canvas.
- Matrix: use a dense grid occupying most of the artwork, not a small table inside a decorative frame.

## T1 Compact Evidence Matrix

Use for bottleneck, task, indicator, method, verification, and evidence mappings.

- Canvas: portrait body figure, 150-160 mm wide.
- Structure: title outside artwork, then a dense table grid inside artwork.
- Columns: `序号 | 对象/问题 | 方法/技术 | 验证/依据 | 成果/证据`.
- Style: pale gray-blue header, white body, dark gray text, blue-gray grid lines.
- Quality rule: table fills most of the figure; no floating row numbers, badges, or decorative icons.
- Strong-anchor option: use S7 Review Matrix Enhanced when the figure is a key review matrix; the matrix itself is the visual anchor.
- Typography rule: if the matrix has 3-5 columns and short phrases, use larger print-readable body text rather than treating it as a dense data table.
- Alignment rule: headers, serial numbers, and all body cells are horizontally and vertically centered by default. Combine multi-item evidence into two centered lines before shrinking text.
- Print rule: if the printed proof looks weak, enlarge the table footprint and reduce unused margins before reducing content.

## T2 Technical Route Lane

Use for project implementation routes and staged R&D plans.

- Canvas: horizontal or vertical lane depending on chapter space.
- Structure: 4-6 equal step cards in one lane, with short orthogonal arrows.
- Optional: a narrow evidence row under the main lane for data, prototype, report, or demonstration outputs.
- Style: same-size cards, restrained blue emphasis on the active or core step, neutral fills for supporting steps.
- Strong-anchor option: use S4 Milestone Timeline when dates or staged outputs matter; use S3 when each task maps directly to an indicator.
- Quality rule: avoid zigzag arrows and uneven card sizes.
- Card rule: when cards have step numbers, place the number in a reserved top band above the title or in a dedicated narrow column; never let the number badge overlap the title.
- Card rule: if equal cards must be tall but contain little text, vertically balance the number/title/body group inside each card or reduce card height so the lane does not look underfilled.
- Card rule: do not place evidence, output, or note text as a bottom footer in sparse cards. Split long evidence lists into centered 2-3 line groups inside the card or in a separate evidence band.
- Revision rule: when one route card has a badge/title collision or top-heavy text, fix all route cards in the same figure and audit other route figures in the document.

## T3 Layered Principle Stack

Use for technical principles, algorithms, processes, systems, and mechanism explanation.

- Canvas: 3-5 stacked layers or left-to-right stages.
- Structure: input/object layer -> method/model layer -> integration/control layer -> validation/output layer.
- Style: layer bands with subtle fills; internal modules aligned in columns.
- Quality rule: show causality through layer order and short connectors, not through scattered component placement.
- Strong-anchor option: use S2 Layered Pyramid Principle when the section needs a reviewer to see the scientific logic chain immediately.
- Card rule: short labels may use compact modules, but badges/icons must not occupy the same line as the main label unless the remaining title width is verified to fit.
- Card rule: tall principle cards should not cluster text at the top; center the content group visually or add concise mechanism/evidence labels.

## T4 Formal Closed Loop

Use for validation, iteration, application feedback, and continuous improvement.

- Canvas: compact loop occupying the center of the artwork.
- Structure option A: four equal blocks in a 2x2 grid, connected by short orthogonal arrows around the perimeter.
- Structure option B: two-row feedback lane, where the upper row is R&D/design/test/application and the lower row is data/evaluation/optimization feedback.
- Center label: optional small center tag only; do not use a large isolated center box.
- Style: one restrained blue loop color plus neutral gray support labels.
- Quality rule: never use detached boxes around a large center box with long diagonal arrows.
- Strong-anchor option: use S6 Lifecycle Governance Loop for data/evidence reuse and S8 Field Validation Loop for scenario demonstration.
- Node rule: each loop node uses a centered content group: badge in a top band, title below with a visible gap, then 1-2 body lines below the title.
- Spacing rule: if badge and title collide, adjust vertical bands or node height while preserving requested font sizes.
- Center label rule: if a center evidence tag is used, center both the header and body text and keep the header band tall enough that it does not crowd the body.

## T5 Comparison Card Pair

Use only when the user asks for explanatory, presentation, training, or public-facing visuals rather than formal Word body figures.

- Canvas: two balanced cards side by side with a clear divider.
- Structure: card header with label/icon, 3-4 bullet rows, one visual anchor area, and a bottom takeaway band.
- Style: one accent color per side, consistent icon style, large readable labels.
- Quality rule: this is suitable for slide/video explainers; for government application正文, tone down icons, color, and oversized typography.

## T6 System Architecture Grid

Use for platform, data, model, service, and application architecture.

- Canvas: 3-4 horizontal layers or a left-to-right pipeline with grouped modules.
- Structure: data layer -> model/algorithm layer -> system/service layer -> application/validation layer.
- Style: layer headers at left or top, modules in aligned cells, connectors only between adjacent layers.
- Quality rule: avoid a web of crossing lines; if dependencies are complex, split into main architecture plus a separate evidence matrix.
- Strong-anchor option: use S5 Layered Architecture Stack and make each layer carry domain-specific modules, not generic placeholders.

## Template Failure Check

Redraw if the figure no longer resembles its chosen template:

- Step cards are no longer equal or aligned.
- The loop no longer reads as a loop.
- The matrix has become sparse or oversized.
- Architecture connectors cross repeatedly.
- Decorative elements compete with technical content.
- The main message cannot be found within about 10 seconds.
