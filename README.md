# waveform_classification
Discription: Waveform classifcation with extracellular recordings in mouse brain using Neuropixels probes

This repo include supplemental materials, data and code used in JNP paper:

  High-density extracellular probes reveal dendritic backpropagation and facilitate neuron classification
  https://doi.org/10.1152/jn.00680.2018
  

Data includes:
>    1. multi-channel waveforms
>    2. single-channel waveforms
>    3. extracted features and cluster labels
>    4. velocity profiles


Codes used to process multi-channel waveform features and quality metrics are in the ecephys_spike_sorting repo:
https://github.com/AllenInstitute/ecephys_spike_sorting/tree/master/ecephys_spike_sorting/modules/mean_waveforms


The quality metrics and waveform features developed in this paper are included in the unit_table of publicly released Neuropixels dataset, which can be accessed through AllenSDK:
https://github.com/AllenInstitute/AllenSDK/tree/master/allensdk/brain_observatory/ecephys

