# Mixed representations in V1 neurons (Stringer dataset)
Pod: Wistful Wolves 

Group: Neuronas Stringer

### Team members:

[Adrián Alemán-Zapata](https://github.com/Aleman-Z)

Julián Guiral

# Abstract
Mixed representations is the phenomenon in which motor information is encoded and integrated with sensory state variables, creating a multidimensional representation of experiences in the same neuronal population (Stringer, C. et al., 2019). We ask if the combined motor and sensory information during a mice visual-stimuli task improves the accuracy of a predictive model describing the population activity of V1 cortex neurons compared to models trained with the individual motor or sensory variables. This comparison could provide us with insights about the mixed representation phenomenon during different conditions. We hypothesize that the prediction of the V1 cortex population spontaneous activity should improve with a model trained with both motor and sensory variables. On the contrary, the prediction of activity during visual stimuli tasks should benefit less from such a model and instead, improve by using a model trained with only sensory information. Therefore, we expect the visual stimulus to modify the performance of models trained with combined sensory and motor information. To investigate this hypothesis we trained an encoding model with sensory, motor and their combined  information, under the absence and presence of visual stimuli, and during periods of high and low motion. We found that the model trained with combined information improved the prediction of spontaneous activity, but worsened the prediction of activity during visual stimuli. Our preliminary results confirm the proposed hypothesis, although the model showed a high error due to the low variability and simplicity of the angle and the running speed data, which represents a limitation of this study. Another limitation was the lack of standardization of the data between spontaneous and stimuli datasets. We consider that a future direction would be to make use of a more homogeneous and richer version of the Stringer datasets. Including real images instead of gradings of different angles during the stimulation, as well as the use of more detailed measures of the mice behavior, would allow training models using data containing more variability. 
