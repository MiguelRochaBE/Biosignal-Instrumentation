# Biosignal-Instrumentation

This project entails the MultiSim simulation files of circuits developed to acquire Electrocardiogram (ECG) and Electroencephalographam (EEG). 

Once validated, the EEG circuit was implemented on a breadboard and the signal was acquired at one scalp position (F8), with electrode F7 establishing the system's reference and another on the left arm for noise cancelling purposes (Common Mode Rejection Ratio).

The hardware conditioned (amplified and filtered) EEG signal was then digitized and processed in real-time with LabVIEW, where each frequency band associated with the EEG was seperated and quantified every 2 seconds, with additional real-time plotting of the frequency spectrum.

In the EEG folder, a 3 page ".pdf" file is provided overviewing the the whole system development and integration. 
