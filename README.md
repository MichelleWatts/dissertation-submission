# Diagnosing Affective Shortcut Behaviour in BERT-Based Misinformation Classification on LIAR

Code and data accompanying the MSc dissertation submitted to the Department of Computer Science, University of Bath, May 2026.


## Repository structure

```
.
├── README.md                                    (this file)
├── LICENSE                                      (MIT)
├── requirements.txt                             (library versions)
├── notebooks/
│   ├── 01_liar_affective_exploration.ipynb     (Section 5.2 of dissertation)
│   ├── 02_liar_baseline_classifier.ipynb       (Section 5.3 of dissertation)
│   └── 03_liar_emotion_diagnostic.ipynb        (Section 5.4 of dissertation)
└── data/
    └── counterfactual_statements.csv            (Appendix B of dissertation)
```


## Data

The LIAR corpus (Wang, 2017) is downloaded automatically by Notebook 01 from the canonical UCSB distribution at `https://www.cs.ucsb.edu/~william/data/liar_dataset.zip`. It is not redistributed in this repository.

The 50-statement counterfactual dataset (`data/counterfactual_statements.csv`) was hand-curated by the dissertation author from established factual claims, with documentation of severity ratings, emotional markers, and source categories. The full curation protocol is described in Section 3.5 and Appendix B of the dissertation.
