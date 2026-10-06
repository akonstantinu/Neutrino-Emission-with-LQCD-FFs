# Hyperonic Direct-Urca Neutrino Emission with Lattice-QCD-Informed Form Factors

This repository contains the numerical and symbolic analysis accompanying:

Andreas Konstantinou,
"Hyperonic Direct-Urca Neutrino Emission with Lattice-QCD-Informed Form Factors",
submitted to The Astrophysical Journal.

## Contents

- `Hyperon_DU_neutrino_emission.ipynb`
  Main Python analysis.
  Computes:
  - FSU2H/FSU2R beta-equilibrated matter
  - direct-Urca thresholds
  - momentum transfer q_F^2
  - direct-Urca emissivities
  - TOV stellar sequences
  - redshifted neutrino luminosities
  - figures used in the manuscript

- `...Mathematica notebook...`
  Symbolic derivation of the six-form-factor spin-summed matrix element.

## Requirements


Main Python packages:
- numpy
- scipy
- pandas
- matplotlib
- gvar

## Reproducing the results

1. Install the Python dependencies.
2. Open the main notebook.
3. Run the notebook from top to bottom.
4. The notebook produces the EOS tables, emissivities,
   stellar sequences, and figures used in the paper.

## EOS models

The main analysis uses the FSU2H relativistic mean-field EOS.
FSU2R is included as an EOS-sensitivity test in Appendix B.

## License

The software in this repository is released under the MIT License.

## Citation

Please cite the associated paper.
