# Layout Template Library

Use a template before drawing. Good figures come from stable layout systems, not from placing boxes one by one on a blank canvas.

## Template Selection Rule

Before producing editable source, choose one template and state it briefly in the design intent. Do not invent a free-form layout unless none of these templates fits.

## T1 Compact Evidence Matrix

Use for bottleneck, task, indicator, method, verification, and evidence mappings.

- Canvas: portrait body figure, 150-160 mm wide.
- Structure: title outside artwork, then a dense table grid inside artwork.
- Columns: `序号 | 对象/问题 | 方法/技术 | 验证/依据 | 成果/证据`.
- Style: pale gray-blue header, white body, dark gray text, blue-gray grid lines.
- Quality rule: table fills most of the figure; no floating row numbers, badges, or decorative icons.

## T2 Technical Route Lane

Use for project implementation routes and staged R&D plans.

- Canvas: horizontal or vertical lane depending on chapter space.
- Structure: 4-6 equal step cards in one lane, with short orthogonal arrows.
- Optional: a narrow evidence row under the main lane for data, prototype, report, or demonstration outputs.
- Style: same-size cards, restrained blue emphasis on the active or core step, neutral fills for supporting steps.
- Quality rule: avoid zigzag arrows and uneven card sizes.

## T3 Layered Principle Stack

Use for technical principles, algorithms, processes, systems, and mechanism explanation.

- Canvas: 3-5 stacked layers or left-to-right stages.
- Structure: input/object layer -> method/model layer -> integration/control layer -> validation/output layer.
- Style: layer bands with subtle fills; internal modules aligned in columns.
- Quality rule: show causality through layer order and short connectors, not through scattered component placement.

## T4 Formal Closed Loop

Use for validation, iteration, application feedback, and continuous improvement.

- Canvas: compact loop occupying the center of the artwork.
- Structure option A: four equal blocks in a 2x2 grid, connected by short orthogonal arrows around the perimeter.
- Structure option B: two-row feedback lane, where the upper row is R&D/design/test/application and the lower row is data/evaluation/optimization feedback.
- Center label: optional small center tag only; do not use a large isolated center box.
- Style: one restrained blue loop color plus neutral gray support labels.
- Quality rule: never use detached boxes around a large center box with long diagonal arrows.

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

## Template Failure Check

Redraw if the figure no longer resembles its chosen template:

- Step cards are no longer equal or aligned.
- The loop no longer reads as a loop.
- The matrix has become sparse or oversized.
- Architecture connectors cross repeatedly.
- Decorative elements compete with technical content.
- The main message cannot be found within about 10 seconds.
