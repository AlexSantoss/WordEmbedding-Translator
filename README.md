# WordEmbedding-Translator
Notebook using two models from different languages to translate words. This code use the Procrustes Problem and a subset of words with known translations to find the best translation matrix.

## Dependencies
gensim - <code>pip install gensim</code>

## How to run
1 - Download two word embedding models with Word2Vec format and same dimensions  and change the path on the second cell for the name of the files <br />
2 - Create a file named 'words' where each line is like 'wordA wordB' with wordA a word from the first dataset and wordB a word from the second dataset <br />
3 - Change word\_A and word\_B from the last two cells to words you want to translate <br />
4 - Have fun! <br />

## Glove model
You can transform Glove models to Word2Vec model by running:
<code>python -m gensim.scripts.glove2word2vec --input  glove.model.txt --output w2v.model.txt</code>

