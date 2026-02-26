Results

This study compared AI-generated and human learner (CEFR B1) texts using three core syntactic complexity measures: Mean Length of Sentence (MLS), Mean Length of T-unit (MLT), and Clausal Subordination (CS). Descriptive and inferential statistical analyses were conducted in R.

The results indicate clear structural differences between AI-generated and human-written texts at the B1 proficiency level.

For Mean Length of Sentence (MLS), a Wilcoxon rank-sum test revealed a statistically significant difference between the two groups (p < .001). AI-generated texts produced systematically different sentence length patterns compared to human learner writing, suggesting measurable divergence in sentence structuring.

For Clausal Subordination (CS), an independent samples Welch t-test showed a highly significant difference between AI and human texts (p < .001). This indicates that the groups differ in clause-level complexity and subordination patterns, reflecting distinct structural organization strategies.

In contrast, Mean Length of T-unit (MLT) did not show a statistically significant difference (p > .05). This suggests that while overall sentence length and clause embedding differ, T-unit expansion at the B1 level appears comparable between AI-generated and human learner texts.

Overall, the findings demonstrate that AI-generated texts at the CEFR B1 level exhibit distinct syntactic patterns compared to authentic learner production. These structural differences remain statistically detectable despite the increasing fluency and surface-level similarity of AI-generated writing.
## Data Source and Methodology
Data Source and Methodology

Data Source

The human learner texts were extracted from the EFCAMDAT (EF Cambridge Open Language Database), a large-scale learner corpus containing English learner writings across CEFR proficiency levels. For this study, only CEFR B1-level texts were selected in order to ensure proficiency control and comparability.

A balanced dataset was constructed consisting of:
	•	Human learner texts (CEFR B1)
	•	AI-generated texts produced under controlled prompts simulating B1-level writing

All texts were controlled for topic and length to minimize confounding variation and to allow structural comparison under equivalent conditions.

⸻

Structural Complexity Measures

Three established syntactic complexity metrics from Second Language Acquisition (SLA) research were used:
	•	Mean Length of Sentence (MLS) – measuring overall sentence expansion.
	•	Mean Length of T-unit (MLT) – measuring clausal development within minimal terminable units.
	•	Clausal Subordination (CS) – measuring the degree of clause embedding and subordination.

These metrics are widely used in developmental and corpus-based research to quantify structural sophistication in learner writing.

⸻

Analytical Procedure

The analysis was conducted in R using the following steps:
	1.	Data cleaning and preprocessing.
	2.	Group-level descriptive statistics (mean, standard deviation).
	3.	Normality testing using Shapiro–Wilk tests.
	4.	Selection of appropriate inferential tests:
	•	Welch t-test for normally distributed variables.
	•	Wilcoxon rank-sum test for non-normal distributions.
	5.	Visualization using boxplots with group means.

All statistical decisions were based on distributional assumptions and sample characteristics to ensure methodological rigor.

⸻

Research Design Rationale

By focusing on a single proficiency level (CEFR B1), this study isolates structural differences attributable to authorship (AI vs human) rather than developmental stage. This controlled design allows for a feature-level comparison grounded in established syntactic complexity metrics.

The methodological approach bridges corpus linguistics, SLA-based complexity measurement, and statistical modeling to evaluate whether AI-generated texts remain structurally distinguishable from authentic learner production.
