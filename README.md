# seq2seq-learning
---
This repository is supposed to handle the following topics:

- **Understanding sequence-to-sequence data**
- **Building a sequence-to-sequence machine translation model**
![encoder-decoder-machine-translation](plots/enc-dec.svg)

***Bidirectional RNN: Reading text forward and backward***

The standard RNN reads the text forward, one time step at a time, and outputs a sequence of outputs. Bidirectional RNNs, as the name suggests, not only read the text forward, but read it backward. This means that bidirectional RNNs have two sequences of outputs. Then these two sequences are combined using a combination strategy (e.g., concatenation) to produce the final output. Bidirectional RNNs typically outperform standard RNNs because they understand relationships in text both forward and backward, as shown in the following figure.
![RNN-vs-biRNN](plots/rnn-bi-rnn.svg)
- **Training and evaluating sequence-to-sequence models**
- **Repurposing the trained model to generate translations for unseen text**


### References and resources
- [TensorFlow in Action](https://www.google.de/books/edition/TensorFlow_in_Action/JYyKEAAAQBAJ?hl=en&gbpv=0)