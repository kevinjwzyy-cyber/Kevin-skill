---
name: gov-rd-chart-designer
description: "Design professional figures for Chinese government science-and-technology R&D project application documents. Use when Codex needs to transform government R&D proposal text, project plans, scientific problems, technical principles, key technologies, technical routes, R&D tasks, indicators, implementation mechanisms, or expected outcomes into Word/PDF body illustrations that are print-readable, logically rigorous, chapter-numbered, and suitable for formal application files."
---

# Government R&D Chart Designer

## Overview

Use this skill to design figures for government science-and-technology R&D project application documents. Design for Word/PDF body insertion and printed review first, not for slide decks or large-screen display.

Default to figures that are restrained, editable, logically explicit, and readable after PDF export and paper printing. Every figure must serve the proposal argument: why the project should be funded, how the technology works, how R&D tasks connect to outcomes, and how indicators will be achieved.

## Core Workflow

1. Establish document context.
   - Identify or infer the chapter number, chapter title, target paragraph, figure purpose, existing figure-number style, and whether the figure is portrait A4, landscape A4, or appendix material.
   - If the context is missing, state reasonable assumptions and use a provisional figure number such as `图2-1` only when the chapter can be inferred.

2. Extract the proposal logic.
   - Build the application chain: `政策需求/行业痛点 -> 科学问题/技术瓶颈 -> 研发思路 -> 关键技术 -> 研发任务 -> 成果产出 -> 应用示范 -> 绩效指标`.
   - Build the technical principle chain: `研究对象/数据/材料 -> 机理/模型/算法/工艺 -> 方法路径 -> 系统集成 -> 验证评价 -> 工程应用`.
   - Prefer causal, hierarchical, sequential, or matrix relationships over decorative grouping.

3. Choose the figure type.
   - Read `references/chart-types.md` when selecting among architecture, technical route, principle, task decomposition, indicator matrix, closed-loop, or mechanism figures.
   - Use the figure type that answers one clear question, such as "what technical bottleneck is solved," "how the core principle works," or "how tasks support indicators."
   - For bottleneck-technology-validation-evidence mappings, default to a compact document matrix with a separate narrow serial-number column.

4. Design the figure for Word/PDF and printing.
   - Read `references/print-spec.md` before giving final dimensions, typography, line weights, color rules, or raster export settings.
   - Prefer editable vector output: SVG, draw.io XML, Mermaid source that can be exported to SVG/PDF, or a PPT/Word-editable structure.
   - For document matrices, keep the table body dominant, reduce outer and cell padding, and avoid floating decorative row numbers.
   - Avoid color-only meaning, low-contrast labels, gradients, shadows, tiny text, screenshot-like raster output, and slide-style decoration.

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
3. Logical structure: modules, sequence, hierarchy, or matrix axes.
4. Visual specification: page fit, orientation, typography, line weights, color, and black-and-white readability notes.
5. Editable source or implementation instructions, when requested or when the user asks for a usable artifact.

For simple requests, keep the response compact. For actual deliverables, produce the editable source and include export guidance.

## Quality Checklist

Before finalizing, verify:

- The figure number follows the chapter and existing document style.
- The caption matches the chapter topic and the target paragraph.
- The figure expresses both proposal logic and technical principle where relevant.
- The visual hierarchy can be understood in 10 seconds by a reviewer.
- Text remains readable in A4 Word/PDF at the intended insertion size.
- Meaning is still clear in black-and-white printing.
- Lines, arrows, labels, and module boundaries are visible after PDF export.
- Document matrices have a reasonable text-to-whitespace ratio; the table body should not look sparse or padded for display.
- Matrix row numbers use a dedicated narrow column, not floating circles, badges, or decorative markers.
- Captions, suggested figure titles, subtitles, and explanatory notes stay outside the artwork unless explicitly requested.
- The figure avoids empty slogans, decorative clutter, and PPT-only visual effects.
