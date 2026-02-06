# CMS-open-data-analysis
This project presents a beginner-level analysis of CMS Open Data (Run 2016, √s = 13 TeV) using the DoubleMuon NanoAOD dataset. The goal of the analysis is to reconstruct the Z boson through its decay into a pair of muons (Z → μ⁺μ⁻) using Python-based data analysis tools.

The analysis uses uproot and awkward-array to read and process ROOT NanoAOD files without relying on the CMSSW framework. Events containing at least two muons are selected, and basic kinematic cuts (such as transverse momentum thresholds) are applied. The invariant mass of muon pairs is then computed and visualized, revealing a clear resonance peak around 91 GeV, corresponding to the Z boson.

The project is intended as a learning-focused introduction to experimental particle physics data analysis and serves as a foundation for more advanced studies in collider physics.

Dataset

Experiment: CMS (CERN LHC)

Collision energy: 13 TeV

Run period: 2016 (Run H)

Dataset: DoubleMuon (NanoAOD)

Source: CERN Open Data Portal

DOI: 10.7483/OPENDATA.CMS.UZD7.Z50M

