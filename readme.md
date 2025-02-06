# Monte Carlo Study of Top Quark Mass Extraction

This project investigates the impact of event selection on top-quark mass extraction in proton-proton collisions at a center-of-mass energy of 100 TeV, focusing on the dileptonic \(\text{t}\bar{\text{t}}\) decay channel. The study employs Monte Carlo simulations to analyze event generation, selection, and mass extraction in preparation for future high-energy hadron colliders like the FCC-hh.

## Project Overview

### Research Paper
The accompanying research paper, titled "Monte Carlo Study of the Impact of Event Selection on Top-Quark Mass Extraction in the Dileptonic \(\text{t}\bar{\text{t}}\) Decay Channel at \( \sqrt{s} = 100 \) TeV," explores how event selection affects the precision of top-quark mass measurements. The study examines the behavior of top-quark production at high-energy scales and aims to evaluate whether event selection introduces significant biases in mass extraction.

### Project Components
- **Event Generation**: Simulated \(\text{t}\bar{\text{t}}\) production events were generated using Monte Carlo event generators (MadGraph5 and Pythia8), with a focus on dileptonic decays.
- **Event Selection**: Physics-based selection cuts were applied, including criteria on lepton and jet \(p_T\) and isolation, to isolate signal events from background noise. The event selection aimed to optimize the purity of the signal while maintaining sufficient event statistics.
- **Top-Quark Mass Extraction**: The top-quark mass was extracted from the simulated events using a relativistic Breit-Wigner distribution. Curve-fitting techniques were applied to measure the top-quark mass before and after event selection to assess the impact of selection criteria.

### Results
The analysis showed that the top-quark mass extracted before and after event selection remained consistent within uncertainties, indicating that event selection does not significantly impact the mass measurement at high-energy scales. 

## Code

This repository includes Python scripts to:
- Generate Monte Carlo events using external event generators.
- Apply event selection criteria.
- Fit the top-quark mass distribution using a relativistic Breit-Wigner function.