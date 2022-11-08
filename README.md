# voice-replicator
Voice replication in PyTorch

This code uses the TacoTron2 model to convert text into spectrograms, and the WaveRNN model to convert those into audio files.
The WaveRNN model is trained on user-supplied data to replicate a given voice.
User supplied data should be provided in the format of a directory of audio files (of a person speaking) and a .csv file with the audio filenames and transcripts.
