# thesis_CSAI

This repository contains the code Jupyter Notebook of the thesis: Evaluating Sentence Embeddings on Syntactic Information Through Representational Similarity Analysis.

The notebook expect to process the Penn Treebank data set, however, this data set is not publicly available. 

The notebook is dependent on the following packages:
* nltk
* [ursa](https://github.com/gchrupala/ursa "Named link title") 
* pickle  
* os
* matplotlib
* numpy
* tensorflow
* [skip-thoughts](https://github.com/tensorflow/models/tree/master/research/skip_thoughts "Named link title")
* scipy
* pandas
* [jsonlines](https://pypi.org/project/jsonlines/ "Named link title")

Further, the analysis in the notebook is dependent on the pre-trained BERT model and the pre-trained uni-skip and bi-skip models.

The BERT model can be downloaded via the following link:
https://storage.googleapis.com/bert_models/2018_10_18/uncased_L-12_H-768_A-12.zip

Store the contents in a folder named: "uncased_L-12_H-768_A-12"

The Skip-Thought models can be downloade via the following instructions:
https://github.com/tensorflow/models/tree/master/research/skip_thoughts#download-pretrained-models-optional

Store the contents in a folder named: "skipthought"
