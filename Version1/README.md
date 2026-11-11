# Chiral Coarse-Quantum Framework — Computational Toolkit

[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains the reference implementation for the computational
methods proposed in:

> **Human Consciousness Can Construct the Universe: A Chiral Coarse-Quantum
> Framework and Testable Predictions**  
> Xiaohui Li (Independent Researcher, Baoji, China)  
> ORCID: 0009-0003-8233-7191

## Conceptual framing

The manuscript puts forward a *conceptual* framework, not a proof. Its central
claim is that **consciousness is not a phenomenon inside the universe, nor an
emergent product of matter**, but a trans-universal, pre-geometric field of
information integration. This field is taken to be extremely weak, non-local,
and **not necessarily chiral** in itself. Its relationship to the physical
universe is proposed to occur through the **initial singularity**: a
mathematical point that serves as the simplest and most suitable interface
between an unextended consciousness and a finite cosmos.

After the originating event, the universe expands and, through symmetry
breaking, develops a **chiral organization** that governs its subsequent
evolution—from quantum fields and elementary particles, to biomolecular
homochirality, and possibly to the structural biases observed in human
language.

## What this code does

This repository does *not* model consciousness itself. It implements
testable estimators for the **chiral signatures that the framework predicts
should be detectable inside the universe**. The three main tools are:

1. **Chiral spin-network simulation** (`src/spin_network.py`,
   `cpp/spin_network.cpp`): a statistical-physics toy model showing how a
   small initial chiral bias can be amplified by like-with-like coupling.
2. **CMB chirality estimator** (`src/cmb_chirality.py`): measures
   large-scale helical correlations between E-mode and B-mode spherical-harmonic
   coefficients.
3. **Linguistic chirality index** (`src/linguistic_chirality.py`): quantifies
   a left-handed helical bias in dependency syntax trees, interpreted as a
   possible organizational imprint of a chiral universe on language.

## Important scientific caveat

The theory is exploratory and highly speculative. The code provides
*falsifiable estimators* derived from the framework; it does not prove that
consciousness creates the universe. Results should be interpreted critically.

## Quick start

```bash
git clone https://github.com/xiaohui-li-lab/chiral-coarse-quantum.git
cd chiral-coarse-quantum
pip install -r requirements.txt
