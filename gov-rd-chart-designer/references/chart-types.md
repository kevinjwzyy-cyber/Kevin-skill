# Chart Type Library

Select a figure type by the question the proposal section must answer.

## Priority Review-Oriented Figure Types

When redesigning a full proposal or matching selected reference quality, prefer these high-signal figure types before falling back to generic diagrams:

- `痛点-中枢-成果`: connects scenario pain points to the project core subject and concrete outputs. Best paired with S1.
- `层级科学原理`: shows scenario constraints, data evidence, domain mechanism, intelligent model, and engineering validation. Best paired with S2.
- `任务-指标`: proves that each research task maps to measurable indicators and acceptance evidence. Best paired with S3 or S7.
- `技术路线-证据链`: shows R&D stages plus output evidence, such as datasets, model versions, logs, reports, and IP. Best paired with S4 or T2.
- `生命周期复用`: shows data/evidence governance from collection to feedback reuse. Best paired with S6.
- `示范验证闭环`: shows field scene, system/model output, human/expert confirmation, feedback optimization, and final validation evidence. Best paired with S8.

Avoid generic `数据层-模型层-服务层-应用层` figures unless each layer is filled with project-specific modules and review evidence.

## Scientific Problem Decomposition

Use when the section explains why the project is necessary.

- Question: What scientific problems or technical bottlenecks prevent the goal from being achieved?
- Structure: policy/application need -> core problem -> sub-problems -> target breakthroughs.
- Best for: project background, necessity, research content overview.
- Selected-style option: use `痛点-中枢-成果` when the project has a clear platform, model, or system as the core subject.
- Avoid: listing needs without showing the bottleneck relationship.

## Technical Principle Figure

Use when the section must show how the core technology works.

- Question: What mechanism, model, algorithm, process, or system principle enables the solution?
- Structure: input objects/data/materials -> mechanism/model/process -> key parameters/modules -> output capability -> validation.
- Best for: technical route, key technology, innovation point, feasibility analysis.
- Selected-style option: use `层级科学原理` with a pyramid or layer stack when the section must look like a scientific logic argument rather than a workflow.
- Avoid: management modules that do not explain the technology.

## Overall Technical Route

Use when the proposal needs to connect research tasks into a coherent path.

- Question: How does the project move from problem analysis to R&D, integration, testing, and application?
- Structure: problem identification -> key technology research -> prototype/system integration -> test verification -> demonstration application.
- Best for: research plan, technical route chapter, implementation plan.
- Selected-style option: use `技术路线-证据链` when each stage should expose data, prototype, report, validation, or IP outputs.
- Avoid: a flat list of tasks without dependencies or milestones.

## R&D Task Decomposition

Use when the proposal must prove that work packages are complete and coordinated.

- Question: How are the R&D tasks divided, and how do they support the overall goal?
- Structure: project objective -> task 1/task 2/task 3 -> key outputs -> shared dependencies.
- Best for: research contents, task assignment, project organization.
- Selected-style option: use `任务-指标` when the reviewer needs to see task-to-acceptance mapping quickly.
- Avoid: too many equal boxes; group tasks by scientific logic or system layer.

## Bottleneck-Technology-Outcome Mapping

Use when the proposal must show targeted problem solving.

- Question: Which bottleneck is solved by which key technology, producing which measurable outcome?
- Structure: `序号 | 技术瓶颈 | 突破技术 | 验证方法 | 成果与证据`.
- Best for: innovation points, feasibility, assessment indicators.
- Layout: use a compact document matrix with a narrow serial-number column and no floating row badges.
- Alignment: center all header text, row numbers, and body cell text horizontally and vertically unless a cell contains a long paragraph-like note that needs left alignment.
- Avoid: one-to-many mappings that become unreadable; split into two figures if needed.

## Document Matrix Figure

Use when formal Word/PDF body text needs a dense, auditable table-like figure rather than a PPT-style visual.

- Question: How do proposal elements correspond row by row for review, replication, or acceptance?
- Structure: `序号 | 核心对象 | 方法/技术 | 验证/依据 | 成果/证据`, renamed to match the chapter.
- Best for: technical bottleneck matrices, task-indicator-result matrices, review evidence matrices.
- Selected-style option: use S7 Review Matrix Enhanced for high-density but print-readable review evidence.
- Layout: first column is a separate narrow serial-number column; remaining columns use concise multi-line phrases.
- Density: the table body should fill most of the artwork, with tight outer margins and compact cell padding.
- Alignment: default every table cell to horizontal and vertical center alignment; keep row numbers centered in their own narrow column.
- Avoid: large internal titles, subtitles, footer notes, decorative circles, icons, and oversized blank cells.

## Indicator-Task-Result Matrix

Use when the proposal must show that indicators can be achieved and verified.

- Question: Which task supports each assessment indicator, and what result will prove completion?
- Structure: rows as indicators or tasks; columns as `序号`, task, method, data/evidence, deliverable, verification when space allows.
- Best for: performance objectives, assessment plan, acceptance criteria.
- Alignment: center headers, serial numbers, and body text in each cell; use left alignment only for deliberately long evidence descriptions.
- Avoid: small dense tables; keep labels concise and use a dedicated numbering column.

## Organization And Collaboration Mechanism

Use when the proposal explains implementation governance.

- Question: How do leading units, participating units, experts, users, and demonstrations coordinate?
- Structure: leadership/coordination -> technical group -> implementation group -> demonstration/user feedback -> quality control.
- Best for: organization implementation, guarantee measures.
- Avoid: treating this as the main technical figure unless the section is managerial.

## Closed-Loop Validation And Application

Use when the proposal must show iterative R&D or application verification.

- Question: How will research, testing, feedback, and improvement form a closed loop?
- Structure: R&D design -> prototype/system -> test verification -> application feedback -> optimization iteration.
- Best for: demonstration application, validation plan, continuous improvement.
- Selected-style option: use `示范验证闭环` when field scenarios, human/expert review, or pilot operation must be explicit.
- Layout: prefer a compact four-step cycle, a two-row feedback lane, or a 2x2 quadrant with equal modules and short orthogonal connectors.
- Center concept: if a central concept is needed, use a small aligned center label or a narrow band, not a large isolated box.
- Avoid: circular arrows without concrete evaluation criteria; detached boxes around a large center box; long diagonal arrows; large blank areas around the loop.

## Application Demonstration And Transformation Path

Use when the section emphasizes adoption, demonstration, or social/economic value.

- Question: How do research outputs become demonstrable applications and scalable impact?
- Structure: research result -> pilot scenario -> demonstration unit -> standard/process/product -> promotion path -> expected benefit.
- Best for: expected results, demonstration, transformation, social benefits.
- Avoid: benefit claims that are not linked to project outputs.

## Data/Evidence Lifecycle Reuse

Use when the proposal must prove that data, logs, model outputs, audit records, or validation materials are reusable and traceable.

- Question: How does the project turn raw data and field feedback into reusable evidence assets?
- Structure: collection -> cleaning/desensitization -> labeling/modeling -> application/audit -> feedback -> dataset/evidence reuse.
- Best for: data governance, model iteration, quality audit, acceptance material chapters.
- Layout: use S6 Lifecycle Governance Loop or T4 loop with a central asset/evidence theme anchor.
- Avoid: plain data-flow arrows without governance, audit, or reuse evidence.
