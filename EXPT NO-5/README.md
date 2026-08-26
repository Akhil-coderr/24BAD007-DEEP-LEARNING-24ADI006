## Experiment 5 — Implementation of RNN for Text Generation

### Aim
To implement a Recurrent Neural Network (RNN) for text generation using the Tiny Shakespeare dataset by predicting the next word in a sequence.

### What I Did
- Loaded and explored the **Tiny Shakespeare** dataset.
- Preprocessed and tokenized the text.
- Created a vocabulary and converted words into integer IDs.
- Generated and padded input sequences for next-word prediction.
- Split the data into training and validation sets.
- Built an RNN using **Embedding, SimpleRNN, and Dense + Softmax layers**.
- Trained the model using **Adam optimizer** and **Sparse Categorical Crossentropy**.
- Evaluated the model using training/validation **accuracy and loss**.
- Visualized **Accuracy vs Epoch** and **Loss vs Epoch**.
- Generated text using different seed inputs.
- Experimented with **temperature-based text generation**.

### Tools Used
**Python | TensorFlow/Keras | NumPy | Matplotlib | VS Code | GitHub**

### Outcome
Successfully implemented an RNN that learned sequential patterns from Shakespeare's text and generated new text by predicting the next word. The experiment helped me understand **sequence modeling, word embeddings, RNNs, model training, evaluation, and text generation**.

### Key Learning
This experiment gave me practical understanding of how an RNN processes sequential text, learns from previous words, and generates new text based on the learned patterns.
