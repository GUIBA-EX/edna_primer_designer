# edna_primer_designer

用于 eDNA 宏条形码引物选择与设计的中文 AI skill：把原始文献转化为可执行的筛选流程，同时保留证据边界。

[English](README.en.md) · [直接阅读 SKILL.md](SKILL.md) · [设计案例](references/method-cases.md)

## 能做什么

- 解释已有引物的设计逻辑，并按目标类群、样本背景和分类终点比较方案。
- 追踪作者相关研究，区分新设计、改型、沿用和定量/建库流程。
- 规划新候选的参考集、计算筛选、指标和分阶段验证。

这是指南与记录模板，不是自动运行的设计软件、完整引物数据库或可直接下单的序列表。文献报告、计算预测和实验验证分别标注。

## 怎么用

先读 [SKILL.md](SKILL.md)，再按任务需要打开参考文件。支持 `SKILL.md` 的工具应加载整个目录，保留 `references/` 和 `templates/`；安装位置遵循所用客户端的说明。若客户端按目录名发现 skill，本地目录名使用 `edna-primer-design`。支持显式调用时可用 `$edna-primer-design`。

示例：

- “使用 $edna-primer-design，比较 MiFish 与 Teleo02 在某流域淡水鱼监测中的适用性，先说明需要哪些数据。”
- “梳理 Minamoto 或 Ushio 参与的引物研究，按设计、改型与应用分类，并给原始来源。”
- “为目标类群制定候选筛选方案，明确覆盖、近缘种区分、背景扩增和验证标准。”

## 按需展开

| 文件 | 内容 |
|---|---|
| [设计案例](references/method-cases.md) | 谱系补偿、背景选择、长度/分辨率、组合与定量案例 |
| [操作细节](references/design-workflow.md) | 参考数据、候选、工具和实验安排 |
| [指标与验证](references/metrics-and-gates.md) | 集合、分母、公平比较和证据终点 |
| [书目](references/bibliography.md) | 原始文献索引 |
| [项目规格](templates/project-spec.yaml) | 需要记录的输入与条件，非可执行配置 |
| [报告模板](templates/design-report.md) | 结论与证据结构；同目录附文献/候选 TSV 表 |

案例包含 MiFish、Teleo02、MiDeca、Scle-12S、BirT、MiMammal、MiBird、μCeta 等；按设计决策组织，不按作者位次或文献数量排名。文献核验记录截至 2026-10-24，具体应用仍需核定版本与原始序列。

## 引用与更正

使用具体引物或方法时，请引用原始论文。收录不代表作者或期刊认可本指南，原文、数据和软件各自的许可不变。

更正请附 DOI、原表/图/补充材料位置及建议修改。不要将未运行的分析或未经验证的序列写成结果。
