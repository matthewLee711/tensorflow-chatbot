# Chatbot based rnn

Dependencies
============
* numpy
* scipy
* six
* tensorflow (https://www.tensorflow.org/versions/r0.12/get_started/os_setup.html)

Use [pip](https://pypi.python.org/pypi/pip) to install any missing dependencies

# Training with a GPU
I do not recommend this unless you are willing to go through a lot of pain.

- Nvidia fermi > 2.0 architecture OR Pascal
- Cuda


Usage
===========

To train the bot, edit the `seq2seq.ini` file so that mode is set to train like so

`mode = train`

then run the code like so

``python execute.py``

To test the bot during or after training, edit the `seq2seq.ini` file so that mode is set to test like so

`mode = test`

then run the code like so

``python execute.py``



Credits
===========
Credit for the vast majority of code here goes to [suriyadeepan](https://github.com/suriyadeepan).
