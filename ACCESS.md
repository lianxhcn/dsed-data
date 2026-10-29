# 获取与配套状态

本页及展示页公开的是案例背景、数据特征、学习任务和官方入口。七套本地数据包准备完成，但本仓库没有附送数据文件。后续按书稿章节组织配套，不把计划写成已交付成果。

| 资源 | 获取方式与当前边界 |
|---|---|
| CSMAR | [CSMAR 官方入口](https://data.csmar.com/)。通过 CSMAR 机构授权获取；本页提供来源说明。本地数据、字典与读取说明已备。课堂表与完整表的样本及处理口径不同。 |
| hybrid | [官方数据](https://doi.org/10.7910/DVN/6X4ZZL)、[来源论文](https://doi.org/10.1038/s41586-024-07500-2)。从 Harvard Dataverse 获取 1.1 版复现资料。本地多表包、逐表索引与字典已备。匿名表缺少共同员工键，不能跨文件拼接个人。 |
| hkfamily | [官方获取说明](https://digital.lib.hkbu.edu.hk/helper-at-home/en/dataset-download.html)、[数据版本](https://doi.org/10.7910/DVN/O7EHQB)。官方项目页及 Dataverse V2；使用须遵守非商业许可。本地数据、字典与同源文献导航已备。当前使用未加权样本；商业教材附送需另核许可。 |
| shoppers | [UCI 官方数据](https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset)。通过 UCI 官方数据页获取，按来源要求引用。本地会话表、变量字典与读取说明已备。先确定预测时点；完整会话特征未必能用于实时预测。 |
| donation | [官方数据 V1](https://doi.org/10.3886/E113224V1)、[来源论文](https://doi.org/10.1257/aer.97.5.1774)。从 openICPSR 获取 V1 复现资料，按原包条件使用。本地数据、核心变量字典与筛选说明已备。全空行不能视为零捐赠；核心分析仅用非空记录。 |
| gym | [作者数据页](https://eml.berkeley.edu/~sdellavi/data/gymdata.shtml)、[来源论文](https://doi.org/10.1257/aer.96.3.694)。通过作者官方数据页获取，依来源说明使用。本地月表、经历表与变量说明已备。零到访、缺失与非在籍月份须区分；业务标记不等于重复行。 |
| WDI | [世界银行 WDI](https://datacatalog.worldbank.org/search/dataset/0037712/world-development-indicators)。通过世界银行官方目录与 API 获取，并保留指标来源。本地固定快照、指标字典与读取说明已备。指标覆盖并不完整，宏观相关性不能直接解释为因果效应。 |
| GMD | [GMD 官方获取](https://www.globalmacrodata.com/data.html)、[使用条款](https://www.globalmacrodata.com/license.html)。读者在 GMD 官网按条款自主获取；本页不提供数据镜像。获取流程已验证；本页提供官方入口与使用提示。属于扩展获取资源，不计入七套本地数据包。 |

数据规模是当前整理范围的说明，不代表每项分析都使用全部记录。实验分析、调查样本、月度统计与宏观比较应按研究问题确定样本和口径。

GMD 的数据规模、覆盖范围和单位以读者实际取得的版本为准；应记录下载日期、软件包与数据版本、筛选参数和单位，并区分实际值与预测值。本仓库不镜像其原始、筛选或派生数据。

AI 辅助不能替代对变量含义、研究设计及结论的人工判断。来源访问若受机构权限、登录或网络限制，请使用官方渠道；本页不提供绕过访问条件的方法。
