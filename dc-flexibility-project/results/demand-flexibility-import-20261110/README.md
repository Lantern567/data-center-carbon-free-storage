# 数据中心需求侧柔性论文材料

本批归档收录截至 2026 年 11 月 10 日的论文和简表 Word，以及对应的主图和结果数据。原研究由方向一仓库 [33](https://github.com/TuzzyT-Laiii/33) 维护。本目录供无碳供电、储能及后续博弈研究参考，使用时沿用各源结果的模型边界。

| 资料 | 内容和对应数据 | 来源 |
| --- | --- | --- |
| 四页结果提纲 | 四个结论分开排版，使用 `figures/` 的图 1–4 | [#71](https://github.com/TuzzyT-Laiii/33/pull/71) |
| 中文 Results v2、第一节英文 Results v1 | 中文结果草稿及第一节英文稿。第一节对应全球网格，第二节对应八城市联合规划与出租 | [#68](https://github.com/TuzzyT-Laiii/33/pull/68)、[#64](https://github.com/TuzzyT-Laiii/33/pull/64) |
| 任务时间柔性简表 | 最新第九章含少配服务器、八城市供能及出租比较。`data/` 保留主要章节的派生表与模型汇总 | [#69](https://github.com/TuzzyT-Laiii/33/pull/69) |
| 论文图 1–4 | PNG、PDF、图注和 `figures/source-data/` 中的逐面板源数据 | [#70](https://github.com/TuzzyT-Laiii/33/pull/70) |
| 联合规划与出租结果 | `data/joint-planning/` 与 `data/idle-gpu-rental/`，包含逐城市与汇总比较 | [#65](https://github.com/TuzzyT-Laiii/33/pull/65)、[#67](https://github.com/TuzzyT-Laiii/33/pull/67) |
| 卡价和冗余补充计算 | `data/cfe-card-price/`，包含经济最优、100% 逐时本地无碳目标、平卡和减卡价格交点、加卡下界及冗余重算 | [#72](https://github.com/TuzzyT-Laiii/33/pull/72) |

Word 存放在 [`word/`](word/)。第七、八章的固定机群经济性与全球网格分别存放在 `data/fixed-fleet-flexibility/` 和 `data/global-flexibility/`。任务、设备及负荷的派生表见 `data/compute-config/`、`data/workload-classification/`、`data/compute-load/` 和 `data/eight-city-load/`。

[来源与 SHA-256 清单](../../data/metadata/demand-flexibility-import-20261110.csv)记录每个导入文件的源路径、来源提交、大小和字节校验。八城市联合规划、出租和卡价补充结果采用各自的任务约束和供能边界。原始任务、逐小时气象输入及服务器归档由原来源维护。
