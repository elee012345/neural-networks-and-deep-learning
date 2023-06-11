## This is a fork of the below fork lol
learning machine learnning :D
know so far:

Take however many inputs, and feed them through a large network. This network has many layers, each one with a different number of nodes (neurons). Each of your inputs (also a neuron, though it's mostly called that for convenience) gets multipled by a weight specific to that neuron and the next (so each neuron connects to each one before and after it). Each neuron (not weight!) has a specific bias to give it more or less 'signal strength', and then take the quadratic cost (error). We take mini batches of this error, and try to decrease this error by changing the inputs (traveling down the gradient in n dimensions, where n is the number of inputs). We take small batches of this cost instead of calculating it for all inputs to make the process faster (it's a heuristic that's 'good enough'). 

To learn:
how does gradient descent actually work? how is it implemented?
and of course later move onto more complex machine learning algorithms like ppo

## This fork is made to work with the latest python versions (3.8.x to 3.10.x)

This is a fork of [Michael Nielsen](https://github.com/mnielsen/neural-networks-and-deep-learning) repository and is meant to be updated with the latest python and dependency versions. Most things have been updated and currently work. Any help is appreciated and if you spotted any problems, please open an issue and/or a PR.

# Code samples for "Neural Networks and Deep Learning"

This repository contains code samples for my book on ["Neural Networks
and Deep Learning"](http://neuralnetworksanddeeplearning.com).

The code is written for Python 2.6 or 2.7. Michal Daniel Dobrzanski
has a repository for Python 3
[here](https://github.com/MichalDanielDobrzanski/DeepLearningPython35). I
will not be updating the current repository for Python 3
compatibility.

The program `src/network3.py` uses version 0.6 or 0.7 of the Theano
library.  It needs modification for compatibility with later versions
of the library.  I will not be making such modifications.

As the code is written to accompany the book, I don't intend to add
new features. However, bug reports are welcome, and you should feel
free to fork and modify the code.

## License

MIT License

Copyright (c) 2012-2018 Michael Nielsen

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
