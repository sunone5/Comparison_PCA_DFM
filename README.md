# Comparison_PCA_DFM
Dimension Reduction: Facing the Curse of Dimensionality Comparison of PCA and dynamic factor model

Many data scientists are forced to deal with the challenge of dimension. Data sets can contain huge amounts of variables, making them complex to understand and compute. For example an asset manager can be overwhelmed with the many dynamic variables associated with its portfolio, and processing a large amount of data can lead to computational issues. Reducing the dimension is a way to extract the information from a large number of variables into a smaller set of reduced variables, without loosing too much of the explainability. In other words, dimension reduction methods can be considered as the research of a sub-space which minimises the reconstitution error.

Several methods exist to proceed with this information extraction, each adapted to different use cases. This article aims at providing a detailed comparison of two of these methods: the principal component analysis (PCA) and the dynamic factor model (DFM). The PCA can be used for any type of structured dataset, while the dynamic factor model is used for time series application, as it embeds the evolution of the series over time.

The analysis is made on economic and financial data. The data used for this study is a replication of the data used for the article measuring uncertainty and its impact on the economy by Clark, Todd; Carriero, Andrea; Marcellino, Massimiliano and is available on the Harvard dataverse. It consists of 18 macro economical variables and 12 financial variables. It covers the evolution of these variables from 1960 to 2014. The data is transformed to ensure stationarity, before being processed with the algorithms for dimension reduction.

Comparison of PCA and Dynamic Factor Model(DFM)
https://towardsdatascience.com/dimension-reduction-facing-the-curse-of-dimensionality-63a743e4b199
