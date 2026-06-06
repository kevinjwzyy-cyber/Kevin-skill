---
name: gov-rd-chart-designer
description: "Design professional figures for Chinese government science-and-technology R&D project application documents. Use when Codex needs to transform government R&D proposal text, project plans, scientific problems, technical principles, key technologies, technical routes, R&D tasks, indicators, implementation mechanisms, or expected outcomes into Word/PDF body illustrations that are print-readable, logically rigorous, chapter-numbered, and suitable for formal application files."
---

# Government R&D Chart Designer

## Overview

Use this skill to design figures for government science-and-technology R&D project application documents. Design for Word/PDF body insertion and printed review first, not for slide decks or large-screen display.

Default to formal proposal infographics: restrained enough for Word/PDF body text, but strong enough that expert reviewers can identify the core claim, project subject, and acceptance evidence at A4 page size. Every figure must serve the proposal argument: why the project should be funded, how the technology works, how R&D tasks connect to outcomes, and how indicators will be achieved.

## Qualified Proposal Infographic Standard

A qualified figure is not merely a clean diagram. It must make the section's argument visible.

- Official figure numbers and captions stay outside the artwork, but the artwork may contain a short theme anchor such as `多智能体中枢（项目核心主体）`, `低空数据资产全生命周期复用`, or `核心逻辑：数据证据约束模型输出`.
- The main content should occupy about 75-90% of the artwork area. Avoid small diagrams floating inside a large pale frame or square export canvas.
- Core labels should be larger and heavier than the minimum print text. Use concise project-specific phrases and measurable outcomes rather than generic labels.
- Extract and display the project's industry terms, core pain points, key technologies, quantitative outcomes, demonstration scenes, and acceptance evidence before choosing a layout.
- Default visual direction is `正式打印增强版`: white or very light background, deep blue/gray-blue main structure, teal or muted orange for limited emphasis, visible line weights, and grayscale-readable encoding.
- Light blue layering or subtle gradient bands are allowed when they improve hierarchy. Avoid decorative shadows, glow, low contrast, video-cover styling, and color-only meaning.

## Core Workflow

1. Establish document context.
   - Identify or infer the chapter number, chapter title, target paragraph, figure purpose, existing figure-number style, and whether the figure is portrait A4, landscape A4, or appendix material.
   - If the context is missing, state reasonable assumptions and use a provisional figure number such as `图2-1` only when the chapter can be inferred.

2. Extract the proposal logic.
   - Build the application chain: `政策需求/行业痛点 -> 科学问题/技术瓶颈 -> 研发思路 -> 关键技术 -> 研发任务 -> 成果产出 -> 应用示范 -> 绩效指标`.
   - Build the technical principle chain: `研究对象/数据/材料 -> 机理/模型/算法/工艺 -> 方法路径 -> 系统集成 -> 验证评价 -> 工程应用`.
   - Extract the domain vocabulary that must appear in the figure: industry scene, core pain point, proprietary model/system name, key technology terms, acceptance quantities, evidence names, and demonstration setting.
   - Prefer causal, hierarchical, sequential, or matrix relationships over decorative grouping.

3. Choose the figure type.
   - Read `references/chart-types.md` when selecting among architecture, technical route, principle, task decomposition, indicator matrix, closed-loop, or mechanism figures.
   - Read `references/layout-templates.md` and choose a stable template before drawing; avoid free-form placement.
   - Read `references/style-profiles.md` when choosing the visual style. Choose one of S1-S8 after selecting the chart type; style profiles do not replace T1-T6 layout templates.
   - Read `references/official-4x3-prompt-rules.md` when the user asks for national/provincial/municipal key R&D application figure norms, strict proposal prompts, 4:3 official figures, or selected "申报书必备图" patterns.
   - Use the figure type that answers one clear question, such as "what technical bottleneck is solved," "how the core principle works," or "how tasks support indicators."
   - For bottleneck-technology-validation-evidence mappings, default to a compact document matrix with a separate narrow serial-number column.

