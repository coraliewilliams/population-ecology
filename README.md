# Population Ecology Models in R

This repository is set up as a workspace for trying population ecology models from the [NRES 470 course schedule](https://kevintshoemaker.github.io/NRES-470/schedule.html) with R scripts.

## Folder layout

Each model type has its own folder under `/models`, with the same internal structure:

- `data/` for input data, sample datasets, or parameter tables
- `scripts/` for the R scripts that build, fit, or simulate the model
- `outputs/` for figures, tables, and exported results

```text
models/
├── 01_exponential-growth/
│   ├── data/
│   ├── outputs/
│   └── scripts/
├── 02_density-dependent-growth/
│   ├── data/
│   ├── outputs/
│   └── scripts/
├── 03_age-structured-populations/
│   ├── data/
│   ├── outputs/
│   └── scripts/
├── 04_matrix-population-models/
│   ├── data/
│   ├── outputs/
│   └── scripts/
├── 05_stochastic-models/
│   ├── data/
│   ├── outputs/
│   └── scripts/
├── 06_individual-based-models/
│   ├── data/
│   ├── outputs/
│   └── scripts/
├── 07_population-viability-analysis/
│   ├── data/
│   ├── outputs/
│   └── scripts/
├── 08_metapopulations-and-source-sink/
│   ├── data/
│   ├── outputs/
│   └── scripts/
├── 09_mark-recapture/
│   ├── data/
│   ├── outputs/
│   └── scripts/
└── 10_species-interactions/
    ├── data/
    ├── outputs/
    └── scripts/
```

## Suggested topic coverage

These folders group the main model types covered in the course into a structure that works well for R-based experiments:

- `01_exponential-growth`: basic population growth models
- `02_density-dependent-growth`: logistic growth, regulation, and MSY-style exercises
- `03_age-structured-populations`: life-stage or age-class models
- `04_matrix-population-models`: Leslie or Lefkovitch matrix workflows
- `05_stochastic-models`: stochasticity and uncertainty exercises
- `06_individual-based-models`: individual-based simulation experiments
- `07_population-viability-analysis`: PVA case studies and supporting scripts
- `08_metapopulations-and-source-sink`: patch dynamics and source-sink models
- `09_mark-recapture`: capture-mark-recapture and parameter estimation work
- `10_species-interactions`: competition and predator-prey models

## How to use this repo

1. Pick a model folder.
2. Put any input files in `data/`.
3. Write or copy your R code into `scripts/`.
4. Save plots, summaries, and exported results in `outputs/`.

A good starting convention is to name scripts in the order you run them, for example:

- `01_load_data.R`
- `02_fit_model.R`
- `03_plot_results.R`

## Next steps

If you want, the next setup step could be adding starter `.R` scripts for one or more of these model folders.
