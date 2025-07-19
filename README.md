# English-to-French-Transformer-Neural-Machine-Translation-Project
This project implements a Transformer-based neural machine translation (NMT) model from scratch using TensorFlow and Keras. The model translates English sentences into French using core components introduced in the original Attention is All You Need paper. It achieves ~89% training accuracy after 57 epochs on a dataset of over 40,000 English–French sentence pairs.

# Project Highlights
+ Implemented custom Transformer model: scaled dot-product attention, multi-head attention, positional encoding, encoder/decoder blocks
  
+ Achieved ~89% training accuracy on tokenized bilingual pairs
  
+ Built full preprocessing pipeline: tokenization, padding, and masking
  
+ Used custom learning rate scheduler and Adam optimizer

+ Trained with end-to-end teacher forcing and evaluated on validation examples

+ Inference pipeline generates French translations token-by-token

# Model Architecture
+ Embedding Layer: Word embedding + positional encoding

+ Encoder: Stacked multi-head attention + feedforward blocks

+ Decoder: Includes masked multi-head attention and cross-attention layers

+ Output: Final dense layer with softmax activation over French vocabulary

# Requirements
+ Python 3.8+

+ TensorFlow

+ NumPy

+ matplotlib

+ tqdm

# Training Results
+ Training Accuracy: ~89% after 57 epochs

+ Evaluation: Translations improve steadily across epochs

+ Sample outputs are shown in the notebook
