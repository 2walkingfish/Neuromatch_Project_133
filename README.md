# Neuromatch_Project_133

Initial question for this project was whether the topology of the circuits is getting more complicated within sequential trials of task performing. We studied this question based on Steinmetz et al. data set. However, before building the circuit, we need to define what determines connectivity between single neutrons. 
To start with features analysis, we explored temporal components of spike waveforms for the probe with the highest amplitude by reducing dimensionality with PCA and TSNE methods, calculated optimal amount of clusters and plot waveforms concerning clusters. We find that waveforms in each cluster have distinguished parameters of amplitude and spike width. 
It yet does not provide the answer to the question, so we thought what can be done next: 1) Plot clusters statistics per different brain areas to define whether any of waveforms defined by a region; 2) Calculate shifts of waveforms in milliseconds to build a signal spreading map; 3) Compare results per different stages of trial; 4) Compare results per first and last trails. 
The main result of exploration is asking more in-depth questions about data set and neural circuits formation.  
