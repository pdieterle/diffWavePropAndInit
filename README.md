# diffWavePropAndInit

This Mathematica notebook is an accompaniment to Dieterle et al. (https://www.biorxiv.org/content/10.1101/2019.12.27.887273v1). In this code, we implement the information wave front algorithm discussed in the SI of that paper (and used to generate figures 1 and 2); we also implement the initiation time calculations used to generate figure 3 and the gradient calculations used to generate figure 4.

Any corrections or questions can be directed to Paul Dieterle (pauldieterle@gmail.com).

We note that because of numerical integration issues in Mathematica 12 (presumably caused by the migration from 32 to 64 bit), the operations in this notebook only work properly for Mathematica <=11.