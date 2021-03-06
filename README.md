# Learning Based Evaluation of Medical NER

This code is related to the paper entitled "Extensive Error Analysis and a Learning-Based Evaluation of Medical Entity Recognition Systems to Approximate User Experience" published at BioNLP2020. 


## Description of files:

#### [st21pv_NER_results/stpv_biobert_lstm_results.json](https://github.com/nrc-cnrc/NRC-MedNER-Eval/blob/master/st21pv_NER_results/stpv_biobert_lstm_results.json)
contains the sentences of the st21pv test set along with IOB formatted true lables and predicted labels generated by BioBERT-based NER model.  

#### [build_Entity_Classifier.ipynb](https://github.com/nrc-cnrc/NRC-MedNER-Eval/blob/master/build_Entity_Classifier.ipynb)
creats entity classifiers from training dataset of the NER model in IOB format stored in *data/st21pv/*. The trained classifier is stored in *entity_identifier_models/st21pv*.

#### [Learning-Based-Fscore.ipynb](https://github.com/nrc-cnrc/NRC-MedNER-Eval/blob/master/Learning_Based_Fscore.ipynb)
uses the trained classifier for error analysis and evaluation of the NER model given the NER output file described above. 



