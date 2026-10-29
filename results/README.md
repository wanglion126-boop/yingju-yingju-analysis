# 结果目录

初始化仅创建本说明，不生成 T001 分析结果。

收到用户指令后，在对应 `results/<taskId>/` 下输出 `analysis.json` 和 `summary.md`，默认状态 pending_review。第一阶段只整理信息，第二阶段才比较行动；字段与校验边界见 [输出约定](../context/03-输出约定.md)。

不得静默覆盖原结果。复核或切换阶段时，使用 `analysis-r02.json`、`summary-r02.md` 等未占用的配对名称，并在 summary 记录前版、修改依据与待确认项。结论与案例草稿留在该任务结果目录，未经确认不改输入、context 或正式案例。
