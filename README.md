# Arc_Eager_Dependency_Parsing
The notebook contains the implementation of a neural transition-based parser for dependency grammars, with unlabelled dependencies. There are two implementations techniques:
- BiLSTM
- BERT

The performances of the two models on the test set are the following, using UAS (Unlabeled Attachment Score) as evaluation metric:
- Bi-LSTM based model: UAS = 0.704;
- BERT based model: UAS = 0.857.
