### Amzon polarity review

This project is a sentiment analysis project on amazon polarity review dataset. The project makes use of a subset of the amazon polarity dataset (60,000) and compare the Bag of words model with embedding models like Glove, Word2Vec and Facebook FastText word embedding.

This project compares the training accuracy and the ROC-AUC score of the BoW model and the different word embedding models.

Here is the Validation Accuracy of the different models

<p />
<img src="./images//amazon-polarity-review/Validation-Accuracy.png" alt="drawing" width="300"/>
<p />

Here is the ROC-AUC score of the different models

<p />
<img src="./images//amazon-polarity-review/ROC-AUC-score.png" alt="drawing" width="300"/>
<p />


Here is the ROC-AUC curve of the different models

<p />
<img src="./images//amazon-polarity-review/ROC-AUC-Curve.png" alt="drawing" width="300"/>
<p />

The Bag of Words model outperformed the word embedding models.

**Note** : In this project, the major pre-processing step done on the dataset is to remove just words with frequency less than 10. The dataset can be downloaded on the Hugging Face website via this [link](https://huggingface.co/datasets/amazon_polarity).

Cheers.