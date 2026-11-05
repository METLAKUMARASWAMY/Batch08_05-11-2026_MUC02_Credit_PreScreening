# MUC02 KLU — submission package

Prepared as an individual submission for Metla Kumara Swamy, following the existing notebook identity.

## Submit

- `MetlaKumaraSwamy_MUC02_KLU_Notebook.ipynb` — executed notebook, CBIM canvas, all seven steps, figures, interpretations and final briefing.
- `MetlaKumaraSwamy_MUC02_KLU_Summary.docx` — one-page insight summary, below 400 words.
- `MUC02_Credit_PreScreening_Dataset.csv` — unchanged supplied dataset, renamed to the assignment's canonical filename; keep beside the notebook.

`MetlaKumaraSwamy_MUC02_KLU_Overall_Report.docx` is the additional overall project report, covering the business problem, methods, findings, threshold, fairness and limitations.

The HTML notebook is an optional read-only preview. The supporting folder contains evidence tables, metrics, tested versions and a requirements audit; these are extras, not additional mandatory reports. No separate presentation or app is required for this individual assignment. Group-only reflections are not applicable to this individual package.

## Reproduce

From this extracted folder:

```sh
python -m venv .venv
# macOS/Linux:
source .venv/bin/activate
# Windows instead: .venv\Scripts\activate
python -m pip install -r requirements.txt
jupyter notebook MetlaKumaraSwamy_MUC02_KLU_Notebook.ipynb
```

Select Restart Kernel and Run All Cells. All code cells were executed in order with a fresh Jupyter kernel; outputs are retained. `supporting/tested_versions.txt` records the environment actually tested, while requirements.txt lists installable dependencies without locking users to that environment. Minor numerical differences across library versions are possible.

## Findings

The required all-applicant threshold is 0.90: 4.66% observed wrong declines, about 456 monthly reviews / 190 hours saved. Retaining every new-to-credit applicant for human review changes this to about 441 reviews / 184 hours and 3.12% wrong among flags. The notebook explains uncertainty, threshold-selection limitations and subgroup errors. These are educational retrospective estimates, not a live-deployment certification.

## Provenance and ownership

Original notebooks and CSV are preserved outside this package. Source assignment documents define the requested deliverables; trainer material was used as context, not as a substitute for computation. The canvas is first, but this revision does not claim it was historically completed before the original code. Review the submission and be prepared to explain the analysis; no invented personal reflection or group contribution is included.
# Batch08_05-11-2026_MUC02_Credit_PreScreening
