# EEG-Band-Seperation-and-PSD
EEG composes of 5 bands: delta (1–3 Hz), theta (4–7 Hz), alpha (8–12 Hz), beta (13–30 Hz), and gamma (30–100 Hz).
In EEG, the bands are combined. They can be separated as individual frequency components by appropriate filters and wavelet decomposition.
Here, The program contains Frequency based band separation of ECG by Band pass filter (Butterworth and Chebyshev method) with two channels: O1 - A1, O2 - A2
After band separation Power Spectral Density has been done for each band. Auto-correlation and Cross-correlation between the two channels
For band separation using Wavelet decomposition, refer: https://in.mathworks.com/matlabcentral/answers/108034-wavelet-decomposition-and-power-spectrum-of-an-eeg-signal
PSD can also be implemented for the same.
