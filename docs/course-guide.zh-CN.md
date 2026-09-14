# 爱丁堡大学 MSc Bioinformatics 2026/27

[English](./course-guide.en.md) | **简体中文**

## 课程与历年试卷参考

课程信息、历年试卷链接、题型分析和公开学生经验。

**难度分级：LLM-as-judge 主观评估。** 以具备基本生物学、入门编程和基础统计知识、但未系统学过每门课程的入学者为参照，综合数学抽象、编程实践、知识广度、考核压力和项目依赖判断。1/5 很低、2/5 较低、3/5 中等、4/5 较高、5/5 很高；允许半档。它不是官方评级、学生口碑统计或预测分数。已有相关背景可降低难度，零基础则可能显著增加难度。

**重点建议：MATH11205 Machine Learning in Python 难度高，本版不建议选修。** 此为保守选课建议，不代表官方禁止选课，也不意味着所有学生都会觉得难；需要机器学习训练且基础充分者应另行向课程负责人确认要求。

**覆盖与时效** ：本版覆盖 [2026/27 官方 DPT](https://www.drps.ed.ac.uk/26-27/dpt/ptmscbioin1f.htm) 中显式列出的 19 门课程（4 门必修、15 门选修），包括 PGBI11126 Population Genomic Analysis。DPT、MATH11205 与 PGBI11126 于 2026-09-14 核对；其他课程与试卷的整理日期见文末，未逐项重新核验。选课名额、先修、课表冲突及最终考核须以当届学校信息为准。

## 目录

- [必修课程](#required-courses)
  - [PGBI11095 生物信息学编程与系统管理](#course-pgbi11095)
    - [历年试卷（13 条档案，6 份 PDF）](#papers-pgbi11095)
    - [历年规律与 LLM 难度](#analysis-pgbi11095)
  - [PGBI11003 统计与数据分析](#course-pgbi11003)
    - [历年试卷（14 条档案，3 份 PDF）](#papers-pgbi11003)
    - [历年规律与 LLM 难度](#analysis-pgbi11003)
  - [PGBI11114 生物信息学研究计划](#course-pgbi11114)
    - [考核结构与 LLM 难度](#analysis-pgbi11114)
  - [PGBI11034 生物信息学硕士论文](#course-pgbi11034)
    - [LLM 难度、导师与方向建议](#analysis-pgbi11034)
- [选修 1：Semester 1](#semester-1-electives)
  - [BICH11011 药物结合的定量测定](#course-bich11011)
    - [考核结构与 LLM 难度](#analysis-bich11011)
  - [INFR11211 应用机器学习](#course-infr11211)
    - [历年试卷（4 份）](#papers-infr11211)
    - [逐题核验、覆盖边界与难度评估](#analysis-infr11211)
  - [MATH11205 Python 机器学习](#course-math11205)
    - [历年试卷（10 条档案，6 份 PDF）](#papers-math11205)
    - [历年规律与 LLM 难度](#analysis-math11205)
  - [PGBI11051 生物细胞中的信息处理](#course-pgbi11051)
    - [历年试卷（19 条档案，2 份 PDF）](#papers-pgbi11051)
    - [历年规律与 LLM 难度](#analysis-pgbi11051)
  - [PGBI11122 使用 R 进行数据科学](#course-pgbi11122)
    - [历年试卷（5 份）](#papers-pgbi11122)
    - [历年规律与 LLM 难度](#analysis-pgbi11122)
  - [PGBI11129 生物数据库](#course-pgbi11129)
    - [历年试卷（4 份）](#papers-pgbi11129)
    - [历年规律与 LLM 难度](#analysis-pgbi11129)
- [选修 2：Semester 2](#semester-2-electives)
  - [BILG11004 新一代基因组学](#course-bilg11004)
    - [历年试卷（16 条档案，11 份 PDF）](#papers-bilg11004)
    - [历年规律与 LLM 难度](#analysis-bilg11004)
  - [BILG11016 网站与数据库设计导论](#course-bilg11016)
    - [考核结构与 LLM 难度](#analysis-bilg11016)
  - [BITE11004 宏基因组学](#course-bite11004)
    - [考核结构与 LLM 难度](#analysis-bite11004)
  - [CMSE11576 技术创业与商业化](#course-cmse11576)
    - [考核结构与 LLM 难度](#analysis-cmse11576)
  - [EPCC11017 编程技能](#course-epcc11017)
    - [考核结构与 LLM 难度](#analysis-epcc11017)
  - [PGBI11040 功能基因组技术](#course-pgbi11040)
    - [历年试卷（19 条档案，17 份 PDF）](#papers-pgbi11040)
    - [历年规律与 LLM 难度](#analysis-pgbi11040)
  - [PGBI11057 生物信息学算法](#course-pgbi11057)
    - [历年试卷（15 条档案，14 份 PDF）](#papers-pgbi11057)
    - [历年规律与 LLM 难度](#analysis-pgbi11057)
  - [PGBI11130 生物结构与药物功能](#course-pgbi11130)
    - [考核结构与 LLM 难度](#analysis-pgbi11130)
  - [PGBI11126 群体基因组分析](#course-pgbi11126)
    - [是否新课、考核与 LLM 难度](#analysis-pgbi11126)
- [LLM 难度总表与选课参考](#personalised-plans)
  - [方案 A：基础应用与分散考核](#plan-easiest)
  - [方案 B：计算方法与组学方向](#plan-cs)

## 本资料覆盖课程考核总览

下表难度均为本版 LLM 主观判断，详见开篇评级口径。Total Hours 是此前整理记录的官方名义学习量，不等同于课堂时数，也不是实际耗时预测。

| 类别 | 代码与课程 | 学分 | Total Hours | 2026/27 官方考核 | 可确认的考试资料规则 | 试卷库 | LLM 难度 |
|---|---|---:|---:|---|---|---:|---:|
| 必修 S1 | [PGBI11095 生物信息学编程与系统管理](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11095.htm) | 20 | **200**  | Class Test 50% + Exam 50%，两项须分别达到 50% | 当前官网明确两项均为闭卷线下考核 | 13 / 6 PDF | **3.5/5**  |
| 必修 S1 | [PGBI11003 统计与数据分析](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11003.htm) | 20 | **200**  | 正式 Assessment 栏：Class Test 45% + 55%，Coursework 100% | 官网 Summary 与正式栏有冲突；须以当届 Learn 为准 | 14 / 3 PDF | **4.0/5**  |
| 必修 S2 | [PGBI11114 生物信息学研究计划](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11114.htm) | 10 | **100**  | Research proposal 100% | 无中央笔试 | 0 | **3.0/5**  |
| 必修项目 | [PGBI11034 生物信息学硕士论文](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11034.htm) | 60 | **600**  | Coursework 100%；必须达到 50% | 无中央笔试 | 0 | **4.0/5**  |
| 选修 S1 | [BICH11011 药物结合的定量测定](https://www.drps.ed.ac.uk/26-27/dpt/cxbich11011.htm) | 20 | **200**  | 展示 30% + 扩展实验报告 70% | 无中央笔试 | 0 | **3.5/5**  |
| 选修 S1 | [INFR11211 应用机器学习](https://www.drps.ed.ac.uk/26-27/dpt/cxinfr11211.htm) | 20 | **200**  | Written exam 60% + Coursework 40% | 当前官方课程站：闭卷 120 分钟，三题选二 | 4 / 4 PDF | **4.0/5**  |
| 选修 S1 | [MATH11205 Python 机器学习](https://www.drps.ed.ac.uk/26-27/dpt/cxmath11205.htm) | 10 | **100** （分项 99.5） | Written exam 50% + Coursework 50% | 2022/23-2024/25 允许 3 张 A4 双面笔记和科学计算器；2026/27 未公布 | 10 / 6 PDF | **4.5/5**  |
| 选修 S1 | [PGBI11051 生物细胞中的信息处理](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11051.htm) | 10 | **100**  | Written exam 50% + Coursework 50% | 两份旧卷均为 3 小时、全部作答，只准非编程计算器；当前规则未公布 | 19 / 2 PDF | **4.5/5**  |
| 选修 S1 | [PGBI11122 使用 R 进行数据科学](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11122.htm) | 10 | **100**  | Written exam 50% + Coursework 50% | 2022/23 为 open-book；2023/24 起为现场 2 小时卷，未授权笔记 | 5 / 5 PDF | **2.5/5**  |
| 选修 S1 | [PGBI11129 生物数据库](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11129.htm) | 10 | **100**  | Written exam 50% + Coursework 50% | 2022/23 为 open-book；2023/24 起为现场 2 小时卷，未授权笔记 | 4 / 4 PDF | **3.0/5**  |
| 选修 S2 | [BILG11004 新一代基因组学](https://www.drps.ed.ac.uk/26-27/dpt/cxbilg11004.htm) | 10 | **100**  | Essay exam 50% + Essay coursework 50% | 2021/22 open-book；2022/23 起现场 2 小时、三题选二 | 16 / 11 PDF | **3.0/5**  |
| 选修 S2 | [BILG11016 网站与数据库设计导论](https://www.drps.ed.ac.uk/26-27/dpt/cxbilg11016.htm) | 10 | **100**  | 数据库批判性论文 50% + MySQL 网站 50% | 无中央笔试 | 0 | **3.0/5**  |
| 选修 S2 | [BITE11004 宏基因组学](https://www.drps.ed.ac.uk/26-27/dpt/cxbite11004.htm) | 10 | **100**  | Report 1 30% + Contract Research Report 70% | 无中央笔试 | 0 | **3.0/5**  |
| 选修 S2 | [CMSE11576 技术创业与商业化](https://www.drps.ed.ac.uk/26-27/dpt/cxcmse11576.htm) | 10 | **100**  | 个人作业 30% + 小组展示 70% | 无中央笔试 | 0 | **3.0/5**  |
| 选修 S2 | [EPCC11017 编程技能](https://www.drps.ed.ac.uk/26-27/dpt/cxepcc11017.htm) | 10 | **100** （S2 实例） | 实践型 Coursework 100% | 无中央笔试 | 0 | **3.0/5**  |
| 选修 S2 | [PGBI11040 功能基因组技术](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11040.htm) | 10 | **100**  | Written exam 50% + Assignments 50% | 2020/21-2022/23 open-book；2023/24 起现场 2 小时、第一题必答再二选一 | 19 / 17 PDF | **3.5/5**  |
| 选修 S2 | [PGBI11057 生物信息学算法](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11057.htm) | 10 | **100**  | Written exam 50% + Written assessment 50% | 2020/21-2022/23 open-book；2023/24 起现场 2 小时、第一题必答再二选一 | 15 / 14 PDF | **3.5/5**  |
| 选修 S2 | [PGBI11130 生物结构与药物功能](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11130.htm) | 20 | **200**  | Class test 30% + 小组 mini-project 70% | 无中央正式笔试；30% 课堂测验的当届条件待 Learn 公布 | 0 | **3.5/5**  |
| 选修 S2 | [PGBI11126 群体基因组分析](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11126.htm) | 10 | **100**  | Coursework 100%：每周 quiz 25% + 第 5 周限时上机 75% | Block 3；上机材料、时长与工具规则待当届说明 | 未取得可核对旧卷 | **4.0/5**  |

### 官方名义学习量如何纳入判断

- 本版覆盖的 19 门课程遵循约 **10 小时/SCQF credit**  的总量口径：10 学分为 100 小时、20 学分为 200 小时、60 学分 dissertation 为 600 小时。完整学位因此是 **1,800 小时** ：必修 1,100 小时，选修 700 小时。
- S1 必须选 20 学分、S2 必须选 50 学分，所以任何合规选课组合的选修总量都是 **700 小时** 。`Total Hours` 本身不会让方案 A 比方案 B 少工时；它真正改变的是**工时集中度** ——一门 20 学分课把 200 小时、考核与挂科风险集中在同一门课，两门 10 学分课则把相同 200 小时拆开。
- DRPS 活动分类不完全等同于课表接触时间。有些课程描述明确包含 lab、workshop 或 field excursion，却未在结构化字段中单列监督实践；本文只按官方原始分类报告，不把“未单列”解释成“没有”。
- `MATH11205` 的官方总数是 100 小时，但公开分项相加为 99.5 小时，页面没有解释 0.5 小时差异。`EPCC11017` 同时开 S1/S2 两个实例；本文按 Bioinformatics DPT 指定的 **Semester 2**  实例统计 100 小时。

---

<a id="required-courses"></a>
# 必修课程

四门必修课合计 110 credits；加上 Semester 1 的 20 credits 选修和 Semester 2 的 50 credits 选修，全年共 180 credits。

<a id="course-pgbi11095"></a>
## [PGBI11095 生物信息学编程与系统管理 / Bioinformatics Programming and System Management](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11095.htm)

- **学分与学期：** 20 credits，Semester 1，必修。
- **官方名义学习量：** Total Hours **200** （讲授 20；监督实践/工作坊 40；项目级教学 4；定向/独立学习 136）。
- **课程内容：** 以 Python、Unix/Linux、版本控制、脚本、数据库/网络服务与可复现工作流为主，目标是把生物信息分析做成可靠、可维护、能让他人使用的系统。
- **2026/27 官方考核：** 50% in-person closed-book Class Test + 50% in-person closed-book December Exam；主考试页列为 **180 分钟** ，**两项必须分别达到 50%** 。课程页还说明，若只挂其中一项，通常可在 Semester 2 参加相应 alternative assessment；若两项都挂，除非有获批的 exceptional circumstances，一般不提供两项替代考核。

<a id="papers-pgbi11095"></a>
### 历年试卷

共 13 条档案：6 份可读取 PDF、7 条 `Paper Unavailable`。2022/23、2023/24 的 PDF 标题明确写着 **Essay question only** ，只能代表该题，不能冒充整份试卷。

#### [2025/2026：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/a624c6b8-67e3-4465-888c-957e23918413/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/e2dddc3c-afd1-4851-bec4-fb0c30f58450)

#### [2024/2025：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/eda4f4a4-42f0-42c0-99a2-60208a2cccca/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/cb5f73a5-1156-4ad7-aed2-883c035d194d)

#### [2023/2024：Essay question only PDF](https://exampapers.ed.ac.uk/bitstreams/b4b1d960-42d7-494f-937d-0726eb7c0518/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/ed351d6c-e38d-4c9a-a6b4-b0037f246f49)

#### [2022/2023：Essay question only PDF](https://exampapers.ed.ac.uk/bitstreams/f9da7d46-8fb7-4588-a511-808c2367dd89/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/1091c790-46f9-4bc9-8251-92bfeea4c763)

#### [2021/2022：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/d6b3bca4-ffd6-48a4-9070-4ce7f90673ff/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/95263af6-1469-4919-a6cb-75ae16b2369b)

#### [2020/2021：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/a9aa34a2-fb2d-431a-ae72-170a83f43b23/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/5916cc9f-0e4d-4fb4-9723-a73b3f747b5d)

#### Paper Unavailable 档案

- [2019/2020](https://exampapers.ed.ac.uk/items/01197488-e935-45ff-a724-87c7731a561e)
- [2018/2019](https://exampapers.ed.ac.uk/items/3fc6d273-6a47-4bbf-adc8-f698b0eeed90)
- [2017/2018](https://exampapers.ed.ac.uk/items/9b8f0d0d-3ab7-4774-8667-32eb1ae8429b)
- [2016/2017](https://exampapers.ed.ac.uk/items/354afda4-a20f-4507-b97f-b423db880bbd)
- [2015/2016](https://exampapers.ed.ac.uk/items/2b8f5c58-8181-4346-938d-4b693e90d360)
- [2014/2015](https://exampapers.ed.ac.uk/items/d16786d7-7342-43bf-ace9-3e9e4a3cdffc)
- [2013/2014](https://exampapers.ed.ac.uk/items/c9bae40c-82db-4edd-9405-1cce07bf22e3)

<a id="analysis-pgbi11095"></a>
### 历年规律、当前风险与 LLM 难度

| 维度 | 核验结果 |
|---|---|
| 历年实际题型 | 六份资料都要求设计一个有真实生物意义的 Python/Linux 序列分析服务：2020/21-2023/24 围绕 BLAST，2024/25-2025/26 改为序列保守性分析 `conservED`。核心一直是输入校验、数据流、工具调用、输出与用户防错。 |
| 重复程度 | **模板重复很高。** 2022/23 与 2023/24 的 BLAST essay prompt 接近逐字重复；2020/21-2023/24 的整体服务设计逻辑也高度一致。2024/25 与 2025/26 又连续使用同一个保守性产品场景，后一年仍按用户、程序员/数据流、Python 实现三种视角考。 |
| 旧卷考试形态 | 2020/21 为疫情期 open-book；2021/22 是 4 小时窗口（建议作答 3 小时 + 1 小时提交）；2022/23、2023/24 公开的只是 essay question。它们不能证明当年整卷或当前考试都开卷。 |
| 2026/27 是否可押题 | **可押能力框架，不可押具体生物工具。** 服务设计、输入输出、防错和 Python/Linux 综合题大概率仍重要，但当前官网已经明确改为两个线下闭卷组件，不能照搬疫情卷的查资料策略。 |
| 主要风险 | Python/Linux 综合应用与闭卷系统设计并重；两个考核组件分别过线，不能只靠总分补偿。 |
| **LLM 难度**  | **3.5/5。** Python/Linux 综合应用与闭卷系统设计并重；两个考核组件分别过线，不能只靠总分补偿。 |

<a id="course-pgbi11003"></a>
## [PGBI11003 统计与数据分析 / Statistics and Data Analysis](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11003.htm)

- **学分与学期：** 20 credits，Semester 1，必修。
- **官方名义学习量：** Total Hours **200** （讲授 41；监督实践/工作坊 16；复习课 6；项目级教学 4；定向/独立学习 133）。
- **课程内容：** 概率分布、实验设计、线性模型/ANOVA、广义线性模型、R 分析与结果解释，目标是让学生能为生物数据选择并解释合适的统计方法。
- **2026/27 官方考核：** 正式 `Assessment` 栏写的是 Coursework 100%，由 Class Test 1（45%）与 Class Test 2（55%）构成；但同一页 `Summary` 又提到 two assignments、quiz 和 open-book exam。两处信息互相冲突，本文不替校方猜测；正式入学后应以当届 Learn、Assessment brief 与 Course Organiser 书面说明为准。

<a id="papers-pgbi11003"></a>
### 历年试卷

共 14 条档案：3 份 PDF、11 条 `Paper Unavailable`。可读卷只覆盖 2021/22-2023/24，且是旧考核制度，不能直接代表 2026/27 两次 class test。

#### [2023/2024：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/b0902e22-9d3b-4c78-a99d-388fcb8965d4/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/8daebd64-b237-4be6-adb5-998e9c916ab3)

#### [2022/2023：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/59bcaa75-4dab-4268-9d4a-bdc15461ebba/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/c3636a6b-9017-42c9-9aac-3dfac6ede45d)

#### [2021/2022：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/572e6fd9-42e4-4db8-9b2e-c0712b8f544a/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/527f146e-8284-4916-8794-381a094fbcea)

#### Paper Unavailable 档案

- [2020/2021](https://exampapers.ed.ac.uk/items/9a3e1a68-1a3d-46b4-9536-1313e4de1185)
- [2019/2020](https://exampapers.ed.ac.uk/items/70bdf50d-4601-408b-8af0-9ebe8d1e16ef)
- [2018/2019](https://exampapers.ed.ac.uk/items/e65f4fc1-47a3-48de-a4c1-6e599b674bb2)
- [2017/2018](https://exampapers.ed.ac.uk/items/8f58293e-389f-49d2-8663-59dcb16a2802)
- [2016/2017](https://exampapers.ed.ac.uk/items/3dabd47a-4c7c-4421-9721-a6e8f6482ddd)
- [2015/2016](https://exampapers.ed.ac.uk/items/20864787-39c9-4c8f-b215-92ff0d01759e)
- [2014/2015](https://exampapers.ed.ac.uk/items/896b695c-1489-47f6-afa4-756d29601bd9)
- [2013/2014](https://exampapers.ed.ac.uk/items/8ec6b6e5-0c15-4bee-b7db-b375543220de)
- [2012/2013](https://exampapers.ed.ac.uk/items/38d9c99d-0d20-4d64-bd2e-53076c287403)
- [2011/2012](https://exampapers.ed.ac.uk/items/4e9378b2-0be9-4425-b235-40dc8e1916c0)
- [2010/2011](https://exampapers.ed.ac.uk/items/287bf4ac-7915-4cbd-9f28-db294c84f32e)

<a id="analysis-pgbi11003"></a>
### 历年规律、当前风险与 LLM 难度

| 维度 | 核验结果 |
|---|---|
| 三份旧卷共同核心 | 概率/分布 **3/3** 、线性模型与 ANOVA **3/3** 、R 输出或代码解释 **3/3** ；GLM/计数数据 **2/3** ，实验设计 **2/3** 。 |
| 重复程度 | **知识骨架稳定，具体数据与设问变化。** 没有发现整道大题逐字复刻；重复的是“识别设计 → 选模型 → 读 R 输出 → 解释结论”的流程。 |
| 旧卷形态 | 三份卷都要求全部大题作答，并允许以 R 代码/输出支持答案；当时采用电子作答上传。 |
| 2026/27 参考价值 | 内容仍有价值，但考核已在正式栏改写为 45% + 55% class tests。旧卷能反映统计深度，**不能可靠预测当前时长、开闭卷或题数** 。 |
| 主要风险 | 概率、线性模型、ANOVA/GLM 与 R 解释需要同时掌握；公开考核信息有冲突，须查当届说明。 |
| **LLM 难度**  | **4.0/5。** 概率、线性模型、ANOVA/GLM 与 R 解释需要同时掌握；公开考核信息有冲突，须查当届说明。 |

<a id="course-pgbi11114"></a>
## [PGBI11114 生物信息学研究计划 / Research Proposal (Bioinformatics)](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11114.htm)

- **学分与学期：** 10 credits，Semester 2，必修。
- **官方名义学习量：** Total Hours **100** （研讨/辅导 3；项目级教学 2；定向/独立学习 95）。
- **官方考核：** Coursework 100%，提交一份约 6 页、最多 7 页的研究计划；中央试卷库对精确代码检索为 0 条。
- **课程要求：** 提出清晰研究问题，说明背景与意义，设计可执行的方法、数据分析、时间表与风险/伦理安排，并论证该项目适合作为 MSc 独立研究。

<a id="analysis-pgbi11114"></a>
### LLM 难度与拿分风险

- 主要风险是**一份成品占 100%** ：选题边界、导师反馈利用、方法可行性和英文论证任何一处薄弱都没有其他组件对冲。
- **LLM 难度：3.0/5。** 重点是问题界定、方法可行性与英文论证；单份研究计划占全部成绩。

<a id="course-pgbi11034"></a>
## [PGBI11034 生物信息学硕士论文 / MSc Dissertation (Bioinformatics)](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11034.htm)

- **学分与时间：** 60 credits，Block 5（Semester 2）及以后；该课程必须达到至少 50%。
- **官方名义学习量：** Total Hours **600** （项目级教学 12；定向/独立学习 588）。DRPS 未另列 supervision hours，不能把未单列理解为没有导师指导。
- **官方考核：** Coursework 100%，无中央正式笔试，试卷库精确检索为 0 条。60 学分使它成为全学年权重最大的单项。
- **项目形态：** 可以是校内研究，也可能有公司共同提出或共同指导的 industry-linked project；但企业项目是这门 dissertation 的一种实施形式，**不是用实习替换或免修 PGBI11034** 。具体名额每年变化，必须由 Programme Director 批准并按本课程交付成果评分。

<a id="analysis-pgbi11034"></a>
### LLM 难度、导师与方向建议

- 若做 ML/AI4Science/大模型，可找 Informatics 老师参与指导，但项目归属、主导师资格、数据合规和考核仍需 Bioinformatics Programme 批准。最现实的组合是：生物问题/数据明确的主项目 + 信息学院方法导师或 co-supervisor。
- 推荐题型是“可复现生物数据 pipeline + 明确基线 + 严格验证”的 AI/ML 项目；不要只写成通用大模型 demo，否则生物学研究问题和可评价性会不足。
- **LLM 难度：4.0/5。** 独立研究、数据与导师依赖、英文写作和长期进度管理叠加；60 学分的总负担不可忽略。

---

<a id="semester-1-electives"></a>
# Semester 1 选修课

<a id="course-bich11011"></a>
## [BICH11011 药物结合的定量测定 / Quantitating Drug Binding](https://www.drps.ed.ac.uk/26-27/dpt/cxbich11011.htm)

- **学分与学期：** 20 credits，Semester 1；单独选这一门即可满足 S1 的 exactly 20 credits。
- **官方名义学习量：** Total Hours **200** （讲授 8；研讨/辅导 15；监督实践/工作坊 16；总结性考核 6；项目级教学 4；定向/独立学习 151）。
- **官方考核：** Coursework 100%。ICA1 为 presentation，占 30%；ICA2 为 extended practical laboratory report，占 70%。没有中央正式笔试。
- **课程解释：** 从生物物理学角度理解药物与靶点的结合，学习常用亲和力和动力学测定方法，并通过实验获得和分析行业常用的结合参数，例如解离常数 `Kd`。方向更偏药物发现、实验生物物理与定量药理，而不是纯计算机或纯机器学习。
- **选课提示：** 20 学分且扩展实验报告占比高，适合愿意做实验、展示和长报告的学生；“无笔试”不代表工作量低。

### 历年试卷

官方试卷库对精确代码 `BICH11011` 的检索为 0 条，和课程页的 Coursework 100% 相符，因此没有可列出的正式笔试卷。

<a id="analysis-bich11011"></a>
### 考核结构与 LLM 难度

| 维度 | 评估 |
|---|---|
| 是否闭卷 | 无中央笔试；30% presentation + 70% extended practical laboratory report。 |
| 可预测性 | 产出类型很清楚，但没有历年卷可判断题目复用；70% 集中在一份长实验报告。 |
| 主要风险 | 需要定量生物物理、实验分析与长报告；20 学分和高权重实验报告使工作量集中。 |
| **LLM 难度**  | **3.5/5。** 需要定量生物物理、实验分析与长报告；20 学分和高权重实验报告使工作量集中。 |

<a id="course-infr11211"></a>
## [INFR11211 应用机器学习 / Applied Machine Learning](https://www.drps.ed.ac.uk/26-27/dpt/cxinfr11211.htm)

- **学分与学期：** 20 credits，Semester 1，School of Informatics 开设；与 `MATH11205` 最多选一门。
- **官方名义学习量：** Total Hours **200** （讲授 20；研讨/辅导 4；监督实践/工作坊 4；总结性考核 2；项目级教学 4；定向/独立学习 166）。Additional Class Delivery 另写约 30 小时（20 小时预录 + 10 次现场 Q&A），与结构化直接教学类别合计 28 小时的映射并未完全说明。
- **官方考核：** Written exam 60% + Coursework 40%；课程页列为 December main diet、120 分钟。官方课程考试说明称 2022 年起为 closed-book，2 小时，三题选二作答；无官方 solutions。
- **课程解释：** 覆盖监督学习、无监督学习、模型选择与评估等核心机器学习内容，既要求使用实际工具，也强调以统计和数学原则正确表述问题。相比 `MATH11205`，本课学分更高、理论和考试权重也更重。
- **先修与风险：** DPT 明确要求线性代数、基础微积分、统计和编程经验，并建议先联系 Programme Director。它一门就占满 S1 的 20 学分，且 60% 笔试使最终成绩更集中于考试表现。
- **官方补充：** [AML 公开课程主页](https://groups.inf.ed.ac.uk/teaching/aml/)、[考试说明与往年提示](https://groups.inf.ed.ac.uk/teaching/aml/exam/)、[官方 Exam Tips PDF](https://groups.inf.ed.ac.uk/teaching/aml/slides/W11_Exam.pdf)。旧 `IAML` 试卷只可能覆盖部分相近内容，不是 `INFR11211` 本课程试卷，故未混入下表。

<a id="papers-infr11211"></a>
### 历年试卷

共 4 条，4 份均可下载。

#### [2025/2026：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/b36a42f4-3d95-4d2c-b1e4-83131e407dbd/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/d1e637d8-2b21-4c53-a9b4-0a3e6e81cf6a)

#### [2024/2025：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/aee21aaf-106d-4b04-b5a8-d6b314913ebc/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/cfd90df8-1908-4df0-9694-ef1a9279f185)

#### [2023/2024：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/6d73bf04-e8e6-46ab-9b5b-5e979863c587/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/3c390c56-ed68-48fa-95e4-fe7166b622bd)

#### [2022/2023：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/eceb10e4-8cd0-406b-8e33-12d0ee969baa/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/765e0039-a487-4f94-b7ae-363300d43284)

<a id="analysis-infr11211"></a>
### 历年卷逐题核验、覆盖边界与难度评估

**直接结论：** 四份正式 `INFR11211` 试卷共有 24 个半题、300 个卷面 marks。没有发现任何一道题落在当前公开课程的主要教学模块之外，但“没有超纲”不等于“历年都一样”。`PCA`、聚类、评估、回归/树四个宽口径题族合计占 **190/300 marks（63.3%）** ；其余约三分之一会在 Naive Bayes、逻辑回归、神经网络、推荐系统、非线性降维、伦理、公平性、半监督与主动学习等模块间轮换。

这里有两个不同的“范围”，必须分开：

- **相对当前课程范围：** 四年题目都能在最新公开的 2025 lecture blocks 中找到对应模块，没有看到 SVM、Nearest Neighbours、Gaussian Mixture Models 等旧 `IAML` 内容混入。
- **相对此前历年卷范围：确实会超出。** 2023/24、2024/25 都加入了此前 `INFR11211` 卷没有出现过的整块内容；只背旧卷会漏分。在历年卷分析中，2025/26 的重复度最高，但不能据此保证下一年继续照搬。

截至 2026-08-14，学校公开的详细 AML 课程站仍是 2025 版。下面以[当前公开 Schedule](https://groups.inf.ed.ac.uk/teaching/aml/schedule/)中的 18 个 lecture blocks、4 个 tutorials、5 个 labs 为最新可核对范围；2026/27 开课后的 Learn 和当届材料仍具有最终优先级。

#### 24 个半题逐项核验

每套卷共有三道 25-mark 大题，考生任选两道；下表仍统计整套 75 marks，才能比较命题覆盖。

| 学年 | 题号 | 分值 | 实际考查内容 | 相对此前正式卷 |
|---|---|---:|---|---|
| 2022/23 | Q1(a) | 12 | 决策树与逻辑回归决策边界、参数、异常点影响、模型适用性比较 | 首份 `INFR11211` 卷，作为基线 |
| 2022/23 | Q1(b) | 13 | 线性/二次多项式回归的 SSE、SSE 局限、回归树训练与树集成 | 基线 |
| 2022/23 | Q2(a) | 13 | PCA 判断题、80% explained variance、elbow、主成分、投影方差、重构误差 | 基线；此后多次复用 |
| 2022/23 | Q2(b) | 12 | confusion matrix、accuracy、precision、recall、F-measure、类别不平衡、PR curve | 基线；此后多次复用 |
| 2022/23 | Q3(a) | 12 | K-means 与 single-link 几何性质、complete-link dendrogram、随机初始化选择 | 基线；此后多次复用 |
| 2022/23 | Q3(b) | 13 | Naive Bayes 假设/特征表示/局限、与神经网络比较、ART transparency、algorithmic fairness | 基线；伦理题此后未完整复现 |
| 2023/24 | Q1(a) | 12 | 回归树模型选择、impurity 与 information gain、叶节点值、类别特征及测试时缺失值 | 回归树来自 2022；impurity 数值和缺失值处理为新问法 |
| 2023/24 | Q1(b) | 13 | 树的区域预测、节点正确率、confusion matrix、四项指标、指标选择 | 评估模块重复；形成 2025 再次使用的模板 |
| 2023/24 | Q2(a) | 13 | 半监督学习、主动学习流程与 query methods、树集成、逻辑回归边界 | 半监督/主动学习约 9 marks 为此前未考模块 |
| 2023/24 | Q2(b) | 12 | 单位圆 PCA、PC/解释方差/无损表示、PCA 加 threshold classifier、80% 方差及数据集比较 | PCA 高频模块，但场景和推理任务更新 |
| 2023/24 | Q3(a) | 12 | 生成式与判别式、连续特征多分类 Naive Bayes、缺失值、逻辑回归 | Naive Bayes/逻辑回归重复，加入多分类和缺失值 |
| 2023/24 | Q3(b) | 13 | single-link dendrogram、构造区分 K-means/single-link 的数据、t-SNE 解释 | 聚类重复；t-SNE 3 marks 为新模块 |
| 2024/25 | Q1(a) | 12 | 线性回归、RBF basis expansion、回归假设、类别变量编码和权重解释 | 回归重复；RBF 和更完整的数据表示问题为新 |
| 2024/25 | Q1(b) | 13 | complete-link dendrogram、三簇切分、与 single-link 比较、构造 K-means 反例 | 与 2022/2023 聚类题高度重叠 |
| 2024/25 | Q2(a) | 12 | 全连接网络参数量与训练、CNN、数据收集偏差、视频/序列架构 | 神经网络只在 2022 简答出现过；本题大部分任务为新 |
| 2024/25 | Q2(b) | 13 | PCA 主成分/投影方差/重构误差；F1、TPR/FPR 与 ROC | PCA/评估重复；ROC 作图是新问法 |
| 2024/25 | Q3(a) | 13 | 推荐系统 matrix factorisation、loss、regularisation、latent structure、cold start | **整半题为此前未考模块**  |
| 2024/25 | Q3(b) | 12 | 单/双尾假设、t-statistic、显著性判断、Rand Index | **整半题为此前未考任务；Q3 合计 25 marks 全新**  |
| 2025/26 | Q1(a) | 12 | 回归树/分类树区别、impurity 公式与计算、过拟合、与线性回归比较、梯度下降可行性 | 回归树高频；impurity 的 4 marks 及模型比较可追溯到 2023，其他追问换角度 |
| 2025/26 | Q1(b) | 13 | 连续两次 PCA、目标与中心化、是否必然降维、PCA 分类边界、80% 方差与 elbow | **至少 10/13 marks 有清晰旧题模板**  |
| 2025/26 | Q2(a) | 13 | 逻辑回归模型/NLL/假设、决策边界、预测、权重缩放、多分类线性模型 | 高频基础模块；多分类的 3 marks 是新追问 |
| 2025/26 | Q2(b) | 12 | complete-link dendrogram、三簇切分、single-link 比较、Lance-Williams 系数 | **前 9/12 marks 近似复用 2024；最后 3 marks 新**  |
| 2025/26 | Q3(a) | 13 | 神经网络与树比较、画网络、激活函数、forward pass、accuracy、改参数提分 | 模块不新，但完整手算和参数修改模板此前未出现 |
| 2025/26 | Q3(b) | 12 | 医疗树区域、节点预测、confusion matrix、四项指标、降低 false negatives | **前 9/12 marks 近似复用 2023；最后 3 marks 新**  |

#### 当前课程模块与四年试卷的边界

| 当前公开教学模块 | 四年正式卷中的实际覆盖 | 四份卷尚未直接点名考查的明显部分 |
|---|---|---|
| Introduction to ML / Classification | 四年都有分类或模型比较场景 | LDA/QDA 的详细数值推导未直接出现 |
| Naive Bayes / Logistic Regression | NB：2022、2023；Logistic：2022、2023、2025 | softmax 的数值计算未直接出现；2025 只要求描述两种多分类方法 |
| Linear Regression / Decision Trees | 四年都有回归或树题；2022、2023、2025 直接考树 | 闭式最小二乘完整推导未出现 |
| Representing Data / EDA / PCA | PCA **4/4** ；特征类型、类别编码或缺失值在 2022-2024 出现 | 通用作图原则和多数 EDA 可视化没有独立题 |
| Optimisation / Generalisation | 树集成、模型训练、regularisation、overfitting、gradient descent 分散在四年题中 | 没有要求复杂梯度推导；bias-variance 与 cross-validation 没有完整独立计算题 |
| Evaluation / Model Selection | 基础分类指标 **4/4** ；正式 t-test 只在 2024 | MAE、correlation、`R²`、多分类评估和完整 cross-validation 流程未直接考 |
| Clustering / Non-linear DR | 聚类 **4/4** ；t-SNE 只在 2023 | Kernel PCA、MDS、Isomap、LLE、UMAP 均未直接出现在四份卷中 |
| Recommender Systems / Neural Networks | 推荐系统只在 2024；NN 在 2022、2024、2025 | Transformer 未直接考；RNN/序列模型只通过 2024 视频场景间接触及 |
| Ethics and Fairness / Further Topics | 伦理与公平 2022；半监督/主动学习 2023；2024 有数据收集偏差 | label propagation、entropy minimisation 等细项未被直接点名 |

因此，**没有发现“课程没讲却突然考一个外部算法”的证据** ；真正的风险是课件中的低频细项此前没出过，但仍可能第一次被抽中。过去没考过不等于不在范围，尤其是 `Kernel PCA / MDS / Isomap / LLE / UMAP`、regression metrics、cross-validation、Transformer 等。

#### 稳定题族到底占多少分

这里把连续四年都出现的四个宽口径题族定义为：`PCA`、`clustering`、`evaluation`、`regression/decision trees`。它们不等于原题，但代表最稳定的复习投资。

| 学年 | 四大稳定题族 / 75 | 占整卷 | 若选稳定题族最多的两道题，题族覆盖 / 50 |
|---|---:|---:|---:|
| 2022/23 | 53 | 70.7% | 41 |
| 2023/24 | 47 | 62.7% | 37 |
| 2024/25 | 41 | 54.7% | 38 |
| 2025/26 | 49 | 65.3% | 37 |
| **合计/平均**  | **190/300**  | **63.3%**  | **平均 38.25/50（76.5%）**  |

归类加总为：2022/23 的决策树 3 + Q1(b) 13 + Q2 25 + Q3(a) 12 = 53；2023/24 的 Q1 25 + Q2(b) 12 + Q3(b) 中聚类部分 10 = 47；2024/25 的 Q1 25 + Q2(b) 13 + Rand Index 3 = 41；2025/26 的 Q1 25 + Q2(b) 12 + Q3(b) 12 = 49。

这不是预计得分，而是**题族覆盖率** ：会这些模块不代表自动拿满对应分数。不过，三选二的结构确实允许先读卷再避开最陌生的一道。四年中，选择最熟悉的两题后，约 74%-82% 的可作答分值都来自四个稳定题族；这说明历年卷非常有用，也说明选题策略本身很重要。

#### 历年卷有没有被“超出”

| 新卷 | 相比此前正式 `INFR11211` 卷新增的明确内容 | 结论 |
|---|---|---|
| 2023/24 | 半监督/主动学习至少 9 marks；t-SNE 3 marks；另有缺失值等新问法 | 至少 12 marks 属于此前没出现过的具名模块/任务 |
| 2024/25 | 推荐系统 13 marks；假设检验与 Rand Index 12 marks；另有 RBF、CNN/视频、ROC | **Question 3 整道 25 marks 在此前两卷中没有对应模块**  |
| 2025/26 | 没有全新的大 lecture block，但新增 Lance-Williams、多分类、NN 手算与参数修改等追问 | 大模块最可预测的一年，细项仍没有完全照搬 |

最关键的反例是 2024/25：如果当时只按 2022/23 和 2023/24 两份卷划范围，整道 Q3 都会落在准备之外。好消息是可以不选 Q3；坏消息是 Q1、Q2 仍分别包含 RBF、CNN/视频、ROC 等新细项，所以没有一组“两道题全部是旧模板”的绝对安全组合。

#### 接近原题复现的部分

| 年份组合 | 重复内容 | 程度 |
|---|---|---|
| 2022/23 与 2025/26 | 分步 PCA 是否等于直接降维、PCA 是否必然降维、按 80% 解释方差选主成分并比较 elbow | **很强** ：再加上 2023 的 PCA 分类模板，2025 Q1(b) 至少 10/13 marks 可追溯到旧题 |
| 2022/23 与 2024/25 | 求第一主成分、投影方差与重构误差 | **强** ：同一计算模板，数据点不同 |
| 2023/24 与 2025/26 | 医疗场景中的树分类区域、节点预测、confusion matrix、accuracy/precision/recall/F-measure | **很强** ：2025 Q3(b) 前 9/12 marks 沿用结构，最后一问改变 |
| 2024/25 与 2025/26 | 距离矩阵、complete-linkage dendrogram、切成三个簇、与 single linkage 比较 | **很强** ：2025 Q2(b) 前 9/12 marks 沿用模板，矩阵和最后一问改变 |
| 2023/24 与 2024/25 | 构造能区分 K-means 与 single-linkage 行为的二维数据 | **强** ：目标相同，2023 的版本更全面 |
| 2023/24 与 2025/26 | 回归树节点 impurity 的定义与数值计算 | **中强** ：核心方法相同，数据和附加概念题不同 |

按较严格的“题面结构近似复用”口径，仅 2025/26 的 PCA、聚类、评估三个半题中，就有至少 **28 marks**  能对应到旧题模板。它确实产生了接近“划到重点”的复习优势，但仍没有整道大题逐字逐数复制，也不是泄题。

#### 官方范围声明与实际命题的关系

- [官方 Course Information](https://groups.inf.ed.ac.uk/teaching/aml/about/)说 lecture slides、tutorial questions 和 labs 共同定义考试范围；这句话只是上限，不代表各模块概率相同。
- 四年实际数据表明概率明显不均：PCA、聚类、评估、回归/树是高频骨架；推荐系统、非线性降维、伦理、半监督/主动学习更像轮换模块。
- 旧 `IAML` 卷中的 Nearest Neighbours、SVM、Gaussian Mixture Models 不属于当前 AML；四份 `INFR11211` 正式卷也没有考这些内容。
- 2025 官方 Exam Tips 不提供未来考点或答案，但明确不要求复杂推导、不写代码、计算量通常低于 tutorial；展示中间步骤有利于获得部分分。

#### 难度与高分可能性

| 维度 | 评估 | 原因 |
|---|---|---|
| 题型可预测性 | **较高，但不是全覆盖**  | 四大题族约占整卷 63%；2025 有多组近似旧题，2024 又证明会加入整块新内容 |
| 数学推导难度 | 中低 | 主要是公式、短计算、画图和解释；官方明确不强调复杂推导 |
| 知识面 | 中高 | 低频模块会轮换，课件中仍有多个四年未直接考的子主题 |
| 时间压力 | 中等偏上 | 120 分钟完成两道 25-mark 大题，每题有多个 1-5 分小问 |
| 闭卷记忆压力 | 中高 | 不允许笔记或计算器，需要熟悉定义、公式和比较框架 |
| 过程分友好度 | 较高 | 小问拆分细，官方明确建议展示 working 以便给部分分 |

**对试卷本身的定性分析：中等偏上。**  对已有线性代数、概率统计和基础 ML 的学生，大约是 `3/5`；第一次系统学习机器学习时，闭卷广度更接近 `4/5`。从原卷本身可以支持的结论是：**选题自由、稳定题族和部分重复模板让它具有较强的可准备性，2025/26 尤其明显。** 但没有公开 marking scheme、分数分布或可靠的当前学生样本，因此不能把“题型重复”进一步推断成“老师给分宽松”或“稳拿高分”。

#### LLM 难度评估

**4.0/5。** 覆盖较广，20 学分且 60% 闭卷；旧题有助复习，但不能替代完整课程范围。
<a id="course-math11205"></a>
## [MATH11205 Python 机器学习 / Machine Learning in Python](https://www.drps.ed.ac.uk/26-27/dpt/cxmath11205.htm)

- **学分与学期：** 10 credits，Semester 1；与 `INFR11211` 最多选一门，因此若选本课，还需从其余 10 学分 S1 课程中再选一门。
- **官方名义学习量：** Total Hours **100** （讲授 14；监督实践/工作坊 15；总结性考核 1.5；项目级教学 2；定向/独立学习 67）。这些分项只合计 99.5 小时，官方页未解释与总数的 0.5 小时差异。
- **官方考核：** Written exam 50% + Coursework 50%。Coursework 由 applied machine-learning project 与 weekly workshop assignments 构成。2026/27 课程页同时显示 “No Exam Information”，这通常表示当年具体考试安排尚未发布，并不推翻页面给出的 50% written exam。
- **课程解释：** 以 Python 实践机器学习流程，并配合必要理论；重点是把模型用于实际数据、理解训练和评估，而不只是调用库函数。
- **先修与风险：** 需要 Python、概率与统计基础；DPT 还要求机器学习选课者具备线性代数、基础微积分、统计和编程经验。50/50 的结构比 AML 更均衡，但持续性 workshop 作业意味着平时负担更分散。

<a id="papers-math11205"></a>

### 历年试卷

共 10 条：6 份 PDF，4 条 Paper Unavailable；Main 与 Resit 分开列示。

#### [2025/2026 Main：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/8813d318-3d69-4a8f-a8c5-334ae2db7f0a)

- 校方保留了元数据，但没有提供可下载 PDF。

#### [2024/2025 Main：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/676299f6-cd54-41ec-a7fe-fedf9c83986f/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/ed35f15b-f221-407c-bf25-a3c4d1a9f97c)

#### [2024/2025 Resit：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/d2bd1f0e-b36b-45fe-b059-d524eebba97a)

- 校方保留了元数据，但没有提供可下载 PDF。

#### [2023/2024 Main：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/08e229b5-9a4f-418c-8aa7-3043a5de6473/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/3a68791a-6f08-4320-a9ec-e7db6f2bddac)

#### [2023/2024 Resit：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/2189f49e-cc2d-4c9a-b904-a9cf19caa535)

- 校方保留了元数据，但没有提供可下载 PDF。

#### [2022/2023 Main：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/2025da29-0a93-44de-8320-4a5357574f5e/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/7c085717-d7c6-487c-bf03-68f277a11752)

#### [2022/2023 Resit：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/a19253f0-4d7f-4449-9913-83f73fba6c5e)

- 校方保留了元数据，但没有提供可下载 PDF。

#### [2021/2022 Main：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/f569e45f-8a63-45a2-a818-b769223a89b1/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/faddafa6-4866-4ccb-b8dd-c21e8c9a6159)

#### [2020/2021 Main：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/fac81fab-0f22-4b79-ae96-5ce08b012637/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/eb2b9dc8-1a2d-4d5d-b27c-4b8a9bea9c5f)

#### [2019/2020 Main：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/76e65955-d56f-48f3-b4df-36c843ede5cf/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/cf7a50a7-e2e4-4716-83f2-7c0157c032d9)

<a id="analysis-math11205"></a>
### 历年规律、当前风险与 LLM 难度

| 维度 | 六份可读卷的结果 |
|---|---|
| 高频考点 | 回归/正则化 **6/6** ，模型评估与交叉验证 **6/6** ，预处理/编码 **5/6** ，神经网络 **4/6** ，决策树 **3/6** ；聚类、SVM/kernel、PCA 各 **2/6** 。 |
| 重复程度 | 方法族重复高，但未发现整份卷或整道大题逐字复刻；数据、计算和比较对象都会变化。可预测的是回归、评估、预处理，不是具体答案。 |
| 作答规则 | 六份卷都要求所有题目作答。2019/20-2021/22 为远程/特殊安排；2022/23-2024/25 明确允许 **3 张 A4 双面笔记（6 面）+ 科学计算器** ，2024/25 时长为 90 分钟。 |
| 当前边界 | 2026/27 页仍写 50% written exam + 50% coursework，但未公布当届开闭卷/笔记规则；旧卷中的 SVM、神经网络等内容也不能自动视为当届 syllabus。 |
| 入课限制 | 课程页列出 `MATH08065 Computing and Numerics` 先修要求；Bioinformatics DPT 只说可在与 Programme Director 讨论基础后选，**不能把 DPT 出现课程等同于已自动豁免先修** 。 |
| **LLM 难度**  | **4.5/5。** 难度高，不建议选修。不能把它当成轻松的 Python 工具课：数学理解、编程、每周作业与项目并行；笔试占 50%。 |

<a id="course-pgbi11051"></a>
## [PGBI11051 生物细胞中的信息处理 / Information Processing in Biological Cells](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11051.htm)

- **学分与学期：** 10 credits，Semester 1。
- **官方名义学习量：** Total Hours **100** （讲授 20；总结性考核 3；项目级教学 2；定向/独立学习 75）。官方未把 3 小时总结性考核进一步拆成 2 小时考试与其他组件。
- **官方考核：** Written exam 50% + Coursework 50%；课程页列为 December main diet、120 分钟。平时考核由两次 in-course assessments 构成，题型可包含问题求解、讨论和短答。
- **课程解释：** 用信息处理、数学和计算建模视角理解细胞如何感知信号、储存信息、作出响应并适应环境。内容连接细胞生物学、系统生物学和定量模型，理论抽象度通常高于普通湿实验课程。
- **学习提示：** 适合希望理解生命系统建模和 AI4Science 基础思想的学生，但它不是通用 AI/ML 课程。可先看官方的[课程介绍视频](https://media.ed.ac.uk/media/Information+Processing+in+Biological+Cells/1_aumuua7w)。

<a id="papers-pgbi11051"></a>

### 历年试卷

共 19 条：2 份 PDF，17 条 Paper Unavailable。2008/09 至 2009/10 的记录通过精确课程名与旧代码补查，其中涉及旧代码 `P02377`，另有一条 VS1 记录 `P02988`。

#### [2025/2026：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/85e50144-5dca-4b94-a5eb-2808ce782d18)

- 校方保留了元数据，但没有提供可下载 PDF。

#### [2024/2025：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/4b2e6565-544a-4c61-a544-be08d1b3777b)

- 校方保留了元数据，但没有提供可下载 PDF。

#### [2023/2024：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/76fe2ee2-bdb3-48eb-87f6-69c3cf1acd63)

- 校方保留了元数据，但没有提供可下载 PDF。

#### [2022/2023：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/ba3d7ea7-bcff-4890-bec2-096d21955542)

- 校方保留了元数据，但没有提供可下载 PDF。

#### [2021/2022：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/6b78f529-5d0a-456a-b361-bc751efdb128)

- 校方保留了元数据，但没有提供可下载 PDF。

#### [2020/2021：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/77a2038a-ab57-4fb8-8e34-23ecb7f6a3f3)

- 校方保留了元数据，但没有提供可下载 PDF。

#### [2019/2020：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/abaf902f-a4a8-4504-a11c-d88a79e4b532)

- 校方保留了元数据，但没有提供可下载 PDF。

#### [2018/2019：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/019775d3-5b5c-4e1e-a4df-798b27bb15dd)

- 校方保留了元数据，但没有提供可下载 PDF。

#### [2017/2018：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/bd86fbf7-7aaf-4d53-952d-546e360f87cb)

- 校方保留了元数据，但没有提供可下载 PDF。

#### [2016/2017：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/5241db28-a760-468e-8c0b-472b59791c1c)

- 校方保留了元数据，但没有提供可下载 PDF。

#### [2015/2016：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/d9ea65d8-b0c8-453b-bdc6-f6e1deea3c56)

- 校方保留了元数据，但没有提供可下载 PDF。

#### [2014/2015：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/5afd6964-0b5b-4ae1-9a3e-1cf5ab0ee7a8/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/befaf30e-6c76-4a7e-9839-d7384454efcf)

#### [2013/2014：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/d69654a1-f1d4-4883-aeab-25948a067eb6)

- 校方保留了元数据，但没有提供可下载 PDF。

#### [2012/2013：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/3276faea-df87-4be5-8aaa-5fac22f65af4)

- 校方保留了元数据，但没有提供可下载 PDF。

#### [2011/2012：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/1adacef8-8787-41c6-a069-a59cfc4ab88f/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/59a727e6-816a-4735-b89d-a32441c92011)

#### [2010/2011：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/2decf5b9-0ac9-45e5-8c2f-cfc43e180f6e)

- 校方保留了元数据，但没有提供可下载 PDF。

#### [2009/2010：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/f5f55b3e-9d09-42b6-84dd-8457af302a41)

- 校方保留了元数据，但没有提供可下载 PDF。

#### [2008/2009：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/6ed031f1-390e-423d-9a61-ff9a728b6551)

- 校方保留了元数据，但没有提供可下载 PDF。

#### [2008/2009 VS1：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/5875a21c-9589-441f-ace0-7c03aa1b4bdf)

- 校方保留了元数据，但没有提供可下载 PDF。

<a id="analysis-pgbi11051"></a>
### 历年规律、当前风险与 LLM 难度

| 维度 | 两份可读旧卷的结果 |
|---|---|
| 2011/12 | 扩散与分子马达、Src/变构和正反馈、operon/转录因子/表观遗传。 |
| 2014/15 | 膜运输与稳态、化学计量矩阵/质量作用、quorum sensing 与稳定性反馈。 |
| 重复程度 | **低。** 两份卷都考“定量理解细胞信息处理”，但具体系统和数学工具变化明显，没有可确认的原题复用。 |
| 作答规则 | 两份旧卷均为 3 小时、三道大题全部作答，只准 non-programmable calculator。当前页写 120 分钟，因此旧格式已不能直接外推。 |
| 证据缺口 | 19 条档案只有 2 份 PDF，其余 17 条 unavailable；这是本版覆盖的有笔试选修中历史资料不确定性较高的一门。 |
| **LLM 难度**  | **4.5/5。** 细胞机制与定量建模交叉，抽象推理要求高，近期可读旧卷不足；不建议作为减负选项。 |

<a id="course-pgbi11122"></a>
## [PGBI11122 使用 R 进行数据科学 / Using R for Data Science](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11122.htm)

- **学分与学期：** 10 credits，Semester 1。
- **官方名义学习量：** Total Hours **100** （讲授 30；项目级教学 2；定向/独立学习 68）。页面没有单列总结性考核小时，不能据此视为 0 小时。
- **官方考核：** Written exam 50% + Coursework 50%；课程页列为 December main diet、120 分钟。Coursework 是 R data-analysis task；笔试共三题，第一题必答，第二、三题中选一题。
- **课程解释：** 用 R 处理复杂生物数据，重点可涉及统计分析、可视化、regulatory genomics 与机器学习方法。它比通用 R 入门更贴近生物数据情境。
- **学习提示：** 适合希望建立 R/Bioconductor 数据分析能力的学生。虽然只有 10 学分，但考试和 coursework 各占一半，不能按“软件操作课”理解为轻松课。

<a id="papers-pgbi11122"></a>
### 历年试卷

共 5 条，5 份均可下载。

#### [2025/2026：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/dc9b4717-f24c-4cae-b557-02ff8cd2759d/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/06e41d8b-eed7-4b78-bc06-2ae444b6a344)

#### [2024/2025：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/16e2a4eb-5b3e-4730-93cb-4e26629da56a/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/0d85e145-2fa9-4b6f-94f8-46e67d481d60)

#### [2023/2024：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/7531f742-1bf5-475d-9384-d776d8a8ebd1/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/415e8751-c1cb-41a8-9306-109d9c23b934)

#### [2022/2023：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/594a8edd-4a17-448f-a0a6-b9df33420cee/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/80dface5-6cd6-4d26-9689-70a0107c9ba0)

#### [2021/2022：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/21d7bdba-a320-4573-9438-7ccf931985c1/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/9a75bc90-b64e-4a2f-a6ae-dfbe9f604053)

<a id="analysis-pgbi11122"></a>
### 历年规律、当前风险与 LLM 难度

| 维度 | 五份可读卷的结果 |
|---|---|
| 高频考点 | R 语言语义、分析 workflow/可复现性、数据对象与 wrangling、错误/包/环境均为 **5/5** ；Shiny 为 **3/5** 。 |
| 明显复用 | “R 是 dynamically typed / functional / interpreted”在 2022/23、2023/24、2025/26 接近重复；fail-well errors 在 2021/22 与 2024/25 重现；Git、data frame/tibble、R Markdown/Snakemake/pipeline 持续出现。 |
| 作答规则 | 第一题必答，第二、三题选一。2022/23 为 open-book；2023/24 起是现场 2 小时卷，卷面没有授权携带笔记。 |
| 可准备性 | **高。** 不是整卷照抄，但核心概念和短答模板非常稳定；把常见概念写成准确、短小的英文答案有明显收益。 |
| **LLM 难度**  | **2.5/5。** 有 R 基础时相对易准备；语言语义、数据处理和可复现流程仍需准确理解，另有 50% 笔试。 |

<a id="course-pgbi11129"></a>
## [PGBI11129 生物数据库 / Biological Databases](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11129.htm)

- **学分与学期：** 10 credits，Semester 1。
- **官方名义学习量：** Total Hours **100** （讲授 10；监督实践/工作坊 20；项目级教学 2；定向/独立学习 68）。页面没有单列总结性考核小时，不能据此视为 0 小时。
- **官方考核：** Written exam 50% + Coursework 50%；课程页列为 December main diet、120 分钟。Coursework 要求使用 R/Python 脚本构建小型、整合式 biological database。
- **课程解释：** 学习数据库设计、查询、数据检索与生物数据库整合，并把脚本能力用于实际生命科学数据。它既不是单纯背诵公共数据库，也不是完整的计算机数据库系统课。
- **学习提示：** 对希望发展数据工程、bioinformatics pipeline、数据库与后端能力的学生较实用；需要同时处理概念理解与动手构建。

<a id="papers-pgbi11129"></a>

### 历年试卷

共 4 条，4 份均可下载。精确标题搜索还出现了 2004/05 的 `Bioinformatics 2 (P00861)`，但代码和课程名都不同，已作为误匹配排除。

#### [2025/2026：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/fc3c299b-29eb-4322-993f-777347aeee59/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/c4f02456-dbc1-4b18-a163-8687867d7797)

#### [2024/2025：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/f05dd3eb-b935-4ba5-8850-b9b4d8e8fcbb/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/0f8d09bb-1a90-4d44-827d-1c7b9cc957df)

#### [2023/2024：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/d1d5ffdd-f825-48ae-9ac6-1a81f5397c6b/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/88fc4ad0-b8e8-4b64-a044-e850671d1339)

#### [2022/2023：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/1b25ced1-d41b-45e7-8684-7bab392d1e87/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/af6ed110-864f-4fa1-9ed3-96e1491c8dc3)

<a id="analysis-pgbi11129"></a>
### 历年规律、当前风险与 LLM 难度

| 维度 | 四份可读卷的结果 |
|---|---|
| 高频考点 | 数据库模型/设计、API/web services、semantic web/ontology、生物数据库使用均为 **4/4** ；XML/JSON 为 **3/4** 。 |
| 明显复用 | flat-file vs relational 与 REST/JSON/XML 在 2022/23、2024/25 的问法高度相似；Ensembl/BioMart/GO 在 2023/24-2025/26 连续出现。 |
| 作答规则 | 第一题必答，第二、三题选一。2022/23 为 open-book；2023/24 起为现场 2 小时，卷面未授权笔记。 |
| 可准备性 | **高。** 核心名词、数据库比较、API 和公共生物数据库案例稳定；但 50% coursework 还要求真正用 R/Python 构建小型整合数据库。 |
| **LLM 难度**  | **3.0/5。** 兼顾数据库概念、API、生物数据库与脚本整合；旧题较稳定，但作业需要实际构建。 |

---

<a id="semester-2-electives"></a>

# Semester 2 选修课

<a id="course-bilg11004"></a>
## [BILG11004 新一代基因组学 / Next Generation Genomics](https://www.drps.ed.ac.uk/26-27/dpt/cxbilg11004.htm)

- **学分与学期：** 10 credits，Semester 2；DPT 强烈推荐。
- **官方名义学习量：** Total Hours **100** （讲授 30；总结性考核 3；项目级教学 2；定向/独立学习 65）。课程描述提到 hands-on practicals，但结构化字段未单列监督实践小时。
- **官方考核：** Written exam 50% + Coursework 50%；课程页列为 April/May main diet、120 分钟。Coursework 为 genome-quality assessment essay，占 50%；其余 50% 为 essay-style written exam。
- **课程解释：** 涵盖第二、第三代测序技术、相关生物信息学算法、组装和质量控制，并强调非模式生物基因组数据的解释。它把测序原理、数据质量和分析决策连在一起。
- **学习提示：** 这是 MSc Bioinformatics 的核心方向课之一。适合希望走 genomics、NGS、组装或序列数据分析方向的学生，但 essay 型考试仍要求概念组织和书面论证。

<a id="papers-bilg11004"></a>
### 历年试卷

共 16 条：**11 份有效 PDF，5 条 Paper Unavailable** 。正文内容复核发现，之前列作 2020/21 的 bitstream 实际是 `PGBI11057 Bioinformatics Algorithms` 2011/12 试卷，因此已剔除，不能用“链接能打开”代替课程代码与卷首标题核验。

#### [2025/2026：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/27a79495-46d2-4c38-b908-5b184fb098d6/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/9744c93d-a9bd-4e58-8dc0-eb6f506665a1)

#### [2024/2025：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/17bed6bc-4a88-4022-92c7-f5caaa3fbf7c/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/ed97e87a-1596-4532-9d04-282cd9794682)

#### [2023/2024：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/889c0a7e-cc70-4e43-a64c-b2651546c1fe/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/b83e6226-ab8c-4bd5-ad27-7618f8a364ed)

#### [2022/2023：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/32a67a7b-a1d7-4439-ba5c-8a9f565f1fb6/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/e9c67551-208f-413b-a3ee-2c3c984f3fd1)

#### [2021/2022：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/90af23e9-419d-4b3b-baed-b261d6098d2b/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/fce4f2a0-c7b5-4635-afd2-8d2ca0fe1180)

#### [2020/2021：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/3c97d19d-c93d-4a23-a114-3db7bda4c83b)

- 当前条目没有 `BILG11004` PDF；曾关联到该条目的旧 bitstream 实际打开的是另一门课 2011/12 试卷，已排除。

#### [2019/2020：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/83dccd63-e6fd-40dc-a7b7-f88b43f86113)

- 校方保留了元数据，但没有提供可下载 PDF。

#### [2018/2019：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/40df4a68-b6f2-4b12-94ca-fe04b166aa8c/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/62dd5139-d98e-40fd-9469-fdce3b8e1604)

#### [2017/2018：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/642579dc-ca62-4d36-bbbf-566d45b21fb9)

- 校方保留了元数据，但没有提供可下载 PDF。

#### [2016/2017：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/fdc0dd17-b12c-45c8-a644-7bf4c4c53e4b)

- 校方保留了元数据，但没有提供可下载 PDF。

#### [2015/2016：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/6518ce78-9c15-4882-ad0e-fffea628377e)

- 校方保留了元数据，但没有提供可下载 PDF。

#### [2014/2015：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/ebe88fe2-365e-48a4-89e6-8735efb244b8/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/96515d99-3a99-46bc-b647-d6f975eeda20)

#### [2013/2014：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/a124a96b-9683-4984-91c6-efb4ab441a56/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/cf924b2c-72a4-44b0-91c2-c7045e406769)

#### [2012/2013：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/b5d58054-44fe-446f-9f9d-7c100c08c9d8/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/8a71ece9-5a6a-4f5f-868d-0403882c6c60)

#### [2011/2012：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/fbe1a2b4-1d36-48e0-b116-f677617cc905/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/6b6dc088-5431-439d-a7cd-557f62409b25)

#### [2010/2011：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/6f1eadac-2b3c-4c16-ad5e-6acfe4ab71b2/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/9abe1ee9-a7fe-4e0e-9679-1f625b1daa4f)

<a id="analysis-bilg11004"></a>
### 历年规律、当前风险与 LLM 难度

| 维度 | 11 份有效卷的结果 |
|---|---|
| 高频考点 | 基因组组装/graph/k-mer **10/11** ，测序质量与 QC **10/11** ，变异/群体基因组 **5/11** ，read mapping **4/11** ，转录组 **4/11** 。 |
| 近年结构 | 2021/22 为 open-book；2022/23 起为现场 2 小时、三题选二。近年稳定围绕测序策略、组装、QC 和 population genomics 组织大题。 |
| 重复程度 | **题族重复高，逐字原题复用低。** de Bruijn graph/k-mer、assembly quality、平台选择与群体变异反复出现，但物种、数据和论证场景会换。 |
| 可准备性 | 高。用固定框架准备“平台选择 → reads/QC → assembly → evaluation → biological interpretation”很有效，但 essay 型答案仍需针对场景论证。 |
| **LLM 难度**  | **3.0/5。** 测序、组装、QC 和群体基因组概念较多，essay 考试要求组织论证；生物基础薄弱者需补课。 |

<a id="course-bilg11016"></a>
## [BILG11016 网站与数据库设计导论 / Introduction to website and database design](https://www.drps.ed.ac.uk/26-27/dpt/cxbilg11016.htm)

- **学分与学期：** 10 credits，Semester 2。
- **官方名义学习量：** Total Hours **100** （讲授 20；项目级教学 2；定向/独立学习 78）。Additional Class Delivery 把每周 2 小时写作 lecture/workshop，但结构化字段全部归在 Lecture Hours。
- **官方考核：** Coursework 100%。Critical essay on databases 占 50%；面向公众的 MySQL database website 项目占 50%。没有中央正式笔试。
- **课程解释：** 学习从生物数据中提取信息、设计关系数据库、使用 MySQL，并将数据库通过网页界面提供给用户。它偏应用型数据库与网站构建，目标用户情境是生物学家或公众，而不是纯前端设计。
- **学习提示：** 适合希望积累数据库、Web 和可展示项目经验的学生。考核虽无笔试，但两个 50% 产出分别要求批判性写作和完整可用的网站。

### 历年试卷

官方试卷库对精确代码 `BILG11016` 的检索为 0 条，和 Coursework 100% 相符，因此没有正式笔试卷。

<a id="analysis-bilg11016"></a>
### 考核结构与 LLM 难度

| 维度 | 评估 |
|---|---|
| 是否闭卷 | 无；critical database essay 50% + MySQL database website 50%。 |
| 可预测性 | 交付物和比例明确，没有旧卷；难度取决于数据库 schema、SQL、后端/网页整合与英文批判性写作。 |
| 主要风险 | coursework 不是“做出能跑的页面”就结束，50% essay 需要分析数据库设计与局限；项目调试可能耗时。 |
| **LLM 难度**  | **3.0/5。** 无中央笔试，但 SQL、关系建模、网站实现与批判性论文都需要投入；调试成本不可忽略。 |

<a id="course-bite11004"></a>
## [BITE11004 宏基因组学 / Metagenomics](https://www.drps.ed.ac.uk/26-27/dpt/cxbite11004.htm)

- **学分与学期：** 10 credits，Semester 2；DPT 说明本课不能以 “Class Only” 方式修读。
- **官方名义学习量：** Total Hours **100** （讲授 33；项目级教学 2；定向/独立学习 65）。Summary 明确包含 field excursion、采样和实验训练，但结构化字段未单列野外或监督实验小时。
- **官方考核：** Coursework 100%。Report 1（summary and methods）占 30%；Contract Research Report 占 70%。没有中央正式笔试。
- **课程解释：** 覆盖环境样本采集与实验设计、DNA 提取和扩增、NGS/qPCR，以及宏基因组数据分析 pipeline。课程把湿实验、测序和计算分析串联起来，最终以合同研究式报告呈现。
- **学习提示：** 适合 microbiome、environmental genomics 和宏基因组研究方向。70% 集中在一份大型报告，属于无笔试但高权重写作型课程。

### 历年试卷

官方试卷库对精确代码 `BITE11004` 的检索为 0 条，和 Coursework 100% 相符。按标题 “Metagenomics” 搜索会出现其他代码或其他项目的同名内容，均未混入。

<a id="analysis-bite11004"></a>
### 考核结构与 LLM 难度

| 维度 | 评估 |
|---|---|
| 是否闭卷 | 无；Report 1 30% + Contract Research Report 70%。 |
| 可预测性 | 两份报告的形式稳定，但没有公开旧作业，不能判断数据质量、实验排期或评分尺度。 |
| 主要风险 | 70% 集中在最终报告，湿实验/样本数据和团队实验流程可能造成不可控延迟；英文科研写作质量决定上限。 |
| **LLM 难度**  | **3.0/5。** 实验流程、数据分析与科研报告跨多个环节；无中央笔试不代表轻松，最终报告权重大。 |

<a id="course-cmse11576"></a>

## [CMSE11576 技术创业与商业化 / Technology Entrepreneurship and Commercialisation](https://www.drps.ed.ac.uk/26-27/dpt/cxcmse11576.htm)

- **学分与学期：** 10 credits，Semester 2。
- **官方名义学习量：** Total Hours **100** （讲授 10；研讨/辅导 3；项目级教学 2；定向/独立学习 85）。
- **官方考核：** Coursework 100%。Individual coursework 占 30%；group presentation 占 70%。没有中央正式笔试。
- **课程解释：** 围绕可扩展技术创业，学习识别机会、商业模式、客户与市场验证、知识产权和 venture creation。它不是生物信息算法课，更适合希望理解科研转化、创业或产品商业化的学生。
- **学习提示：** 70% 为小组展示，成绩会较多依赖团队协作和商业表达。选课时应把这一点与“没有闭卷考试”一起考虑。

### 历年试卷

官方试卷库对精确代码 `CMSE11576` 的检索为 0 条。未加引号搜索时曾命中代码 `CMSE11108` 的 Financial Analysis，属于搜索引擎误匹配，已排除。

<a id="analysis-cmse11576"></a>
### 考核结构与 LLM 难度

| 维度 | 评估 |
|---|---|
| 是否闭卷 | 无；个人 coursework 30% + group presentation 70%。 |
| 可预测性 | 形式明确但题目与团队每年变化；没有中央旧卷，也没有可靠课程级学生评价。 |
| 主要风险 | 技术门槛相对有限，但商业论证、英语展示和团队协作共同影响成绩，70% 小组考核风险较集中。 |
| **LLM 难度**  | **3.0/5。** 技术门槛相对有限，但商业论证、英语展示和团队协作共同影响成绩，70% 小组考核风险较集中。 |

<a id="course-epcc11017"></a>
## [EPCC11017 编程技能 / Programming Skills](https://www.drps.ed.ac.uk/26-27/dpt/cxepcc11017.htm)

- **学分与学期：** 10 credits。课程页说明每年可开两次，但 Bioinformatics DPT 明确要求本项目学生在 **Semester 2**  修读，选课时以 DPT 为准。
- **官方名义学习量：** Semester 2 实例 Total Hours **100** （讲授 9；监督实践/工作坊 18；项目级教学 2；定向/独立学习 71）。S1 实例另把 1 小时列为 Feedback/Feedforward，因此本文不混用两套分项。
- **官方考核：** Coursework 100%，实践型课程；当前课程页没有列出更细的固定百分比分拆，也没有中央正式笔试。因此不能把旧表中的任何进一步比例当作官方事实。
- **课程解释：** 训练如何写出可读、可维护、正确且高效的科研代码，内容包括 Linux/Unix、测试、版本控制、性能分析和 HPC 思维。它不是从零开始的 Programming 101，而是把已有编程经验提升为可靠的软件实践。
- **学习提示：** 对科研编程、可复现分析和未来做计算项目都很实用；若编程基础极弱，应提前补齐基础语法和命令行，而不是只依赖课堂。

### 历年试卷

官方试卷库对精确代码 `EPCC11017` 的检索为 0 条，和 Coursework 100% 相符。按标题 “Programming Skills” 搜索会出现大量其他专业课程，均不是本课。

<a id="analysis-epcc11017"></a>
### 考核结构与 LLM 难度

| 维度 | 评估 |
|---|---|
| 是否闭卷 | 无中央正式笔试；实践型 Coursework 100%，官网未公布固定细分比例。 |
| 入课基础 | 课程期待学生已经写过超过约 100 行的程序，并建议熟悉至少一种语言及 bash/Unix；它不是从零入门。 |
| 主要风险 | 软件工程习惯、测试、版本控制、性能与可维护性会被评价；会写分析脚本不等于自动能拿高分，持续实践也可能耗时。 |
| **LLM 难度**  | **3.0/5。** 适合已有编程基础者；测试、版本控制、性能和代码质量比会写脚本要求更高，不是零基础入门。 |

<a id="course-pgbi11040"></a>
## [PGBI11040 功能基因组技术 / Functional Genomic Technologies](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11040.htm)

- **学分与学期：** 10 credits，Semester 2；DPT 强烈推荐。
- **官方名义学习量：** Total Hours **100** （讲授 20；监督实践/工作坊 10；总结性考核 2；项目级教学 2；定向/独立学习 66）。
- **官方考核：** Written exam 50% + Assignments 50%；课程页列为 April/May main diet、120 分钟。
- **课程解释：** 覆盖 microarray、RNA-seq、ChIP-seq、SNP/aCGH、proteomics 等高通量功能基因组技术，并使用 R/Bioconductor 与 Unix 工具完成数据分析和解释。重点不只在技术原理，也在选择合适方法和判断数据质量。
- **学习提示：** 与 `BILG11004`、`PGBI11057` 一起构成很典型的 genomics + bioinformatics 组合。50% assignments 能展示实操能力，但仍有 50% 笔试。

<a id="papers-pgbi11040"></a>
### 历年试卷

共 19 条：17 份 PDF，2 条 Paper Unavailable。2007/08 至 2009/10 的早期记录使用旧代码 `P02551`，通过精确课程名补查后纳入。

#### [2025/2026：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/03d71423-7ee8-40e6-9ffd-071b6193b0ee/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/b8d47008-d6c4-4a25-8222-a51b6d0aaa0e)

#### [2024/2025：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/d6ffc5f4-dfcf-48b6-8198-292f0826e649/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/0364efbd-ea37-4e91-85bb-e6e0e500fb20)

#### [2023/2024：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/b17fb861-26dc-4c14-9d85-dad617dc7ecf/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/d7ca2ed3-7b10-4b45-8adf-1c9fd88fead1)

#### [2022/2023：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/75d299ac-21b7-4cdc-a06d-dc8d943a707e/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/b45e01ad-b9af-4cbd-81ef-a26c78128cab)

#### [2021/2022：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/493f3827-6be9-40cd-bcb2-fbe75e4d8838/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/3b5970ae-9e1d-48ce-a7f6-263a1638c895)

#### [2020/2021：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/cace234f-fbca-4b9a-81a0-c6a8870ce62d/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/be5bd4d3-a4ef-41ad-8039-9b2d9834033b)

#### [2019/2020：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/e12fd68f-2a70-4b42-97bf-762d8906c43f)

- 校方保留了元数据，但没有提供可下载 PDF。

#### [2018/2019：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/cf6d55e1-f17a-45dc-bb8b-dd31e9664948/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/901caa61-1d58-43c3-9e5d-bef10f1d8edf)

#### [2017/2018：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/a981dcf3-9807-4123-abec-945f88888bea/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/c587ceef-173d-4b41-8fc6-a3689c3190b3)

#### [2016/2017：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/df8125e4-05c4-470b-bb29-3296af070caa/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/640fe2cf-8941-4411-999a-f75e33b4d372)

#### [2015/2016：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/f61867a7-5c83-4f70-8005-ed227423b436/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/ff4e5af3-414c-4d98-8293-8aaa29feffaa)

#### [2014/2015：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/5d584ba9-ec07-49da-bf04-ba8745a374de/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/c12ee319-7110-43e1-9970-61f37f4bebd5)

#### [2013/2014：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/58efde0b-597e-4e2c-83a3-4f55901e206a/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/aa3b0060-67c6-41a3-863b-4203491263f0)

#### [2012/2013：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/f2965304-9004-4ce0-9ce1-a3acdd19bf48/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/b7852440-6bf3-4f5d-a83c-97a5513c8831)

#### [2011/2012：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/54313974-2ddd-43cb-9e7c-baaa047053d9/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/649f3b3d-75d6-494f-b3ad-90c862aa1ab8)

#### [2010/2011：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/d8b55a1c-d0c8-4426-be5e-a1001af48bb0/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/af429003-a3fd-483c-9f4b-5efd35a061cd)

#### [2009/2010：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/d3619d25-4942-494d-a61d-5650804767ef/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/1bcdbff0-bd4c-49a6-a99c-a3ca66fcca9e)

#### [2008/2009：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/2872719e-e76d-47db-8d80-1941d27239fa)

- 校方保留了元数据，但没有提供可下载 PDF。

#### [2007/2008：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/c0c8c6c7-03c4-4502-8b17-f1805cf7affe/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/72368896-25a5-4029-acec-8df74ea1aa83)

<a id="analysis-pgbi11040"></a>
### 历年规律、当前风险与 LLM 难度

| 维度 | 17 份可读卷的结果 |
|---|---|
| 高频考点 | microarray **15/17** ，RNA-seq/transcriptomics **14/17** ，ChIP/TF binding **14/17** ，QC/normalisation/experimental design **12/17** ，clustering/PCA **8/17** ，single-cell/新技术 **4/17** 。 |
| 明显复用 | microarray hybridisation 长期重复；“data fishing”在 2021/22 与 2023/24 重现；ChIP peak calling 在 2023/24 与 2025/26 近似；联合 ChIP/RNA-seq 在 2021/22、2022/23、2025/26 反复出现。 |
| 作答规则 | 第一题必答，第二、三题选一；2020/21-2022/23 为 open-book，2023/24 起为现场 2 小时卷。 |
| 可准备性 | **很高。** 17 份卷显示核心技术族长期稳定，且有近似题；但新技术、实验设计与具体数据解释仍会轮换，不能只背旧答案。 |
| 数据核验提醒 | 2024/25 PDF 卷首内部误印代码 `PGBI11114`，但标题、档案元数据与全部内容均是 Functional Genomic Technologies；这是卷面代码错误，不是本文把研究计划卷混进来。 |
| **LLM 难度**  | **3.5/5。** 功能基因组技术、统计解释与 R/Unix 实践并重；旧题多，但需覆盖实验设计和新技术。 |

<a id="course-pgbi11057"></a>
## [PGBI11057 生物信息学算法 / Bioinformatics Algorithms](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11057.htm)

- **学分与学期：** 10 credits，Semester 2；DPT 强烈推荐。
- **官方名义学习量：** Total Hours **100** （讲授 10；监督实践/工作坊 10；总结性考核 2；项目级教学 2；定向/独立学习 76）。
- **官方考核：** Written exam 50% + Written assessment 50%；课程页列为 April/May main diet、120 分钟。
- **课程解释：** 学习计算机科学与生物学交界处的算法思想，理解常见 bioinformatics 软件背后的计算方法，并以 Python 实现算法。它比单纯调用现成工具更强调复杂度、算法设计和实现能力。
- **学习提示：** 对算法、科研软件和 AI4Science 的计算基础很有价值，但强 Python 实作和 50% 笔试意味着不适合只想避开编程或理论的学生。

<a id="papers-pgbi11057"></a>

### 历年试卷

共 15 条：14 份 PDF，1 条 Paper Unavailable。

#### [2025/2026：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/6403ab0e-12e4-48f6-8517-a4b6422efdcb/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/3d26febd-49a0-4e35-b196-b513bcc96b29)

#### [2024/2025：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/c2f53508-2333-40c1-bedd-67d46580392d/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/c6d6a298-7987-4d0e-989e-1b4b585bde5f)

#### [2023/2024：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/a0122c24-3cc6-412a-a173-186ec7058790/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/cec1697e-8372-4b22-b79b-b9d614c95464)

#### [2022/2023：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/9a27272f-b1c1-4350-88af-c77a62e51229/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/46025da4-25df-4de1-ba34-c2dd925b8d43)

#### [2021/2022：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/9c39b04e-a4ea-47db-a411-f005e551b6de/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/a6224b81-b39c-4ba5-a2cb-57bc11af7758)

#### [2020/2021：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/2678eb94-ea51-4cc2-9c56-a9f6a458522a/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/e5953b8d-7b33-47b8-a75e-8cd36bfff8ae)

#### [2019/2020：档案条目（Paper Unavailable）](https://exampapers.ed.ac.uk/items/0bf10821-9b80-480c-8130-214729cbf855)

- 校方保留了元数据，但没有提供可下载 PDF。

#### [2018/2019：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/39ad1f45-3cfd-43b3-8c4b-557bb31dbfc7/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/ff962d68-c63f-44e0-b9ca-20913f1c3ede)

#### [2017/2018：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/88769d75-81f9-4b92-bf60-049f023526e4/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/a66ff681-8c24-42d1-8476-c96e1f1243ce)

#### [2016/2017：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/1517df78-f457-4009-a429-43a8eb79172a/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/95258736-204d-4729-9631-7caf21007095)

#### [2015/2016：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/37ff2654-ce68-4c35-bbea-055d92c1f8e6/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/7ed6ebaf-63f9-423e-84fa-f7ccb3a5f807)

#### [2014/2015：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/fe9d2b79-a658-4451-bdee-65b10492d371/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/f2208a88-1c20-4ccb-9a79-0f36df6d2b11)

#### [2013/2014：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/7d71951d-c43d-481e-8d53-0ddb25c110e4/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/21291164-6dd6-4bea-b7fb-146615a0d736)

#### [2012/2013：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/0330ce57-7bf3-4385-8d5c-88be3a22bbc1/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/1284ab55-996c-4706-bd01-91c249332bb7)

#### [2011/2012：试卷 PDF](https://exampapers.ed.ac.uk/bitstreams/efc8f023-99a1-44c3-8f01-3bec0e7cd865/download)

- [校方档案条目](https://exampapers.ed.ac.uk/items/e8a0b280-ec34-4a99-96d5-728bc09b2ae0)

<a id="analysis-pgbi11057"></a>
### 历年规律、当前风险与 LLM 难度

| 维度 | 14 份可读卷的结果 |
|---|---|
| 高频考点 | complexity/sorting/data structures **14/14** ，programming/code reading **12/14** ，genetic algorithms **11/14** ，clustering/trees **11/14** ，alignment/BLAST **9/14** ，motifs **8/14** ，MapReduce **7/14** ，HMM **5/14** 。 |
| 明显复用 | Quicksort 在 2020/21、2022/23、2023/24 近似复用；2024/25 Q1 重组了旧卷的 bubble sort/tree/stack/GA/MapReduce；2025/26 的 hierarchical clustering + GA 与 2020/21 Q3 接近，decision tree 又延续 2022/23-2023/24。 |
| 作答规则 | 第一题必答，第二、三题选一；2020/21-2022/23 open-book，2023/24 起现场 2 小时。 |
| 可准备性 | **非常高。** 在本项目有卷课程中，原题结构和短问元素复用最明显之一；但代码跟踪、复杂度和算法应用需要真正会做，不能只认题。 |
| **LLM 难度**  | **3.5/5。** 需要代码跟踪、复杂度、数据结构和生信算法；旧题有规律，但不能依靠背概念替代计算。 |

<a id="course-pgbi11130"></a>
## [PGBI11130 生物结构与药物功能 / Biological Structure and Drug Function](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11130.htm)

- **学分与学期：** 20 credits，Semester 2；DPT 说明本课不能以 “Class Only” 方式修读。
- **官方名义学习量：** Total Hours **200** （讲授 12；研讨/辅导 8；监督实践/工作坊 12；总结性考核 2；复习课 4；项目级教学 4；定向/独立学习 158）。
- **官方考核：** Coursework 100%。Structural methods class test 占 30%；group mini-project report 占 70%。项目分数中 90% 由两位 markers 评定，10% 来自 peer assessment。没有中央正式笔试。
- **课程解释：** 学习生物分子结构的测定方法、结构质量指标和分子建模，并把结构信息用于 virtual screening 与 drug discovery。方向偏结构生物学、计算药物发现和分子层面的机制解释。
- **学习提示：** 一门课占 20 学分，且 70% 集中在小组项目；适合愿意做结构/药物方向并能承担团队项目风险的学生。课堂测验不等同于中央考试卷。

### 历年试卷

官方试卷库对精确代码 `PGBI11130` 的检索为 0 条，和 Coursework 100% 相符。课程内 30% class test 不属于中央正式笔试库，因此没有公开历年卷可列。

<a id="analysis-pgbi11130"></a>
### 考核结构与 LLM 难度

| 维度 | 评估 |
|---|---|
| 是否闭卷 | 无中央正式笔试；30% structural methods class test 的开闭卷/材料规则未在公开页给出，70% 为 group mini-project report。 |
| 可预测性 | 总比例明确，但课堂测验无公开旧卷；项目 90% 由两位 markers 评分、10% peer assessment，团队与题目影响大。 |
| 主要风险 | 一门占 20 学分，70% 依赖小组；结构生物学学习曲线和团队方差都集中在高权重组件。 |
| **LLM 难度**  | **3.5/5。** 结构生物学与分子建模有学习门槛，20 学分、课堂测验及高权重小组项目带来集中风险。 |

---

<a id="course-pgbi11126"></a>
## [PGBI11126 群体基因组分析 / Population Genomic Analysis](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11126.htm)

- **学期与学分：**  Semester 2，Block 3 开始；10 SCQF credits（5 ECTS），Level 11。列在 Bioinformatics 的 S2 50 学分选修池中。
- **名义学习量：**  100 小时：Lecture 30、Programme-level 2、独立学习 68。课程正文描述为交互式 Jupyter notebook 上机实践；结构化字段写 Lecture Hours，不代表纯讲授。
- **考核：**  DRPS 分类为 Coursework 100%，实际为每周 Learn 数值题/选择题测验 25%，第 5 周限时上机（class exam）75%。**不是无考试课程。** 公开页未给出上机时长、开闭卷、联网或工具使用规则，须查当届 assessment brief。
- **内容：**  以基因组样本的祖先关系为核心，学习合祖理论（coalescent）、genealogies、tree sequences 与图结构，结合模拟和统计推断理解遗传漂变、重组、群体历史、混合与自然选择。
- **基础：**  未列强制先修代码，但课程描述明确预期基本群体遗传学知识；“无先修代码”不等于零基础。课程负责人为 Dr Konrad Lohse。

<a id="analysis-pgbi11126"></a>
### 是否新课、考核与 LLM 难度

**不是 2026/27 新开课。** [2021/22 课程目录](https://www.drps.ed.ac.uk/21-22/dpt/cxpgbi11126.htm) 已有同名同代码课程；[2024/25](https://www.drps.ed.ac.uk/24-25/dpt/cxpgbi11126.htm) 与 [2025/26](https://www.drps.ed.ac.uk/25-26/dpt/cxpgbi11126.htm) 也有记录。

**相较上一学年，是 Bioinformatics 选修表中新列出的课程。** [2025/26 Bioinformatics DPT](https://www.drps.ed.ac.uk/25-26/dpt/ptmscbioin1f.htm) 未列 PGBI11126；[2026/27 DPT](https://www.drps.ed.ac.uk/26-27/dpt/ptmscbioin1f.htm) 明确列入。这个比较证明两版目录的变化，不证明课程历史上从未向本专业学生开放。

| 维度 | 判断 |
|---|---|
| LLM 难度 | **4.0/5，较高。** 随机模型与群体遗传学的概念门槛、计算实践及限时考核叠加；这是主观判断，不是学生评价统计。 |
| 最大风险 | 75% 集中在一次限时上机；即使平时 quiz 全拿，也不能替代上机表现。 |
| 哪类方向适合 | 希望研究群体历史、演化、遗传祖先关系及模型推断的同学，内容相关性较强。 |
| 减负建议 | 不作为轻松凑学分选项。与通用 R/数据库课相比，它更偏专门的模型与推断训练；不能仅因 Coursework 100% 而优先选。 |
| 与 NGG 的区别 | 重点是群体遗传变异及祖先关系的推断，而不是以测序平台、组装和 QC 为主要目标；二者可能互补，但不能视为同一门课。 |
| 名额提醒 | 当届页面 Quota 字段为 0，而 DPT 又列为可选；页面未解释该字段，不据此断言停开、满额或无限名额，实际注册需向项目确认。 |

### 历年卷与准备资料

本次以精确代码及课程名检索公开索引，未取得可核对的历年试卷；没有据此宣称试卷库为 0 条。该课的 class exam 可能通过 Learn 管理，中央试卷库是否收录仍需校方确认。已核对的 2021/22、2024/25、2025/26、2026/27 课程页均使用 25% quiz + 75% timed practical 的结构，但这不证明题目重复。

复习建议属于 LLM 判断：先补群体遗传学和基本概率，再练习 notebook 数据处理、模拟结果解释与限时分析。具体软件、允许资料和考试时长应以当届材料为准。

# 公开学生经验与项目实例

## 社交平台证据等级

| 等级 | 含义 | 可以怎么用 |
|---|---|---|
| A | 能确认是本 MSc 当前学生或毕业生的第一手经历 | 可作为项目体验的重要旁证，但仍只是个体样本 |
| B | 与本项目直接相关，但身份、完整上下文或平台数据无法独立核实 | 可提示问题，不宜单独下结论 |
| C | 爱大相邻学院、旧课程或学校层面的学生经验 | 只能帮助理解环境，不能外推到某门选修课 |
| D | 未就读者、转述、申请中介、排名或自动聚合页 | 只记录其存在，不能当课程口碑 |

LinkedIn 毕业帖和学校官网学生故事往往偏正面；Reddit 更容易出现负面或求助样本。两边都有选择偏差，不能用“帖子多/点赞多”替代课程调查。

## 最有价值的本项目亲历材料

| 来源 | 身份与时间 | 可提取的信息 | 局限与等级 |
|---|---|---|---|
| [Reddit：Questions about MSc Bioinformatics program](https://www.reddit.com/r/bioinformatics/comments/pkj956/questions_about_msc_bioinformatics_program_at_the/) | 发帖者后来选择了 UoE，并在 2023 年以国际学生身份回访 | 项目比不少同类 MSc 更偏 genomics；选修空间较大；至少一门编程语言与命令行基础很重要，基础薄弱者更容易吃力；其本人总体满意 | 单个匿名样本，未逐课评价；**A-**  |
| [Kavya Manjula Gurubasavaiah，2025 届](https://biology.ed.ac.uk/study-with-us/postgraduate-taught/meeting-us/meet-our-students/kavya-manjula-gurubasavaiah) | 学校官网确认的 MSc Bioinformatics 毕业生 | 强调真实数据、工具与实践；称早期 lab 节奏快，需要预习、试跑分析和主动反馈；dissertation 与 Quas Drinks 合作，做 16S/shotgun metagenomics 和可复现 pipeline | 学校明确披露其受到激励分享故事，存在宣传筛选；**A-**  |
| [Lodan E，2026 届在读](https://biology.ed.ac.uk/study-with-us/postgraduate-taught/meeting-us/meet-our-students/lodan-e) | 学校官网确认的当前学生，CS 背景 | 认可选修范围和跨背景同学；认为课程会介绍关键概念帮助补基础；自己需要额外补 biology；描述 lecture 后常配 workshop，并称教师支持积极 | 受激励的学校学生故事；尚未完成项目；**A-**  |
| [Rahul D，2026 届在读](https://biology.ed.ac.uk/study-with-us/postgraduate-taught/meeting-us/meet-our-students/rahul-d) | 学校官网确认的当前学生 | 强调 transferable skills、互动课堂、lab 支持与组织；提醒从第一天管理 lectures/tutorials/assignments；当时尚无正式 internship，期待五月开始 dissertation | 受激励的学校学生故事；**A-**  |
| [Karin Hrovatin，2019 届](https://biology.ed.ac.uk/study-with-us/taught-programmes/meeting-us/meet-our-students/karin-hrovatin) | 学校官网确认的毕业生，后进入研究岗位及机器学习型 bioinformatics PhD | 认为课程实践导向对独立研究最有价值；实践作业投入很大；从 biotechnology 转向 bioinformatics 时需要大量补 statistics/data analysis；其 distinction 和最佳论文奖帮助求职 | 优秀毕业生样本，信息主要形成于 2020 年；**A-**  |
| [Max Falk，2024/25 届 LinkedIn](https://www.linkedin.com/posts/max-falk1_it-was-a-pleasure-to-return-to-the-university-activity-7397566728353783808-8Jmg) | 该届 top student prize、Distinction | 明确把课程形容为 challenging 但 hugely enjoyable，并肯定 Programme Director 与 dissertation supervisor 的指导 | 顶尖获奖者、毕业庆祝帖，正向选择偏差强；**A-**  |
| [Xi Yang，2024 届 LinkedIn](https://www.linkedin.com/posts/ianyangxi_computationalchemistry-machinelearning-activity-7266782734281281536-KUFX) | MSc 毕业后获 EPSRC PhD scholarship | 将一年概括为高强度成长，学习 ML、bioinformatics、project management 和 LSTM；强调 ML 不能脱离统计与生物背景；称求 PhD 过程很艰难 | 自我总结/庆祝帖，未评价具体课程；**A-**  |
| [Anooraag Basu，2024/25 届 LinkedIn](https://www.linkedin.com/posts/anooraagbasu_a-moment-that-i-had-looked-forward-to-is-activity-7397269329320476672-J5fm) | Merit 毕业生 | 称项目并不轻松，但推动其挑战极限、建立国际联系；肯定教师、导师和支持系统 | 毕业庆祝帖，正向选择偏差；**A-**  |
| [Miles McGibbon，2022 届 LinkedIn](https://www.linkedin.com/posts/miles-mcgibbon_im-delighted-to-have-graduated-with-distinction-activity-7005568886557294593--hGq) | Distinction 毕业生 | dissertation 与 AskBio 合作，使用机器学习预测 microRNA interactions；证明该项目历史上确实出现过企业合作型 AI/bioinformatics 论文 | 只证明这个个案，不保证 2026/27 仍有同类名额；**A-**  |
| [Shiksha：UoE reviews 页面中的 2023 届匿名评价](https://www.shiksha.com/studyabroad/uk/universities/the-university-of-edinburgh/reviews?bc=100) | 页面标注 “Verified”、MSc Bioinformatics、Batch of 2023 | 给出 3.8/5，称校园人际体验友好、获得奖学金，并自报每周课前准备 32 小时 | 匿名且由商业留学平台核验；月支出、预期薪资等自报数字无法独立确认，不应拿来做预算或就业预测；**B**  |

## 其他有内容的 Reddit 与论坛讨论

| 帖子 | 实际内容 | 证据判断 |
|---|---|---|
| [What do I need to know before starting my masters course](https://www.reddit.com/r/bioinformatics/comments/mcxtsv/what_do_i_need_to_know_before_starting_my_masters/) | OP 后来说明自己将读爱大 Bioinformatics；回复者建议 Linux、bash/Python、统计和分子生物学，但回复者没有证明自己读的是爱大项目 | 很有用的通用预习建议，不是爱大亲历评价；**B/C**  |
| [MSc Bioinformatics at University of Edinburgh，2026](https://www.reddit.com/r/bioinformaticscareers/comments/1swzgks/msc_bioinformatics_at_university_of_edinburgh/) | 有人批评课程 “dated”、偏传统 genetics/stats；追问后该评论者明确承认从未就读，只看了 module catalogue | 这是**未就读者意见** ，不能当作负面亲历评价；**D**  |
| [KCL Applied Bioinformatics vs Edinburgh Bioinformatics，2026](https://www.reddit.com/r/UniUK/comments/1sx0nha/msc_applied_bioinformatics_at_either_kcl_or_msc/) | 评论者认为 Edinburgh 更利于研究/PhD、KCL 有伦敦区位，但依据主要是排名和亲属经历 | 间接转述，不能证明就业结果；**D**  |
| [Re: Opinions from Current University Students](https://www.reddit.com/r/Edinburgh_University/comments/siufuy/re_opinions_from_current_university_students/) | 本项目 offer holder 求亲历回复；其他回复主要讨论爱大一般环境、独立学习与城市 | 学校层面旁证，不能套到本 MSc；**C**  |
| [The Student Room：MSc in Bioinformatics，2009](https://www.thestudentroom.co.uk/showthread.php?t=983072) | 当年参与者称项目 “pretty good”，生物课程由研究人员授课，也可选较多 ML/信息学课 | 第一手可能性较高，但已约 16 年，课程代码、选课规则和培养方案均已改变；**C**  |
| [The Student Room：York or Edinburgh，2013](https://www.thestudentroom.co.uk/showthread.php?t=2395540) | 一名用户称 Edinburgh 在 bioinformatics 领先，但没有证明自己就读过 | 很旧、非亲历；**D**  |

## 相邻课程与学校层面信号

- [Reddit：Can someone provide a review of ML courses?](https://www.reddit.com/r/Edinburgh_University/comments/g681uh/can_someone_provide_a_review_of_ml_courses/) 中有 2018/19 学生把旧课 **Introductory Applied Machine Learning (`IAML`)**  评为 1/5，批评翻转课堂和组织；另有旧帖把 IAML 称为 good course。当前 `INFR11211 Applied Machine Learning` 并不等于旧 IAML，官方只说旧卷可能有部分相关内容，因此这只能作为历史相邻信号，不能当作当前 AML 评价。
- [Reddit：U of Edinburgh Software Eng](https://www.reddit.com/r/Edinburgh_University/comments/14eij76/u_of_edinburgh_software_eng/) 的信息学院毕业生称工作量高度依赖既有编程基础，lecture 往往只覆盖理论基础，实施部分需要大量自学，教师体验有好有坏。它可提示 `INFR11211` 的学院环境，但不是本课或本 MSc 评价。
- [Reddit：Honest Review on Edinburgh University](https://www.reddit.com/r/UniUK/comments/1antg8a/honest_review_on_edinburgh_university/) 是一名爱大 CS 本科生的长篇负评；[The Student Room：UoManchester or UoEdinburgh](https://www.thestudentroom.co.uk/showthread.php?t=7648270) 则是一名爱大 biology 本科生对高工作量、Python 支持与学生体验的负面描述。两者都值得知道，但学院、年级和培养方案不同，**不能外推为 MSc Bioinformatics 的事实** 。
- [Reddit：Is UoE really worth its tuition fee?](https://www.reddit.com/r/Edinburgh_University/comments/1p4c2e2/is_uoe_really_worth_its_exorbitant_tuition_fee/) 汇集了对 contact hours、反馈、求职和学费价值的不同意见，涉及多个项目。它适合提示读者核实支持和就业服务，不适合给任一选修课打分。

## 毕业项目、方向与公开去向实例

- [Kavya，2025](https://biology.ed.ac.uk/study-with-us/postgraduate-taught/meeting-us/meet-our-students/kavya-manjula-gurubasavaiah)：Quas Drinks 合作；16S/shotgun metagenomics、QIIME2、MetaPhlAn4、HUMAnN3、DRAM。
- [Miles McGibbon，2022](https://www.linkedin.com/posts/miles-mcgibbon_im-delighted-to-have-graduated-with-distinction-activity-7005568886557294593--hGq)：AskBio 合作；机器学习预测 microRNA interactions。
- [Giulia Guasoni，2025 届公开档案](https://uk.linkedin.com/in/giulia-guasoni-92a968293)：公开列出的选课覆盖 Algorithms、Programming/System Management、Biological Databases、Functional Genomics、Website/Database、NGG、Statistics、Entrepreneurship、Using R；论文使用公共 RNA-seq 数据研究 laminopathies。它是路径实例，不是课程评分。
- [Elijah Downs 个人主页](https://elijahdowns.github.io/)：公开称其 MSc industry placement 在 Edinburgh 的 CEXAL Ltd，开发核酸检测探针设计自动化 pipeline。该页面能证明又一个企业合作个案，但项目安排仍应向 Programme Director 逐年确认。
- [Karin Hrovatin，2019](https://biology.ed.ac.uk/study-with-us/taught-programmes/meeting-us/meet-our-students/karin-hrovatin)：毕业后进入 bioinformatics 研究岗位，再进入机器学习导向的 bioinformatics PhD。

这些个案支持“可以把 dissertation 做成 AI/ML、组学或企业合作项目”，但不等于企业 placement 可以自动替代 `PGBI11034`，也不等于每年会向每位学生提供公司项目。

## 有实际材料的平台覆盖

| 平台 | 扩大检索结果 | 使用限制 |
|---|---|---|
| Reddit | 找到 1 条较强项目亲历，以及若干有内容的比较帖和相邻学院讨论 | 匿名、样本少、负面/求助选择偏差 |
| LinkedIn | 找到多名可确认项目关系的毕业生、论文合作与去向实例 | 毕业庆祝和职业展示偏正面，不能代表普通成绩段 |
| 学校 Student Stories | 找到 2019、2025、2026 届项目学生材料 | 学校页面明确披露部分学生受到激励，属于经过筛选的宣传环境 |
| The Student Room | 找到 2009 项目参与者评论和 2013 比较帖 | 材料较旧或身份不完整；不得套用旧选课规则 |

## 第三方评分页为什么不能直接相信

- [Shiksha 的 2023 届本项目匿名评价](https://www.shiksha.com/studyabroad/uk/universities/the-university-of-edinburgh/reviews?bc=100) 是少数明确标注本 MSc 的条目，可以作为 B 级个案；但该页同时混排全校其他专业，费用、工时和预期薪资均为自报。
- [UniversityGuru 的 Bioinformatics 页面](https://www.universityguru.com/c/the-university-of-edinburgh-edinburgh/bioinformatics-msc) 虽显示 “30 respondents/76%”，同页却把比较学科和薪资标成 **Finance, Banking, Corporate Finance, Fintech** ，并混列 9 个月与 1 年学制。字段明显错配，因此本文不把其数字当成本项目可靠统计。

## 公开学生经验的共同信号

- 当前可核验的社交材料主要反映项目整体体验和毕业项目，不能据此形成 14 门课程的可靠逐课口碑排序。同名或近似名称也不能自动视为本课材料：旧 IAML、Intro to Databases、Genomes and Genomics、Programming Skills for Engineers 等均与本文课程代码不完全对应。
- 目前最稳健的共同信号是：项目偏 genomics，编程/命令行/统计基础会显著影响体验；课程节奏快、独立学习比重高；实践作业和 dissertation 对研究/求职作品最有价值；确有企业合作与 AI/ML 项目个案，但并非保证。
- 公开材料不足以支持“coursework 100% 一定更容易得高分”或“某门具体课公认水/难”。选课仍应把官方考核结构、个人基础、历年卷和当届学生口头反馈放在社交平台热度之前。

<a id="personalised-plans"></a>
# LLM 难度总表与选课参考

以下评级不是排名调查。相同分数不表示学习内容或工作量相同；100 小时与 200 小时课程不可只比较评分。两门 10 学分课能分散单门考核权重，但也可能增加同时赶作业的次数，并不自动更省力。

| 课程代码 | LLM 难度 | 主要理由 |
|---|---:|---|
| [PGBI11122](#course-pgbi11122) | 2.5/5 | 有 R 基础时相对易准备；语言语义、数据处理和可复现流程仍需准确理解，另有 50% 笔试。 |
| [PGBI11114](#course-pgbi11114) | 3.0/5 | 重点是问题界定、方法可行性与英文论证；单份研究计划占全部成绩。 |
| [PGBI11129](#course-pgbi11129) | 3.0/5 | 兼顾数据库概念、API、生物数据库与脚本整合；旧题较稳定，但作业需要实际构建。 |
| [BILG11004](#course-bilg11004) | 3.0/5 | 测序、组装、QC 和群体基因组概念较多，essay 考试要求组织论证；生物基础薄弱者需补课。 |
| [BILG11016](#course-bilg11016) | 3.0/5 | 无中央笔试，但 SQL、关系建模、网站实现与批判性论文都需要投入；调试成本不可忽略。 |
| [BITE11004](#course-bite11004) | 3.0/5 | 实验流程、数据分析与科研报告跨多个环节；无中央笔试不代表轻松，最终报告权重大。 |
| [CMSE11576](#course-cmse11576) | 3.0/5 | 技术门槛相对有限，但商业论证、英语展示和团队协作共同影响成绩，70% 小组考核风险较集中。 |
| [EPCC11017](#course-epcc11017) | 3.0/5 | 适合已有编程基础者；测试、版本控制、性能和代码质量比会写脚本要求更高，不是零基础入门。 |
| [PGBI11095](#course-pgbi11095) | 3.5/5 | Python/Linux 综合应用与闭卷系统设计并重；两个考核组件分别过线，不能只靠总分补偿。 |
| [BICH11011](#course-bich11011) | 3.5/5 | 需要定量生物物理、实验分析与长报告；20 学分和高权重实验报告使工作量集中。 |
| [PGBI11040](#course-pgbi11040) | 3.5/5 | 功能基因组技术、统计解释与 R/Unix 实践并重；旧题多，但需覆盖实验设计和新技术。 |
| [PGBI11057](#course-pgbi11057) | 3.5/5 | 需要代码跟踪、复杂度、数据结构和生信算法；旧题有规律，但不能依靠背概念替代计算。 |
| [PGBI11130](#course-pgbi11130) | 3.5/5 | 结构生物学与分子建模有学习门槛，20 学分、课堂测验及高权重小组项目带来集中风险。 |
| [PGBI11003](#course-pgbi11003) | 4.0/5 | 概率、线性模型、ANOVA/GLM 与 R 解释需要同时掌握；公开考核信息有冲突，须查当届说明。 |
| [PGBI11034](#course-pgbi11034) | 4.0/5 | 独立研究、数据与导师依赖、英文写作和长期进度管理叠加；60 学分的总负担不可忽略。 |
| [INFR11211](#course-infr11211) | 4.0/5 | 覆盖较广，20 学分且 60% 闭卷；旧题有助复习，但不能替代完整课程范围。 |
| [PGBI11126](#course-pgbi11126) | 4.0/5 | 合祖随机模型、群体遗传推断与计算实践相结合；75% 限时上机使成绩集中，不建议作为减负课程。 |
| [MATH11205](#course-math11205) | 4.5/5 | 难度高，不建议选修。不能把它当成轻松的 Python 工具课：数学理解、编程、每周作业与项目并行；笔试占 50%。 |
| [PGBI11051](#course-pgbi11051) | 4.5/5 | 细胞机制与定量建模交叉，抽象推理要求高，近期可读旧卷不足；不建议作为减负选项。 |

<a id="plan-easiest"></a>
## 方案 A：基础应用与分散考核

适合希望同时练习 R、数据库、科研编程与组学分析的同学。它不是“保证最简单”或“保证高分”的方案；实验、报告和网站开发均可能耗时。

| 学期 | 课程 | 学分 |
|---|---|---:|
| S1 | PGBI11122 Using R for Data Science | 10 |
| S1 | PGBI11129 Biological Databases | 10 |
| S2 | BITE11004 Metagenomics | 10 |
| S2 | EPCC11017 Programming Skills | 10 |
| S2 | BILG11016 Introduction to website and database design | 10 |
| S2 | BILG11004 Next Generation Genomics | 10 |
| S2 | PGBI11057 Bioinformatics Algorithms | 10 |

S1 20 学分、S2 50 学分，共 70 学分；按名义学习量口径为 700 小时名义学习量。此方案未包含官方强烈推荐的 PGBI11040，偏功能基因组方向者可考虑用它替换一门 S2 选修。

<a id="plan-cs"></a>
## 方案 B：计算方法与组学方向

| 学期 | 课程 | 学分 |
|---|---|---:|
| S1 | PGBI11122 Using R for Data Science | 10 |
| S1 | PGBI11129 Biological Databases | 10 |
| S2 | EPCC11017 Programming Skills | 10 |
| S2 | BILG11016 Introduction to website and database design | 10 |
| S2 | PGBI11057 Bioinformatics Algorithms | 10 |
| S2 | BILG11004 Next Generation Genomics | 10 |
| S2 | PGBI11040 Functional Genomic Technologies | 10 |

共 70 学分、700 小时名义学习量。相较方案 A，以 Functional Genomic Technologies 替换 Metagenomics；增加功能组学方法训练，但也增加中央笔试权重。

**明确需要机器学习课时** ：可在符合先修、获得项目批准且课表允许的前提下，考虑用 INFR11211 Applied Machine Learning（20 学分）替换 S1 的两门课。它本身为较高难度，不能理解成轻松替代品。MATH11205 不纳入本版推荐组合；即使以往允许携带笔记，也不足以据此判断课程容易。

**群体/演化基因组方向的替换选项** ：可考虑用 PGBI11126（S2，10 学分）替换一门 S2 10 学分选修，而不是额外叠加学分。它不加入本版减负组合，原因是随机模型门槛与 75% 限时上机。

上述组合仅满足当前 DPT 中可见的学分算术与课程列表，不代表已经获准注册；须核对先修、名额和实际 timetable。LLM 评分为序数性质，不计算所谓“平均拿分难度”，不作学位认证或就业结果承诺。

# 官方入口与版本说明

- [Bioinformatics MSc 2026/27 DPT](https://www.drps.ed.ac.uk/26-27/dpt/ptmscbioin1f.htm)
- [University of Edinburgh Exam Papers Online](https://exampapers.ed.ac.uk/home)
- [Library：Exam papers 使用与收录说明](https://library.ed.ac.uk/exam-papers)
- [Library：Exam papers 收录范围、排除与缺卷说明](https://library.ed.ac.uk/finding-resources/exams)
- [Applied Machine Learning 官方开放课程](https://opencourse.inf.ed.ac.uk/aml)

本文件的课程与官方学习量已于 **2026-08-15**  再核验；考核与试卷链接核验日期为 2026-08-14。课程考核、开课学期、学习量分类和试卷可用状态都可能后续更新；正式选课和考试安排应以 MyEd、Learn、个人 timetable 及 Programme Director 的书面确认优先。

更新日期：2026-09-14。难度为通用 LLM 主观评级；DPT、MATH11205 和 PGBI11126 页面于本次核对，其余历史统计保留此前整理结果，不代表已完成新一轮全量核验。
