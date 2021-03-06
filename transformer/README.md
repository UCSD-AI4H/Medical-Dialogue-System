#### How to Run

1. Use `preprocess.py` to generate the input data.
2. Run `trans_train.py` for training, `trans_perplexity.py` to calculate the perplexity, and `trans_generate.py` to generate the response and calculate the other metrics.
3. The original data is "\*.json", please run `preprocess.py` to generate the "\*.pth", which is the input file of our model. Note that, the full training data of Meddialog `train_data.pth` is more than 36GB, please make sure that you have enough space to save it.



#### Requirement
Torch==1.4.0 
Python==3.7.0 (or above)
Transformers==2.8.0 (or above)
NLTK==3.5.0




### Pre-trained models
We provide the pre-trained models here:

**Transformer trained on MedDialog** ([transformer pretrained model.pth](https://drive.google.com/file/d/1C8K7fAHzR2eSqZMc9wugbTG-MMA_SUlj/view?usp=sharing))
