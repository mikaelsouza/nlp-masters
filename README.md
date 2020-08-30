# Restauração de Pontuação usando Redes Neurais

### Informações Importantes:

Este trabalho está sendo financiado pelo [Conselho Nacional de Desenvolvimento Científico e Tecnológico - CNPq](http://www.cnpq.br/) pela [Universidade Federal do Amazonas](https://ufam.edu.br/).

### Sobre:

Em diversos sistemas de [Speech-to-Text](https://en.wikipedia.org/wiki/Speech_recognition), sentenças são geradas, na maioria das vezes, sem tratamento em relação a pontuações, capitalização e contexto. Entretanto pontuação em textos é importante tanto para o entendimento dos mesmos para leitores e para pós-processamento de sistemas de [NLP](https://en.wikipedia.org/wiki/Natural_language_processing). Mais recentemente há um crescimento na utilização de sistemas que dependem primariamente da interação por voz, como assistentes virtuais, smartspeakers, etc e por conta disso há espaço para melhorias neste espaço.

Este trabalho busca explorar técnicas de restauração de pontuação em textos não pontuados utilizando a combinação de [Embeddings](https://en.wikipedia.org/wiki/Word_embedding) pré-treinados em diversos níveis.

### Inspiração:

A inspiração deste trabalho se dá em parte pelo meu interesse em trabalhar com áudio (especificamente música) no contexto de Deep Learning e este ser um ponto próximo de trabalho atual.

Artigos influentes até o momento:

- [Adversarial Transfer Learning for Punctuation Restoration](https://arxiv.org/abs/2004.00248)
- [Joint word-and character-level embedding CNN-RNN models for punctuation restoration](https://ieeexplore.ieee.org/abstract/document/8639876/)
- [Sequence-to-sequence models for punctuated transcription combining lexical and acoustic features](http://www.cstr.ed.ac.uk/downloads/publications/2017/icassp-2017.pdf)
- [Self-attention Based Model for Punctuation Prediction Using Word and Speech Embeddings](https://ieeexplore.ieee.org/document/8682260/)
- [Experiments in Character-Level Neural Network Models for Punctuation ](http://www.isca-speech.org/archive/Interspeech_2017/abstracts/1710.html)