# rnn-vs-lstm-text-generation

# RNN vs LSTM: Text Generation on Shakespeare Dataset

This project explores text generation using Recurrent Neural Networks (RNNs) and Long Short-Term Memory Networks (LSTMs). Models were trained on a subset of the Shakespeare dataset to generate coherent, Shakespeare-like text.

---

## Dataset Preprocessing
- **Dataset**: First half of the Shakespeare dataset.
- **Splits**: 
  - 90% Training, 5% Validation, 5% Testing.
- **Encoding**: One-hot encoded 67 unique characters into input-target pairs.

---

## Features
1. **Standard RNN**:
   - Visualized architecture, learning curves, and error rates.
   - Evaluated text generation at different training stages.
2. **LSTM**:
   - Performed similar tasks and compared results with RNN.
3. **Hyperparameter Tuning**:
   - Explored the effects of hidden state size and sequence length on training loss.
4. **Text Generation**:
   - Primed models with input text (e.g., "JULIET") to generate Shakespeare-like text.

---

## Results
- **LSTM** outperformed **RNN** in error rates and text quality.
- Hyperparameters (hidden state size and sequence length) significantly influenced performance.
