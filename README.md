Music RNN Capstone -- README
W. Emerson ODonnell


This is a capstone project for the Machine Learning Nanodegree. A recurrent neural network is used to generate short samples of classical music.

The project contains two Jupyter notebooks. The first, midi_processing_matrices, runs Python 2, while the other, RNN_final, runs Python 3. The Python 2 environment requires the following libraries: midi, numpy, pandas, pickle, and os. The Python 3 environment requires numpy and tensorflow.

To replicate my results, you can use the midi_processing_matrices notebook to process the files contained in the included corpus (the path strings in the notebook will need to be replaced with the path you save the files at.)

Once you have generated a master training matrix and a test matrix, these can be used to train an RNN using the RNN_final notebook. Again, the path strings in that notebook will need to be modified according to where you save the relevant files.

Once the network is trained, the second half of the RNN_final notebook can be used to sample it. Finally, the second half of the midi_processing_matrices notebook can be used to convert the generated matrices into playable .mid files.
