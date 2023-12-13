# Neural Machine Translation using Recurrent Neural Networks and attention

## Overview

This project implements a Neural Machine Translation (NMT) system to translate text from French to English using a sequence-to-sequence architecture with GRUs (Gated Recurrent Units). The model is trained on parallel text data obtained from the translation site [Tatoeba](https://tatoeba.org/).

## Model Architecture

The NMT system is built on an encoder-decoder architecture with GRUs. The encoder processes the input sequence (French sentence), and the decoder generates the corresponding output sequence (English translation). The decoder used Bahdanau attention to effectively capture long term dependencies.

