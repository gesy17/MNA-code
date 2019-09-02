### Requirements
#### Dependencies
* numpy
* tensorflow-gpu 1.12.0
* keras 2.2.4 (with tensorflow as backend)
* NLTK
* jupyter notebook (with 'nbextensions' if you want to prettify the code)

#### Word Embedding
* word2vec Twitter (https://github.com/loretoparisi/word2vec-twitter)

#### Tips
* the path of source file is named `source_file`. which corresponds to the code `source_file='/data/gesy/MNA/WebMD8000.csv'`.
the path of word embedding is named `model_path`. which corresponds to the code `model_path ='/data/qit16/Lib/word2vec_twitter_model.bin'`.

* You may encounter some missing file errors when first using NLTK tokenizer, just add the required file in the NLTK directory as the error infor suggested.

* Some errors may append if there exists a mismatch between  tensorflow-gpu and keras. If this happens, change this to the one I specify.