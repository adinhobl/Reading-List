# Reading-List
An organized list of papers and resources that I have read or want to read.
--------------------------------------------------------------------------------

## Read

### Genetic Algorithms
* [Evolving simple programs for playing Atari games](https://arxiv.org/abs/1806.05695):
    Evolving programs of scalar and matrix functions to play Atari games on pixel input. Generally programs found a simple way to consistently achieve decent results without much finesse. 

### Deep Learning
* [The deepest problem with deep learning](https://medium.com/@GaryMarcus/the-deepest-problem-with-deep-learning-91c5991f5695): A defense of the idea that deep-learning is only a piece of the puzzle of AI. AI has a long way to go to approach general reasoning or logical abilities. Recommends symbol-manipulation.
    
* [Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/pdf/1409.0473v7.pdf): Uses an end-to-end learned architecture consisting of a bidirectional RNN encoder, an alignmnet layer, and an LSTM decoder to translate sentences from English to French. The bi-RNN encodes each word in a sentence and the dependencies on the words around it, which the decoder uses to produce each output word.

### Machine Learning
* [Neural Ordinary Differential Equations](https://arxiv.org/pdf/1806.07366.pdf): More mathy than a typical paper, but with some good insights into how the much-more-explored optimization research can benefit machine learning. The authors suggest taking the idea that using a neural network, such as a residual network, with more and more layers to approximate a function can be taken to the infinitesimal limit and set up as an Ordinary Differential Equation that can be solved using today's powerful ODE solvers. This leads to better approximations of time-series with non-uniform observations, and is also impressive in that its memory cost is constant and it can train to similar accuracy as neural nets, but with fewer parameters. Further reading: https://blog.acolyer.org/2019/01/09/neural-ordinary-differential-equations/
