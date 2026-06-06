# Official 4:3 Proposal Prompt Rules

Use these rules when the user asks for strict national/provincial/municipal key R&D application figure norms, selected proposal prompt templates, or "申报书必备图" in a unified 4:3 style.

This mode is stricter than the default formal infographic style. It is intended for review-expert-friendly Word/PDF application figures that must look clean, official, and printable without relying on decorative effects.

## Trigger Conditions

Apply this mode when any of these signals appear:

- `国家重点研发计划`, `省市重点研发计划`, `申报书插图规范`, `严格遵循`, `4:3标准比例`, or similar wording.
- The user provides prompt-style instructions for required proposal figures.
- The task asks for a unified set of official body figures rather than a visually expressive infographic pack.
- The output must be suitable for A4 printing, black-and-white review, or conservative expert review.

If the user asks for a selected-reference infographic style but does not require strict official 4:3, keep the default true-ratio style profile rules from `style-profiles.md`.

## Visual Baseline

- Canvas: unified 4:3 unless the user explicitly asks for another ratio.
- Background: pure white.
- Style: flat technology diagram, minimalist, formal, and clean.
- Lines: sharp, clear, straight or orthogonal; use thin but visible arrows.
- Layout: symmetric, balanced, and grid-aligned; no free-floating boxes.
- Main palette: deep blue `#1890ff`, deep green `#52B788`, orange `#F2994A`, with optional deep blue `#4267B2` or muted brown-orange `#C45A2F` only when semantically useful.
- Grayscale: modules must remain distinguishable in black-and-white through position, line style, fill value, labels, or numbering.

## Typography

- Use Microsoft YaHei, SimHei, or the document's formal Chinese sans font for in-artwork labels.
- Use bold or semi-bold Chinese text for core labels.
- Minimum in-artwork text: equivalent to 12 pt at final Word insertion size in this strict mode.
- If print proof or screenshot review shows weak text, increase important labels to about 14 pt before removing content.
- Avoid artistic fonts, decorative lettering, blurred text, low contrast, and tiny annotations.
- Keep text centered horizontally and vertically in modules unless a long paragraph note explicitly requires left alignment.

## Negative Rules

Reject and redraw if the figure contains:

- 3D rendering, cartoon figures, decorative icons that distract from the technical logic, or video-cover styling.
- Complex background patterns, border decorations, glow, drop shadow, heavy transparency, or excessive gradient transitions.
- Watermark, copyright mark, brand logo, or unrelated iconography.
- Excessively bright colors, low black-and-white contrast, blurred text, or small unreadable labels.
- Text overflow, title/badge overlap, clipped glyphs, crowded baselines, or arrows crossing confusingly.

## Required Official Figure Patterns

Use these patterns as first choices for common proposal sections.

### Topic Overall Framework

Use for `课题总体框架图` or independent research-topic positioning.

- Structure: one central blue rounded rectangle naming the AI/core technical engine or project core.
- Surrounding modules: four balanced green or pale modules around the center for scene object, scene pain points, R&D chain, and controllable outputs.
- Connectors: short blue arrows point toward the central engine or show a simple upstream-to-core-to-output relation.
- Content: include the real project subject, industry scene, core pain points, R&D chain, and autonomous/acceptance outcomes.

### Scientific Principle And Technical Logic

Use for `科学原理与技术逻辑图`.

- Structure: five equal left-to-right modules.
- Default chain: `场景约束 -> 数据证据 -> 领域机理 -> 智能模型 -> 工程验证`.
- Add one bottom innovation band that states the core scientific or technical innovation in one sentence.
- Use short arrows between adjacent modules only; avoid diagonal or distant connectors.

### Technical Route

Use for `技术路线图` or phased implementation.

- Structure: 4-5 vertical or horizontal phase cards with clear stage names, time nodes when available, and stage outputs.
- Connectors: one main route arrow from diagnosis/data foundation to model/system/prototype, demonstration, and acceptance.
- Each phase card should include work focus plus output evidence, not only a management label.

### System Architecture

Use for `系统架构图`.

- Structure: bottom-up or top-down layered architecture.
- Typical layers: source/sensing layer, data layer, model layer, application/service layer, user/governance layer.
- Modules inside each layer must use project-specific names; avoid only `数据层/模型层/服务层`.
- Use only adjacent-layer connectors unless a cross-layer relation is essential.

### Research Content And Assessment Indicators

Use for `研究内容与考核指标对应图`.

- Structure: left column for research contents, right column for assessment indicators or acceptance evidence.
- Use one-to-one dotted or straight connectors between rows.
- Put quantitative indicators directly in the right column, such as datasets, model count, accuracy, prototype systems, patents, software copyrights, standards, reports, or demonstration batches.
- Keep rows aligned exactly; do not use scattered mapping lines.

## Word/PDF Delivery

- Preferred source: editable SVG or draw.io; if raster is needed, export PNG at 300 DPI or higher.
- Recommended Word body insertion: inline, centered, about 15 cm wide unless the document template uses a different figure width.
- Keep the official caption outside the artwork and immediately below the image.
- Do not force page breaks before every chapter to increase page count. Follow the existing template's pagination rhythm.
- For long Word tables near figures, add a page break only when it prevents an orphaned table header or one-row split at the bottom of a page.
- Page numbers must render as one centered page number, not as split fragments.
- After replacing figures, render or inspect DOCX/PDF pages that contain figures and long tables.
