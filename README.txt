%%Electrophysiology datasets (4 files)%%

1. ephys_parameters.mat
  contains:
  - parameters for visual stimuli given in milliseconds
  - acquisition parameters including sampling frequency
    * note that the electrophysiology traces are acquired at 8.33 KHz, so the time base must always be converted from points to ms
   
   
2. examplePC_type1_DS_motion_onset.mat
  - sample dataset from a Purkinje cell with a direction-selective motion onset complex spike phenotype ('group 1')
    - this data is contained as a MATLAB structure organized by trial and includes:
        1) the trace from the Purkinje cell recording 
        2) the ventral root recording
        3) the time base for points to ms conversion (time 0 = when the trigger begins, as there is a slight delay from trace onset)
        4) the condition, 'stimuli' or 'blank' (spontaneous activity, no visual stimuli)
        
3. examplePC_type2_DS_rotational_velocity.mat
  - sample dataset from a Purkinje cell with a direction-selective rotational velocity complex spike phenotype ('group 2')
  - same structure as for #2

4. examplePC_type3_luminance.mat
  - sample dataset from a Purkinje cell with a luminance complex spike phenotype ('group 3')
  - same structure as for #2


%%Functional imaging datasets%%

To come.
