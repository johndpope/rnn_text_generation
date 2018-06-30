# RNN Text Generation
Simple recurrent architecture that generates Shakespeare. Built using Keras. Heavily inspired by [Andrej Karpathy](http://karpathy.github.io/2015/05/21/rnn-effectiveness/).

Thoughts after building this:
 - I'm surprised at just how well this works. The network builds up an understanding of how to string words together, punctuation, and formatting automatically.
 - Keras is amazing, but it can sometimes be rigid and too high level. I'm still not sure, for example, how to pass a single cell's output back as input to another cell without defining custom LSTM cells.
 - The number of hidden units in each LSTM cell has a big impact on overall training time and validation accuracy. 
