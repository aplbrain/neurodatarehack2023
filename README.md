# NeuroData ReHack 2023

We propose continued secondary analysis of the MICrONS dataset, including the dataset of two-photon calcium imaging hosted on the DANDI archive and the co-registered electron microscopy data hosted in the BossDB archive. In particular, comparison and generation of functional connectivity networks and structural connectivity networks has been under-explored in this dataset, and requires joint analysis across archives. We propose to generate functional connectivity estimates, using a rolling time window, using the two-photon calcium imaging data in the MICrONS dataset to create a sequence of graphs over time and across stimuli conditions. We will utilize an existing table of co-registered neuron IDs, which connect the structural graph derived from the electron microscopy data, to align the functional networks to the structural networks. We will create visualizations of the graphs and characterize common graph metrics in the structural and functional graphs.

If successful, this work will generate novel insight into the stimulus-dependent and time-dependent activation of functional subnetworks. This will also allow direct investigation of causal connectivity estimation using functional data. Follow on work could investigate improvements to functional connectivity estimation methods. Even more exciting, however, is the potential to generate a wide range of hypotheses relating the structure and function of neural networks within mammalian cortex.

## How to run

1. Install python requirements from `requirements.txt`
2. Run `microns_nwb_coreg_demo` notebook for demo 
3. Import `microns_nwb_coreg` script functions for your own use-case!
