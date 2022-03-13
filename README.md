
# Deep Neural Networks for Protein Glutarylation Sites Prediction
Deep Neural Network Framework Based on Word Embedding for Protein Glutarylation Sites Prediction
![image](https://user-images.githubusercontent.com/16794121/158044138-f350d3af-a59f-47a2-9bd7-af555ba83983.png)
![image](https://user-images.githubusercontent.com/16794121/158044142-c8120cf2-2916-4288-9b7c-449490937d7d.png)
## Abstract
Lysine glutarylation, a new identified protein post-translational modification regulated by sirtuin 5 (SIRT5), 
has been investigated to be evolutionarily conserved and is present in both prokaryotic and eukaryotic cells. 
These glutarylated proteins play an essential role in various cellular functions, such as translation, metabolism, 
and exhibited diverse subcellular localizations. 

## Method
This paper proposed a novel deep neural network framework for glutarylation prediction based on word embedding techniques. 
We conducted multiple deep neural network (DNNs) models, including LSTM, S-LSTM, B-LSTM, CNN-LSTM, and CNN-BLSTM to evaluate the performance on glutarylation prediction. 
In addition, we also examined different word embedding techniques, including embedding layer, GloVe, and ELMo embeddings performed on the sequence of amino acids. 
![image](https://user-images.githubusercontent.com/16794121/158044152-bd69034a-8081-408e-aa52-14d4da17ba51.png)

## Results
The results suggest that the proposed DNNs framework not only improves protein sequence representation, but also works effectively in protein glutarylation prediction by obtained high accuracy and confident rate. 
Moreover, we found that the embedding layer works more productively than the pre-trained word embedding techniques GloVe and ELMo over the independent test. 
The achievement in this paper can be used for in practical with large dataset as well as increase the probability of the lysine glutarylation site identification. 
The proposed DNNs framework achieved accuracy, specificity, sensitivity, and correlation coefficient of 0.79, 0.65, 0.85, and 0.5, respectively. 
![image](https://user-images.githubusercontent.com/16794121/158044183-8bc960d0-ae14-4e77-a73a-4f7173d8584e.png)
![image](https://user-images.githubusercontent.com/16794121/158044190-4b6e530d-4bfa-433f-a929-68d44d163a6f.png)
![image](https://user-images.githubusercontent.com/16794121/158044205-8221b68e-ceb6-4aea-8076-2e8bc5076457.png)
![image](https://user-images.githubusercontent.com/16794121/158044212-05804767-3f71-4c29-84a0-8a069f1154e9.png)



