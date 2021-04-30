# Speech-to-Text
Speech to text implementation using PyTorch on transformers

In this notebook we are going to see how to convert speech into text using Facebook's Wav2Vec 2.0 model.

Wav2Vec2 is a speech model that accepts a float array corresponding to the raw waveform of the speech signal.

Wav2Vec2 model is trained using connectionist temporal classification (CTC) so the model output has to be decoded using Wav2Vec2Tokenizer.
