# Translation and Cultural Adaptation of the GEQ into Brazilian Portuguese

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![DOI](https://img.shields.io/badge/DOI-Zenodo%3A%20TBD-blue)](https://doi.org/)

Repository containing the article, data, analysis scripts, and supporting materials for:

> **Translation and Cultural Adaptation of the GEQ into Brazilian Portuguese**

**Authors**: *Douglas Fabiano Lourenço, Rogério de Oliveira, Silvana Maria Blascovi de Assis, Ana Grasielle Dionísio Corrêa*

<br>

## Overview

This repository accompanies the study on the translation and cultural adaptation of the **Game Experience Questionnaire (GEQ)** into Brazilian Portuguese.

The study followed a cross-cultural adaptation process based on the guidelines of Beaton et al. (2000), including:

1. Initial translation from English into Brazilian Portuguese;
2. Back-translation into English;
3. Synthesis of the translations;
4. Review by a multidisciplinary expert committee;
5. Pilot testing with the target population;
6. Statistical analysis of the collected data;
7. Final adjustments to the adapted instrument.

The study involved **115 university students** recruited at a private university in São Paulo, Brazil. Participants had experience with electronic games and played education- and health-related serious games developed at the host university.

The statistical analysis included:

- Cronbach's alpha;
- McDonald's omega;
- Exploratory Factor Analysis (EFA);
- Principal component extraction;
- Oblique Promax rotation;
- Kaiser-Meyer-Olkin (KMO) measure;
- Bartlett's test of sphericity.

The results indicated generally adequate reliability and factorial structure for the Brazilian Portuguese adaptation, while also identifying factor-structure instabilities in several GEQ components, consistent with findings reported in previous international studies.

## GEQ modules

The Brazilian Portuguese adaptation covers the three GEQ modules:

- **Core Module (CM)** — 33 items;
- **Post-Game Questionnaire (PGQ)** — 17 items;
- **Social Presence Questionnaire (SPGQ)** — 17 items.

The final Brazilian Portuguese versions are reported in Tables 7–9 of the article.

## Main findings

The sample showed adequate suitability for exploratory factor analysis:

| Module | KMO | Bartlett's test |
|---|---:|---:|
| GEQ Core | 0.844 | p < 0.05 |
| PGQ Post-Game | 0.771 | p < 0.05 |
| SPGQ Social Presence | 0.842 | p < 0.05 |

The overall modules showed high internal reliability:

| Module | McDonald's ω | Cronbach's α |
|---|---:|---:|
| GEQ Core | 0.993 | 0.911 |
| PGQ | 0.978 | 0.812 |
| SPGQ | 0.973 | 0.910 |

Some individual components showed lower reliability, notably:

- Negative Affect (Core Module): α = 0.672;
- Return to Reality (Post-Game): α = 0.394;
- Negative Feeling (Social Presence): α = 0.694.

The EFA also indicated that the empirical factor structure does not always correspond exactly to the theoretical structure of the original GEQ. In particular, the Core Module showed instability in the Challenge and Negative Affect components.

## Repository contents

The repository is intended to contain the following materials:

```text
.
├── README.md
├── CITATION.cff
├── LICENSE
│
├── article/
│   └── GEQ_Portuguese_Adaptation.pdf
│
├── data/
│   ├── README.md
│   └── [raw and/or anonymized pilot data]
│
├── code/
│   ├── README.md
│   └── [R analysis scripts]
│
├── results/
│   ├── README.md
│   ├── tables/
│   └── figures/
│
└── instrument/
    ├── GEQ_Core_Brazilian_Portuguese.pdf
    ├── GEQ_Post_Game_Brazilian_Portuguese.pdf
    └── GEQ_Social_Presence_Brazilian_Portuguese.pdf
```

The exact filenames and organization may be adjusted as the repository is finalized.

## Article

The manuscript included in this repository is:

**Lourenço, D. F., de Oliveira, R., Blascovi de Assis, S. M., & Corrêa, A. G. D. (2027). Translation and Cultural Adaptation of the GEQ into Brazilian Portuguese. Journal on Interactive Systems, 18(1).**

- [Article PDF](article/GEQ_Portuguese_Adaptation.pdf)
- Journal DOI: `10.5753/jis.2027.XXXX` *(replace with the final DOI after publication)*

## Tables and results

The article contains the following main tables:

| Table | Content | Location in article |
|---|---|---|
| Table 1 | Sample characterization (n = 115) | Section 3.1 |
| Table 2 | KMO and Bartlett's test | Section 4 |
| Table 3 | GEQ Core Module — rotated pattern matrix | Section 4.1 |
| Table 4 | PGQ — rotated pattern matrix | Section 4.2 |
| Table 5 | SPGQ — rotated pattern matrix | Section 4.2 |
| Table 6 | Internal reliability: ω, α, and 95% CI | Section 4.3 |
| Table 7 | Brazilian Portuguese GEQ Core Module | Section 5 |
| Table 8 | Brazilian Portuguese Post-Game GEQ | Section 5 |
| Table 9 | Brazilian Portuguese Social Presence GEQ | Section 5 |

If machine-readable versions of the tables are added to this repository, links will be provided here, for example:

- `results/tables/table_01_sample_characterization.csv`
- `results/tables/table_02_efa_adequacy.csv`
- `results/tables/table_03_geq_core_pattern_matrix.csv`
- `results/tables/table_04_pgq_pattern_matrix.csv`
- `results/tables/table_05_spgq_pattern_matrix.csv`
- `results/tables/table_06_reliability.csv`

At the time of repository creation, these paths are placeholders and should only be linked after the corresponding files have been added.

## Data

The repository is intended to provide the pilot-study data used in the analyses reported in the article.

**Data repository:** `[Zenodo DOI — to be added]`

Before publication of participant-level data, the authors should ensure that the released dataset is fully consistent with the approved ethics protocol and informed-consent terms and that no directly or indirectly identifying information is included.

## Analysis code

The statistical analyses were conducted in **R**.

**Code:** `[GitHub / code directory — to be added]`

The analysis scripts should reproduce, as applicable:

- data preparation;
- descriptive analyses;
- KMO and Bartlett's tests;
- exploratory factor analyses;
- Promax rotations;
- communalities and factor loadings;
- Cronbach's alpha;
- McDonald's omega;
- confidence intervals;
- tables and figures reported in the article.

## Reproducibility

To reproduce the analyses:

1. Clone this repository.
2. Install the R dependencies listed in `code/README.md` or the project dependency file.
3. Obtain the dataset described in `data/README.md`.
4. Run the analysis scripts in the documented order.
5. Generated tables and figures should be written to the `results/` directory.

The repository will distinguish between:

- **raw data** — original participant-level data, where ethically and legally shareable;
- **processed data** — cleaned or transformed data used by the analyses;
- **analysis code** — scripts required to reproduce the statistical analyses;
- **derived results** — tables, figures, and intermediate outputs.

## Ethics and participant data

The study was approved by the Institutional Human Research Ethics Committee of the host university. Participants provided written informed consent, and confidentiality and anonymity were guaranteed.

Ethics information in the manuscript:

- CAAE: `[ANONYMIZED FOR PEER REVIEW]`
- Ethical framework: Brazilian National Health Council, CNS Resolution 510/2016.

The public release of any participant-level data must preserve the confidentiality and anonymity commitments made during the study and comply with the applicable ethics approval.

## Citation

If you use the code, data, or adapted instrument from this repository, please cite the associated article and the archived repository version.

**Article citation:** to be updated with the final bibliographic information after publication.

**Repository DOI:** `[Zenodo DOI — to be added]`

A machine-readable citation is provided in [`CITATION.cff`](CITATION.cff).

## License

The article states that the work is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

The license for code and data may be specified separately if appropriate. In particular, the authors should consider using a software license for source code and an appropriate data license for datasets rather than assuming that the article's CC BY license is automatically the best license for every repository component.

## Acknowledgements

[Add acknowledgements, funding information, institutional support, and/or grant information here.]

## Contact

For questions regarding the study, adapted instrument, data, or analysis code, please contact the corresponding author:

**Douglas Fabiano Lourenço**  
Mackenzie Presbyterian University  
Email: douglas.fab@gmail.com

