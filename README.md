# Compare_D_V

#
The motor and sensory axon models are based on the framework of the MRG model and the ion channels provided by Gaines.  
Before using the axon models, the mod files need to be compiled.  

https://senselab.med.yale.edu/ModelDB/showmodel.cshtml?model=3810#tabs-1.  
https://modeldb.science/243841?tab=1  

motor_fiber.hoc
sensory_fiber.hoc

#  
stim_bipha_square.hoc contains the stimulation waveform and parameters.  

#  
The rx folder contains the rx_xtra values for each fiber. Run the following Python code to call the extracellular mechanism for stimulation.  

# Recruiting fibers  
The order for running the Python scripts is:  
                      1.stim_recruitment.py  
                      2.stim_Bootstrap.py    
                      3.BS_SI.py      

# Plotting  
       1.Line_BS_recru_batch.py  
       2.Bar_BS_Thres_Satu_batch.py  
       3.Line_SelectivityOverall_batch.py  
       4.Bar_BS_SI_batch.py  
