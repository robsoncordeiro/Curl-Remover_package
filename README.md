# The Method Curl-Remover for Dimensionality Reduction in Big Data

Given a very large dataset of moderate-to-high dimensionality, how to mine useful patterns from it? In such cases, dimensionality reduction is essential to overcome the “curse of dimensionality”. Although there exist algorithms to reduce the dimensionality of Big Data, unfortunately, they all fail to identify/eliminate non-linear correlations between attributes. Our method Curl-Remover helps in tackling the problem by exploring concepts of the Fractal Theory and massive parallel processing. It is a novel dimensionality reduction technique for very large datasets. Our contributions are: Curl-Remover eliminates linear and non-linear attribute correlations as well as irrelevant attributes; it is unsupervised and suits for analytical tasks in general – not only classification; it presents linear scale-up; it does not require the user to guess the number of attributes to be removed, and; it preserves the attributes' semantics. Experiments on synthetic and real data spanning up to 1.1 billion points show that Curl-Remover is up to 8% more accurate than a PCA-based algorithm.

## Package Description

The file synthetic\_sierpinski.tar.bz2 contains the source code to generate the two synthetic datasets used for the experiments.

The real datasets can be downloaded from the following links:
 - Hepmass: https://archive.ics.uci.edu/ml/datasets/HEPMASS
 - Susy: https://archive.ics.uci.edu/ml/datasets/SUSY
 - Ethylene: https://archive.ics.uci.edu/ml/datasets/Gas+sensor+array+under+dynamic+gas+mixtures
 - Astro: https://mega.nz/#!X0xWnZia!4PIaash-xd6OSXXYEk38EiJt3-rEfIYkYeCskH4lAL0
 - Yahoo! Network Flows: https://webscope.sandbox.yahoo.com/catalog.php?datatype=g

Source code of sPCA: https://github.com/Qatar-Computing-Research-Institute/sPCA
Source code of KPCA: KPCA.tar.bz2
Source code of Curl-Remover: CR.tar.bz2