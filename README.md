# distilBERT_BiLSTM

NOTE: You should have the glove embeddings file and also load the datasets before you run the student model code (BiLSTM).


Firstly, we'll need to load the glue benchmark datasets.
We have the corresponding code for each dataset for doing this in the folder 'load'.

Secondly, we need to augment the data, code for doing this for each of the dataset is present inside the folder 'upgrade'

Thirdly, we append the teacher logits and true label logits of the train split to the dataset. We do this part of the preprocessing in the code files inside 'upgrade'.


