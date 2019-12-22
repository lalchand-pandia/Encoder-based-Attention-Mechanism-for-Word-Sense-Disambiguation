 In this work we present a BERT based approach for Word Sense Disambiguation(WSD). Unlike previous works which use feature based language representations for WSD, we fine tune an existing BERT based representation model to construct our model.

We have evaluated our approach on the standard line, hard, serve and interest datasets  and obtained new state-of-the-art micro-averaged F1 scores.

To handle the extreme sample size imbalance in the dataset we have used a weighted version of the loss function while constructing the model and found that even senses with very few training examples can be correctly classified. We obtained better macro-averaged F1 scores  for interest, hard and line datasets as compared to the standard  unweighted loss function.

Most of the code is taken as present in BERT webpage.


