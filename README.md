# BIT 4131 Statistical Computing and Reporting: Group Work

**Guiding question:** what drives student performance?
**Dataset:** UCI Student Performance, Portuguese course (`data/student-por.csv`, 649 students, 33 columns, no missing values, `;`-separated). Source: Cortez (2008), UCI Machine Learning Repository, CC BY 4.0, https://doi.org/10.24432/C5TG7T

Each topic folder holds an executed Python notebook (with outputs) and a `figures/` folder.
Every notebook follows the six required parts: 1 theory, 2 mathematical formulation, 3 worked example, 4 dataset analysis (code), 5 expected output, 6 interpretation.
For the presentation, share the parts 3 to 6 links below.

| # | Topic | Python notebook | Status |
|---|---|---|---|
| 1 | Central tendency and dispersion | [notebook](01_central_tendency_dispersion/topic01_central_tendency_dispersion.ipynb) | Done |
| 4 | Sampling distributions and CLT | [notebook](04_sampling_distributions_clt/topic04_sampling_distributions_clt.ipynb) | Done |
| 5 | Confidence intervals | [notebook](05_confidence_intervals/topic05_confidence_intervals.ipynb) | Done |

## Where each requirement from the brief is met
Every notebook uses the same section numbers, so the presentation links point to the same place in all three.

| Brief item | Where in each notebook |
|---|---|
| 1. Theoretical explanation | Section 1 |
| 2. Mathematical formulation | Section 2 |
| 3. Worked example (Python) | Section 3: a small hand-computed example, checked against numpy/scipy |
| 4. Dataset analysis | Section 4: analysis of `student-por.csv` |
| 5. Expected statistical output | Section 5: summary table of key results (plots are saved in `figures/`) |
| 6. Interpretation and visualisation | Section 6 (written from the computed results), plus the figures in section 4 |

## How to run
```bash
pip install -r requirements.txt
cd 01_central_tendency_dispersion && jupyter notebook     # open the .ipynb
```
All simulations use a fixed seed (`4131`) so results reproduce.
