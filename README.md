<h1>Word Embedding Translator</h1>
<p>
    Undergraduate course completion work presented to the Computer Institute of Federal University of Rio de Janeiro as part of the requirements for obtaining the degree of Bachelor in Computer Science.
</p>
<p>
    Notebook using models from different languages to translate words. This code use the Procrustes Problem and a subset of words with known translations to find the best translation matrix.
</p>

<h2>Dependencies</h2>
<ul>
    <li>
        Python 3.9 or higher
    </li>
    <li>
        Jupyter notebook - <code>pip install notebook</code>
    </li>
    <li>
        Gensim - <code>pip install gensim</code>
    </li>
</ul>


<h2>How to run</h2>
<ol>
    <li>
        Download this repo: 
        <code>git clone https://github.com/AlexSantoss/WordEmbedding-Translator.git</code>
    </li>
    <li>
        Run the file <a href="https://github.com/AlexSantoss/WordEmbedding-Translator/blob/automation/main.ipynb">main.ipynb</a>
    </li>
</ol>


<h3>Glove model</h3>

You can transform Glove models to Word2Vec model by running:

<p>
    <code>python -m gensim.scripts.glove2word2vec --input  glove.model.txt --output w2v.model.txt</code>
</p>