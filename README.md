# Movie Chatbot
Chatbot using the Cornell Movie-Dialogs Corpus
https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html

Dependencies
============
* python
* numpy
* scipy 
* six
* tensorflow

Use [pip](https://pypi.python.org/pypi/pip) to install any missing dependencies


Usage
============

To train the bot, edit the `seq2seq.ini` file so that mode is set to train like so

`mode = train`

then run the code like so

``python execute.py``

To test the bot during or after training, edit the `seq2seq.ini` file so that mode is set to test like so

`mode = test`

then run the code like so

``python execute.py``
