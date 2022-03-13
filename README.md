# Deep Neural Networks for Protein Glutarylation Sites Prediction

## Abstract
Lysine glutarylation, a new identified protein post-translational modification regulated by sirtuin 5 (SIRT5), 
has been investigated to be evolutionarily conserved and is present in both prokaryotic and eukaryotic cells. 
These glutarylated proteins play an essential role in various cellular functions, such as translation, metabolism, 
and exhibited diverse subcellular localizations. 

## Method
This paper proposed a novel deep neural network framework for glutarylation prediction based on word embedding techniques. 
We conducted multiple deep neural network (DNNs) models, including LSTM, S-LSTM, B-LSTM, CNN-LSTM, and CNN-BLSTM to evaluate the performance on glutarylation prediction. 
In addition, we also examined different word embedding techniques, including embedding layer, GloVe, and ELMo embeddings performed on the sequence of amino acids. 

## Results
The results suggest that the proposed DNNs framework not only improves protein sequence representation, but also works effectively in protein glutarylation prediction by obtained high accuracy and confident rate. 
Moreover, we found that the embedding layer works more productively than the pre-trained word embedding techniques GloVe and ELMo over the independent test. 
The achievement in this paper can be used for in practical with large dataset as well as increase the probability of the lysine glutarylation site identification. 
The proposed DNNs framework achieved accuracy, specificity, sensitivity, and correlation coefficient of 0.79, 0.65, 0.85, and 0.5, respectively. 
