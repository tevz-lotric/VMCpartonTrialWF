# VMC paired parton trial Wavefunctions
Julia implementation of the VMC code used for 'Paired Parton Trial States for the Superfluid-Fractional Chern Insulator Transition' by T. Lotrič and S. H. Simon.

This code is companion to the paper arXiv:2504.20139

Due to the subpar state of the documentation, contact tevz.lotric@physics.ox.ac.uk for help using the code.

'Pf_VMC_parton_wf' includes the variational optimizer, set up to work using Julia's multi-threading.

'MC_ED_WF_Overlap' includes the script to compare the variational WF to the result from ED. The ED wavefunctions are not included, as the files are too large, but they were simply generated using DiagHam.
Note that a minor modification of DiagHam was required, allowing for NN hopping phases different to pi/4 for the checkerboard model.
