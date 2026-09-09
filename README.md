# Translation and Cultural Adaptation of the GEQ into Brazilian Portuguese

<!-- <a href="url"><img src="https://github.com/GEQ-Portuguese-Adaptation/geq-portuguese-adaptation/blob/main/others/GEQ_img.png?raw=true" align="right" width="200" ></a> -->

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22681094.svg)](https://doi.org/10.5281/zenodo.22681094)

Repository containing the article, data, analysis scripts, and supporting materials for:

> **Translation and Cultural Adaptation of the GEQ into Brazilian Portuguese**

**Authors**: *Douglas Fabiano Lourenço, Rogério de Oliveira, Silvana Maria Blascovi de Assis, Ana Grasielle Dionísio Corrêa*

<br>
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
| PGQ Post-Game | 0.978 | 0.812 |
| SPGQ Social Presence | 0.973 | 0.910 |

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
├── GEQ_translation_complete_analysis.ipynb
│
├── article/
│   ├── GEQ_Portuguese_Adaptation.pdf
|   └── GEQ_Portuguese_Adaptation.zip 
│
├── data/
│   ├── GEQ_Core.xlsx
│   ├── GEQ_Final_Translation_all_modules.xlsx
│   ├── PSQ_Post-Game.xlsx
│   ├── SPGQ_Social_Presence.xlsx
│   └── population_info.xlsx
│ 
└── others/
    ├── CEP_7176627.pdf
    └── GEQ_img.png

```

## Data & Analysis code

* **Data repository:** [`https://doi.org/10.5281/zenodo.22681094`](https://doi.org/10.5281/zenodo.22681094) The repository is intended to provide the data used in the analyses reported in the article.

* **Analysis code:** The statistical analyses were conducted in **Python**, all scripts are available in a Python [notebook](https://github.com/GEQ-Portuguese-Adaptation/geq-portuguese-adaptation/blob/main/GEQ_translation_complete_analysis.ipynb).

* **Final translation:** Here the [final translation and cultural adaptation of the GEQ into brazilian portuguese](https://github.com/GEQ-Portuguese-Adaptation/geq-portuguese-adaptation/blob/main/data/GEQ_Final_Translation_all_modules.xlsx).

## Ethics and participant data

The study was approved by the Institutional Human Research Ethics Committee of the host university ([CAAE: 83094424.6.0000.0084](https://github.com/GEQ-Portuguese-Adaptation/geq-portuguese-adaptation/blob/main/others/CEP_7176627.pdf)). Participants provided written informed consent, and confidentiality and anonymity were guaranteed. 

## Article & Citation

Lourenço, D. F., de Oliveira, R., Blascovi de Assis, S. M., & Corrêa, A. G. D. (2027). [Translation and Cultural Adaptation of the GEQ into Brazilian Portuguese](https://github.com/GEQ-Portuguese-Adaptation/geq-portuguese-adaptation/blob/main/article/GEQ_Portuguese_Adaptation.pdf). Journal on Interactive Systems, 18(1). DOI: [`10.5753/jis.2027.XXXX`]() *(it will be replaced after publication)*

<br>

## Contact

For questions regarding the study, adapted instrument, data, or analysis code, please contact the corresponding author [**Douglas Fabiano Lourenço**](mailto:douglas.fab@gmail.com). 

