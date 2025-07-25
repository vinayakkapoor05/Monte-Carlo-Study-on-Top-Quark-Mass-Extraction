## Monte Carlo Study of Top Quark Mass Extraction

Investigates the impact of event selection on top-quark mass extraction in proton-proton collisions at a center-of-mass energy of 100 TeV, focusing on the dileptonic $t\bar{t}$ decay channel. Analyze event generation, selection, and mass extraction, contributing to physics projections for future high-energy hadron colliders like the FCC-hh.

### Research Paper
The research paper, **"Monte Carlo Study of the Impact of Event Selection on Top-Quark Mass Extraction in the Dileptonic $t\bar{t}$ Decay Channel at $\sqrt{s} = 100$ TeV,"** explores how event selection affects the precision of top-quark mass measurements. The study aims to determine whether selection criteria introduce biases in mass extraction.

### Components
- **Event Generation**: Simulated $t\bar{t}$ production events were generated using **MadGraph5** and **Pythia8**.
- **Event Selection**: Events were selected based on physics-motivated criteria:
  - Two oppositely charged leptons ($e^+e^-, \mu^+\mu^-, e^\pm \mu^\mp$).
  - Leptons with **$p_T > 20$ GeV** and **$|\eta| < 2.5$**.
  - Jets with **$p_T > 20$ GeV** and **$|\eta| < 2.5$**.
  - **Two b-tagged jets** to reduce backgrounds.
  - A **Z+jets veto**: Events with dilepton invariant mass between **76 and 106 GeV** were removed.
- **Top-Quark Mass Extraction**: The **relativistic Breit-Wigner function** was fit to the observed mass distributions of the top quark before and after event selection.

### Results
- The extracted top-quark mass **without event selection**: $252.48 \pm 86.00$ GeV.
- The extracted top-quark mass **after event selection**: $281.24 \pm 103.10$ GeV.
- **Conclusion**: Within uncertainties, the event selection **did not significantly alter the extracted top-quark mass**, indicating that selection effects may not be a major source of bias in high-energy mass measurements.

### Code

This repo includes Python scripts for:
- Applying event selection cuts on **lepton, jet, and b-jet properties**.
- Extracting the top-quark mass using **curve fitting with a relativistic Breit-Wigner function (SciPy's `curve_fit`)**.
