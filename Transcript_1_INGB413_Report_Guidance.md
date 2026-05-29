# Interpretation of Transcript 1 for the INGB413 2026 Tangra Inc. Report

## 1. Main message from the lecturer

The lecturer is saying that the assignment is not only about calculating charts. It is about showing that you can conduct an engineering investigation. This directly links to ECSA Graduate Attribute 4, which requires research methods, design of experiments, analysis and interpretation of data, and valid conclusions.

Your report must therefore show a logical investigation:

**Process understanding → data classification → correct statistical tool selection → analysis → interpretation → conclusion and recommendation.**

## 2. What you must do before analysing the data

The lecturer emphasises that you must first map and understand the process, not jump straight into calculations.

For each process, ask:

1. What is the first step in the process?
2. What is the second step?
3. What is the third step?
4. What type of data was collected?
5. Is the data attribute or variable data?
6. Is the data counting defectives or counting defects?
7. Which control chart fits that type of data?
8. What does the result say about the process?

This is important because the 2026 assignment requires you to test two different sampling processes for Tangra Inc. and investigate whether enough tangrams can be assembled while identifying defective pieces efficiently.

## 3. Key distinction: defect versus defective

This is one of the most important parts of the transcript.

A **defect** is a specific nonconformity, for example one scratch, one wrong edge, one incorrect shape, or one piece that does not fit.

A **defective item** is an item that is unacceptable because it contains one or more serious defects.

For Tangra Inc.:

| Concept | Meaning in this assignment |
|---|---|
| Defect | A puzzle piece does not fit the required figurine shape or size |
| Defective piece | A tangram piece that cannot be used in the figurine |
| Defective assembly | A full figurine or tangram set that cannot be completed correctly because one or more pieces are defective |

This distinction matters because it determines whether you use a **p-chart, np-chart, c-chart, u-chart, or g-chart**.

## 4. Process 1: likely chart logic

The 2026 assignment states that Process 1 involves receiving raw material in bulk, taking samples of 5, testing for defects, removing defective parts, and assembling the figurine.

Because Process 1 uses a fixed sample size of **n = 5**, and each piece is classified as either defective or non-defective, this is **attribute data**.

Best chart choice:

**p-chart** if you analyse the proportion defective per sample.

Alternative:

**np-chart** if the sample size is constant and you analyse the number of defective pieces per sample.

For your report, the safer and more flexible choice is usually:

**p-chart for Process 1**, because you can express the defect rate as a proportion and compare it to the 2-sigma requirement.

## 5. Process 2: likely chart logic

The 2026 assignment states that Process 2 uses raw material already sorted, parts are picked from bins, a figurine is assembled, and defective pieces are identified during assembly.

The lecturer strongly hints that Process 2 can be treated differently from Process 1 because you may be counting how many acceptable pieces or assemblies occur before a defect appears.

Best chart choice:

**g-chart** if your data records the number of non-defective pieces or successful placements before a defective piece occurs.

Alternative:

**u-chart** if you count defects per varying opportunity size.

However, based on the lecturer’s explanation and examples from last year, the stronger choice for Process 2 is usually:

**g-chart**, because it fits “number of conforming items before the first nonconforming item”.

## 6. What the lecturer means by Phase 1 and Phase 2 control charting

The lecturer explains that you first collect preliminary data, calculate the first control limits, and look for unusual or assignable causes.

In your report, this means:

**Phase 1:** Use your collected experiment data to estimate the process average and calculate control limits.

**Assignable causes:** Identify any unusual observations. For example:

- wrong inspection method
- incorrect assembly protocol
- confusion between colours
- fatigue
- material shortage
- wrong bin arrangement
- learning effect during the first few minutes
- defective batch from a supplier
- process interruption

**Phase 2:** Comment that proper monitoring would require future data collection after removing assignable causes. Since this is an exam assignment with limited time, state that only a Phase 1 study was possible.

This is useful because it shows maturity. You are not pretending that one short experiment proves permanent process control.

## 7. Process capability and 2-sigma requirement

The assignment requires you to determine whether the process can run at a **2-sigma level in terms of defective parts per million**.

The lecturer’s key point is that:

- Control limits show whether the process is statistically stable.
- Specification limits or sigma capability show whether the process meets the required performance standard.
- A process can be statistically stable but still incapable.
- A process can be in control but still produce too many defective pieces.

Your report must therefore not stop at control charts. You must also calculate or discuss:

- defect proportion
- DPMO or DPPM
- sigma level comparison
- whether the process meets the 2-sigma target
- which process is better for Tangra Inc.

## 8. Profitability and operational interpretation

The lecturer also wants interpretation, not only statistics.

You should explain why one process may be better from a business perspective:

| Process | Likely advantage | Likely disadvantage |
|---|---|---|
| Process 1 | Defects are removed before assembly, reducing wasted assemblies | Takes time to inspect samples before assembly |
| Process 2 | Faster start because pieces are already sorted | If a defect is found late, more pieces and time are wasted |

This links directly to the assignment context, where Tangra Inc. must maintain demand while identifying defective parts efficiently.

## 9. Strong report structure based on the transcript

Use this logic in your report:

### Background

Introduce Tangra Inc., customer complaints, defective pieces, demand pressure, quality reputation, and the need to compare two processes.

### Problem statement

Tangra Inc. must identify defective tangram pieces efficiently while assembling enough figurines to meet demand.

### Aim and objectives

Aim: To compare Process 1 and Process 2 using quality management and SPC techniques to determine the better process.

Objectives:

- define the CTQ requirement
- map both processes
- classify the data
- select appropriate control charts
- analyse process stability
- evaluate sigma capability
- compare cost and productivity
- recommend the better process

### CTQ and data classification

Define the CTQ as correct fitting of each tangram piece into the required figurine. Explain whether each dataset is attribute data, variable data, defect data, or defective data.

### Experimental procedure

Describe Process 1 and Process 2 exactly as performed.

### Data analysis

Include descriptive statistics, charts, control charts, DPMO/sigma analysis, and hypothesis testing if appropriate.

### Discussion

Explain what the charts mean, what assignable causes may exist, and why one process performs better.

### Recommendation

Recommend the better process based on quality, throughput, capability, waste, and profitability.

### Conclusion

Return directly to GA 4: investigation, data analysis, interpretation, and valid conclusion.

## 10. Best way to use this transcript in your report

Do not cite the transcript as an academic source. Use it as guidance for your analysis logic.

The transcript tells you what the lecturer expects:

- show the process
- classify the data correctly
- justify the chart choice
- explain CTQ
- interpret trends
- discuss assignable causes
- compare capability
- conclude which process is better
- do not only paste Excel outputs

Your strongest report will be one that reads like an engineering investigation, not like a statistics worksheet.
