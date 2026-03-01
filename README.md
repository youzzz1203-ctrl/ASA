# ASA: Antibody-Semantic Alignment for H&E-to-IHC Virtual Staining

This repository contains the official implementation of the paper:

**"Antibody-Guided Chromogenic Adaptation for Pathology-Semantic Consistent H&E-to-IHC Translation"**  

## Overview
ASA is a biologically interpretable virtual staining framework for translating Hematoxylin & Eosin (H&E) images into Immunohistochemistry (IHC) images.

Unlike conventional image-to-image translation methods that rely purely on visual correspondence, ASA explicitly integrates:

Antibody-aware global feature reweighting (ACRA)

Spatially coherent chromogenic adaptation (SCA)

Protein-related optical density supervision (PRDS)

The framework is evaluated on paired H&E–IHC datasets and further validated through downstream protein expression classification.

## Status

The complete source code, training scripts, and evaluation pipelines will be publicly released upon formal publication of the manuscript.

## Acknowledgements

We would like to acknowledge the following projects that have contributed to our work:
This project is built upon the work of [CEFF](https://github.com/babyinsunshine/CEFF). We thank the authors for making their code available.

## Contact

For any questions, please contact: youzzz1203@gmail.com
