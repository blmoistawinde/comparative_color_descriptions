# comparative_color_descriptions
Simple reproduction of the paper ['Lighter' Can Still Be Dark: Modeling Comparative Color Descriptions](https://aclweb.org/anthology/P18-2125) by Winn et al. in pytorch. Correctness not verfied.

An interesing approach that links comparative color descriptions to a vector direction in RGB space.

darker + blue ![darker + blue](imgs/darker_blue.png)

more electric + purple ![more electric + purple](imgs/more_electric_purple.png)

dataset from https://bitbucket.org/o_winn/comparative_colors.git

word embedding from https://www.kaggle.com/yekenot/fasttext-crawl-300d-2m , only relevant words are extracted and saved in embeddings.pickle 