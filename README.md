# CAraNER

This repository contains the dataset for the "CAraNER: The COVID-19 Arabic Named Entity Corpus" paper published at the WANLP workshop @EMNLP2022.

# Format and structure
The dataset is in csv format and has 7 columns:

- **Sentence_ID**: A unique identifier for a sentence. Note that senentence are not ordered as in the original text (shuffled).
- **Word_ID**: A unique identifier for a word in the corpus (unique id for each word). The word ids are ordered within the sentence.
- **Word**: Text representation for a word.
- **Annotator1**: Tag given by the first annotator (not always the same person when considering different sentences).
- **Annotator2**: Tag given by the second annotator (not always the same person when considering different sentences).
- **Agreed_Label**: Tag given by the annotators if there is an agreements; otherwise, the tag is *no_agr*.
- **Revised_Label**: The final tag (after revision) if there is no agreement.

# Citation
If you are going to use the dataset, please cite "CAraNER: The COVID-19 Arabic Named Entity Corpus", Abdulmohsen Al-Thubaity, Sakhar Alkhereyf, Wejdan Alzahrani, and Alia Bahanshal, WANLP 2022.
