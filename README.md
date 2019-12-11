# completeted experiment: clustering test corpus with LDA and with tSNE and ADW scores

Two Jupyter Notebooks implementing different approaches to finding clusters, similarities and patterns from the opinions collected by Digital Peace Talks

## LDA with Segments
This notebook utilizes the opinion segmentation and then implements a topic modelling alogorithim, Latent Dirichilet Allocation, on the segmented opinions. The ideal number of topics is chosen dynamically using the topic coherence scoring. We see some positive results as 22 topics are discovered with various themes such as global fatalism, veganism, energy production, etc.

## tSNE with ADW scores
This notebook takes the opinions weight scoring results from ADW algorithm and creates a matrix of all opionions to all opinions with the weight scores as cell values. Then the tSNE dimensionality reduction algorithm is used to reduce the matrix down to 3 columns which could potentially be used for 3D visualization. As the tSNE algorithm relies on a range of hyperparameters, this notebook creates 60 possible combinations of the algorithm which can be explored using appropriate filters in Google Data Studio: https://datastudio.google.com/u/0/reporting/1yv0-2NZn_AdOrRIfMXsbg7_f0s0OsTx-/page/C96Z

