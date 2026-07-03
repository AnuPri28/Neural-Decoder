# Neural-Decoder
NeuralDecoder is a neural-network-based decoder for a Hamming (7,4) system. It takes 7 noisy received bits as input and predicts the original 4-bit message from 16 possible outputs. It uses Eb/N0 to model noise and trains a classifier with Adam optimizer and CrossEntropyLoss to learn error correction from noisy codewords.
