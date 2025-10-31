# WIVERN-ghostnet

WIVERN-Deep-GhostNet is a comprehensive deep learning framework for removing ghost echoes and reconstructing physically consistent radar reflectivity profiles from Doppler radar simulations.

The framework integrates multiple neural architectures, including a CNN-BiLSTM hybrid, 1D U-Net, and 2D U-Net, optimized for different levels of spatial–temporal feature extraction and multi-channel signal correction.

It features a streaming data-loading system for handling very large NetCDF radar datasets and is optimized for HPC GPU training environments.

Developed within the ESA–Earth Explorer 11 WIVERN mission (Wind Velocity Radar Nephoscope), this framework contributes to the Level-1 and Level-2 algorithm development and validation by addressing a key issue, such as:

Ghost-echo contamination and correction

The models have been tested on realistic WIVERN-simulated scenes (e.g., Derecho, Babet, ConstantZgradConstantUgrad), and the pipeline supports real-time analysis and visualization of training and inference results.
