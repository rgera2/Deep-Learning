This repository consists of some deep learning projects.
# Description
1. **CNN and Fine Tuning:** Here, we leveraged CNN and transfer learning algorithm to label the contents of the images using ResNet18 deep learning architecture by extracting features. Furthermore, test accuracy was improved from 75% to 92% by fine-tuning model’s parameters.

2. **Movie Embeddings:** Created movie embeddings from Movielens data. Loss was optimized using gradient descent. After that, we plotted Loss as a function of iteration for different learning rates and choice of optimizers. Finally, cosine similarity was used to recommend movies.

3. **RNN for Language Modeling:** Built a Markov (n-gram) and LSTM (n-gram) language model. For each model, starting with the phrase "My favorite movie ", sentences of 20 word length were generated and compared.

4. **Seq2seq for Translation:** Two translation models - Hindi to English and English to Hindi were created using encoder-decoder and attention mechanism. GloVe embeddings were leveraged for English to Hindi translation and random sentences were generated and compared.
