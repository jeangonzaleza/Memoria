# Degree Project
### REQUIRES python 2.7 (I'm using python 2.7.18)

For training use THEANO_FLAGS=mode=FAST_RUN,device=cuda1,floatX=float32 PYTHONPATH=. python model/train.py -t -i ./clean_es.json -m "new_model" -E 3

Note: "-E 3" means 3 epochs, modify this paremeter if necessary

### Source Code from: https://github.com/soroushv/Tweet2Vec
#### Soroush Vosoughi, Prashanth Vijayaraghavan and Deb Roy. (2016). Tweet2Vec: Learning Tweet Embeddings using Character-level CNN-LSTM Encoder-Decoder. In Proceedings of the 39th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2016). Pisa, Italy.
