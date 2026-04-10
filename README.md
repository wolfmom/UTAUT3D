## UTAUT3D
Unified Theory of Acceptance and Use of Technology (UTAUT) extended into a 3D printing education and training context
UTAUT3D CFA/SEM Python

This repository contains a Colab-ready Jupyter notebook that replicates the UTAUT3D measurement and structural analyses originally conducted in SPSS/AMOS, but fully implemented in Python.

## Theoretical Question

This research addresses a central question derived from the Unified Theory of Acceptance and Use of Technology (UTAUT), extended to 3D printing in education and training (UTAUT3D):

Which psychological and contextual factors most strongly predict technology acceptance and use behavior in applied 3D printing education, and how do cognitive ability (spatial reasoning) and industry context (education vs. manufacturing) moderate these relationships?

## Analysis Workflow

Data Input: Accepts Excel survey data (upload, Google Drive, or local path).

Construct Measures: Builds scales for Performance Expectancy (PE), Effort Expectancy (EE), Attitude Toward Technology (ATUT), Self-Efficacy (SE), Behavioral Intention (BI), and Coursework Fit (CF).

Reliability: Computes Cronbach’s alpha for all scales.

Factorability: Performs KMO and Bartlett’s tests.

CFA: Fits the 6-factor UTAUT3D measurement model with semopy (reports CFI, TLI, RMSEA, SRMR, χ²).

Hypothesis Tests: Moderated OLS regressions for

H3: Effort Expectancy × Spatial Reasoning → Behavioral Intention

H4: Attitude × Industry → Behavioral Intention

Plots: Visualizes significant interactions (simple slopes).

Export: Outputs Excel file with reliability, factor loadings, regression summaries, and fit indices.

## Key Findings

Measurement model shows good fit (CFI > .90, RMSEA ~ .06–.07).

High reliability across constructs (α > .80; SE reaches .83 with 3-item subset).

H3 supported: Spatial reasoning strengthens the effect of Effort Expectancy on Behavioral Intention.

H4 supported: Attitude has a stronger effect on Behavioral Intention in manufacturing contexts than in education.

Behavioral Intention strongly predicts Use Behavior, explaining ~75% of variance.

Results mirror SPSS/AMOS findings, confirming robustness of UTAUT3D conclusions.

## How to Use

Open the notebook in Google Colab
.

Set INPUT_METHOD (upload, gdrive, or local) in the first cell.

Run all cells to replicate analyses.

Outputs are saved as:

UTAUT3D_Python_CFA_SEM_Results.xlsx

## Citation

If you use this notebook or results in your work, please cite:

Wolf, E. (2025). UTAUT3D CFA/SEM Replication in Python. GitHub repository.
