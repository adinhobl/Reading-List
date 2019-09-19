# Reading-List
An organized list of papers and resources that I have found interesting.
--------------------------------------------------------------------------------

### Genetic Algorithms
* [Evolving simple programs for playing Atari games](https://arxiv.org/abs/1806.05695):
    Evolving programs of scalar and matrix functions to play Atari games on pixel input. Generally programs found a simple way to consistently achieve decent results without much finesse. 

### Deep Learning
* [The deepest problem with deep learning](https://medium.com/@GaryMarcus/the-deepest-problem-with-deep-learning-91c5991f5695): A defense of the idea that deep-learning is only a piece of the puzzle of AI. AI has a long way to go to approach general reasoning or logical abilities. Recommends symbol-manipulation.
    
* [Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/pdf/1409.0473v7.pdf): Uses an end-to-end learned architecture consisting of a bidirectional RNN encoder, an alignmnet layer, and an LSTM decoder to translate sentences from English to French. The bi-RNN encodes each word in a sentence and the dependencies on the words around it, which the decoder uses to produce each output word.

### Machine Learning
* [Neural Ordinary Differential Equations](https://arxiv.org/pdf/1806.07366.pdf): More mathy than a typical paper, but with some good insights into how the much-more-explored optimization research can benefit machine learning. The authors suggest taking the idea that using a neural network, such as a residual network, with more and more layers to approximate a function can be taken to the infinitesimal limit and set up as an Ordinary Differential Equation that can be solved using today's powerful ODE solvers. This leads to better approximations of time-series with non-uniform observations, and is also impressive in that its memory cost is constant and it can train to similar accuracy as neural nets, but with fewer parameters. Further reading: https://blog.acolyer.org/2019/01/09/neural-ordinary-differential-equations/

* [Real numbers, data science and chaos:How to fit any dataset with a single parameter](https://arxiv.org/pdf/1904.12320.pdf): Shows that any dataset can be transformed into an arbitrarily long string of digits, which can be expressed as a decimal real number. The data can then be recovered by passing it through a periodic, exponential function to recover each sample from the dataset. An interesting way to "capture" a full dataset in one parameter. The author questions if number of parameters is a useful metric for classifying the learning capacity of neural networks, but does acknowledge that the method used is not 'learning' anything.

### Generative Modeling
* [Generative Adversarial Networks](https://arxiv.org/abs/1406.2661): The GAN paper. A GAN consists of a generative neural network that samples from its learned distribution, and a discriminative model that classifies whether the sample is actual data, or from the generative model. By jointly training these two separate networks, the generative network learns a distribution and generates increasingly realistic samples.

### Reinforcement Learning
* [Optimizing Chemical Reactions with Deep Reinforcement Learning](https://pubs.acs.org/doi/full/10.1021/acscentsci.7b00492): Authors reach new state-of-the-art for optimizing chemical reaction conditions using reinforcement learning and automated microdroplet reaction system. The system selects reaction conditions (in this case flowrate, voltage, pressure) to achieve a target (yield) by iteratively testing new conditions, and then feeding the previous conditions and result to a RNN. The model was pretrained on simulated reactions, but still worked on real reactions and could generalize fairly well to reactions with a completely different mechanism.

### Neuroscience
* [A critique of pure learning and what artificial neuralnetworks can learn from animal brains](https://www.nature.com/articles/s41467-019-11786-6.pdf): A comparison of the way animals learn vs the way ANNs learn, how the genome has been optimized through millions of years to make certain animal learning easier, the duality of learning and evolution.
