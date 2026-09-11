# Organism Stability Disruption (OSD) Cancer Reset Axis

This repository contains the reproducibility package for the manuscript:

**Organism Stability Disruption as a Testable Cancer Reset Axis: A data-anchored hypothesis of pathological repair-state stabilization, clinical resistance, and laboratory-replicable state reversal**

The manuscript does **not** claim that a universal cancer cure has been discovered. It introduces a falsifiable, data-anchored framework for measuring pathological repair-state stabilization across cancer datasets and for translating that framework into mechanistic laboratory tests.

## Repository Contents

- `manuscript/`: LaTeX manuscript with all current TikZ figures embedded directly in `main.tex`.
- `scripts/`: Python analysis scripts used during the computational validation workflow.
- `results/`: JSON/CSV result summaries generated from public datasets.
- `reports/`: Human-readable validation reports and experiment summaries.
- `metadata/`: Data source manifest and reproducibility notes.
- `workflow/`: Environment and container scaffolding for reproducible execution.

## Primary Evidence Layers

1. TCGA/GTEx tumor-normal OSD testing.
2. TCGA PanCancer Atlas survival modeling.
3. IMvigor210 immunotherapy response and survival validation.
4. GSE78220 melanoma anti-PD-1 baseline validation.
5. DepMap/PRISM/LINCS perturbational and dependency analyses.
6. Public 10x Visium spatial proof-of-concept.
7. Prospective organoid/PDX reset-rechallenge protocol.

## Reproducibility Philosophy

Large raw datasets are not committed to this repository. Instead, the repository records public source names, scripts, result tables, locked module definitions, analysis outputs and workflow scaffolding.

This is intentional: TCGA, GTEx, DepMap, PRISM, GEO, 10x Genomics and IMvigor210 should be retrieved from their public or license-governed sources rather than redistributed here.

## Key Output Files

- `manuscript/main.tex`
- `results/organism_reset_axis_survival_results.json`
- `results/imvigor210_reset_validation_results.json`
- `results/gse78220_baseline_reset_validation_results.json`
- `results/visium_multisample_governance_validation_results.json`
- `reports/lab_replicable_reset_validation_protocol.md`

## Citation and DOI

Before journal submission, this repository should be archived with Zenodo to mint a permanent DOI.

**Zenodo DOI:** pending

## Clinical Scope

This repository is for research reproducibility only. It does not provide medical advice, treatment recommendations, or evidence of clinical efficacy for any proposed intervention.
