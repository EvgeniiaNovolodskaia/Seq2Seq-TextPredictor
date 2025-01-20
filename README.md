# Seq2Seq-TextPredictor
This project implements a sequence-to-sequence model to predict the next paragraph of text based on the preceding one. The model operates on a character level and is based on LSTM.

- **Encoder**: A bidirectional LSTM that processes the input text into tensors.
- **Decoder**: A unidirectional LSTM that generates the next text one character at a time.

The project uses the text of Gustave Flaubert's novel *Madame Bovary* from **Project Gutenberg** as the dataset.
