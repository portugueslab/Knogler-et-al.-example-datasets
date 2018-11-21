1. Electrophysiology datasets

The file "electrophysiology.mat" contains
  - parameters for visual stimuli given in milliseconds
  - acquisition parameters including sampling frequency
    * note that the electrophysiology traces are acquired at 8.33 KHz, so the time base must always be converted from points to ms
  - sample datasets from 3 Purkinje cells, one from each visual complex spike phenotype
    - this data is contained as a MATLAB structure organized by trial and includes:
        1) the trace from the Purkinje cell recording 
        2) the ventral root recording
        3) the time base for points to ms conversion (time 0 = when the trigger begins, as there is a slight delay from trace onset)
        4) the condition, 'stimuli' or 'blank' (spontaneous activity, no visual stimuli)
        
2. Functional imaging datasets

To come.
