# VMC paired parton trial Wavefunctions
Julia implementation of the VMC code used for 'Paired Parton Trial States for the Superfluid-Fractional Chern Insulator Transition' by T. Lotrič and S. H. Simon.

This code is companion to the paper arXiv:2504.20139

Due to the subpar state of the documentation, contact tevz.lotric@physics.ox.ac.uk for help using the code.

'Pf_VMC_parton_wf' includes the variational optimizer, set up to work using Julia's multi-threading.

'MC_ED_WF_Overlap' includes the script to compare the variational WF to the result from ED. The ED wavefunctions are not included, as the files are too large, but they were simply generated using DiagHam.
Note that a minor modification of DiagHam was required, allowing for NN hopping phases different to pi/4 for the checkerboard model.

# Phases of itinerant anyons in Laughlin's quantum Hall states on a lattice

The new paper (arXiv:2603.22389) uses largely the same code base, with some big adjustments.
See "_A_Generalized_Kapit_Mueller_FERMI" and "_A_Generalized_Kapit_Mueller_BOSE" for hole-doping the nu=1/3 and nu=1/2 Laughlin states respectively.
