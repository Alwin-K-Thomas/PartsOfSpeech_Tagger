# PartsOfSpeech_Tagger
Custom Viterbi algorithm for assigning Parts of speech tags (Natural Language Processing)

In this project, we will build your own HMM-based POS tagger and implement the Viterbi algorithm using the **Penn Treebank training corpus**. The vanilla Viterbi algorithm we had written had resulted in ~87% accuracy. The approx. 13% loss of accuracy was majorly due to the fact that when the algorithm encountered an unknown word (i.e. not present in the training set, such as 'Twitter'), it assigned an incorrect tag arbitrarily. This is because, for unknown words, the emission probabilities for all candidate tags are 0, so the algorithm arbitrarily chooses (the first) tag.

 In this project, we will modify the Viterbi algorithm to solve the problem of unknown words using at least two techniques.
