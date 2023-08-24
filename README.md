# Testing For Signatures of Natural Selection Through Recurrent Neural Network Analysis of Allele Frequency Trajectories

Muna Omar Hersi

I've divided the code into 5 sections:

1. **Simulations** : This shows the code for the Wright-Fisher simulations used to train the LSTM model, as well as the code to generate the simulations.
2. **Building the LSTM Model** : Here, the data is split into training, validation, and test, and the model is built using Keras/TensorFlow.
3. **Training and Testing on Simulations** : The model is trained on the training set, and tested on the test set.
4. **LSTM Model Application on Black Death Variants** : Input data and target data generated using frequencies reported by Klunk et al. (2022). The model is then tested on this data. The variants associated with an increase in the expression of *ERAP2* and *TICAM2* are identified on the scatter plot showing the model's predictions against the true values.
5. **Training Improvement** : Simulation generation is improved by incorporating a range of initital allele frequencies instead of just 0.1.
