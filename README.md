# Neural-Machine-Translation
In this project we implement Neural Machine Translation (NMT) models to translate from Hindi to English. One of the prominent model architectures used in NMT is encoder-decoder architecture. It consists of two components: an encoder and a decoder. The encoder takes the source language sentence (e.g., Hindi) as input and learns a representation for it, this representation is then fed to the decoder that then decodes (i.e., predicts) the target language sentence (e.g, English) word by word. There is flexibility with regard to the neural architecture of the encoder and the decoder.

# Data - Set
The train.csv file dataset provided contains Hindi and English parallel sentences. For each Hindi sentence in the first column, the second sentence contains the corresponding English translation. Train dataset consists of 102,322 Hindi-English sentence pairs. The train set and evaluation scripts are provided. Evalution scripts calculate the BLEU score and METEOR score.

We were only providing the train set and evaluation script. We have randomly split (e.g., 80-20 split) the train set into train and dev (validation) sets and used the dev set to evaluate my models internally. This gave us a good idea about different models that we experimented with and helped us select the final model. Our final model was evaluated using a separate test set that was not provided during the training phase.