4. Design the figure for Word/PDF and printing.
   - Read `references/print-spec.md` before giving final dimensions, typography, line weights, color rules, or raster export settings.
   - Read `references/visual-quality.md` before choosing a layout pattern or producing editable source.
   - Prefer editable vector output: SVG, draw.io XML, Mermaid source that can be exported to SVG/PDF, or a PPT/Word-editable structure. If raster insertion is needed, export at the true figure ratio and print resolution rather than placing a small figure inside a square canvas.
   - For document matrices, keep the table body dominant, reduce outer and cell padding, and avoid floating decorative row numbers.
   - For step cards, route cards, phase cards, and closed-loop nodes, use a centered content group by default: badge/tag, title, body, and note/evidence each occupy separate vertical zones with visible gaps.
   - For selected-style infographics, make the primary visual anchor obvious within 10 seconds: center bar, pyramid, dual-column mapping, time axis, layered architecture, lifecycle loop, matrix, or validation loop.
   - If a reviewer flags small text, top-heavy cards, non-centered text, or badge-title collisions in one figure, audit every figure in the same document using the same template before finalizing.
   - Avoid floating boxes on blank canvas, long diagonal arrows, color-only meaning, low-contrast labels, decorative shadows, tiny text, screenshot-like raster output, and slide-style decoration.

5. Generate chapter-aware labels.
   - Read `references/captions-numbering.md` when assigning figure numbers, captions, body references, or explanatory text.
   - Align the caption with the chapter and paragraph rather than using generic titles like "总体架构图" without context.

6. Strengthen R&D logic and technical language.
   - Read `references/logic-patterns.md` when the source text is loose, slogan-like, or lacks technical causality.
   - Replace vague management phrasing with explicit relationships among scientific problems, mechanisms, methods, parameters, validation, and outcomes.

## Default Response Shape

When asked to design a figure, provide:

1. Figure metadata: figure number, caption, insertion context, and body-reference sentence.
2. Design intent: the single question the figure answers.
3. Logical structure: chosen layout template, modules, sequence, hierarchy, or matrix axes.
4. Visual specification: page fit, orientation, typography, line weights, color, and black-and-white readability notes.
5. Editable source or implementation instructions, when requested or when the user asks for a usable artifact.

For simple requests, keep the response compact. For actual deliverables, produce the editable source and include export guidance.

## Quality Checklist

Before finalizing, verify:

- The figure number follows the chapter and existing document style.
- The caption matches the chapter topic and the target paragraph.
- The figure uses a named layout template unless there is a clear reason to use a custom structure.
- The figure uses a named style profile S1-S8 when the task asks for a formal proposal infographic or full-document chart redesign.
- Strict official 4:3 mode is used when requested by the prompt or document context: 4:3 canvas, white background, flat technology style, sharp lines, restrained blue/green/orange accents, no gradient, no shadow, no 3D, no cartoon, no watermark, no logo, and no decorative background.
- The figure expresses both proposal logic and technical principle where relevant.
- The visual hierarchy can be understood in 10 seconds by a reviewer.
- The project subject, domain terms, and acceptance evidence are visible in the artwork, not only in the surrounding paragraph.
- The layout uses a clear grid, lane, table, or symmetric structure rather than freely placed boxes.
- Text remains readable in A4 Word/PDF at the intended insertion size.
- The main visual structure fills the artwork; large blank margins or small centered charts inside a wide frame are rejected.
- Printed proof readability is the final standard: if a printed page photo shows labels weaker than surrounding body text, enlarge core labels, remove redundant in-artwork titles, and tighten whitespace before accepting the figure.
- Text boxes do not overflow, clip, or collide: numbered badges, corner tags, icons, or labels must occupy their own reserved zone and must not share a cramped title baseline.
- If the user asks to fix badge/title overlap without changing font size, preserve font sizes and adjust only spacing, coordinates, card height, or reserved zones.
- Sparse text in tall cards is visually balanced: if a card has only a short title and 1-3 body lines, center the content group vertically or reduce the card height instead of leaving a large empty lower area.
- Route, task, phase, and closed-loop cards do not place note/evidence text at the bottom as a loose footer unless the card is explicitly designed as a footer card; concise evidence belongs inside the centered content group.
- Meaning is still clear in black-and-white printing.
- Lines, arrows, labels, and module boundaries are visible after PDF export.
- Arrows are short, deliberate, and aligned; long diagonal connectors and awkward collisions are rejected.
- Document matrices have a reasonable text-to-whitespace ratio; the table body should not look sparse or padded for display.
- Matrix row numbers use a dedicated narrow column, not floating circles, badges, or decorative markers.
- Matrix headers, row numbers, and body cell text are horizontally and vertically centered unless a long evidence note explicitly requires left alignment.
- Official captions, formal figure numbers, `建议图题`, and long explanatory notes stay outside the artwork. Short in-artwork theme anchors are allowed when they clarify the project subject or evidence logic.
- When inserting or replacing figures in a DOCX, preserve the document template's pagination rhythm: do not force page breaks before every chapter just to increase pages; keep each figure with its external caption; fix page numbers if they split or render as multiple vertical fragments.
- The figure avoids empty slogans, decorative clutter, large unused canvas areas, and PPT-only visual effects.
