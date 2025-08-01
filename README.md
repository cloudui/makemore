# makemore
Based on Andrej Karpathy's makemore YouTube series.

Done in Pytorch.

# basic overview
deep learning and language modeling from the ground up.

goal is to generate new names based on names dataset using DL.

- l1: simple bigram model and super basic 1-layer NN 
  - tried a trigram model for fun
  - frequency analysis
- l2: 2-layer MLP, 3 token input 1 token prediction
  - basic train-dev-test splitting
  - basic embedding layer
- l3: same as l2 with additional complexities
  - batchnorm
  - kaiming initialization
  - activations analysis
  - learning rate decay
- pytorch l3: more pytorch-native simplifications
  - gradient distributions
  - weights distribution
  - grad to data ratios
- l4: `backward()` manually
  - implemented gradients without autograd engine
  - step by step math ops and hand-computed simplifications