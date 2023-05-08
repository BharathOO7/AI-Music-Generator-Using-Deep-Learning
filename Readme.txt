-It is necessary to install the music21 and TensorFlow libraries to run the different programs.


-The music folder contains the songs in MIDI format on which the neural network trains


-The Training.py file contains the python code which made it possible to create the mapping tables which associate a number with each note and vice versa: model_rnn_int_to_vocab and model_rnn_vocab_to_int. In addition it trains a model then saves it: model_rnn.h5

WARNING running Training.py can take a long time


- The CreateSong.py file allows to create a song from the trained model and with test_son.mid which contains a song which the model is not trained.



- Running CreateSong.py creates test_output.mid a midi file containing the music created by our neural network. Just run CreateSong.py to get the result of our work.