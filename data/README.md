
# Dataset Documentation

## Selected dataset

**Initial candidate:** Case Western Reserve University (CWRU)
Bearing Data Center.

**Official source:** https://engineering.case.edu/bearingdatacenter

## Purpose

Use vibration recordings to explore signal characteristics and
develop a reproducible baseline for anomaly detection.

## Data provenance

- Original provider: Case Western Reserve University
- Data type: Bearing vibration measurements
- Formats: Includes MATLAB-format recordings
- Intended use in VibeSense: Initial signal exploration and
  baseline experiments

## Download and licensing

Retrieve recordings from the official data source. Before
redistributing any files, verify the applicable terms and
attribution requirements.

The raw dataset is not stored in this repository.

## Planned preprocessing

1. Identify the relevant vibration channel.
2. Document sampling rate and recording conditions.
3. Inspect missing, corrupted, or unexpected values.
4. Divide signals into documented windows.
5. Keep related recordings separated across evaluation
   splits wherever needed to avoid leakage.

## Current status

Dataset selection is provisional. Exact files, labels,
preprocessing choices, and evaluation splits will be documented
after inspecting the source data.
