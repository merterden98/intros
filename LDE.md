### Practice with Low Dimensional Embeddings.

> Note that this lab will have far less guidance. Part of it is to work with things you've seen in the past (an to simulate what your PI might request).

--- 

1. Self select into groups of 2-3. You will be coding on **one** computer _together_.
2. With your partner(s), either read up on [tSNE](https://distill.pub/2016/misread-tsne/) or [UMAP](https://pair-code.github.io/understanding-umap/). Your selection of algorithm will dictate what you will be implementing.
3. Download the [titanic dataset](https://github.com/datasciencedojo/datasets/blob/master/titanic.csv) locally onto your machine.
4. Create a Jupyter Notebook or a Python file (title it whatever you want).
5. Install the correct package onto the conda environment to run tSNE or UMAP. 
6. Load the titanic dataset into a pandas dataframe and generate the UMAP or tSNE embeddings for the dataset. Make sure to **exclude** the label that dictates survival. Additionally you may consider removing columns or rows that might present some challenges.
7. Plot your low dimensional embedding using seaborn, and color the points according to whether or not they survived.
8. If you complete all the tasks either play around with the tSNE or UMAP hyperparameters or find another group that did not do your LDE algorithm and compare findings (remember to describe the properties of the algorithm you used). 