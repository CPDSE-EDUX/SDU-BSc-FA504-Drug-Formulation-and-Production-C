# FA504: Drug Formulation and Production C

Data science material for **FA504 Drug Formulation and Production C** (BSc Pharmacy, University of Southern Denmark). The material shows students how to analyse experimental data in R and write their lab reports in Quarto.

This repository holds the R and Quarto material only. The full course material, including the lab manual and the course schedule, lives in itslearning.

The student-facing documents are written in Danish.

## Structure

```
├── caco2_permeability/             Exercise class: Caco-2 permeability (first R analysis)
├── lab/
│   ├── exercise1_erythrocytes/       Osmolytes, erythrocyte volume and hemolysis
│   ├── exercise2_nicotinate_release/ In vitro release of nicotinates from ointment bases
│   └── exercise3_asa_stability/      Accelerated stability of acetylsalicylic acid
├── report/
│   ├── quarto_guide/                 How to write the lab report in Quarto
│   ├── template/                     Lab report template (renders to Word)
│   └── example_caco2/                Complete example report
├── CHANGELOG.md
├── CITATION.cff
├── LICENSE                           CC BY 4.0 (teaching content)
└── LICENSE-code                      MIT (code)
```

Each folder is self-contained: the guide and the files it needs sit together, so students can download a single folder and work from it.

Exercise 4 (sterile preparation of eye drops) is mainly practical and has no R material.

## Suggested order

1. `caco2_permeability/`: first hands-on R analysis, done in an exercise class on a provided data set.
2. `report/quarto_guide/`: read before writing the first report.
3. `lab/exerciseX_.../`: data processing guide for each lab exercise.
4. `report/template/`: start each lab report from this template; see `report/example_caco2/` for a finished example.

## Setup

You need:

- [R](https://cran.r-project.org/) (version 4.3 or newer)
- [RStudio](https://posit.co/download/rstudio-desktop/) (includes Quarto)
- Microsoft Word, to open the rendered reports
- [Zotero](https://www.zotero.org/) (optional, for references)

Install the R packages used in the course:

```r
install.packages(c("tidyverse", "readxl", "knitr"))
```

## Versions

The `main` branch holds the material for the current year. When a course run ends, it is archived in a branch named after the year (for example `2026`). See [CHANGELOG.md](CHANGELOG.md) for what changed between years.

## Citation and license

If you reuse or adapt the material, please cite it using [CITATION.cff](CITATION.cff) (GitHub shows a "Cite this repository" button).

Teaching content is licensed under [CC BY 4.0](LICENSE) and code under [MIT](LICENSE-code).

Part of the [CPDSE](https://github.com/CPDSE-EDUX) teaching material from the Center for Pharmaceutical Data Science Education.
