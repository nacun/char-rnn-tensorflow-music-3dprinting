# char-rnn-tensorflow
Multi-layer Recurrent Neural Networks (LSTM, RNN) for character-level language models in Python using Tensorflow.

Inspired from Andrej Karpathy's [char-rnn](https://github.com/karpathy/char-rnn).


.

.

.

.


#Updated By jeremy Ellis twitter @rocksetta 
Oct 24, 2016

Getting this working on cloud9 http://c9.io and with php support so that it can be done from a web page

Setup by making a blank workspace and running the setup.sh bash file.

Install this github 



https://github.com/hpssjellis/char-rnn-tensorflow-music-3dprinting.git

I use a blank workspace but php5 or python would probably work.

To setup pythyon

right click --> run setup.py

To run the web server 

Right click --> run the rnn-both.php file

(for a simple situtaion use rnn-serve.php with rnn-serve.html)

Open the link provided in the terminal output


I also have a github for installing both Magenta and this github onto cloud9 at


https://github.com/hpssjellis/my-tensorflow-magenta-online



use at your own risk!
.

.

.

.

back to the original readme.md

.



# Requirements
- [Tensorflow](http://www.tensorflow.org)

# Basic Usage
To train with default parameters on the tinyshakespeare corpus, run `python train.py`.

To sample from a checkpointed model, `python sample.py`.
# Roadmap
- Add explanatory comments
- Expose more command-line arguments
- Compare accuracy and performance with char-rnn
