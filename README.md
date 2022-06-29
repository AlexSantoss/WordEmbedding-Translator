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
        Jupyter notebook - <code>pip install notebook</code>
    </li>
    <li>
        Gensim - <code>pip install gensim</code>
    </li>
<ul>


<h2>How to run</h2>
<ol>
    <li>
        Download this repo: 
        <code>git clone https://github.com/AlexSantoss/WordEmbedding-Translator.git</code>
    </li>
    <li>
        Inside the folder "Datasets", create a new one called "FastText".
    </li>
    <li>
        Download and extract the following files inside the FastText folder:
        <ul> 
            <li>
                Danish: https://dl.fbaipublicfiles.com/fasttext/vectors-crawl/cc.da.300.vec.gz
            </li>
            <li>
                Dutch: https://dl.fbaipublicfiles.com/fasttext/vectors-crawl/cc.nl.300.vec.gz
            </li>
            <li>
                English: https://dl.fbaipublicfiles.com/fasttext/vectors-crawl/cc.en.300.vec.gz
            </li>
            <li>
                French: https://dl.fbaipublicfiles.com/fasttext/vectors-crawl/cc.fr.300.vec.gz
            </li>
            <li>
                German: https://dl.fbaipublicfiles.com/fasttext/vectors-crawl/cc.de.300.vec.gz
            </li>
            <li>
                Italian: https://dl.fbaipublicfiles.com/fasttext/vectors-crawl/cc.it.300.vec.gz
            </li>
            <li>
                Portuguese: https://dl.fbaipublicfiles.com/fasttext/vectors-crawl/cc.pt.300.vec.gz
            </li>
            <li>
                Romanian: https://dl.fbaipublicfiles.com/fasttext/vectors-crawl/cc.ro.300.vec.gz
            </li>
            <li>
                Spanish: https://dl.fbaipublicfiles.com/fasttext/vectors-crawl/cc.es.300.vec.gz
            </li>
            <li>
                Swedish: https://dl.fbaipublicfiles.com/fasttext/vectors-crawl/cc.sv.300.vec.gz
            </li>
        </ul>
    </li>
    <li>
        Run the file Translator.ipynb
    </li>
</ol>


<h3>Glove model</h3>

You can transform Glove models to Word2Vec model by running:

<p>
    <code>python -m gensim.scripts.glove2word2vec --input  glove.model.txt --output w2v.model.txt</code>
</p>