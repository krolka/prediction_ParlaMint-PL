The aim of this project was to investigate the classification of deputies’ gender, political
affiliation and political party, from the transcripts of the debates from the lower and the upper
chamber of the Polish Parliament. The parliament proceedings were tokenized, lemmatized and
part-of-speech tagged using two text pre-processing tools: Spacy and Morfeusz. The speeches pre-
processed with both tools were used for extraction of five features: word embeddings, obtained with
Word2Vec model, Bag-of-Words (BOW), Bag-of-Words lemmas (BOWL), term frequency-inverse
document frequency (TF-IDF) and term frequency-inverse document frequency of words’ lemmas
(TF-IDFL). 

The experiment was done on the ParlaMint-PL dataset https://www.clarin.eu/parlamint
