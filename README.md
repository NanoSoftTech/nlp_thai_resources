# Thai NLP Resource
Collection of Thai NLP libraries, dictionaries, and corpus.
Always welcome for pull requests.

## Thai NLP Libraries

### Thai Character Cluster
Library | Description | Programming Languages | Features | License | Author & Link
--- | --- | --- | --- | --- | ---
TCC| Thai Character Cluster | C | | | Thanaruk et.al. 


### Word Segmentation
<table>
<thead>
<tr>
<th>Library</th>
<th>Description</th>
<th>Programming Languages</th>
<th>Features</th>
<th>License</th>
<th>Author &amp; Link</th>
</tr>
</thead>
<tbody>
<tr>
<td>Swath</td>
<td>SWATH (Smart Word Analysis for THai) is a word segmentation for Thai</td>
<td>C</td>
<td>Longest Matching, Maximal Matching and Part-of-Speech Bigram.</td>
<td>GPL</td>
<td><a href="http://www.cs.cmu.edu/%7Epaisarn/software.html">CMU</a></td>
</tr>
<tr>
<td rowspan="3">Lexto</td>
<td rowspan="3">Lexto: Thai Lexeme Tokenizer</td>
<td>Java</td>
<td></td>
<td>LGPL</td>
<td>
<a href="http://www.sansarn.com/lexto/license-lexto.php">NECTEC</a>
</td>
</tr>
<tr>
<td>Python 2</td>
<td></td>
<td>LGPL</td>
<td><a href="https://github.com/Remixman/PythonLexTo">Python2 Wrapper</a></td>
</tr>
<tr>
<td>Python 3</td>
<td></td>
<td>LGPL</td>
<td><a href="https://github.com/c4n/PythonLexTo">Python3 Wrapper</a></td>
</tr>
<tr>
<td>Wordcut</td>
<td>Thai word breaker for Node.js</td>
<td>JavaScript, Node.JS</td>
<td></td>
<td>LGPL-3.0</td>
<td><a href="https://github.com/veer66/wordcut">Veer66, github</a></td>
</tr>
<tr>
<td>CutKum</td>
<td>Thai Word-Segmentation with Deep Learning in Tensorflow</td>
<td>Python</td>
<td>0.93 recall, 0.92 precision, 0.93 F-measure.</td>
<td>MIT</td>
<td><a href="https://github.com/pucktada/cutkum">Pucktada, github</a></td>
</tr>
</tbody>
</table>

### Part of Speech Tagging (POS Tagging)
Library | Description | Programming Languages | Features | License | Author & Link
--- | --- | --- | --- | --- | ---
Jitar+NAiST | A simple Trigram HMM part-of-speech tagger | Java |  |  | [Ver66](https://veer66.wordpress.com/2012/03/20/part-of-speech-tagger-%E0%B8%AA%E0%B8%B3%E0%B8%AB%E0%B8%A3%E0%B8%B1%E0%B8%9A%E0%B8%A0%E0%B8%B2%E0%B8%A9%E0%B8%B2%E0%B9%84%E0%B8%97%E0%B8%A2/), [Jitar](https://github.com/danieldk/jitar) + [NAiST, 1](http://naist.cpe.ku.ac.th/pkg/jitar_model_large.zip) + [NAiST, 2](http://naist.cpe.ku.ac.th/pkg/jitar-20100224.zip)

### Name Entity Recognition


### Syntactic Parsing & Tools 

Library | Description | Programming Languages | Features | License | Author & Link
--- | --- | --- | --- | --- | ---
Chart-parser | Extract Syntactic Structure from POS Tagged Sentence. | C |  | Copyright | Thanaruk T. (thanaruk@siit.tu.ac.th)
Grammar Processing | Labelled Buckets -> Context Free Grammer (CFG) | Python | Transform and compute probability | |  [Thodsaporn C.](https://github.com/tchayintr/nlp-python/tree/master/grammar_processing)  


## Dictionaries / Translation Pairs
Library | Description | Size | Features | License | Link
--- | --- | --- | --- | --- | ---
Transliteration Corpus |  | 31K pairs | Thai-Eng Translation Pair | CC BY-NC-SA 3.0 TH | [NECTEC](https://www.nectec.or.th/corpus/index.php?league=pm)
Lexitron | Opensource Thai-English Dictionary | | TH->EN, EN->TH | LGPL | [NECTEC](http://www.sansarn.com/lexto/license-lexitron.php)

## Downloadable Text Corpus

Library | Description | Size | Features | License | Link
--- | --- | --- | --- | --- | ---
ORCHID | | 30K sent. | Word Seg., POS Tagged. | CC BY-NC-SA 3.0 TH | [NECTEC](https://www.nectec.or.th/corpus/index.php?league=pm)
InterBEST 2009/2010 | | 5M words | Word Seg. | CC BY-NC-SA 3.0 TH | [NECTEC](https://www.nectec.or.th/corpus/index.php?league=pm)
Thai Wikipedia | Formal Articles | 1.49GB (~213.1 MB compressed) | XML | GFDL | [WIKIPEDIA](https://dumps.wikimedia.org/thwiki/latest/thwiki-latest-pages-articles.xml.bz2)
TNC Top-5000 Words | Word frequency | 5,000 words | Frequency of Thai words in various genres, EXCEL | Copyright | [CHULA](http://www.arts.chula.ac.th/~ling/TNC/category.php?id=58&) 

## Web Query Text Corpus
Library | Description | Size | Features | License | Link
--- | --- | --- | --- | --- | ---
Thai National Corpus 2 | | 32M words. | Query text by genre, domain | Copyright | [CHULA](http://www.arts.chula.ac.th/~ling/TNCII/)

## Pre-trained Word Vectors
Pre-trained Model | Description | Size | Dimensions | License | Link
--- | --- | --- | --- | --- | ---
fastText | Skip-Gram model trained on Wikipedia using fastText | | 300 | CC BY-SA 3.0 | [Facebook](https://github.com/facebookresearch/fastText/blob/master/pretrained-vectors.md) + [Bin & Text](https://s3-us-west-1.amazonaws.com/fasttext-vectors/wiki.th.zip) + [Text Only](https://s3-us-west-1.amazonaws.com/fasttext-vectors/wiki.th.vec) 
