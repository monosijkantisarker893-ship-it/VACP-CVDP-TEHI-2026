# VACP-CVDP-TEHI-2026

Reproducibility repository for the research study:

**VACP-CVDP: Shift-Weighted Conformal Reliability for Cross-Version Software Defect Prediction under Temporal Shift**

## Overview

This repository contains the experimental notebook, derived results, and figures used to evaluate cross-version software defect prediction under temporal distribution shift.

The study evaluates:

- Random Forest and Logistic Regression
- Split Conformal Prediction
- Mondrian Conformal Prediction
- Proposed Version-Aware Shift-Weighted Mondrian Conformal Prediction (VA-SWMCP)
- 90% nominal conformal coverage
- Temporal distribution shift
- Exact-overlap-controlled evaluation

## Dataset

The study uses the class-level software defect benchmark introduced by:

M. Jureczko and L. Madeyski,  
“Towards identifying software project clusters with regard to defect prediction,”  
PROMISE 2010.  
DOI: 10.1145/1868328.1868342

The experimental notebook retrieves the selected CSV files from the public
`feiwww/PROMISE-backup` repository.

The GitHub mirror is used only as a reproducible distribution source and is not
claimed as the original source of the dataset.

## Experimental Scope

- 10 open-source Java projects
- 38 software releases
- 28 consecutive cross-version transitions
- 15,071 module-version observations
- Five random source-calibration seeds

## Repository Contents

The repository will contain:

- executable experiment notebook
- seed-level experimental results
- release-pair-level results
- project-level results
- statistical summaries
- figures used in the research paper
