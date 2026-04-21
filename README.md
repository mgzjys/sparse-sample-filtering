# Improving Malaria Parasite Gene Flow Inference Under Sparse Spatial Sampling

This repository contains data, code, and figures associated with the study on improving spatial gene flow inference for *Plasmodium falciparum* under sparse and uneven spatial sampling.

## Overview

The project develops and evaluates a sample location-aware (SLA) filtering workflow designed to improve the reliability of inferred spatial migration patterns from georeferenced genomic data. The repository includes simulation inputs, simulation outputs, empirical results from Cambodia, analysis code, and manuscript figures.

## Repository Structure

- `code/`  
  Scripts for data processing, simulation, filtering, and analysis.

- `figures/`  
  Figures used in the manuscript and related materials.

- `input_data/`  
  Input data used for simulation experiments.

- `simulated_results/`  
  Output files from simulation experiments and empirical analyses.

## Zenodo Archive

Archived dataset record:  
https://zenodo.org/records/19683797

The Zenodo record includes the following files:

- `3-hex_pattern_simulation.zip`  
  Input data for simulations based on a 3-hex spatial pattern using simulated *P. falciparum* genomic data.  
  MD5: `16047297ea79519adf17f3a49ead521e`

- `random_pattern_simulation.zip`  
  Input data for simulations based on a random spatial pattern using simulated *P. falciparum* genomic data.  
  MD5: `368e70b4d8faf7cb09ff7de9c0680b22`

- `3-hex_simulation_results.zip`  
  Simulation results generated from the 3-hex spatial pattern.  
  MD5: `2a7f411a45acd41aa64347b6de01a428`

- `random_pattern_simulation_results.zip`  
  Simulation results generated from the random spatial pattern.  
  MD5: `9d30e1612f6e7b0883b514b74ff0b51d`

- `Cambodia_simulation_results.zip`  
  Simulation results for the empirical case study based on *P. falciparum* genomic data from Cambodia.  
  MD5: `ea565bf803a743377d4e5aa9479add11`

## Study Focus

This repository supports analyses of malaria parasite gene flow inference under sparse spatial sampling, with an emphasis on identifying and filtering spatial features that are weakly supported by sample locations.

## Keywords

*Plasmodium falciparum*, malaria, gene flow, EEMS, MAPS, spatial sampling, landscape genomics

## Citation

If you use these materials, please cite the associated manuscript and the Zenodo record.

**Manuscript:**  
Li, Y., Guo, B., O’Connor, T. D., Takala-Harrison, S., and Stewart, K.  
*Improving malaria parasite gene flow inference under sparse spatial sampling.*

## Contact

**Dr. Yao Li**  
Department of Earth, Environmental, and Geographical Sciences  
University of North Carolina at Charlotte  
Email: yao.li@charlotte.edu