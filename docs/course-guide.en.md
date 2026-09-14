# University of Edinburgh MSc Bioinformatics 2026/27

[Chinese](./course-guide.zh-CN.md) | **English**

## Courses and Past Papers

Course information, past-paper links, exam-topic analysis and public student accounts.

**Difficulty ratings: subjective LLM-as-judge assessments.** The reference learner has basic biology, introductory programming and elementary statistics, but has not systematically studied each course. Ratings consider mathematical abstraction, practical programming, breadth, assessment pressure and project dependencies. The scale runs from 1/5 (very low) to 5/5 (very high), with half-point steps. These are not official ratings, student-survey results or grade predictions. Relevant experience can reduce difficulty; starting from scratch can increase it substantially.

**Recommendation: MATH11205 Machine Learning in Python is difficult and is not recommended in this guide.** Students specifically seeking machine-learning training should confirm the requirements with the course organiser.

**Coverage and dates:** This guide covers the 19 courses explicitly listed in the [2026/27 Degree Programme Table (DPT)](https://www.drps.ed.ac.uk/26-27/dpt/ptmscbioin1f.htm): 4 compulsory and 15 optional courses, including PGBI11126 Population Genomic Analysis. The DPT, MATH11205 and PGBI11126 were checked on 2026-09-14. Other course and past-paper review dates appear at the end; those entries have not all been checked again. Registration depends on current availability, prerequisites, timetable compatibility and assessment arrangements.

## Contents

- [Compulsory courses](#required-courses)
  - [PGBI11095 Bioinformatics Programming and System Management](#course-pgbi11095)
    - [Past papers: 13 records, 6 PDFs](#papers-pgbi11095)
    - [Recurring topics and LLM difficulty](#analysis-pgbi11095)
  - [PGBI11003 Statistics and Data Analysis](#course-pgbi11003)
    - [Past papers: 14 records, 3 PDFs](#papers-pgbi11003)
    - [Recurring topics and LLM difficulty](#analysis-pgbi11003)
  - [PGBI11114 Research Proposal (Bioinformatics)](#course-pgbi11114)
    - [Assessment and LLM difficulty](#analysis-pgbi11114)
  - [PGBI11034 MSc Dissertation (Bioinformatics)](#course-pgbi11034)
    - [LLM difficulty, supervision and project directions](#analysis-pgbi11034)
- [Semester 1 options](#semester-1-electives)
  - [BICH11011 Quantitating Drug Binding](#course-bich11011)
    - [Assessment and LLM difficulty](#analysis-bich11011)
  - [INFR11211 Applied Machine Learning](#course-infr11211)
    - [Past papers: 4 PDFs](#papers-infr11211)
    - [Question-level review, coverage and difficulty](#analysis-infr11211)
  - [MATH11205 Machine Learning in Python](#course-math11205)
    - [Past papers: 10 records, 6 PDFs](#papers-math11205)
    - [Recurring topics and LLM difficulty](#analysis-math11205)
  - [PGBI11051 Information Processing in Biological Cells](#course-pgbi11051)
    - [Past papers: 19 records, 2 PDFs](#papers-pgbi11051)
    - [Recurring topics and LLM difficulty](#analysis-pgbi11051)
  - [PGBI11122 Using R for Data Science](#course-pgbi11122)
    - [Past papers: 5 PDFs](#papers-pgbi11122)
    - [Recurring topics and LLM difficulty](#analysis-pgbi11122)
  - [PGBI11129 Biological Databases](#course-pgbi11129)
    - [Past papers: 4 PDFs](#papers-pgbi11129)
    - [Recurring topics and LLM difficulty](#analysis-pgbi11129)
- [Semester 2 options](#semester-2-electives)
  - [BILG11004 Next Generation Genomics](#course-bilg11004)
    - [Past papers: 16 records, 11 PDFs](#papers-bilg11004)
    - [Recurring topics and LLM difficulty](#analysis-bilg11004)
  - [BILG11016 Introduction to Website and Database Design](#course-bilg11016)
    - [Assessment and LLM difficulty](#analysis-bilg11016)
  - [BITE11004 Metagenomics](#course-bite11004)
    - [Assessment and LLM difficulty](#analysis-bite11004)
  - [CMSE11576 Technology Entrepreneurship and Commercialisation](#course-cmse11576)
    - [Assessment and LLM difficulty](#analysis-cmse11576)
  - [EPCC11017 Programming Skills](#course-epcc11017)
    - [Assessment and LLM difficulty](#analysis-epcc11017)
  - [PGBI11040 Functional Genomic Technologies](#course-pgbi11040)
    - [Past papers: 19 records, 17 PDFs](#papers-pgbi11040)
    - [Recurring topics and LLM difficulty](#analysis-pgbi11040)
  - [PGBI11057 Bioinformatics Algorithms](#course-pgbi11057)
    - [Past papers: 15 records, 14 PDFs](#papers-pgbi11057)
    - [Recurring topics and LLM difficulty](#analysis-pgbi11057)
  - [PGBI11130 Biological Structure and Drug Function](#course-pgbi11130)
    - [Assessment and LLM difficulty](#analysis-pgbi11130)
  - [PGBI11126 Population Genomic Analysis](#course-pgbi11126)
    - [Course history, assessment and LLM difficulty](#analysis-pgbi11126)
- [LLM difficulty summary and course combinations](#personalised-plans)
  - [Plan A: applied foundations and distributed assessment](#plan-easiest)
  - [Plan B: computational methods and genomics](#plan-cs)

## Assessment Overview

Difficulty scores use the LLM rating approach above. Total Hours is the official nominal study effort recorded in the earlier review, not classroom time or a prediction of actual effort.

| Category | Code and course | Credits | Total Hours | Official 2026/27 assessment | Verified exam-material rules | Paper archive | LLM difficulty |
|---|---|---:|---:|---|---|---:|---:|
| Compulsory S1 | [PGBI11095 Bioinformatics Programming and System Management](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11095.htm) | 20 | **200** | Class test 50% + exam 50%; each must reach 50% | Both explicitly in-person and closed-book | 13 records / 6 PDFs | **3.5/5** |
| Compulsory S1 | [PGBI11003 Statistics and Data Analysis](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11003.htm) | 20 | **200** | Formal Assessment field: class tests 45% + 55%, Coursework 100% | The Summary conflicts with the Assessment field; check current Learn materials | 14 / 3 PDFs | **4.0/5** |
| Compulsory S2 | [PGBI11114 Research Proposal (Bioinformatics)](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11114.htm) | 10 | **100** | Research proposal 100% | No centrally scheduled written exam | 0 | **3.0/5** |
| Compulsory project | [PGBI11034 MSc Dissertation (Bioinformatics)](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11034.htm) | 60 | **600** | Coursework 100%; at least 50% required | No centrally scheduled written exam | 0 | **4.0/5** |
| Optional S1 | [BICH11011 Quantitating Drug Binding](https://www.drps.ed.ac.uk/26-27/dpt/cxbich11011.htm) | 20 | **200** | Presentation 30% + extended practical report 70% | No centrally scheduled written exam | 0 | **3.5/5** |
| Optional S1 | [INFR11211 Applied Machine Learning](https://www.drps.ed.ac.uk/26-27/dpt/cxinfr11211.htm) | 20 | **200** | Written exam 60% + coursework 40% | Public course site: closed-book, 120 minutes, answer two of three questions | 4 / 4 PDFs | **4.0/5** |
| Optional S1 | [MATH11205 Machine Learning in Python](https://www.drps.ed.ac.uk/26-27/dpt/cxmath11205.htm) | 10 | **100** (components total 99.5) | Written exam 50% + coursework 50% | 2022/23-2024/25 allowed three double-sided A4 sheets of notes and a scientific calculator; 2026/27 rules not published | 10 / 6 PDFs | **4.5/5** |
| Optional S1 | [PGBI11051 Information Processing in Biological Cells](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11051.htm) | 10 | **100** | Written exam 50% + coursework 50% | Both older papers: three hours, answer all questions, non-programmable calculator only; current materials rules not published | 19 / 2 PDFs | **4.5/5** |
| Optional S1 | [PGBI11122 Using R for Data Science](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11122.htm) | 10 | **100** | Written exam 50% + coursework 50% | 2022/23 open-book; from 2023/24 an in-person two-hour paper, with no permission for notes stated | 5 / 5 PDFs | **2.5/5** |
| Optional S1 | [PGBI11129 Biological Databases](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11129.htm) | 10 | **100** | Written exam 50% + coursework 50% | 2022/23 open-book; from 2023/24 an in-person two-hour paper, with no permission for notes stated | 4 / 4 PDFs | **3.0/5** |
| Optional S2 | [BILG11004 Next Generation Genomics](https://www.drps.ed.ac.uk/26-27/dpt/cxbilg11004.htm) | 10 | **100** | Essay exam 50% + essay coursework 50% | 2021/22 open-book; from 2022/23 in-person, two hours, answer two of three questions | 16 / 11 PDFs | **3.0/5** |
| Optional S2 | [BILG11016 Introduction to Website and Database Design](https://www.drps.ed.ac.uk/26-27/dpt/cxbilg11016.htm) | 10 | **100** | Critical database essay 50% + MySQL website 50% | No centrally scheduled written exam | 0 | **3.0/5** |
| Optional S2 | [BITE11004 Metagenomics](https://www.drps.ed.ac.uk/26-27/dpt/cxbite11004.htm) | 10 | **100** | Report 1 30% + Contract Research Report 70% | No centrally scheduled written exam | 0 | **3.0/5** |
| Optional S2 | [CMSE11576 Technology Entrepreneurship and Commercialisation](https://www.drps.ed.ac.uk/26-27/dpt/cxcmse11576.htm) | 10 | **100** | Individual coursework 30% + group presentation 70% | No centrally scheduled written exam | 0 | **3.0/5** |
| Optional S2 | [EPCC11017 Programming Skills](https://www.drps.ed.ac.uk/26-27/dpt/cxepcc11017.htm) | 10 | **100** (S2 instance) | Practical coursework 100% | No centrally scheduled written exam | 0 | **3.0/5** |
| Optional S2 | [PGBI11040 Functional Genomic Technologies](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11040.htm) | 10 | **100** | Written exam 50% + assignments 50% | 2020/21-2022/23 open-book; from 2023/24 in-person, two hours, Q1 compulsory plus one of Q2/Q3 | 19 / 17 PDFs | **3.5/5** |
| Optional S2 | [PGBI11057 Bioinformatics Algorithms](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11057.htm) | 10 | **100** | Written exam 50% + written assessment 50% | 2020/21-2022/23 open-book; from 2023/24 in-person, two hours, Q1 compulsory plus one of Q2/Q3 | 15 / 14 PDFs | **3.5/5** |
| Optional S2 | [PGBI11130 Biological Structure and Drug Function](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11130.htm) | 20 | **200** | Class test 30% + group mini-project 70% | No centrally scheduled written exam; current conditions for the 30% class test await Learn materials | 0 | **3.5/5** |
| Optional S2 | [PGBI11126 Population Genomic Analysis](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11126.htm) | 10 | **100** | Coursework 100%: weekly quizzes 25% + week-5 timed computer practical 75% | Block 3; permitted materials, duration and tool rules require current assessment guidance | No verifiable past paper obtained | **4.0/5** |

### Interpreting Nominal Study Hours

- The 19 courses follow a general allocation of **10 hours per SCQF credit**: 100 hours for 10 credits, 200 for 20 credits and 600 for the 60-credit dissertation. The full degree therefore represents **1,800 hours**: 1,100 compulsory and 700 optional.
- S1 requires exactly 20 optional credits and S2 exactly 50, so every compliant option combination totals **700 hours**. Total Hours does not make Plan A shorter than Plan B. The difference is **concentration of work**: one 20-credit course concentrates 200 hours, assessment and failure risk in one course, whereas two 10-credit courses distribute the same 200 hours.
- DRPS activity categories do not map perfectly to timetabled contact hours. Some descriptions include labs, workshops or field excursions without listing a separate supervised-practical allocation. This guide reports the official categories; an unlisted category does not establish that the activity is absent.
- MATH11205 lists 100 total hours but its components sum to 99.5; the page does not explain the half-hour difference. EPCC11017 has S1 and S2 instances; this guide uses the **Semester 2** instance specified by the Bioinformatics DPT, with 100 hours.

---

<a id="required-courses"></a>
# Compulsory Courses

The four compulsory courses total 110 credits. Together with 20 elective credits in Semester 1 and 50 elective credits in Semester 2, the full year totals 180 credits.

<a id="course-pgbi11095"></a>
## [PGBI11095 Bioinformatics Programming and System Management](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11095.htm)

- **Credits and semester:** 20 credits, Semester 1, compulsory.
- **Official notional workload:** Total Hours **200** (lectures 20; supervised practicals/workshops 40; programme-level teaching 4; directed/independent study 136).
- **Course content:** Mainly Python, Unix/Linux, version control, scripting, databases/web services and reproducible workflows, with the aim of turning bioinformatics analyses into reliable, maintainable systems that others can use.
- **Official 2026/27 assessment:** 50% in-person closed-book Class Test + 50% in-person closed-book December Exam. The main examination page lists **180 minutes**, and **each component must separately achieve 50%**. The course page also states that students who fail only one component can usually take the corresponding alternative assessment in Semester 2. Students who fail both are generally not offered alternative assessments for both components unless exceptional circumstances have been approved.

<a id="papers-pgbi11095"></a>
### Past Papers

There are 13 archive entries: 6 readable PDFs and 7 marked `Paper Unavailable`. The 2022/23 and 2023/24 PDFs are explicitly titled **Essay question only** and cover only that question; they must not be presented as complete papers.

#### [2025/2026: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/a624c6b8-67e3-4465-888c-957e23918413/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/e2dddc3c-afd1-4851-bec4-fb0c30f58450)

#### [2024/2025: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/eda4f4a4-42f0-42c0-99a2-60208a2cccca/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/cb5f73a5-1156-4ad7-aed2-883c035d194d)

#### [2023/2024: Essay question only PDF](https://exampapers.ed.ac.uk/bitstreams/b4b1d960-42d7-494f-937d-0726eb7c0518/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/ed351d6c-e38d-4c9a-a6b4-b0037f246f49)

#### [2022/2023: Essay question only PDF](https://exampapers.ed.ac.uk/bitstreams/f9da7d46-8fb7-4588-a511-808c2367dd89/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/1091c790-46f9-4bc9-8251-92bfeea4c763)

#### [2021/2022: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/d6b3bca4-ffd6-48a4-9070-4ce7f90673ff/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/95263af6-1469-4919-a6cb-75ae16b2369b)

#### [2020/2021: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/a9aa34a2-fb2d-431a-ae72-170a83f43b23/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/5916cc9f-0e4d-4fb4-9723-a73b3f747b5d)

#### Paper Unavailable Entries

- [2019/2020](https://exampapers.ed.ac.uk/items/01197488-e935-45ff-a724-87c7731a561e)
- [2018/2019](https://exampapers.ed.ac.uk/items/3fc6d273-6a47-4bbf-adc8-f698b0eeed90)
- [2017/2018](https://exampapers.ed.ac.uk/items/9b8f0d0d-3ab7-4774-8667-32eb1ae8429b)
- [2016/2017](https://exampapers.ed.ac.uk/items/354afda4-a20f-4507-b97f-b423db880bbd)
- [2015/2016](https://exampapers.ed.ac.uk/items/2b8f5c58-8181-4346-938d-4b693e90d360)
- [2014/2015](https://exampapers.ed.ac.uk/items/d16786d7-7342-43bf-ace9-3e9e4a3cdffc)
- [2013/2014](https://exampapers.ed.ac.uk/items/c9bae40c-82db-4edd-9405-1cce07bf22e3)

<a id="analysis-pgbi11095"></a>
### Past Patterns, Current Risks and LLM Difficulty

| Aspect | Verified findings |
|---|---|
| Actual past question types | All six documents require students to design a Python/Linux sequence-analysis service with a meaningful biological purpose: the 2020/21-2023/24 papers centre on BLAST, while 2024/25-2025/26 switch to the sequence-conservation analysis service `conservED`. Input validation, data flow, tool invocation, outputs and prevention of user errors remain central throughout. |
| Degree of repetition | **Very high repetition of the question template.** The BLAST essay prompts in 2022/23 and 2023/24 are almost word-for-word repeats; the overall service-design logic is also highly consistent across 2020/21-2023/24. The 2024/25 and 2025/26 papers then use the same conservation-analysis product scenario in consecutive years, with the latter again examining it from three perspectives: the user, the programmer/data flow, and Python implementation. |
| Past examination formats | The 2020/21 paper was open-book during the pandemic; 2021/22 used a four-hour window (three hours recommended for answering + one hour for submission); only the essay question is publicly available for 2022/23 and 2023/24. These do not establish that the full papers in those years, or the current examinations, are open-book. |
| What can be anticipated for 2026/27? | **The skills framework, not the specific biological tool.** Service design, inputs and outputs, error prevention and integrated Python/Linux questions are likely to remain important, but the current official website explicitly specifies two in-person closed-book components. The reference-checking strategy used for pandemic-era papers cannot simply be carried over. |
| Main risks | Equal emphasis on integrated Python/Linux application and closed-book system design; both assessment components must be passed separately, so a higher overall mark cannot compensate for failing one. |
| **LLM difficulty** | **3.5/5.** Equal emphasis on integrated Python/Linux application and closed-book system design; both assessment components must be passed separately, so a higher overall mark cannot compensate for failing one. |

<a id="course-pgbi11003"></a>
## [PGBI11003 Statistics and Data Analysis](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11003.htm)

- **Credits and semester:** 20 credits, Semester 1, compulsory.
- **Official notional workload:** Total Hours **200** (lectures 41; supervised practicals/workshops 16; revision sessions 6; programme-level teaching 4; directed/independent study 133).
- **Course content:** Probability distributions, experimental design, linear models/ANOVA, generalised linear models, analysis in R and interpretation of results. The aim is to enable students to select and explain suitable statistical methods for biological data.
- **Official 2026/27 assessment:** The formal `Assessment` section states 100% coursework, comprising Class Test 1 (45%) and Class Test 2 (55%). However, the `Summary` on the same page mentions two assignments, a quiz and an open-book exam. These statements conflict, and this guide does not guess which the University intends. Once enrolled, students should follow the current cohort's Learn materials, assessment brief and written clarification from the Course Organiser.

<a id="papers-pgbi11003"></a>
### Past Papers

There are 14 archive entries: 3 PDFs and 11 marked `Paper Unavailable`. The readable papers cover only 2021/22-2023/24 and belong to an earlier assessment system; they do not directly represent the two class tests for 2026/27.

#### [2023/2024: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/b0902e22-9d3b-4c78-a99d-388fcb8965d4/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/8daebd64-b237-4be6-adb5-998e9c916ab3)

#### [2022/2023: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/59bcaa75-4dab-4268-9d4a-bdc15461ebba/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/c3636a6b-9017-42c9-9aac-3dfac6ede45d)

#### [2021/2022: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/572e6fd9-42e4-4db8-9b2e-c0712b8f544a/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/527f146e-8284-4916-8794-381a094fbcea)

#### Paper Unavailable Entries

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
### Past Patterns, Current Risks and LLM Difficulty

| Aspect | Verified findings |
|---|---|
| Shared core of the three past papers | Probability/distributions **3/3**, linear models and ANOVA **3/3**, interpretation of R output or code **3/3**; GLMs/count data **2/3**, experimental design **2/3**. |
| Degree of repetition | **A stable knowledge framework, with changing data and questions.** No complete major question was found repeated word for word. What recurs is the process of identifying the design, choosing a model, reading R output and interpreting the conclusions. |
| Past paper format | All three papers require answers to every major question and allow R code/output to support answers; answers were submitted electronically. |
| Relevance to 2026/27 | The content remains useful, but the formal assessment section now specifies class tests weighted at 45% + 55%. Past papers indicate the depth of statistical knowledge required, but **cannot reliably predict the current duration, open-/closed-book rules or number of questions**. |
| Main risks | Probability, linear models, ANOVA/GLMs and interpretation of R must all be mastered; published assessment information is contradictory, so the current cohort's guidance must be checked. |
| **LLM difficulty** | **4.0/5.** Probability, linear models, ANOVA/GLMs and interpretation of R must all be mastered; published assessment information is contradictory, so the current cohort's guidance must be checked. |

<a id="course-pgbi11114"></a>
## [PGBI11114 Research Proposal (Bioinformatics)](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11114.htm)

- **Credits and semester:** 10 credits, Semester 2, compulsory.
- **Official notional workload:** Total Hours **100** (seminars/tutorials 3; programme-level teaching 2; directed/independent study 95).
- **Official assessment:** 100% coursework: a research proposal of approximately six pages, with a maximum of seven. An exact-code search of the central examination paper archive returns 0 entries.
- **Course requirements:** Formulate a clear research question, explain its background and significance, devise feasible methods, data analysis, a timetable and risk/ethics arrangements, and justify the project's suitability for independent MSc research.

<a id="analysis-pgbi11114"></a>
### LLM Difficulty and Risks to Marks

- The main risk is that **one submission accounts for 100% of the mark**: weaknesses in topic scope, use of supervisory feedback, methodological feasibility or argumentation in English cannot be offset by other components.
- **LLM difficulty: 3.0/5.** The focus is on defining the question, methodological feasibility and argumentation in English; a single research proposal determines the entire mark.

<a id="course-pgbi11034"></a>
## [PGBI11034 MSc Dissertation (Bioinformatics)](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11034.htm)

- **Credits and timing:** 60 credits, Block 5 (Semester 2) onwards; a mark of at least 50% is required for this course.
- **Official notional workload:** Total Hours **600** (programme-level teaching 12; directed/independent study 588). DRPS does not list supervision hours separately; this does not mean there is no supervision.
- **Official assessment:** 100% coursework, with no centrally scheduled formal written examination; an exact-code search of the paper archive returns 0 entries. At 60 credits, this is the single largest component of the year's assessment.
- **Project format:** Projects may be university-based or industry-linked, with a company helping to propose or supervise the work. However, an industry project is one way of undertaking this dissertation, **not an internship that replaces PGBI11034 or grants exemption from it**. Availability varies annually; projects must be approved by the Programme Director and assessed against this course's required deliverables.

<a id="analysis-pgbi11034"></a>
### LLM Difficulty, Supervision and Suggested Directions

- For ML/AI4Science/large-model work, Informatics academics may be involved in supervision, but project affiliation, eligibility of the principal supervisor, data compliance and assessment still require approval from the Bioinformatics Programme. The most practical arrangement is a main project with a clear biological question and data, supported by a methods supervisor or co-supervisor from the School of Informatics.
- A recommended AI/ML project combines a reproducible biological data pipeline, clear baselines and rigorous validation. Avoid producing only a generic large-model demo, as this would lack a sufficiently developed biological research question and basis for evaluation.
- **LLM difficulty: 4.0/5.** Independent research, dependence on data and supervision, writing in English and long-term progress management all combine; the overall workload of 60 credits should not be underestimated.

---

<a id="semester-1-electives"></a>
# Semester 1 Electives

<a id="course-bich11011"></a>
## [BICH11011 Quantitating Drug Binding](https://www.drps.ed.ac.uk/26-27/dpt/cxbich11011.htm)

- **Credits and semester:** 20 credits, Semester 1; taking this course alone fulfils the requirement for exactly 20 credits in S1.
- **Official notional workload:** Total Hours **200** (lectures 8; seminars/tutorials 15; supervised practicals/workshops 16; summative assessment 6; programme-level teaching 4; directed/independent study 151).
- **Official assessment:** 100% coursework. ICA1 is a presentation worth 30%; ICA2 is an extended practical laboratory report worth 70%. There is no centrally scheduled formal written examination.
- **Course overview:** Understand drug-target binding from a biophysical perspective, learn common methods for measuring affinity and kinetics, and experimentally obtain and analyse binding parameters widely used in industry, such as the dissociation constant `Kd`. The course leans towards drug discovery, experimental biophysics and quantitative pharmacology rather than pure computing or machine learning.
- **Course selection advice:** At 20 credits, with a heavily weighted extended laboratory report, this suits students willing to undertake experiments, presentations and long reports. Having no written exam does not mean a light workload.

### Past Papers

An exact-code search for `BICH11011` in the official examination paper archive returns 0 entries, consistent with the course page's 100% coursework assessment. There are therefore no formal written examination papers to list.

<a id="analysis-bich11011"></a>
### Assessment Structure and LLM Difficulty

| Aspect | Assessment |
|---|---|
| Closed-book assessment? | No centrally scheduled written examination; 30% presentation + 70% extended practical laboratory report. |
| Predictability | The required types of output are clear, but there are no past papers from which to judge question reuse; 70% rests on one long laboratory report. |
| Main risks | Requires quantitative biophysics, experimental analysis and a long report; the 20-credit size and heavily weighted laboratory report concentrate the workload. |
| **LLM difficulty** | **3.5/5.** Requires quantitative biophysics, experimental analysis and a long report; the 20-credit size and heavily weighted laboratory report concentrate the workload. |

<a id="course-infr11211"></a>
## [INFR11211 Applied Machine Learning](https://www.drps.ed.ac.uk/26-27/dpt/cxinfr11211.htm)

- **Credits and semester:** 20 credits, Semester 1, offered by the School of Informatics; you may take at most one of this course and `MATH11205`.
- **Official notional learning hours:** Total Hours **200** (lectures 20; seminars/tutorials 4; supervised practicals/workshops 4; summative assessment 2; programme-level teaching 4; directed/independent learning 166). Additional Class Delivery separately states approximately 30 hours (20 hours of pre-recorded material + 10 live Q&A sessions); how this maps onto the 28 hours in the structured direct-teaching categories is not fully explained.
- **Official assessment:** Written exam 60% + coursework 40%; the course page lists a 120-minute exam in the December main diet. The official course examination guidance states that, from 2022 onwards, the exam is closed-book, lasts 2 hours and requires answers to two of three questions; no official solutions are available.
- **What the course covers:** Core machine learning topics, including supervised learning, unsupervised learning, model selection and evaluation. It requires both the use of practical tools and the correct formulation of problems using statistical and mathematical principles. Compared with `MATH11205`, it carries more credits and places greater weight on theory and the examination.
- **Prerequisites and risks:** The DPT explicitly requires linear algebra, basic calculus, statistics and programming experience, and recommends contacting the Programme Director first. This course alone fills the 20-credit S1 allocation, and the 60% written exam makes the final mark more dependent on examination performance.
- **Additional official resources:** [AML public course homepage](https://groups.inf.ed.ac.uk/teaching/aml/), [examination guidance and past advice](https://groups.inf.ed.ac.uk/teaching/aml/exam/), [official Exam Tips PDF](https://groups.inf.ed.ac.uk/teaching/aml/slides/W11_Exam.pdf). Old `IAML` papers may cover some related material, but they are not papers for `INFR11211` and are therefore excluded from the list below.

<a id="papers-infr11211"></a>
### Past Examination Papers

4 entries in total; all 4 papers are available to download.

#### [2025/2026: Examination Paper PDF](https://exampapers.ed.ac.uk/bitstreams/b36a42f4-3d95-4d2c-b1e4-83131e407dbd/download)

- [University archive record](https://exampapers.ed.ac.uk/items/d1e637d8-2b21-4c53-a9b4-0a3e6e81cf6a)

#### [2024/2025: Examination Paper PDF](https://exampapers.ed.ac.uk/bitstreams/aee21aaf-106d-4b04-b5a8-d6b314913ebc/download)

- [University archive record](https://exampapers.ed.ac.uk/items/cfd90df8-1908-4df0-9694-ef1a9279f185)

#### [2023/2024: Examination Paper PDF](https://exampapers.ed.ac.uk/bitstreams/6d73bf04-e8e6-46ab-9b5b-5e979863c587/download)

- [University archive record](https://exampapers.ed.ac.uk/items/3c390c56-ed68-48fa-95e4-fe7166b622bd)

#### [2022/2023: Examination Paper PDF](https://exampapers.ed.ac.uk/bitstreams/eceb10e4-8cd0-406b-8e33-12d0ee969baa/download)

- [University archive record](https://exampapers.ed.ac.uk/items/765e0039-a487-4f94-b7ae-363300d43284)

<a id="analysis-infr11211"></a>
### Question-by-Question Review, Coverage Boundaries and Difficulty Assessment

**Bottom line:** The four official `INFR11211` papers contain 24 half-questions worth 300 marks in total. No question was found to fall outside the main teaching modules in the current public course materials, but "within the syllabus" does not mean "the same every year". Four broad question families, `PCA`, clustering, evaluation and regression/trees, account for **190/300 marks (63.3%)**. The remaining third or so rotates among Naive Bayes, logistic regression, neural networks, recommender systems, non-linear dimensionality reduction, ethics, fairness, semi-supervised learning and active learning.

Two different meanings of "scope" need to be distinguished:

- **Relative to the current course syllabus:** Questions from all four years map to modules in the latest publicly available 2025 lecture blocks. There is no sign of old `IAML` material such as SVMs, Nearest Neighbours or Gaussian Mixture Models being included.
- **Relative to earlier past papers: the scope does expand.** Both 2023/24 and 2024/25 introduced entire topics absent from earlier `INFR11211` papers; memorising old papers alone would leave marks uncovered. Of the papers analysed, 2025/26 had the most repetition, but this does not guarantee that the following year will continue to reuse material.

As of 2026-08-14, the University's detailed public AML course site was still the 2025 version. The analysis below uses the 18 lecture blocks, 4 tutorials and 5 labs in the [current public Schedule](https://groups.inf.ed.ac.uk/teaching/aml/schedule/) as the latest verifiable scope; Learn and the materials for the 2026/27 cohort take precedence once that year's teaching begins.

#### Review of All 24 Half-Questions

Each paper contains three 25-mark questions, of which candidates answer two. The table still counts all 75 marks on each paper so that examination coverage can be compared.

| Academic year | Question | Marks | Content actually assessed | Compared with earlier official papers |
|---|---|---:|---|---|
| 2022/23 | Q1(a) | 12 | Decision boundaries and parameters of decision trees and logistic regression, the effect of outliers, and comparison of model suitability | First `INFR11211` paper; used as the baseline |
| 2022/23 | Q1(b) | 13 | SSE for linear/quadratic polynomial regression, limitations of SSE, regression tree training and tree ensembles | Baseline |
| 2022/23 | Q2(a) | 13 | PCA true/false statements, 80% explained variance, the elbow criterion, principal components, projected variance and reconstruction error | Baseline; reused several times subsequently |
| 2022/23 | Q2(b) | 12 | Confusion matrix, accuracy, precision, recall, F-measure, class imbalance and PR curve | Baseline; reused several times subsequently |
| 2022/23 | Q3(a) | 12 | Geometric properties of K-means and single linkage, complete-linkage dendrogram and selection among random initialisations | Baseline; reused several times subsequently |
| 2022/23 | Q3(b) | 13 | Naive Bayes assumptions, feature representation and limitations; comparison with neural networks; transparency in ART; algorithmic fairness | Baseline; the ethics question has not subsequently reappeared in full |
| 2023/24 | Q1(a) | 12 | Regression tree model selection, impurity and information gain, leaf-node values, categorical features and missing values at test time | Regression trees appeared in 2022; numerical impurity calculations and handling missing values were new question formats |
| 2023/24 | Q1(b) | 13 | Tree predictions by region, node accuracy, confusion matrix, four metrics and choice of metric | Repeated the evaluation module; established a template reused in 2025 |
| 2023/24 | Q2(a) | 13 | Semi-supervised learning, the active learning workflow and query methods, tree ensembles and logistic regression boundaries | Approximately 9 marks on semi-supervised/active learning covered modules not previously assessed |
| 2023/24 | Q2(b) | 12 | PCA on the unit circle, principal components/explained variance/lossless representation, PCA followed by a threshold classifier, 80% variance and dataset comparisons | PCA was a frequent module, but the scenarios and reasoning tasks changed |
| 2023/24 | Q3(a) | 12 | Generative versus discriminative models, multiclass Naive Bayes with continuous features, missing values and logistic regression | Repeated Naive Bayes/logistic regression, adding multiclass classification and missing values |
| 2023/24 | Q3(b) | 13 | Single-linkage dendrogram, constructing data that distinguish K-means from single linkage, and explaining t-SNE | Repeated clustering; the 3 marks on t-SNE introduced a new module |
| 2024/25 | Q1(a) | 12 | Linear regression, RBF basis expansion, regression assumptions, encoding categorical variables and interpreting weights | Repeated regression; RBFs and more comprehensive data representation questions were new |
| 2024/25 | Q1(b) | 13 | Complete-linkage dendrogram, cutting it into three clusters, comparison with single linkage and constructing a counterexample for K-means | Substantial overlap with the 2022/2023 clustering questions |
| 2024/25 | Q2(a) | 12 | Parameter counts and training for fully connected networks, CNNs, data collection bias and architectures for video/sequences | Neural networks had appeared only in a short-answer question in 2022; most tasks here were new |
| 2024/25 | Q2(b) | 13 | PCA principal components/projected variance/reconstruction error; F1, TPR/FPR and ROC | Repeated PCA/evaluation; plotting an ROC curve was a new question format |
| 2024/25 | Q3(a) | 13 | Matrix factorisation for recommender systems, loss, regularisation, latent structure and cold start | **The entire half-question covered a module not previously assessed** |
| 2024/25 | Q3(b) | 12 | One-/two-tailed hypotheses, t-statistic, judging significance and Rand Index | **The entire half-question consisted of previously unassessed tasks; all 25 marks in Q3 were new** |
| 2025/26 | Q1(a) | 12 | Differences between regression and classification trees, impurity formulae and calculations, overfitting, comparison with linear regression and the feasibility of gradient descent | Regression trees were frequent; the 4 marks on impurity and the model comparison can be traced to 2023, while other follow-up questions took different angles |
| 2025/26 | Q1(b) | 13 | Two successive PCA operations, the objective and centring, whether PCA necessarily reduces dimensionality, PCA classification boundaries, 80% variance and the elbow criterion | **At least 10/13 marks have clear templates in earlier papers** |
| 2025/26 | Q2(a) | 13 | Logistic regression model/NLL/assumptions, decision boundaries, predictions, weight scaling and multiclass linear models | A frequently assessed foundational module; the 3 marks on multiclass classification were a new follow-up question |
| 2025/26 | Q2(b) | 12 | Complete-linkage dendrogram, cutting it into three clusters, comparison with single linkage and Lance-Williams coefficients | **The first 9/12 marks closely reused 2024 material; the final 3 marks were new** |
| 2025/26 | Q3(a) | 13 | Comparing neural networks with trees, drawing a network, activation functions, forward pass, accuracy and changing parameters to improve performance | The module was not new, but a full hand-calculation and parameter-adjustment template had not appeared before |
| 2025/26 | Q3(b) | 12 | Tree regions in a medical scenario, node predictions, confusion matrix, four metrics and reducing false negatives | **The first 9/12 marks closely reused 2023 material; the final 3 marks were new** |

#### Current Course Modules and the Boundaries of Four Years of Papers

| Current public teaching module | Actual coverage in four years of official papers | Notable areas not yet explicitly assessed in the four papers |
|---|---|---|
| Introduction to ML / Classification | Classification or model comparison scenarios in all four years | Detailed numerical derivations for LDA/QDA have not appeared directly |
| Naive Bayes / Logistic Regression | NB: 2022, 2023; logistic regression: 2022, 2023, 2025 | Numerical softmax calculations have not appeared directly; 2025 only asked for descriptions of two multiclass methods |
| Linear Regression / Decision Trees | Regression or tree questions in all four years; trees directly assessed in 2022, 2023 and 2025 | A complete derivation of closed-form least squares has not appeared |
| Representing Data / EDA / PCA | PCA **4/4**; feature types, categorical encoding or missing values appeared in 2022-2024 | General plotting principles and most EDA visualisations have not had standalone questions |
| Optimisation / Generalisation | Tree ensembles, model training, regularisation, overfitting and gradient descent were distributed across the four years | No complex gradient derivations required; no complete standalone calculation questions on bias-variance or cross-validation |
| Evaluation / Model Selection | Basic classification metrics **4/4**; a formal t-test only in 2024 | MAE, correlation, `R²`, multiclass evaluation and the full cross-validation workflow have not been directly assessed |
| Clustering / Non-linear DR | Clustering **4/4**; t-SNE only in 2023 | Kernel PCA, MDS, Isomap, LLE and UMAP have not appeared directly in any of the four papers |
| Recommender Systems / Neural Networks | Recommender systems only in 2024; NN in 2022, 2024 and 2025 | Transformers have not been directly assessed; RNNs/sequence models were touched on only indirectly through the 2024 video scenario |
| Ethics and Fairness / Further Topics | Ethics and fairness in 2022; semi-supervised/active learning in 2023; data collection bias in 2024 | Specific topics such as label propagation and entropy minimisation have not been named directly |

There is therefore **no evidence of an external algorithm suddenly being examined without being taught on the course**. The real risk is that a less frequently assessed detail in the slides may be selected for the first time. Not having appeared before does not put a topic outside the syllabus, particularly `Kernel PCA / MDS / Isomap / LLE / UMAP`, regression metrics, cross-validation and Transformers.

#### How Many Marks Come from the Stable Question Families?

The four broad question families that appeared in all four consecutive years are defined here as `PCA`, `clustering`, `evaluation` and `regression/decision trees`. These are not identical repeat questions, but they represent the most consistent return on revision effort.

| Academic year | Four stable question families / 75 | Share of the whole paper | Question-family coverage / 50 when choosing the two questions with the most stable-family content |
|---|---:|---:|---:|
| 2022/23 | 53 | 70.7% | 41 |
| 2023/24 | 47 | 62.7% | 37 |
| 2024/25 | 41 | 54.7% | 38 |
| 2025/26 | 49 | 65.3% | 37 |
| **Total/average** | **190/300** | **63.3%** | **Average 38.25/50 (76.5%)** |

The category totals are: for 2022/23, decision trees 3 + Q1(b) 13 + Q2 25 + Q3(a) 12 = 53; for 2023/24, Q1 25 + Q2(b) 12 + the clustering part of Q3(b) 10 = 47; for 2024/25, Q1 25 + Q2(b) 13 + Rand Index 3 = 41; for 2025/26, Q1 25 + Q2(b) 12 + Q3(b) 12 = 49.

This is **question-family coverage**, not an expected mark: knowing these modules does not automatically earn all the associated marks. However, the two-out-of-three structure does allow candidates to read the paper and avoid the least familiar question. Across the four years, after choosing the two most familiar questions, approximately 74%-82% of the available marks came from the four stable question families. This shows both the value of past papers and the importance of question-selection strategy.

#### Have New Papers Gone Beyond Earlier Papers?

| New paper | Clear additions compared with earlier official `INFR11211` papers | Conclusion |
|---|---|---|
| 2023/24 | At least 9 marks on semi-supervised/active learning; 3 marks on t-SNE; new question formats such as missing values | At least 12 marks concerned named modules/tasks that had not appeared before |
| 2024/25 | Recommender systems 13 marks; hypothesis testing and Rand Index 12 marks; additional material on RBFs, CNNs/video and ROC | **All 25 marks in Question 3 covered modules absent from the previous two papers** |
| 2025/26 | No entirely new major lecture block, but new follow-up questions on Lance-Williams, multiclass classification, NN hand calculations and parameter adjustment | The most predictable year at the level of major modules, although the details were still not wholly repeated |

The crucial counterexample is 2024/25: anyone who had defined their revision scope solely from the 2022/23 and 2023/24 papers would have left all of Q3 unprepared. The good news is that Q3 could be avoided; the bad news is that Q1 and Q2 still contained new details such as RBFs, CNNs/video and ROC, so there was no completely safe pair consisting entirely of old templates.

#### Near-Repeats of Earlier Questions

| Years compared | Repeated content | Extent |
|---|---|---|
| 2022/23 and 2025/26 | Whether stepwise PCA is equivalent to direct dimensionality reduction, whether PCA necessarily reduces dimensionality, and selecting principal components for 80% explained variance and comparing this with the elbow criterion | **Very strong**: together with the 2023 PCA classification template, at least 10/13 marks in 2025 Q1(b) can be traced to earlier questions |
| 2022/23 and 2024/25 | Finding the first principal component, projected variance and reconstruction error | **Strong**: the same calculation template with different data points |
| 2023/24 and 2025/26 | Tree classification regions in a medical scenario, node predictions, confusion matrix and accuracy/precision/recall/F-measure | **Very strong**: the first 9/12 marks in 2025 Q3(b) followed the same structure, with a changed final sub-question |
| 2024/25 and 2025/26 | Distance matrix, complete-linkage dendrogram, cutting into three clusters and comparison with single linkage | **Very strong**: the first 9/12 marks in 2025 Q2(b) followed the same template, with a changed matrix and final sub-question |
| 2023/24 and 2024/25 | Constructing two-dimensional data that distinguish the behaviour of K-means and single linkage | **Strong**: the same objective, with a more comprehensive version in 2023 |
| 2023/24 and 2025/26 | Definition and numerical calculation of regression tree node impurity | **Moderately strong**: the same core method, with different data and additional conceptual questions |

Using the relatively strict criterion of "closely reused question structure", at least **28 marks** across the PCA, clustering and evaluation half-questions in 2025/26 alone can be matched to earlier templates. This did provide a revision advantage approaching that of having correctly identified the likely examination topics, but no entire main question was copied word for word and number for number, and this was not an examination leak.

#### Official Scope Statements and Actual Question-Setting

- The [official Course Information](https://groups.inf.ed.ac.uk/teaching/aml/about/) states that lecture slides, tutorial questions and labs jointly define the examination scope. This sets the outer boundary; it does not mean that all modules are equally likely to appear.
- The four years of actual papers show clearly unequal frequencies: PCA, clustering, evaluation and regression/trees form the frequently assessed core; recommender systems, non-linear dimensionality reduction, ethics and semi-supervised/active learning function more as rotating modules.
- Nearest Neighbours, SVMs and Gaussian Mixture Models in old `IAML` papers are not part of the current AML course; none appeared in the four official `INFR11211` papers either.
- The official 2025 Exam Tips do not provide future examination topics or answers, but explicitly state that complex derivations and code-writing are not required, and calculations are usually less demanding than in tutorials. Showing intermediate steps helps secure partial credit.

#### Difficulty and the Prospects of a High Mark

| Dimension | Assessment | Reason |
|---|---|---|
| Predictability of question types | **Relatively high, but not comprehensive** | The four major question families account for approximately 63% of the whole paper; 2025 had several near-repeats, while 2024 demonstrated that entire new topics can be introduced |
| Difficulty of mathematical derivations | Low to moderate | Mainly formulae, short calculations, diagrams and explanations; the official guidance explicitly does not emphasise complex derivations |
| Breadth of knowledge | Moderate to high | Less frequent modules rotate, and the slides still contain several subtopics not directly assessed in four years |
| Time pressure | Moderately high | 120 minutes for two 25-mark questions, each containing multiple sub-questions worth 1-5 marks |
| Closed-book memory demands | Moderate to high | Notes and calculators are not allowed; definitions, formulae and frameworks for comparison need to be familiar |
| Opportunities for method marks | Relatively high | Questions are broken into detailed subparts, and the official guidance explicitly recommends showing working to receive partial credit |

**Qualitative assessment of the papers themselves: moderately high difficulty.** For students who already know linear algebra, probability, statistics and basic ML, the difficulty is approximately `3/5`; for those studying machine learning systematically for the first time, the breadth required in a closed-book exam is closer to `4/5`. The papers themselves support the conclusion that **choice of questions, stable question families and some repeated templates make the exam relatively amenable to preparation, particularly in 2025/26.** However, there is no public marking scheme, mark distribution or reliable current student sample, so "repeated question types" cannot be taken to mean "generous marking" or "a reliably high mark".

#### LLM Difficulty Assessment

**4.0/5.** Broad coverage, 20 credits and a 60% closed-book exam; past papers help with revision but cannot replace coverage of the full syllabus.

<a id="course-math11205"></a>
## [MATH11205 Machine Learning in Python](https://www.drps.ed.ac.uk/26-27/dpt/cxmath11205.htm)

- **Credits and semester:** 10 credits, Semester 1; students may take at most one of this course and `INFR11211`, so those choosing it must also select another of the remaining 10-credit S1 courses.
- **Official notional workload:** Total Hours **100** (lectures 14; supervised practicals/workshops 15; summative assessment 1.5; programme-level teaching 2; directed/independent study 67). These components total only 99.5 hours; the official page does not explain the 0.5-hour discrepancy.
- **Official assessment:** 50% written exam + 50% coursework. Coursework comprises an applied machine-learning project and weekly workshop assignments. The 2026/27 course page also displays "No Exam Information", which usually means that the year's specific examination arrangements have not yet been published; it does not override the stated 50% written exam.
- **Course overview:** Practise machine-learning workflows in Python alongside the necessary theory, focusing on applying models to real data and understanding training and evaluation, rather than simply calling library functions.
- **Prerequisites and risks:** A grounding in Python, probability and statistics is required. The DPT also requires students choosing machine learning to have experience in linear algebra, basic calculus, statistics and programming. The 50/50 assessment split is more balanced than AML's, but ongoing workshop assignments spread the workload throughout the semester.

<a id="papers-math11205"></a>

### Past Papers

There are 10 entries: 6 PDFs and 4 marked Paper Unavailable. Main and Resit papers are listed separately.

#### [2025/2026 Main: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/8813d318-3d69-4a8f-a8c5-334ae2db7f0a)

- The University retains the metadata but provides no downloadable PDF.

#### [2024/2025 Main: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/676299f6-cd54-41ec-a7fe-fedf9c83986f/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/ed35f15b-f221-407c-bf25-a3c4d1a9f97c)

#### [2024/2025 Resit: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/d2bd1f0e-b36b-45fe-b059-d524eebba97a)

- The University retains the metadata but provides no downloadable PDF.

#### [2023/2024 Main: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/08e229b5-9a4f-418c-8aa7-3043a5de6473/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/3a68791a-6f08-4320-a9ec-e7db6f2bddac)

#### [2023/2024 Resit: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/2189f49e-cc2d-4c9a-b904-a9cf19caa535)

- The University retains the metadata but provides no downloadable PDF.

#### [2022/2023 Main: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/2025da29-0a93-44de-8320-4a5357574f5e/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/7c085717-d7c6-487c-bf03-68f277a11752)

#### [2022/2023 Resit: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/a19253f0-4d7f-4449-9913-83f73fba6c5e)

- The University retains the metadata but provides no downloadable PDF.

#### [2021/2022 Main: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/f569e45f-8a63-45a2-a818-b769223a89b1/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/faddafa6-4866-4ccb-b8dd-c21e8c9a6159)

#### [2020/2021 Main: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/fac81fab-0f22-4b79-ae96-5ce08b012637/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/eb2b9dc8-1a2d-4d5d-b27c-4b8a9bea9c5f)

#### [2019/2020 Main: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/76e65955-d56f-48f3-b4df-36c843ede5cf/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/cf7a50a7-e2e4-4716-83f2-7c0157c032d9)

<a id="analysis-math11205"></a>
### Past Patterns, Current Risks and LLM Difficulty

| Aspect | Findings from the six readable papers |
|---|---|
| Frequently examined topics | Regression/regularisation **6/6**, model evaluation and cross-validation **6/6**, preprocessing/encoding **5/6**, neural networks **4/6**, decision trees **3/6**; clustering, SVMs/kernels and PCA each **2/6**. |
| Degree of repetition | Method families recur frequently, but no complete paper or major question was found repeated word for word; the data, calculations and subjects of comparison change. Regression, evaluation and preprocessing are predictable topics, but specific answers are not. |
| Answering rules | All six papers require every question to be answered. The 2019/20-2021/22 papers used remote/special arrangements; 2022/23-2024/25 explicitly permitted **3 double-sided A4 sheets of notes (6 sides) + a scientific calculator**. The 2024/25 examination lasted 90 minutes. |
| Current limitations | The 2026/27 page still states 50% written exam + 50% coursework, but the year's open-/closed-book rules and rules on permitted notes have not been published. Topics such as SVMs and neural networks in past papers cannot automatically be treated as part of the current syllabus. |
| Entry restrictions | The course page lists `MATH08065 Computing and Numerics` as a prerequisite. The Bioinformatics DPT only says that students may select the course after discussing their background with the Programme Director; **inclusion in the DPT does not mean prerequisites have automatically been waived**. |
| **LLM difficulty** | **4.5/5.** Difficult and not recommended as an elective. This is not an easy Python tools course: mathematical understanding, programming, weekly assignments and a project run alongside one another; the written exam accounts for 50%. |

<a id="course-pgbi11051"></a>
## [PGBI11051 Information Processing in Biological Cells](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11051.htm)

- **Credits and semester:** 10 credits, Semester 1.
- **Official notional workload:** Total Hours **100** (lectures 20; summative assessment 3; programme-level teaching 2; directed/independent study 75). The official information does not further divide the three hours of summative assessment into the two-hour examination and other components.
- **Official assessment:** 50% written exam + 50% coursework; the course page lists a 120-minute examination in the December main diet. Coursework comprises two in-course assessments, which may include problem-solving, discussion and short-answer questions.
- **Course overview:** Use information-processing, mathematical and computational modelling perspectives to understand how cells sense signals, store information, respond and adapt to their environment. The content connects cell biology, systems biology and quantitative models, and is generally more theoretically abstract than a typical wet-lab course.
- **Study advice:** Suits students interested in modelling living systems and the foundational ideas of AI4Science, but it is not a general AI/ML course. Start with the official [course introduction video](https://media.ed.ac.uk/media/Information+Processing+in+Biological+Cells/1_aumuua7w).

<a id="papers-pgbi11051"></a>

### Past Papers

There are 19 entries: 2 PDFs and 17 marked Paper Unavailable. Records from 2008/09 to 2009/10 were found through supplementary searches using the exact course title and former codes, including `P02377`, plus one VS1 record under `P02988`.

#### [2025/2026: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/85e50144-5dca-4b94-a5eb-2808ce782d18)

- The University retains the metadata but provides no downloadable PDF.

#### [2024/2025: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/4b2e6565-544a-4c61-a544-be08d1b3777b)

- The University retains the metadata but provides no downloadable PDF.

#### [2023/2024: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/76fe2ee2-bdb3-48eb-87f6-69c3cf1acd63)

- The University retains the metadata but provides no downloadable PDF.

#### [2022/2023: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/ba3d7ea7-bcff-4890-bec2-096d21955542)

- The University retains the metadata but provides no downloadable PDF.

#### [2021/2022: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/6b78f529-5d0a-456a-b361-bc751efdb128)

- The University retains the metadata but provides no downloadable PDF.

#### [2020/2021: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/77a2038a-ab57-4fb8-8e34-23ecb7f6a3f3)

- The University retains the metadata but provides no downloadable PDF.

#### [2019/2020: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/abaf902f-a4a8-4504-a11c-d88a79e4b532)

- The University retains the metadata but provides no downloadable PDF.

#### [2018/2019: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/019775d3-5b5c-4e1e-a4df-798b27bb15dd)

- The University retains the metadata but provides no downloadable PDF.

#### [2017/2018: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/bd86fbf7-7aaf-4d53-952d-546e360f87cb)

- The University retains the metadata but provides no downloadable PDF.

#### [2016/2017: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/5241db28-a760-468e-8c0b-472b59791c1c)

- The University retains the metadata but provides no downloadable PDF.

#### [2015/2016: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/d9ea65d8-b0c8-453b-bdc6-f6e1deea3c56)

- The University retains the metadata but provides no downloadable PDF.

#### [2014/2015: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/5afd6964-0b5b-4ae1-9a3e-1cf5ab0ee7a8/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/befaf30e-6c76-4a7e-9839-d7384454efcf)

#### [2013/2014: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/d69654a1-f1d4-4883-aeab-25948a067eb6)

- The University retains the metadata but provides no downloadable PDF.

#### [2012/2013: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/3276faea-df87-4be5-8aaa-5fac22f65af4)

- The University retains the metadata but provides no downloadable PDF.

#### [2011/2012: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/1adacef8-8787-41c6-a069-a59cfc4ab88f/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/59a727e6-816a-4735-b89d-a32441c92011)

#### [2010/2011: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/2decf5b9-0ac9-45e5-8c2f-cfc43e180f6e)

- The University retains the metadata but provides no downloadable PDF.

#### [2009/2010: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/f5f55b3e-9d09-42b6-84dd-8457af302a41)

- The University retains the metadata but provides no downloadable PDF.

#### [2008/2009: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/6ed031f1-390e-423d-9a61-ff9a728b6551)

- The University retains the metadata but provides no downloadable PDF.

#### [2008/2009 VS1: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/5875a21c-9589-441f-ace0-7c03aa1b4bdf)

- The University retains the metadata but provides no downloadable PDF.

<a id="analysis-pgbi11051"></a>
### Past Patterns, Current Risks and LLM Difficulty

| Aspect | Findings from the two readable past papers |
|---|---|
| 2011/12 | Diffusion and molecular motors, Src/allostery and positive feedback, operons/transcription factors/epigenetics. |
| 2014/15 | Membrane transport and homeostasis, stoichiometric matrices/mass action, quorum sensing and stability feedback. |
| Degree of repetition | **Low.** Both papers test quantitative understanding of cellular information processing, but the specific systems and mathematical tools differ substantially, with no confirmed reuse of exact questions. |
| Answering rules | Both past examinations lasted three hours, required all three major questions to be answered and permitted only a non-programmable calculator. The current page states 120 minutes, so the old format can no longer be extrapolated directly. |
| Evidence gaps | Only 2 of the 19 archive entries have PDFs; the other 17 are unavailable. Among the electives with written exams covered in this guide, this course has relatively high uncertainty in its historical evidence. |
| **LLM difficulty** | **4.5/5.** Combines cellular mechanisms with quantitative modelling, demands substantial abstract reasoning and lacks recent readable past papers; not recommended as a way to reduce workload. |

<a id="course-pgbi11122"></a>
## [PGBI11122 Using R for Data Science](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11122.htm)

- **Credits and semester:** 10 credits, Semester 1.
- **Official notional workload:** Total Hours **100** (lectures 30; programme-level teaching 2; directed/independent study 68). The page does not list summative assessment hours separately; this should not be interpreted as zero hours.
- **Official assessment:** 50% written exam + 50% coursework; the course page lists a 120-minute examination in the December main diet. Coursework is an R data-analysis task. The written examination has three questions: Question 1 is compulsory, followed by a choice of Question 2 or Question 3.
- **Course overview:** Use R to handle complex biological data, with possible emphasis on statistical analysis, visualisation, regulatory genomics and machine-learning methods. It is more closely grounded in biological data than a general introduction to R.
- **Study advice:** Suits students seeking to develop R/Bioconductor data-analysis skills. Although it is only 10 credits, the examination and coursework each account for half the mark; it should not be assumed to be an easy software-skills course.

<a id="papers-pgbi11122"></a>
### Past Papers

There are 5 entries, all with downloadable papers.

#### [2025/2026: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/dc9b4717-f24c-4cae-b557-02ff8cd2759d/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/06e41d8b-eed7-4b78-bc06-2ae444b6a344)

#### [2024/2025: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/16e2a4eb-5b3e-4730-93cb-4e26629da56a/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/0d85e145-2fa9-4b6f-94f8-46e67d481d60)

#### [2023/2024: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/7531f742-1bf5-475d-9384-d776d8a8ebd1/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/415e8751-c1cb-41a8-9306-109d9c23b934)

#### [2022/2023: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/594a8edd-4a17-448f-a0a6-b9df33420cee/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/80dface5-6cd6-4d26-9689-70a0107c9ba0)

#### [2021/2022: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/21d7bdba-a320-4573-9438-7ccf931985c1/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/9a75bc90-b64e-4a2f-a6ae-dfbe9f604053)

<a id="analysis-pgbi11122"></a>
### Past Patterns, Current Risks and LLM Difficulty

| Aspect | Findings from the five readable papers |
|---|---|
| Frequently examined topics | R language semantics, analysis workflows/reproducibility, data objects and wrangling, and errors/packages/environments all appear in **5/5** papers; Shiny appears in **3/5**. |
| Clear reuse | "R is dynamically typed / functional / interpreted" appears in near-identical form in 2022/23, 2023/24 and 2025/26; fail-well errors recur in 2021/22 and 2024/25; Git, data frames/tibbles and R Markdown/Snakemake/pipelines appear repeatedly. |
| Answering rules | Question 1 is compulsory, followed by a choice of Question 2 or Question 3. The 2022/23 examination was open-book; from 2023/24 onwards, papers are in-person, two-hour examinations with no permission to bring notes stated on the paper. |
| Ease of preparation | **High.** Entire papers are not copied, but the core concepts and short-answer patterns are very stable; preparing accurate, concise English answers to common conceptual questions is clearly worthwhile. |
| **LLM difficulty** | **2.5/5.** Relatively straightforward to prepare for with an existing grounding in R; language semantics, data handling and reproducible workflows still require accurate understanding, and there is a written examination worth 50%. |

<a id="course-pgbi11129"></a>
## [PGBI11129 Biological Databases](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11129.htm)

- **Credits and semester:** 10 credits, Semester 1.
- **Official notional workload:** Total Hours **100** (lectures 10; supervised practicals/workshops 20; programme-level teaching 2; directed/independent study 68). The page does not list summative assessment hours separately; this should not be interpreted as zero hours.
- **Official assessment:** 50% written exam + 50% coursework; the course page lists a 120-minute examination in the December main diet. Coursework requires students to build a small, integrated biological database using R/Python scripts.
- **Course overview:** Learn database design, querying, data retrieval and biological database integration, applying scripting skills to real life-science data. This is neither simply memorising public databases nor a complete computer science course in database systems.
- **Study advice:** Useful for students seeking to develop skills in data engineering, bioinformatics pipelines, databases and back-end development; requires both conceptual understanding and practical implementation.

<a id="papers-pgbi11129"></a>

### Past Papers

There are 4 entries, all with downloadable papers. An exact-title search also returned `Bioinformatics 2 (P00861)` from 2004/05, but both the code and course title differ, so it was excluded as a false match.

#### [2025/2026: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/fc3c299b-29eb-4322-993f-777347aeee59/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/c4f02456-dbc1-4b18-a163-8687867d7797)

#### [2024/2025: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/f05dd3eb-b935-4ba5-8850-b9b4d8e8fcbb/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/0f8d09bb-1a90-4d44-827d-1c7b9cc957df)

#### [2023/2024: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/d1d5ffdd-f825-48ae-9ac6-1a81f5397c6b/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/88fc4ad0-b8e8-4b64-a044-e850671d1339)

#### [2022/2023: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/1b25ced1-d41b-45e7-8684-7bab392d1e87/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/af6ed110-864f-4fa1-9ed3-96e1491c8dc3)

<a id="analysis-pgbi11129"></a>
### Past Patterns, Current Risks and LLM Difficulty

| Aspect | Findings from the four readable papers |
|---|---|
| Frequently examined topics | Database models/design, APIs/web services, the semantic web/ontologies and use of biological databases all appear in **4/4** papers; XML/JSON appears in **3/4**. |
| Clear reuse | Questions on flat-file versus relational databases and REST/JSON/XML are highly similar in 2022/23 and 2024/25; Ensembl/BioMart/GO appear in consecutive years from 2023/24 to 2025/26. |
| Answering rules | Question 1 is compulsory, followed by a choice of Question 2 or Question 3. The 2022/23 examination was open-book; from 2023/24 onwards, it is an in-person, two-hour examination with no permission to bring notes stated on the paper. |
| Ease of preparation | **High.** Core terminology, database comparisons, APIs and public biological database examples remain stable; however, the 50% coursework component still requires students to build a small integrated database using R/Python. |
| **LLM difficulty** | **3.0/5.** Combines database concepts, APIs, biological databases and integration through scripting; past questions are relatively stable, but coursework requires practical implementation. |

---

<a id="semester-2-electives"></a>

# Semester 2 Electives

<a id="course-bilg11004"></a>
## [BILG11004 Next Generation Genomics](https://www.drps.ed.ac.uk/26-27/dpt/cxbilg11004.htm)

- **Credits and semester:** 10 credits, Semester 2; strongly recommended in the DPT.
- **Official notional workload:** Total Hours **100** (lectures 30; summative assessment 3; programme-level teaching 2; directed/independent learning 65). The course description mentions hands-on practicals, but the structured fields do not list supervised practical hours separately.
- **Official assessment:** Written exam 50% + coursework 50%; the course page lists a 120-minute exam in the April/May main diet. Coursework consists of a genome-quality assessment essay worth 50%; the remaining 50% is an essay-style written exam.
- **Course overview:** Covers second- and third-generation sequencing technologies, related bioinformatics algorithms, assembly and quality control, with an emphasis on interpreting genomic data from non-model organisms. It connects sequencing principles, data quality and analytical decisions.
- **Study advice:** This is one of the core subject-area courses for the MSc Bioinformatics. It suits students interested in genomics, NGS, assembly or sequence data analysis, but the essay-style exam still requires well-organised concepts and written argumentation.

<a id="papers-bilg11004"></a>
### Past Papers

16 entries in total: **11 valid PDFs and 5 marked Paper Unavailable**. A review of the paper contents found that the bitstream previously listed under 2020/21 was actually the 2011/12 paper for `PGBI11057 Bioinformatics Algorithms`, so it has been excluded. A working link is no substitute for checking the course code and title on the paper itself.

#### [2025/2026: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/27a79495-46d2-4c38-b908-5b184fb098d6/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/9744c93d-a9bd-4e58-8dc0-eb6f506665a1)

#### [2024/2025: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/17bed6bc-4a88-4022-92c7-f5caaa3fbf7c/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/ed97e87a-1596-4532-9d04-282cd9794682)

#### [2023/2024: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/889c0a7e-cc70-4e43-a64c-b2651546c1fe/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/b83e6226-ab8c-4bd5-ad27-7618f8a364ed)

#### [2022/2023: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/32a67a7b-a1d7-4439-ba5c-8a9f565f1fb6/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/e9c67551-208f-413b-a3ee-2c3c984f3fd1)

#### [2021/2022: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/90af23e9-419d-4b3b-baed-b261d6098d2b/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/fce4f2a0-c7b5-4635-afd2-8d2ca0fe1180)

#### [2020/2021: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/3c97d19d-c93d-4a23-a114-3db7bda4c83b)

- The current entry has no `BILG11004` PDF. An old bitstream once associated with this entry actually opens a 2011/12 paper for another course and has been excluded.

#### [2019/2020: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/83dccd63-e6fd-40dc-a7b7-f88b43f86113)

- The University retains the metadata but provides no downloadable PDF.

#### [2018/2019: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/40df4a68-b6f2-4b12-94ca-fe04b166aa8c/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/62dd5139-d98e-40fd-9469-fdce3b8e1604)

#### [2017/2018: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/642579dc-ca62-4d36-bbbf-566d45b21fb9)

- The University retains the metadata but provides no downloadable PDF.

#### [2016/2017: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/fdc0dd17-b12c-45c8-a644-7bf4c4c53e4b)

- The University retains the metadata but provides no downloadable PDF.

#### [2015/2016: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/6518ce78-9c15-4882-ad0e-fffea628377e)

- The University retains the metadata but provides no downloadable PDF.

#### [2014/2015: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/ebe88fe2-365e-48a4-89e6-8735efb244b8/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/96515d99-3a99-46bc-b647-d6f975eeda20)

#### [2013/2014: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/a124a96b-9683-4984-91c6-efb4ab441a56/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/cf924b2c-72a4-44b0-91c2-c7045e406769)

#### [2012/2013: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/b5d58054-44fe-446f-9f9d-7c100c08c9d8/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/8a71ece9-5a6a-4f5f-868d-0403882c6c60)

#### [2011/2012: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/fbe1a2b4-1d36-48e0-b116-f677617cc905/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/6b6dc088-5431-439d-a7cd-557f62409b25)

#### [2010/2011: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/6f1eadac-2b3c-4c16-ad5e-6acfe4ab71b2/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/9abe1ee9-a7fe-4e0e-9679-1f625b1daa4f)

<a id="analysis-bilg11004"></a>
### Past-Paper Patterns, Current Risks and LLM Difficulty Rating

| Dimension | Findings from 11 valid papers |
|---|---|
| Frequently examined topics | Genome assembly/graphs/k-mers **10/11**, sequencing quality and QC **10/11**, variation/population genomics **5/11**, read mapping **4/11**, transcriptomics **4/11**. |
| Recent format | The 2021/22 exam was open-book; from 2022/23 onwards, it has been a two-hour in-person exam requiring answers to two of three questions. Recent papers have consistently organised their main questions around sequencing strategies, assembly, QC and population genomics. |
| Degree of repetition | **Question families recur frequently, but verbatim reuse is uncommon.** de Bruijn graphs/k-mers, assembly quality, platform selection and population variation recur, but the species, data and scenarios used for argumentation change. |
| Ease of preparation | High. A fixed framework of "platform selection -> reads/QC -> assembly -> evaluation -> biological interpretation" is effective, but essay answers still need arguments tailored to the scenario. |
| **LLM difficulty rating** | **3.0/5.** There are many concepts in sequencing, assembly, QC and population genomics, and the essay exam requires structured argumentation; students with a weak biology background will need to fill in the gaps. |

<a id="course-bilg11016"></a>
## [BILG11016 Introduction to website and database design](https://www.drps.ed.ac.uk/26-27/dpt/cxbilg11016.htm)

- **Credits and semester:** 10 credits, Semester 2.
- **Official notional workload:** Total Hours **100** (lectures 20; programme-level teaching 2; directed/independent learning 78). The Additional Class Delivery section describes two hours per week as a lecture/workshop, but the structured fields classify all of this time as Lecture Hours.
- **Official assessment:** Coursework 100%. A critical essay on databases is worth 50%, and a public-facing MySQL database website project is worth 50%. There is no centrally scheduled formal written exam.
- **Course overview:** Teaches students to extract information from biological data, design relational databases, use MySQL and make databases available to users through a web interface. It focuses on applied database and website development for biologists or the public, rather than purely on front-end design.
- **Study advice:** Suits students seeking experience with databases, the web and projects they can showcase. Although there is no written exam, the two equally weighted submissions require critical writing and a complete, usable website respectively.

### Past Papers

A search of the official exam paper archive for the exact code `BILG11016` returned 0 entries, consistent with 100% coursework assessment, so there are no formal written exam papers.

<a id="analysis-bilg11016"></a>
### Assessment Structure and LLM Difficulty Rating

| Dimension | Assessment |
|---|---|
| Closed-book exam? | No; critical database essay 50% + MySQL database website 50%. |
| Predictability | The deliverables and weightings are clear, but there are no past papers; difficulty depends on database schemas, SQL, back-end/web integration and critical writing in English. |
| Main risks | Coursework does not end with "a page that runs". The 50% essay requires analysis of database design and its limitations; debugging the project may be time-consuming. |
| **LLM difficulty rating** | **3.0/5.** There is no central written exam, but SQL, relational modelling, website implementation and a critical essay all require effort; debugging time should not be underestimated. |

<a id="course-bite11004"></a>
## [BITE11004 Metagenomics](https://www.drps.ed.ac.uk/26-27/dpt/cxbite11004.htm)

- **Credits and semester:** 10 credits, Semester 2; the DPT states that this course cannot be taken on a "Class Only" basis.
- **Official notional workload:** Total Hours **100** (lectures 33; programme-level teaching 2; directed/independent learning 65). The Summary explicitly includes a field excursion, sampling and laboratory training, but the structured fields do not list fieldwork or supervised laboratory hours separately.
- **Official assessment:** Coursework 100%. Report 1 (summary and methods) is worth 30%, and the Contract Research Report is worth 70%. There is no centrally scheduled formal written exam.
- **Course overview:** Covers environmental sampling and experimental design, DNA extraction and amplification, NGS/qPCR, and metagenomic data analysis pipelines. The course connects wet-lab work, sequencing and computational analysis, culminating in a report written in the style of contract research.
- **Study advice:** Suits students interested in microbiome research, environmental genomics and metagenomics. With 70% concentrated in one substantial report, this is a course without a written exam but with a heavily weighted writing component.

### Past Papers

A search of the official exam paper archive for the exact code `BITE11004` returned 0 entries, consistent with 100% coursework assessment. Searching for the title "Metagenomics" returns identically named material under other codes or programmes; none of it has been included here.

<a id="analysis-bite11004"></a>
### Assessment Structure and LLM Difficulty Rating

| Dimension | Assessment |
|---|---|
| Closed-book exam? | No; Report 1 30% + Contract Research Report 70%. |
| Predictability | The two-report format is stable, but no past assignments are publicly available, so data quality, laboratory scheduling and marking standards cannot be assessed. |
| Main risks | The final report accounts for 70%; wet-lab work, sample data and team laboratory workflows may introduce delays beyond your control. The quality of scientific writing in English determines how high a mark you can achieve. |
| **LLM difficulty rating** | **3.0/5.** The course spans laboratory workflows, data analysis and scientific reporting. No central written exam does not mean an easy course, and the final report carries substantial weight. |

<a id="course-cmse11576"></a>

## [CMSE11576 Technology Entrepreneurship and Commercialisation](https://www.drps.ed.ac.uk/26-27/dpt/cxcmse11576.htm)

- **Credits and semester:** 10 credits, Semester 2.
- **Official notional workload:** Total Hours **100** (lectures 10; seminars/tutorials 3; programme-level teaching 2; directed/independent learning 85).
- **Official assessment:** Coursework 100%. Individual coursework is worth 30%, and a group presentation is worth 70%. There is no centrally scheduled formal written exam.
- **Course overview:** Focuses on scalable technology ventures, covering opportunity identification, business models, customer and market validation, intellectual property and venture creation. It is not a bioinformatics algorithms course; it is better suited to students who want to understand research commercialisation, entrepreneurship or product commercialisation.
- **Study advice:** The group presentation accounts for 70%, so marks depend substantially on teamwork and business communication. Consider this alongside the absence of a closed-book exam when choosing the course.

### Past Papers

A search of the official exam paper archive for the exact code `CMSE11576` returned 0 entries. An unquoted search previously returned Financial Analysis under code `CMSE11108`; this was a search-engine mismatch and has been excluded.

<a id="analysis-cmse11576"></a>
### Assessment Structure and LLM Difficulty Rating

| Dimension | Assessment |
|---|---|
| Closed-book exam? | No; individual coursework 30% + group presentation 70%. |
| Predictability | The format is clear, but topics and teams change each year; there are no central past papers or reliable course-specific student reviews. |
| Main risks | The technical entry barrier is relatively low, but business argumentation, presentations in English and teamwork all affect marks. The 70% group assessment concentrates the risk. |
| **LLM difficulty rating** | **3.0/5.** The technical entry barrier is relatively low, but business argumentation, presentations in English and teamwork all affect marks. The 70% group assessment concentrates the risk. |

<a id="course-epcc11017"></a>
## [EPCC11017 Programming Skills](https://www.drps.ed.ac.uk/26-27/dpt/cxepcc11017.htm)

- **Credits and semester:** 10 credits. The course page says it may run twice a year, but the Bioinformatics DPT explicitly requires students on this programme to take it in **Semester 2**. Follow the DPT when registering.
- **Official notional workload:** The Semester 2 instance lists Total Hours **100** (lectures 9; supervised practicals/workshops 18; programme-level teaching 2; directed/independent learning 71). The Semester 1 instance separately lists one hour as Feedback/Feedforward, so the two breakdowns are not combined here.
- **Official assessment:** Coursework 100%, in a practical course. The current course page does not list a more detailed fixed percentage breakdown, and there is no centrally scheduled formal written exam. Any further breakdown in an older table therefore cannot be treated as official fact.
- **Course overview:** Develops the ability to write readable, maintainable, correct and efficient research code, covering Linux/Unix, testing, version control, profiling and an HPC-oriented approach. This is not Programming 101 from scratch; it develops existing programming experience into reliable software practice.
- **Study advice:** Very useful for research programming, reproducible analysis and future computational projects. Students with very limited programming skills should learn basic syntax and command-line use in advance rather than relying entirely on classes.

### Past Papers

A search of the official exam paper archive for the exact code `EPCC11017` returned 0 entries, consistent with 100% coursework assessment. Searching for the title "Programming Skills" returns many courses from other disciplines, none of which is this course.

<a id="analysis-epcc11017"></a>
### Assessment Structure and LLM Difficulty Rating

| Dimension | Assessment |
|---|---|
| Closed-book exam? | No centrally scheduled formal written exam; practical coursework accounts for 100%, with no fixed detailed breakdown published on the official website. |
| Expected background | The course expects students to have written a program longer than approximately 100 lines, and recommends familiarity with at least one language and bash/Unix; it is not a course for complete beginners. |
| Main risks | Software engineering habits, testing, version control, performance and maintainability are assessed. Being able to write analysis scripts does not automatically translate into high marks, and sustained practice may be time-consuming. |
| **LLM difficulty rating** | **3.0/5.** Suits students with an existing programming foundation. Testing, version control, performance and code quality demand more than the ability to write scripts; this is not an introduction for complete beginners. |

<a id="course-pgbi11040"></a>
## [PGBI11040 Functional Genomic Technologies](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11040.htm)

- **Credits and semester:** 10 credits, Semester 2; strongly recommended in the DPT.
- **Official notional workload:** Total Hours **100** (lectures 20; supervised practicals/workshops 10; summative assessment 2; programme-level teaching 2; directed/independent learning 66).
- **Official assessment:** Written exam 50% + assignments 50%; the course page lists a 120-minute exam in the April/May main diet.
- **Course overview:** Covers high-throughput functional genomic technologies including microarrays, RNA-seq, ChIP-seq, SNP/aCGH and proteomics, using R/Bioconductor and Unix tools for data analysis and interpretation. The emphasis is not only on technological principles, but also on choosing appropriate methods and assessing data quality.
- **Study advice:** Together with `BILG11004` and `PGBI11057`, this forms a very typical genomics and bioinformatics combination. The assignments, worth 50%, provide an opportunity to demonstrate practical skills, but there is still a written exam worth 50%.

<a id="papers-pgbi11040"></a>
### Past Papers

19 entries in total: 17 PDFs and 2 marked Paper Unavailable. Early records from 2007/08 to 2009/10 use the old code `P02551` and were included after an additional search using the exact course title.

#### [2025/2026: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/03d71423-7ee8-40e6-9ffd-071b6193b0ee/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/b8d47008-d6c4-4a25-8222-a51b6d0aaa0e)

#### [2024/2025: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/d6ffc5f4-dfcf-48b6-8198-292f0826e649/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/0364efbd-ea37-4e91-85bb-e6e0e500fb20)

#### [2023/2024: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/b17fb861-26dc-4c14-9d85-dad617dc7ecf/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/d7ca2ed3-7b10-4b45-8adf-1c9fd88fead1)

#### [2022/2023: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/75d299ac-21b7-4cdc-a06d-dc8d943a707e/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/b45e01ad-b9af-4cbd-81ef-a26c78128cab)

#### [2021/2022: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/493f3827-6be9-40cd-bcb2-fbe75e4d8838/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/3b5970ae-9e1d-48ce-a7f6-263a1638c895)

#### [2020/2021: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/cace234f-fbca-4b9a-81a0-c6a8870ce62d/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/be5bd4d3-a4ef-41ad-8039-9b2d9834033b)

#### [2019/2020: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/e12fd68f-2a70-4b42-97bf-762d8906c43f)

- The University retains the metadata but provides no downloadable PDF.

#### [2018/2019: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/cf6d55e1-f17a-45dc-bb8b-dd31e9664948/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/901caa61-1d58-43c3-9e5d-bef10f1d8edf)

#### [2017/2018: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/a981dcf3-9807-4123-abec-945f88888bea/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/c587ceef-173d-4b41-8fc6-a3689c3190b3)

#### [2016/2017: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/df8125e4-05c4-470b-bb29-3296af070caa/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/640fe2cf-8941-4411-999a-f75e33b4d372)

#### [2015/2016: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/f61867a7-5c83-4f70-8005-ed227423b436/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/ff4e5af3-414c-4d98-8293-8aaa29feffaa)

#### [2014/2015: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/5d584ba9-ec07-49da-bf04-ba8745a374de/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/c12ee319-7110-43e1-9970-61f37f4bebd5)

#### [2013/2014: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/58efde0b-597e-4e2c-83a3-4f55901e206a/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/aa3b0060-67c6-41a3-863b-4203491263f0)

#### [2012/2013: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/f2965304-9004-4ce0-9ce1-a3acdd19bf48/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/b7852440-6bf3-4f5d-a83c-97a5513c8831)

#### [2011/2012: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/54313974-2ddd-43cb-9e7c-baaa047053d9/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/649f3b3d-75d6-494f-b3ad-90c862aa1ab8)

#### [2010/2011: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/d8b55a1c-d0c8-4426-be5e-a1001af48bb0/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/af429003-a3fd-483c-9f4b-5efd35a061cd)

#### [2009/2010: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/d3619d25-4942-494d-a61d-5650804767ef/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/1bcdbff0-bd4c-49a6-a99c-a3ca66fcca9e)

#### [2008/2009: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/2872719e-e76d-47db-8d80-1941d27239fa)

- The University retains the metadata but provides no downloadable PDF.

#### [2007/2008: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/c0c8c6c7-03c4-4502-8b17-f1805cf7affe/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/72368896-25a5-4029-acec-8df74ea1aa83)

<a id="analysis-pgbi11040"></a>
### Past-Paper Patterns, Current Risks and LLM Difficulty Rating

| Dimension | Findings from 17 readable papers |
|---|---|
| Frequently examined topics | Microarrays **15/17**, RNA-seq/transcriptomics **14/17**, ChIP/TF binding **14/17**, QC/normalisation/experimental design **12/17**, clustering/PCA **8/17**, single-cell/new technologies **4/17**. |
| Clear examples of reuse | Microarray hybridisation has recurred over many years; "data fishing" appears in both 2021/22 and 2023/24; ChIP peak-calling questions in 2023/24 and 2025/26 are similar; combined ChIP/RNA-seq appears repeatedly in 2021/22, 2022/23 and 2025/26. |
| Answering requirements | Question 1 is compulsory; choose either Question 2 or Question 3. Exams were open-book from 2020/21 to 2022/23 and have been two-hour in-person papers since 2023/24. |
| Ease of preparation | **Very high.** The 17 papers show that the core technology families have remained stable over time, with some similar questions. However, new technologies, experimental design and specific data interpretation tasks still rotate, so memorising old answers alone is not enough. |
| Data verification note | The front of the 2024/25 PDF incorrectly prints the code `PGBI11114`, but its title, archive metadata and entire contents are for Functional Genomic Technologies. This is a course-code misprint on the paper, not the accidental inclusion of a research proposal paper in this guide. |
| **LLM difficulty rating** | **3.5/5.** Functional genomic technologies, statistical interpretation and practical R/Unix skills are equally important. There are many past questions, but preparation must cover experimental design and new technologies. |

<a id="course-pgbi11057"></a>
## [PGBI11057 Bioinformatics Algorithms](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11057.htm)

- **Credits and semester:** 10 credits, Semester 2; strongly recommended in the DPT.
- **Official notional workload:** Total Hours **100** (lectures 10; supervised practicals/workshops 10; summative assessment 2; programme-level teaching 2; directed/independent learning 76).
- **Official assessment:** Written exam 50% + written assessment 50%; the course page lists a 120-minute exam in the April/May main diet.
- **Course overview:** Teaches algorithmic thinking at the interface of computer science and biology, the computational methods behind common bioinformatics software, and algorithm implementation in Python. It places greater emphasis on complexity, algorithm design and implementation skills than on simply running existing tools.
- **Study advice:** Valuable for the computational foundations of algorithms, research software and AI4Science, but the substantial Python implementation component and 50% written exam make it unsuitable for students simply seeking to avoid programming or theory.

<a id="papers-pgbi11057"></a>

### Past Papers

15 entries in total: 14 PDFs and 1 marked Paper Unavailable.

#### [2025/2026: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/6403ab0e-12e4-48f6-8517-a4b6422efdcb/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/3d26febd-49a0-4e35-b196-b513bcc96b29)

#### [2024/2025: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/c2f53508-2333-40c1-bedd-67d46580392d/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/c6d6a298-7987-4d0e-989e-1b4b585bde5f)

#### [2023/2024: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/a0122c24-3cc6-412a-a173-186ec7058790/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/cec1697e-8372-4b22-b79b-b9d614c95464)

#### [2022/2023: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/9a27272f-b1c1-4350-88af-c77a62e51229/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/46025da4-25df-4de1-ba34-c2dd925b8d43)

#### [2021/2022: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/9c39b04e-a4ea-47db-a411-f005e551b6de/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/a6224b81-b39c-4ba5-a2cb-57bc11af7758)

#### [2020/2021: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/2678eb94-ea51-4cc2-9c56-a9f6a458522a/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/e5953b8d-7b33-47b8-a75e-8cd36bfff8ae)

#### [2019/2020: Archive entry (Paper Unavailable)](https://exampapers.ed.ac.uk/items/0bf10821-9b80-480c-8130-214729cbf855)

- The University retains the metadata but provides no downloadable PDF.

#### [2018/2019: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/39ad1f45-3cfd-43b3-8c4b-557bb31dbfc7/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/ff962d68-c63f-44e0-b9ca-20913f1c3ede)

#### [2017/2018: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/88769d75-81f9-4b92-bf60-049f023526e4/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/a66ff681-8c24-42d1-8476-c96e1f1243ce)

#### [2016/2017: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/1517df78-f457-4009-a429-43a8eb79172a/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/95258736-204d-4729-9631-7caf21007095)

#### [2015/2016: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/37ff2654-ce68-4c35-bbea-055d92c1f8e6/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/7ed6ebaf-63f9-423e-84fa-f7ccb3a5f807)

#### [2014/2015: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/fe9d2b79-a658-4451-bdee-65b10492d371/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/f2208a88-1c20-4ccb-9a79-0f36df6d2b11)

#### [2013/2014: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/7d71951d-c43d-481e-8d53-0ddb25c110e4/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/21291164-6dd6-4bea-b7fb-146615a0d736)

#### [2012/2013: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/0330ce57-7bf3-4385-8d5c-88be3a22bbc1/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/1284ab55-996c-4706-bd01-91c249332bb7)

#### [2011/2012: Exam paper PDF](https://exampapers.ed.ac.uk/bitstreams/efc8f023-99a1-44c3-8f01-3bec0e7cd865/download)

- [University archive entry](https://exampapers.ed.ac.uk/items/e8a0b280-ec34-4a99-96d5-728bc09b2ae0)

<a id="analysis-pgbi11057"></a>
### Past-Paper Patterns, Current Risks and LLM Difficulty Rating

| Dimension | Findings from 14 readable papers |
|---|---|
| Frequently examined topics | Complexity/sorting/data structures **14/14**, programming/code reading **12/14**, genetic algorithms **11/14**, clustering/trees **11/14**, alignment/BLAST **9/14**, motifs **8/14**, MapReduce **7/14**, HMMs **5/14**. |
| Clear examples of reuse | Similar Quicksort questions appear in 2020/21, 2022/23 and 2023/24; Q1 in 2024/25 recombines bubble sort/tree/stack/GA/MapReduce material from earlier papers; hierarchical clustering + GA in 2025/26 is close to Q3 in 2020/21, while the decision-tree material continues themes from 2022/23-2023/24. |
| Answering requirements | Question 1 is compulsory; choose either Question 2 or Question 3. Exams were open-book from 2020/21 to 2022/23 and have been two-hour in-person exams since 2023/24. |
| Ease of preparation | **Extremely high.** Among the programme's courses with available papers, this has some of the clearest reuse of question structures and short-question elements. However, code tracing, complexity and algorithm applications require genuine problem-solving ability, not just question recognition. |
| **LLM difficulty rating** | **3.5/5.** Requires code tracing, complexity analysis, data structures and bioinformatics algorithms. Past questions follow patterns, but memorising concepts cannot replace working through computations. |

<a id="course-pgbi11130"></a>
## [PGBI11130 Biological Structure and Drug Function](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11130.htm)

- **Credits and semester:** 20 credits, Semester 2; the DPT states that this course cannot be taken on a "Class Only" basis.
- **Official notional workload:** Total Hours **200** (lectures 12; seminars/tutorials 8; supervised practicals/workshops 12; summative assessment 2; revision sessions 4; programme-level teaching 4; directed/independent learning 158).
- **Official assessment:** Coursework 100%. A structural methods class test is worth 30%, and a group mini-project report is worth 70%. Of the project mark, 90% is awarded by two markers and 10% comes from peer assessment. There is no centrally scheduled formal written exam.
- **Course overview:** Covers methods for determining biomolecular structures, structural quality indicators and molecular modelling, and applies structural information to virtual screening and drug discovery. Its focus is structural biology, computational drug discovery and mechanistic explanations at the molecular level.
- **Study advice:** This single course carries 20 credits, with 70% concentrated in a group project. It suits students interested in structural biology or drug discovery who are willing to take on the risks of a team project. A class test is not the same as a central exam paper.

### Past Papers

A search of the official exam paper archive for the exact code `PGBI11130` returned 0 entries, consistent with 100% coursework assessment. The class test worth 30% is not part of the central formal written exam archive, so there are no public past papers to list.

<a id="analysis-pgbi11130"></a>
### Assessment Structure and LLM Difficulty Rating

| Dimension | Assessment |
|---|---|
| Closed-book exam? | No centrally scheduled formal written exam. The public page does not specify whether the 30% structural methods class test is open- or closed-book, or what materials are permitted; the remaining 70% is a group mini-project report. |
| Predictability | The overall weightings are clear, but no past class tests are publicly available. Of the project mark, 90% is awarded by two markers and 10% through peer assessment, so the team and topic have a substantial influence. |
| Main risks | One course carries 20 credits, with 70% dependent on group work. The structural biology learning curve and variability in team performance are both concentrated in a heavily weighted component. |
| **LLM difficulty rating** | **3.5/5.** Structural biology and molecular modelling have a learning barrier, while the 20-credit weighting, class test and heavily weighted group project concentrate the risk. |

---

<a id="course-pgbi11126"></a>
## [PGBI11126 Population Genomic Analysis](https://www.drps.ed.ac.uk/26-27/dpt/cxpgbi11126.htm)

- **Semester and credits:** Semester 2, starting in Block 3; 10 SCQF credits (5 ECTS), Level 11. Listed in the pool from which Bioinformatics students select 50 credits of Semester 2 electives.
- **Notional workload:** 100 hours: lectures 30, programme-level teaching 2, independent learning 68. The course description specifies interactive computer practicals using Jupyter notebooks; the structured field labels these as Lecture Hours, which does not mean the teaching is purely lecture-based.
- **Assessment:** Classified by DRPS as Coursework 100%, but in practice consists of weekly numerical/multiple-choice quizzes on Learn worth 25% and a timed computer-based assessment (class exam) in Week 5 worth 75%. **This is not an exam-free course.** The public page does not specify the practical exam's duration, open- or closed-book status, internet access or rules on tool use; consult the assessment brief for your year.
- **Content:** Centred on ancestral relationships among genomic samples, covering coalescent theory, genealogies, tree sequences and graph structures, with simulation and statistical inference used to understand genetic drift, recombination, population history, admixture and natural selection.
- **Background:** No compulsory prerequisite course codes are listed, but the course description explicitly expects basic knowledge of population genetics. "No prerequisite codes" does not mean no prior knowledge is needed. The course organiser is Dr Konrad Lohse.

<a id="analysis-pgbi11126"></a>
### Course History, Assessment and LLM Difficulty Rating

**This is not a new course introduced in 2026/27.** The [2021/22 course catalogue](https://www.drps.ed.ac.uk/21-22/dpt/cxpgbi11126.htm) already lists a course with the same title and code; records also exist for [2024/25](https://www.drps.ed.ac.uk/24-25/dpt/cxpgbi11126.htm) and [2025/26](https://www.drps.ed.ac.uk/25-26/dpt/cxpgbi11126.htm).

**Compared with the previous academic year, it is newly listed among the Bioinformatics electives.** The [2025/26 Bioinformatics DPT](https://www.drps.ed.ac.uk/25-26/dpt/ptmscbioin1f.htm) does not list PGBI11126, whereas the [2026/27 DPT](https://www.drps.ed.ac.uk/26-27/dpt/ptmscbioin1f.htm) explicitly includes it. This comparison establishes a change between the two catalogues, not that the course had never previously been available to students on this programme.

| Dimension | Judgement |
|---|---|
| LLM difficulty rating | **4.0/5, relatively high.** The conceptual demands of stochastic models and population genetics combine with computational practical work and timed assessment. This is a subjective judgement, not a statistical summary of student reviews. |
| Greatest risk | A single timed practical accounts for 75%; even full marks in the weekly quizzes cannot substitute for performance in that assessment. |
| Who it suits | Particularly relevant to students interested in population history, evolution, genetic ancestry and model-based inference. |
| Advice on reducing workload | Do not treat it as an easy way to make up credits. Compared with general R or database courses, it provides more specialised training in models and inference; do not prioritise it solely because it is classified as Coursework 100%. |
| Difference from NGG | Focuses on inferring population genetic variation and ancestral relationships, rather than primarily on sequencing platforms, assembly and QC. The two courses may complement each other, but should not be treated as the same course. |
| Places available | The Quota field on the page for this academic year is 0, yet the DPT lists the course as an option. The page does not explain this field, so it does not establish that the course is cancelled, full or unlimited in capacity; confirm registration arrangements with the programme. |

### Past Papers and Preparation Materials

This search of public indexes using the exact course code and title did not yield any past papers that could be verified; this is not presented as evidence that the exam archive contains 0 entries. The class exam may be managed through Learn, and the University still needs to confirm whether the central exam paper archive includes it. The checked course pages for 2021/22, 2024/25, 2025/26 and 2026/27 all use the structure of 25% quizzes + 75% timed practical, but this does not establish that questions are repeated.

The revision advice is an LLM judgement: first build a foundation in population genetics and basic probability, then practise notebook-based data processing, interpretation of simulation results and timed analysis. Refer to the materials for your year for the specific software, permitted resources and exam duration.

# Public Student Experiences and Project Examples

## Evidence Grades for Social Platforms

| Grade | Meaning | How it can be used |
|---|---|---|
| A | First-hand experience from someone identifiable as a current student or graduate of this MSc | Useful supporting evidence of the programme experience, but still only an individual account |
| B | Directly related to this programme, but the person's identity, full context or platform data cannot be independently verified | Can highlight questions to investigate, but should not be the sole basis for a conclusion |
| C | Student experience from a neighbouring Edinburgh school, an old course or the University generally | Helps explain the wider environment, but cannot be extrapolated to a particular elective |
| D | Non-attendees, second-hand accounts, study-abroad agents, rankings or automatically aggregated pages | Their existence can be recorded, but they are not evidence of a course's reputation among students |

LinkedIn graduation posts and student stories on the University's website tend to be positive; Reddit is more likely to attract negative accounts or requests for help. Both have selection biases, and the number of posts or likes is no substitute for a course survey.

## The Most Valuable First-Hand Accounts of This Programme

| Source | Identity and timing | Information available | Limitations and grade |
|---|---|---|---|
| [Reddit: Questions about MSc Bioinformatics program](https://www.reddit.com/r/bioinformatics/comments/pkj956/questions_about_msc_bioinformatics_program_at_the/) | The original poster subsequently chose UoE and returned to the discussion in 2023 as an international student | The programme is more genomics-focused than many comparable MSc programmes; there is substantial elective choice; a foundation in at least one programming language and the command line is important, and students with weaker foundations are more likely to struggle; the poster was satisfied overall | A single anonymous account, without course-by-course reviews; **A-** |
| [Kavya Manjula Gurubasavaiah, class of 2025](https://biology.ed.ac.uk/study-with-us/postgraduate-taught/meeting-us/meet-our-students/kavya-manjula-gurubasavaiah) | MSc Bioinformatics graduate confirmed by the University's website | Emphasises real data, tools and practical work; says the early labs moved quickly and required advance preparation, trial analysis runs and actively seeking feedback; the dissertation involved collaboration with Quas Drinks on 16S/shotgun metagenomics and a reproducible pipeline | The University explicitly discloses that she was incentivised to share her story; promotional selection bias applies; **A-** |
| [Lodan E, current student in the class of 2026](https://biology.ed.ac.uk/study-with-us/postgraduate-taught/meeting-us/meet-our-students/lodan-e) | Current student with a CS background, confirmed by the University's website | Values the elective range and classmates from different backgrounds; finds that courses introduce key concepts to help build foundations; personally needed additional biology study; describes lectures as often followed by workshops and reports supportive teaching staff | An incentivised University student story; the student had not yet completed the programme; **A-** |
| [Rahul D, current student in the class of 2026](https://biology.ed.ac.uk/study-with-us/postgraduate-taught/meeting-us/meet-our-students/rahul-d) | Current student confirmed by the University's website | Emphasises transferable skills, interactive classes, lab support and organisation; advises managing lectures/tutorials/assignments from day one; had no formal internship at that point and was looking forward to starting the dissertation in May | An incentivised University student story; **A-** |
| [Karin Hrovatin, class of 2019](https://biology.ed.ac.uk/study-with-us/taught-programmes/meeting-us/meet-our-students/karin-hrovatin) | Graduate confirmed by the University's website, who subsequently entered a research role and a machine-learning-focused bioinformatics PhD | Found the course's practical orientation most valuable for independent research; practical assignments required substantial effort; moving from biotechnology to bioinformatics involved considerable additional study of statistics/data analysis; her Distinction and best dissertation award helped with job applications | A high-achieving graduate's account, with information mainly dating from 2020; **A-** |
| [Max Falk, 2024/25 cohort, LinkedIn](https://www.linkedin.com/posts/max-falk1_it-was-a-pleasure-to-return-to-the-university-activity-7397566728353783808-8Jmg) | Top student prize winner for the cohort; graduated with Distinction | Explicitly describes the programme as challenging but hugely enjoyable, and praises guidance from the Programme Director and dissertation supervisor | A top prize winner's graduation celebration post, with strong positive selection bias; **A-** |
| [Xi Yang, class of 2024, LinkedIn](https://www.linkedin.com/posts/ianyangxi_computationalchemistry-machinelearning-activity-7266782734281281536-KUFX) | Received an EPSRC PhD scholarship after completing the MSc | Describes the year as a period of intensive growth, learning ML, bioinformatics, project management and LSTM; stresses that ML cannot be separated from statistical and biological context; says securing a PhD was very difficult | A personal reflection/celebration post, without reviews of individual courses; **A-** |
| [Anooraag Basu, 2024/25 cohort, LinkedIn](https://www.linkedin.com/posts/anooraagbasu_a-moment-that-i-had-looked-forward-to-is-activity-7397269329320476672-J5fm) | Graduated with Merit | Says the programme was not easy, but pushed him to challenge his limits and build international connections; praises the teaching staff, supervisors and support system | A graduation celebration post, with positive selection bias; **A-** |
| [Miles McGibbon, class of 2022, LinkedIn](https://www.linkedin.com/posts/miles-mcgibbon_im-delighted-to-have-graduated-with-distinction-activity-7005568886557294593--hGq) | Graduated with Distinction | Dissertation in collaboration with AskBio, using machine learning to predict microRNA interactions; demonstrates that industry-collaborative AI/bioinformatics dissertations have occurred on this programme | Establishes this individual case only; does not guarantee comparable places in 2026/27; **A-** |
| [Shiksha: anonymous review from the class of 2023 on the UoE reviews page](https://www.shiksha.com/studyabroad/uk/universities/the-university-of-edinburgh/reviews?bc=100) | Labelled "Verified", MSc Bioinformatics, Batch of 2023 on the page | Gives a rating of 3.8/5, describes friendly social experiences on campus, reports receiving a scholarship and states that pre-class preparation took 32 hours per week | Anonymous and verified by a commercial study-abroad platform; self-reported figures such as monthly spending and expected salary cannot be independently confirmed and should not be used for budgeting or employment forecasts; **B** |

## Other Substantive Reddit and Forum Discussions

| Post | Actual content | Evidence assessment |
|---|---|---|
| [What do I need to know before starting my masters course](https://www.reddit.com/r/bioinformatics/comments/mcxtsv/what_do_i_need_to_know_before_starting_my_masters/) | The OP later clarified that they would be studying Bioinformatics at Edinburgh; replies recommended Linux, bash/Python, statistics and molecular biology, but the respondents did not establish that they had attended the Edinburgh programme | Useful general preparation advice, not a first-hand review of Edinburgh; **B/C** |
| [MSc Bioinformatics at University of Edinburgh, 2026](https://www.reddit.com/r/bioinformaticscareers/comments/1swzgks/msc_bioinformatics_at_university_of_edinburgh/) | One commenter criticised the programme as "dated" and focused on traditional genetics/stats; when asked, they explicitly admitted never having attended and having only read the module catalogue | This is **a non-attendee's opinion**, not a negative first-hand review; **D** |
| [KCL Applied Bioinformatics vs Edinburgh Bioinformatics, 2026](https://www.reddit.com/r/UniUK/comments/1sx0nha/msc_applied_bioinformatics_at_either_kcl_or_msc/) | A commenter thought Edinburgh was better for research/a PhD and KCL benefited from its London location, but relied mainly on rankings and relatives' experiences | Second-hand information; does not establish employment outcomes; **D** |
| [Re: Opinions from Current University Students](https://www.reddit.com/r/Edinburgh_University/comments/siufuy/re_opinions_from_current_university_students/) | An offer holder for this programme asked for first-hand replies; other responses mainly discussed Edinburgh's general environment, independent learning and the city | Supporting evidence at University level, not applicable directly to this MSc; **C** |
| [The Student Room: MSc in Bioinformatics, 2009](https://www.thestudentroom.co.uk/showthread.php?t=983072) | A participant at the time described the programme as "pretty good", with biology courses taught by researchers and a substantial choice of ML/Informatics courses | Likely first-hand, but approximately 16 years old; course codes, selection rules and the programme structure have all changed; **C** |
| [The Student Room: York or Edinburgh, 2013](https://www.thestudentroom.co.uk/showthread.php?t=2395540) | One user described Edinburgh as a leader in bioinformatics without establishing that they had attended | Very old and not first-hand; **D** |

## Signals from Related Courses and the Wider University

- In [Reddit: Can someone provide a review of ML courses?](https://www.reddit.com/r/Edinburgh_University/comments/g681uh/can_someone_provide_a_review_of_ml_courses/), a 2018/19 student rated the old **Introductory Applied Machine Learning (`IAML`)** course 1/5, criticising its flipped classroom and organisation; another old post called IAML a good course. The current `INFR11211 Applied Machine Learning` is not the same as the old IAML course. The official guidance only says that old papers may contain some relevant material, so this is a historical signal from a related course, not a review of current AML.
- An Informatics graduate in [Reddit: U of Edinburgh Software Eng](https://www.reddit.com/r/Edinburgh_University/comments/14eij76/u_of_edinburgh_software_eng/) says workload depends heavily on prior programming knowledge, lectures often cover only the theoretical foundations, implementation requires substantial independent learning, and experiences with lecturers vary. This offers context on the school offering `INFR11211`, but is not a review of this course or this MSc.
- [Reddit: Honest Review on Edinburgh University](https://www.reddit.com/r/UniUK/comments/1antg8a/honest_review_on_edinburgh_university/) is a lengthy negative review by an Edinburgh CS undergraduate; [The Student Room: UoManchester or UoEdinburgh](https://www.thestudentroom.co.uk/showthread.php?t=7648270) contains an Edinburgh biology undergraduate's negative account of high workload, Python support and the student experience. Both are worth knowing about, but the schools, years of study and programme structures differ, so **they cannot be extrapolated as facts about MSc Bioinformatics**.
- [Reddit: Is UoE really worth its tuition fee?](https://www.reddit.com/r/Edinburgh_University/comments/1p4c2e2/is_uoe_really_worth_its_exorbitant_tuition_fee/) brings together differing views on contact hours, feedback, job seeking and value for tuition fees across several programmes. It can prompt readers to check support and careers services, but is not a basis for rating any elective.

## Dissertation Projects, Research Directions and Publicly Reported Destinations

- [Kavya, 2025](https://biology.ed.ac.uk/study-with-us/postgraduate-taught/meeting-us/meet-our-students/kavya-manjula-gurubasavaiah): collaboration with Quas Drinks; 16S/shotgun metagenomics, QIIME2, MetaPhlAn4, HUMAnN3 and DRAM.
- [Miles McGibbon, 2022](https://www.linkedin.com/posts/miles-mcgibbon_im-delighted-to-have-graduated-with-distinction-activity-7005568886557294593--hGq): collaboration with AskBio; machine learning to predict microRNA interactions.
- [Giulia Guasoni, class of 2025, public profile](https://uk.linkedin.com/in/giulia-guasoni-92a968293): publicly listed courses cover Algorithms, Programming/System Management, Biological Databases, Functional Genomics, Website/Database, NGG, Statistics, Entrepreneurship and Using R; the dissertation used public RNA-seq data to study laminopathies. This is an example of a study pathway, not a course rating.
- [Elijah Downs' personal website](https://elijahdowns.github.io/): publicly states that his MSc industry placement was at CEXAL Ltd in Edinburgh, developing a pipeline to automate probe design for nucleic acid detection. The page establishes another instance of industry collaboration, but project arrangements should still be confirmed with the Programme Director each year.
- [Karin Hrovatin, 2019](https://biology.ed.ac.uk/study-with-us/taught-programmes/meeting-us/meet-our-students/karin-hrovatin): entered a bioinformatics research role after graduation, followed by a machine-learning-focused bioinformatics PhD.

These cases support the possibility of an AI/ML, omics or industry-collaborative dissertation, but do not mean that an industry placement can automatically replace `PGBI11034`, or that every student will be offered a company project each year.

## Platforms with Substantive Material

| Platform | Findings from the expanded search | Limitations on use |
|---|---|---|
| Reddit | 1 relatively strong first-hand programme account, plus several substantive comparison posts and discussions from neighbouring schools | Anonymous, small sample, and selection bias towards negative experiences/requests for help |
| LinkedIn | Several graduates whose connection to the programme can be confirmed, with examples of dissertation collaborations and subsequent destinations | Graduation celebrations and professional self-presentation tend to be positive and do not represent students in the ordinary mark ranges |
| University Student Stories | Accounts from programme students in the classes of 2019, 2025 and 2026 | The University pages explicitly disclose that some students were incentivised; this is a selectively curated promotional setting |
| The Student Room | A programme participant's comment from 2009 and a comparison post from 2013 | Old material or incomplete identification; old course-selection rules must not be applied to the current programme |

## Why Third-Party Rating Pages Cannot Be Taken at Face Value

- [Shiksha's anonymous programme review from the class of 2023](https://www.shiksha.com/studyabroad/uk/universities/the-university-of-edinburgh/reviews?bc=100) is one of the few entries explicitly labelled as this MSc and can be used as a grade B individual account. However, the page mixes in other subjects across the University, and costs, hours worked and expected salaries are all self-reported.
- Although [UniversityGuru's Bioinformatics page](https://www.universityguru.com/c/the-university-of-edinburgh-edinburgh/bioinformatics-msc) displays "30 respondents/76%", the same page labels the comparison subject and salaries as **Finance, Banking, Corporate Finance, Fintech**, and mixes programme durations of 9 months and 1 year. The fields are clearly mismatched, so this guide does not treat those figures as reliable statistics for this programme.

## Common Themes in Public Student Accounts

- The currently verifiable social material mainly concerns the overall programme experience and dissertation projects; it cannot support a reliable course-by-course reputation ranking. Identical or similar names cannot automatically be treated as referring to these courses: the old IAML, Intro to Databases, Genomes and Genomics, and Programming Skills for Engineers do not exactly match the course codes in this guide.
- The most robust common themes at present are that the programme leans towards genomics; programming, command-line and statistics foundations significantly affect the experience; teaching moves quickly and places substantial weight on independent learning; practical assignments and the dissertation are the most valuable sources of work to demonstrate in research or job applications; and industry collaborations and AI/ML projects do occur, but are not guaranteed.
- Public material does not support claims that "100% coursework definitely makes it easier to get high marks" or that a particular course is universally regarded as easy or difficult. Course choices should still prioritise the official assessment structure, individual preparation, past papers and conversations with current students over social-platform popularity.

<a id="personalised-plans"></a>
# LLM Difficulty Overview and Course-Selection Suggestions

The following ratings are not the results of a ranking survey. Equal scores do not imply identical content or workload; courses with 100 and 200 learning hours cannot be compared on their ratings alone. Two 10-credit courses can spread the weight of individual assessments, but may also mean more simultaneous assignment deadlines, so they are not automatically less demanding.

| Course code | LLM difficulty | Main reasons |
|---|---:|---|
| [PGBI11122](#course-pgbi11122) | 2.5/5 | Relatively straightforward to prepare for with an R background; still requires an accurate understanding of language semantics, data processing and reproducible workflows, alongside a 50% written exam. |
| [PGBI11114](#course-pgbi11114) | 3.0/5 | Focuses on defining a problem, methodological feasibility and argumentation in English; a single research proposal determines the entire mark. |
| [PGBI11129](#course-pgbi11129) | 3.0/5 | Combines database concepts, APIs, biological databases and script integration; past questions are relatively stable, but coursework requires practical construction. |
| [BILG11004](#course-bilg11004) | 3.0/5 | Covers many concepts in sequencing, assembly, QC and population genomics; the essay exam requires well-organised arguments, and students with limited biology need additional study. |
| [BILG11016](#course-bilg11016) | 3.0/5 | No centrally scheduled written exam, but SQL, relational modelling, website implementation and a critical essay all require effort; debugging time should not be overlooked. |
| [BITE11004](#course-bite11004) | 3.0/5 | Spans experimental workflows, data analysis and scientific reporting; no centrally scheduled written exam does not mean an easy course, and the final report carries substantial weight. |
| [CMSE11576](#course-cmse11576) | 3.0/5 | Relatively limited technical barriers, but business argumentation, presentations in English and teamwork jointly affect marks; 70% group assessment concentrates risk. |
| [EPCC11017](#course-epcc11017) | 3.0/5 | Suitable for those with prior programming knowledge; testing, version control, performance and code quality demand more than the ability to write scripts; not an introduction for complete beginners. |
| [PGBI11095](#course-pgbi11095) | 3.5/5 | Combines practical Python/Linux use with closed-book systems design; both assessment components must be passed individually, so a compensating overall mark is insufficient. |
| [BICH11011](#course-bich11011) | 3.5/5 | Requires quantitative biophysics, experimental analysis and lengthy reports; 20 credits and heavily weighted laboratory reports concentrate the workload. |
| [PGBI11040](#course-pgbi11040) | 3.5/5 | Combines functional genomics technologies, statistical interpretation and R/Unix practical work; many past questions are available, but experimental design and new technologies must also be covered. |
| [PGBI11057](#course-pgbi11057) | 3.5/5 | Requires code tracing, complexity analysis, data structures and bioinformatics algorithms; past questions follow patterns, but memorising concepts cannot replace calculations. |
| [PGBI11130](#course-pgbi11130) | 3.5/5 | Structural biology and molecular modelling present a learning barrier; 20 credits, in-class tests and a heavily weighted group project concentrate risk. |
| [PGBI11003](#course-pgbi11003) | 4.0/5 | Requires simultaneous command of probability, linear models, ANOVA/GLM and interpretation in R; public assessment information conflicts, so the current cohort's guidance must be checked. |
| [PGBI11034](#course-pgbi11034) | 4.0/5 | Combines independent research, dependence on data and supervision, writing in English and long-term progress management; the total workload of 60 credits should not be overlooked. |
| [INFR11211](#course-infr11211) | 4.0/5 | Broad coverage, 20 credits and a 60% closed-book exam; past papers help with revision but cannot replace coverage of the full syllabus. |
| [PGBI11126](#course-pgbi11126) | 4.0/5 | Combines stochastic coalescent models, population genetic inference and computational practical work; a 75% timed computer-based assessment concentrates the marks, so it is not recommended as a lighter-workload option. |
| [MATH11205](#course-math11205) | 4.5/5 | Difficult and not recommended as an elective. It should not be treated as an easy course in Python tools: mathematical understanding, programming, weekly assignments and projects run alongside one another; the written exam is worth 50%. |
| [PGBI11051](#course-pgbi11051) | 4.5/5 | Combines cellular mechanisms with quantitative modelling, requires strong abstract reasoning and has insufficient recent readable past papers; not recommended as a lighter-workload option. |

<a id="plan-easiest"></a>
## Plan A: Foundational Applications and Spread-Out Assessment

Suitable for students who want to practise R, databases, scientific programming and omics analysis together. This is not a plan that guarantees the easiest route or high marks; laboratory work, reports and website development can all be time-consuming.

| Semester | Course | Credits |
|---|---|---:|
| S1 | PGBI11122 Using R for Data Science | 10 |
| S1 | PGBI11129 Biological Databases | 10 |
| S2 | BITE11004 Metagenomics | 10 |
| S2 | EPCC11017 Programming Skills | 10 |
| S2 | BILG11016 Introduction to website and database design | 10 |
| S2 | BILG11004 Next Generation Genomics | 10 |
| S2 | PGBI11057 Bioinformatics Algorithms | 10 |

S1: 20 credits; S2: 50 credits; 70 credits in total, equivalent to 700 notional learning hours. This plan does not include the officially strongly recommended PGBI11040; students leaning towards functional genomics could consider replacing one S2 elective with it.

<a id="plan-cs"></a>
## Plan B: Computational Methods and Omics

| Semester | Course | Credits |
|---|---|---:|
| S1 | PGBI11122 Using R for Data Science | 10 |
| S1 | PGBI11129 Biological Databases | 10 |
| S2 | EPCC11017 Programming Skills | 10 |
| S2 | BILG11016 Introduction to website and database design | 10 |
| S2 | PGBI11057 Bioinformatics Algorithms | 10 |
| S2 | BILG11004 Next Generation Genomics | 10 |
| S2 | PGBI11040 Functional Genomic Technologies | 10 |

70 credits and 700 notional learning hours in total. Compared with Plan A, Functional Genomic Technologies replaces Metagenomics, adding training in functional omics methods but also increasing the weight of centrally scheduled written examinations.

**Where there is a clear need for a machine learning course:** Subject to meeting prerequisites, receiving programme approval and timetable compatibility, consider replacing the two S1 courses with INFR11211 Applied Machine Learning (20 credits). This is itself a relatively difficult course and should not be seen as an easy substitute. MATH11205 is not included in this version's recommended combinations; even if notes were permitted in the past, that alone is not enough to judge the course easy.

**An alternative for population/evolutionary genomics:** Consider replacing one S2 10-credit elective with PGBI11126 (S2, 10 credits), rather than adding extra credits. It is not included in this version's lighter-workload combinations because of the demands of stochastic models and the 75% timed computer-based assessment.

These combinations satisfy only the credit arithmetic and course lists visible in the current DPT; they do not constitute registration approval. Prerequisites, places and the actual timetable must be checked. LLM ratings are ordinal, so no purported "average difficulty of earning marks" is calculated, and no promises are made about degree accreditation or employment outcomes.

# Official Resources and Version Notes

- [Bioinformatics MSc 2026/27 DPT](https://www.drps.ed.ac.uk/26-27/dpt/ptmscbioin1f.htm)
- [University of Edinburgh Exam Papers Online](https://exampapers.ed.ac.uk/home)
- [Library: guidance on using exam papers and archive inclusion](https://library.ed.ac.uk/exam-papers)
- [Library: exam paper coverage, exclusions and missing papers](https://library.ed.ac.uk/finding-resources/exams)
- [Applied Machine Learning official open course](https://opencourse.inf.ed.ac.uk/aml)

The courses and official learning hours in this document were rechecked on **2026-08-15**; assessment details and examination paper links were checked on 2026-08-14. Course assessments, teaching semesters, learning-hour categories and paper availability may subsequently change. For formal course selection and examination arrangements, priority should be given to MyEd, Learn, individual timetables and written confirmation from the Programme Director.

Updated: 2026-09-14. Difficulty scores are general, subjective LLM ratings. The DPT, MATH11205 and PGBI11126 pages were checked in this update; other historical statistics retain the findings of the previous compilation and do not represent a new comprehensive verification exercise.
