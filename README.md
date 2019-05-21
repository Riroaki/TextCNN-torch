# TextCNN using torch and GloVe

> A simple Convolutional Neuron Network predicting sentiment of IMDB comment files using pre-trained word vector GloVe.

1. Download and put pre-trained vector at. `https://nlp.stanford.edu/projects/glove/`, and put the `.txt` files under `glove.6B/`.
2. Configure the embedding dimension of your model in main.py.
3. `python run.py` in shell, or execute the `run.py` in any IDE.

Current accuracy is about 90% due to the relatively small dataset.
