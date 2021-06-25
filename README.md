# PPI_Bioinformatics

High-developed techniques in genomics and proteomics
generate large amounts of data about the function, regulation
and interaction of genes and proteins1
. Detecting proteinprotein interactions (PPI) is very important to generate
knowledge and a better understanding of the protein function
in biological processes in normal and disease states,
including cell cycle progression, DNA replication and signal
transmission. This helps, for instance, in therapeutic target
identification2,3
.
In recent years, to detect PPIs, some high-throughput
technologies were developed such as yeast two-hybrid
screens (Y2H), tandem affinity purification (TAP), and mass
spectrometric protein complex identification (MS-PCI),
Tandem Affinity Purification and Mass Spectrometry (TAPMS), affinity chromatography and Co-Immunoprecipitation
(Co-IP). These methods allowed the growth of the number
of PPIs but these methods have some disadvantages as the
update from data, and high false positives and false negative
rate4
. Compared with these methods, the computational
method has advantages such as fast verification, speed and
strong repeatability, high quality and accuracy
5
. In this
project we used machine learning methods.
As inputs to the machine learning models, we used
embeddings. An embedding is a mapping of a discrete —
categorical — variable to a vector of continuous numbers6
,
these vectors in a low dimensional space capture the
relationships in knowledge graphs (KG)7
. A knowledge
graph is made of nodes and edges. Each edge connects a pair
of nodes indicating that there is a relation between them8
.
Resuming, the proteins are represented as vectors in the
embedding space ready to be used for machine learning
models such as prediction and node classification9
.
In this project, we started by testing different machine
learning models: Decision Trees, Random Forests, Gaussian
Naive Bayes, Multi-Layer Perceptron and Support Vector
Machines. All of these machine learning models are
supervised, and this feature requires labels. All the necessary
information was extracted from a dataset provided to us1
.
After verifying which one got the best parameters using the
most embracing dataset, we chose the best one to go on.
Our goals include seeing which is the best and most efficient
supervised machine learning algorithm, which is the best
embedding combination operation, and the main goal is the
prediction protein-protein interaction using a learning
machine model.
