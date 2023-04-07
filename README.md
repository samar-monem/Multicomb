
# A Multi-Task Graph Deep Learning Model to Predict Drugs Combination Synergy and Sensitivity Scores  
this code implements  a multi-task deep learning model to predict drug combinations' synergy and sensitivity simultaneously. It uses a graph convolution network to represent the SMILES of two drugs and output the features of drugs. And, three fully connected subnetworks extract features of the cancer cell line. Then, drugs and cell line features are concatenated and input to an attention mechanism to output a two-feature representation for the two predicted tasks. After that, the relation between the two tasks is learned by the cross stitch model. Finally, each task feature is fed to fully connected subnetworks to predict the synergy and sensitivity scores. The model is validated with the O'Neil cancer dataset.
# Code run
The folder notebooks contains 5 jupter notebooks one for each fold arragig form 0-4. 
# Cite
