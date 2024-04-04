# ABSTRACT
DNA Microarray technology can be used for simultaneous
learning of the expression levels of thousands of genes. It -
nally produces microarray data that contain information of
biological, diagnostic, and prognostic use for researchers. It
is generally used for cancer classication problems. Identi-
cation of the informative and relevant genes has always been
an important step in microarray data analysis. The cancer
datasets contains more number of features and less number
of samples which increases the complexity of dataset. The
main problem addressed in the section is the selection of
small subset of relevant from the thousands of genes which
contribute for causal of disease. The process of selection be-
comes more dicult as samples are very less and genes are
more which are irrelevant and noisy in nature. This selection
process is dicult due to the availability of a small number
of sample compared with the huge number of genes, many of
which are irrelevant and noisy. Therefore, here we propose
a two step method "RFE-INFO-BPSO" which is combina-
tion of wrapper methods. Firstly we apply Recursive Fea-
ture Elimination(RFE) and Mutual Information to reduce
the dimensionality. Then apply binary particle swarm opti-
mization to select a near-optimal(small) subset of informa-
tive genes and than dataset is reformed based on the BPSO
gene subset. The above reformed dataset is used for the can-
cer classication using various classiers like Support Vector
Machine(SVM), Naive Bayes(NB) Classier, Decision Tree
(DT) and Neural Network(NN). Experimental results show
that the performance of the proposed method is better than
other classication methods in terms of accuracy and the
number of selected genes.
