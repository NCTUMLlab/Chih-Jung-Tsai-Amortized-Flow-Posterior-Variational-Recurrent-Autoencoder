# Amortized-Flow-Posterior-Variational-Recurrent-Autoencoder

In this repository, we implement the AFP-VRAE on four different datasets.
The model uses normalizing flow to learn rich latent distributions for sequences.
The model performs language modeling on Penn TreeBank
and Yelp 2013, as well as sentiment analysis and document summarization on IMDB and DUC 2007, respectively. The model outperforms
its competitors in all measures. It improves VRAE in encoder, decoder and latent space.

## Setting

- Framework:
  - Pytorch 0.4.0

- Hardware:
  - CPU: Intel Core i7-5820K @3.30 GHz
  - RAM: 64 GB DDR4-2400
  - GPU: GeForce GTX 1080ti
