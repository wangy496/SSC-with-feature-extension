This code belongs to the "Enhancement of Convolutional Neural Network for Protein-Protein Interaction Prediction using Sequence Feature Extension" paper manuscript. It is slightly simplified implementation of Convolutional Neural Networks for protein-protein interaction prediction paper. Requirements Python 3.5; Tensorflow > 0.12; Numpy > 1.13; pandas > 0.18.

This code package includes 5 main file: 
(1)model.py: The main training and testing code. After editing the input data (as load_data() function ) the model can be trained properly according to the parameters. 
(2)methods.py: The get_CNN_data_multiple_channel() function is used to construct the three channels. An example is provided to simulate a small part of entire dataset. 
(3)hippie_current.txt: This file is the main dataset from HIPPIE database.
(4)upload_list.txt:This file is the protein list used in experiments.
(5)uniprot.fasta:This file is the sequence matching data of protein list. 



