# CMS-open-data-analysis
This project presents a beginner-level analysis of CMS Open Data (Run 2016, √s = 13 TeV) using the DoubleMuon NanoAOD dataset. The goal of the analysis is to reconstruct the Z boson through its decay into a pair of muons (Z → μ⁺μ⁻) using Python-based data analysis tools.

The analysis uses uproot and awkward-array to read and process ROOT NanoAOD files without relying on the CMSSW framework. Events containing at least two muons are selected, and basic kinematic cuts (such as transverse momentum thresholds) are applied. The invariant mass of muon pairs is then computed and visualized, revealing a clear resonance peak around 91 GeV, corresponding to the Z boson.

The project is intended as a learning-focused introduction to experimental particle physics data analysis and serves as a foundation for more advanced studies in collider physics.

# Dataset

Experiment: CMS (CERN LHC)

Collision energy: 13 TeV

Run period: 2016 (Run H)

Dataset: DoubleMuon (NanoAOD)

Source: CERN Open Data Portal

DOI: 10.7483/OPENDATA.CMS.UZD7.Z50M

# Objectives

Learn how to work with real collider data

Read and process ROOT NanoAOD files using Python

Select physics objects (muons) and events

Reconstruct invariant mass of dimuon pairs

Observe the Z boson resonance peak

# Methodology

1. Load NanoAOD ROOT files using uproot

2. Extract muon kinematic variables (pt, eta, phi, charge)

3. Select events with at least two muons

4. Apply basic transverse momentum cuts

5. Compute the dimuon invariant mass

6. Plot the invariant mass distribution

A clear peak around 91 GeV is observed, corresponding to the Z boson.

# Tools & Libraries

Python

uproot

awkward-array

numpy

matplotlib

# Learning Outcomes

Hands-on experience with CMS Open Data

Introduction to experimental particle physics analysis

Understanding invariant mass reconstruction

Practical use of HEP Python tools

# Acknowledgements

Data provided by the CMS Collaboration via the CERN Open Data Portal.
This work is not endorsed by CMS or CERN.

