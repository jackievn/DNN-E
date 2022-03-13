# Deep Neural Networks for Protein Glutarylation Sites Prediction

## Abstract
Recent researches have been found that dysregulation of glutarylation is associated with many human diseases, such as diabetes, cancer, and glutaric aciduria type I. Therefore, glutarylation identification and characterization are an important task to determine modification-specific proteomics. This study aims to propose a novel deep neural network framework based on word embedding techniques for glutarylation sites prediction. Multiple deep neural network models are implemented to evaluate the performance of glutarylation sites prediction. Furthermore, an extensive experimental comparison of word embedding techniques is conducted to utilize the most efficient method for improving protein sequence data representation. The results suggest that the proposed deep neural networks not only improve protein sequence representation but also work effectively in glutarylation sites prediction by obtaining a higher accuracy and confidence rate compared to the previous work. Moreover, embedding techniques were proven to be more productively than the pre-trained word embedding techniques for glutarylation sequence representation. Our proposed method has significantly improved all traditional performance metrics compared to the advanced integrated vector support, with accuracy, specificity, sensitivity, and correlation coefficient of 0.79, 0.89, 0.59, and 0.51, respectively. It shows the potential to detect new glutarylation sites and uncover the relationships between glutarylation and well-known lysine modification. 

## Method
This paper proposed a novel deep neural network framework for glutarylation prediction based on word embedding techniques. 
We conducted multiple deep neural network (DNNs) models, including LSTM, S-LSTM, B-LSTM, CNN-LSTM, and CNN-BLSTM to evaluate the performance on glutarylation prediction. 
In addition, we also examined different word embedding techniques, including embedding layer, GloVe, and ELMo embeddings performed on the sequence of amino acids. 
### Dataset
![image](https://user-images.githubusercontent.com/16794121/158044320-fd49ac32-fdef-4afc-a286-3569a6bf61f8.png)
#### The overview of the DNN-E framework
![image](https://user-images.githubusercontent.com/16794121/158044321-19c75210-1faa-4326-875f-fda25761ced9.png)
### RNN architecture for sequence classification.
![image](https://user-images.githubusercontent.com/16794121/158044326-1349cd94-d78c-4ffe-bd35-822b18c8b211.png)
### LSTM DNN Architecture
![image](https://user-images.githubusercontent.com/16794121/158044362-0b730964-1aa2-460a-9e5f-cba3dad324f9.png)

## Results
The results suggest that the proposed DNNs framework not only improves protein sequence representation, but also works effectively in protein glutarylation prediction by obtained high accuracy and confident rate. Moreover, we found that the embedding layer works more productively than the pre-trained word embedding techniques GloVe and ELMo over the independent test. The achievement in this paper can be used for in practical with large dataset as well as increase the probability of the lysine glutarylation site identification. The proposed DNNs framework achieved accuracy, specificity, sensitivity, and correlation coefficient of 0.79, 0.65, 0.85, and 0.5, respectively. 
### Model selection
![image](https://user-images.githubusercontent.com/16794121/158044375-3a34fcb0-96c2-4ae0-abe6-3823b43e0e1e.png)
### LSTM Training and Validation performance
![image](https://user-images.githubusercontent.com/16794121/158044398-f3776e8f-2ac9-4533-a9ca-31316edfdd96.png)
### DNN performance comparison
![image](https://user-images.githubusercontent.com/16794121/158044402-3fd9aa91-9ae9-4705-96ec-86360f344a4f.png)
### Embedding techniques comparison
![image](https://user-images.githubusercontent.com/16794121/158044415-d80e1660-5322-4fe1-b511-cea45633eaf4.png)



