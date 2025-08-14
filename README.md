# Cyber Bullying Text Classification in Bangla Language context

Our team created a specific dataset to classify Bengali text into six different groups: political,
geopolitical, gender, religious, personal, and sports. Five freely accessible Bengali hate speech
datasets were combined to make this dataset. We reduced the dataset to about 35,000 unique samples
during preprocessing by removing about 35% of duplicate items. We manually gathered more text
samples from Facebook, meticulously classified them, and incorporated them into the preexisting
dataset in order to further enhance it. The final collection included 29,300 unique, labeled samples
following a thorough deduplication and cleaning process. To evaluate classification performance, we
used two models. First, we applied a transformer-based pretrained model for cross-lingual tasks
called Multilingual BERT (mBERT). mBERT obtained a modest accuracy of roughly 74% when
trained on the complete dataset. Second, we used a smaller subset of 3,000 samples to test a
Bidirectional LSTM model. The Bidirectional LSTM showed remarkable results, attaining an
accuracy of almost 93%, despite the small sample size.

